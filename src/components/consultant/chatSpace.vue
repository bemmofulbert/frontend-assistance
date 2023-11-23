<template>
  <div class="messagerie_backgrounds" id="messagerie_chatSpace">
    <div id="messagerie_chatSpace_header">
      <div id="messagerie_profil">
        <div class="messagerie_contacts_elements texte_title">
          <div class="messagerie_contacts_elements_img">
            <img src="./img/head.svg" />
          </div>
          <div class="messagerie_contacts_elements_infos">
            <div class="messagerie_contacts_elements_name">Ngaba Franck</div>
            <div class="messagerie_contacts_elements_number">16 utilisateurs satisfaits</div>
          </div>
          <div id="messagerie_phoneVideo">
            <img id="messagerie_phone_img" src="./img/video.svg" />
            <img id="messagerie_video_img" src="./img/phone.svg" />
          </div>
        </div>
      </div>
      <div id="messagerie_menu">
        <img src="./img/menu.svg" />
      </div>
    </div>

    <div id="messagerie_chatSpace_messages">
      <!---------------------------------UP-------------------------->
      <div class="messagerie_chatSpace_messageBox">
        <div class="messsagerie_chatSpace_senderMessage">
          <div class="messsagerie_chatSpace_sender">
            <img src="./img/head.svg" />
          </div>

            <div class="messagerie_chatSpace_message">Bonjour</div>

        </div>
        <div class="messagerie_chatSpace_messageBox_time">8:40 AM, Today</div>
      </div>
      <!---------------------------------/UP-------------------------->

      <div class="messagerie_chatSpace_messageBox">
        <div class="messsagerie_chatSpace_senderMessage">
          <div class="messsagerie_chatSpace_sender">
            <img src="./img/head.svg" />
          </div>

            <div class="messagerie_chatSpace_message">Quel est le probleme de votre appareil ?</div>

        </div>
        <div class="messagerie_chatSpace_messageBox_time">8:40 AM, Today</div>
      </div>
    <!---------------------------------PU-------------------------->

    <div class="messagerie_chatSpace_messageBox_reverse">
        <div class="messsagerie_chatSpace_senderMessage_reverse">
          <div class="messsagerie_chatSpace_sender_reverse">
            <img class="imgClient" src="./me.jpg" />
          </div>

            <div class="messagerie_chatSpace_message_reverse">Mon ordinateur reste plante sur l'ecran de demarrage.</div>

        </div>
        <div class="messagerie_chatSpace_messageBox_time">8:55 AM, Today</div>
      </div>
    <!---------------------------------/PU-------------------------->
    <div class="messagerie_chatSpace_messageBox_reverse">
        <div class="messsagerie_chatSpace_senderMessage_reverse">
          <div class="messsagerie_chatSpace_sender_reverse">
            <img class="imgClient" src="./me.jpg" />
          </div>

            <div class="messagerie_chatSpace_message_reverse">Lorsque j'allume l'ordi, il reste plante, je ne comprend pas , ce qui se passe, pourtant hier ca donnait bien meme. Aujourd'hui en demarrant la machine, un ecran noir bizarre s'affiche.</div>

        </div>
        <div class="messagerie_chatSpace_messageBox_time">8:55 AM, Today</div>
      </div>
    <!---------------------------------PU-------------------------->
    </div>
    <div id="messagerie_chatSpace_footer">
      <div>
          <div class="messagerie_chatSpace_footer_extreme">
            <img src="./img/paperclip.svg" />
          </div>
          <div id="messagerie_chatSpace_footer_input">
            <textarea placeholder="Type your message..."/>
          </div>
          <div class="messagerie_chatSpace_footer_extreme messagerie_chatSpace_footer_extreme_droit">
            <img src="./img/send.svg" />
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'chatSpace'
}
</script>

<style src="./chatSpace.css" >

</style>
<style src="./contacts.css">

</style>
