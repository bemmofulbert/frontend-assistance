<template>
  <div class="messagerie_backgrounds texte_title" id="messagerie_contacts">
    <div id="messagerie_contacts_header">
      <div>
        <div>
          <input placeholder="Search..."/>
        </div>
          <img src="./img/search.svg"/>
      </div>
    </div>
    <div id="messagerie_contacts_contacts">
      <div class="messagerie_contacts_elements messagerie_contacts_elements_selected">
        <div class="messagerie_contacts_elements_img">
          <img src="./img/head.svg" />
        </div>
        <div class="messagerie_contacts_elements_infos">
          <div class="messagerie_contacts_elements_name">Mister Peps</div>
          <div class="messagerie_contacts_elements_number">Admin</div>
        </div>
      </div>
      <!--------------------UP------------------------------------------------------------------->
      <div class="messagerie_contacts_elements">
        <div class="messagerie_contacts_elements_img">
          <img src="./img/head.svg" />
        </div>
        <div class="messagerie_contacts_elements_infos">
          <div class="messagerie_contacts_elements_name">BEMMO MBOBDA</div>
          <div class="messagerie_contacts_elements_number">16 utilisateurs satisfaits</div>
        </div>
      </div>
      <!--------------------------/UP------------------------------------------------------------>
    </div>
    <div id="messagerie_contacts_footer"></div>
  </div>
</template>

<script>
export default {
  name: 'conTacts'
}
</script>

<style src="./contacts.css"></style>
<style src="./chatSpace.css"></style>
