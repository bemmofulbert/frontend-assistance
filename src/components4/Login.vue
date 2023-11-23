<!-- eslint-disable vue/no-parsing-error -->
<template>
  <div id="logBox">
    <input type="button" @click="toggleColor" value="Color"/>
    <h2 class="underline" v-html="entete" ></h2>
    <h4>{{ DateNow }}</h4>
    <form>
        <label for="name">UserName: </label>
        <input id="name"/><br/>
        <label for="pass">Password: </label>
        <input id="pass" v-model="userName"/>
        <label for="pass" >{{reverseUserName}}</label><br/><br/>
        <input type="button" @click="toggleColor" value="Enregistrer"/>
        <input type="reset"/>
    </form>
  </div>
  <h1 className="text-3xl font-bold underline">
        Simple Tailwindo CSS application
      </h1>
<button class="bg-transparent hover:bg-blue-500 text-blue-700 font-semibold hover:text-white py-2 px-4 border border-blue-500 hover:border-transparent rounded">
  Save
</button>
<span>
<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 border border-blue-700 rounded">
  Submit
</button>
</span>
</template>

<script>

export default {
  name: 'LogIn',
  data () {
    return ({
      entete: '<h2 style=\'color:red\'>Login</h2>',
      userName: '',
      DateNow: ''
    })
  },
  methods: {
    toggleColor: function () {
      if (this.entete === '<h2 style=\'color:red\'>Login</h2>') this.entete = '<h2 style=\'color:green\'>Login</h2>'
      else this.entete = '<h2 style=\'color:red\'>Login</h2>'
    }
  },
  computed: {
    reverseUserName: function () {
      return this.userName.split('').reverse().join('')
    }
  },
  watch: {
    DateNow: function () {
      return Date.now()
    }
  },
  components: {
  }
}
</script>

<style>
  #logBox{
    border: 2px burlywood solid;
    box-shadow: 89px;
  }
</style>
