<template>
  <div class="about-card">
    <div class="card-title">
      <img src="https://scontent.fsin1-1.fna.fbcdn.net/v/t1.0-9/97989406_10157327716973634_5040229548755517440_n.jpg?_nc_cat=111&_nc_sid=09cbfe&_nc_ohc=LmnMWqIn10UAX-bU_lk&_nc_ht=scontent.fsin1-1.fna&oh=98ebc242030104032bd04209ce7a0b58&oe=5F5C697D" alt="avatar" class="avatar" width="100" height="100">
      <div class="title-text-content">
        <p> Contact Me</p>
        <h2>Laura Tsui</h2>
      </div>
    </div>
    <div class="card-content">

      <p>Feel free to contact me!</p>
      <div class="contact-links">
        <a href = "https://www.linkedin.com/in/lauratsui/"><img src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" width="50" height="50"></a> <a href="https://www.instagram.com/bo_lo_bao/"><img src="https://instagram-brand.com/wp-content/themes/ig-branding/assets/images/ig-logo-email.png" width="50" height="50"></a> <a href="github.com/lauratsui"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="50" height="50"></a>
      </div>
    

    </div>
  </div>
</template>



<style lang="sass" scoped>
  .about-card
    background: #5F7470
    padding: 3em
    border-radius:  10px 
    color: white
    .card-title
      display: flex 
      align-items: center
      background: #889696
      border-radius: 10px
      .avatar
        border: 1px solid rgba(255, 255, 255, 0.4)
        border-radius: 50%
        margin: 0 30px
    .title-text-content
      p
        margin-bottom: 0
        color: rgb(210, 210, 210)
      h2
        margin-top: 0

  .card-content p
    line-height: 1.5
    margin: 30px auto
    a:link
      color: #D2D4C8
    a:visited
      color: #889696
  .card-content-list
    list-style: none
  .contact-links
    text-align: center
  table
    border-spacing: 0px
    margin: 50px auto
    tr th, tr td
      border: 1px solid white
      border-top: none
      padding: 10px
      text-align: center 
      &:first-of-type
        border-left: none
      &:nth-of-type(2)
        border-right: none
  
</style>