<template>
  <div class="about-card">
    <div class="card-title">
      <img src="https://lh3.googleusercontent.com/fQwrdBZIxUDploR1wQFx3KmbXDRQhM0gz8ngcfcTChPSIF31VvtX6Q0LDQ904CS8LLYUw0nElZ1awiHSW0T8xf7foQiFqBm_n4U2bIRurOjlTwRa77EcunxPwX_okRKuvVH80gXC4Yrhxqg3tQtaw8SiCyjm6p6Y4yaZu3-q3N3hXTuJJiul3roH6eaM_P6S3N9qoD-vdMdkvKsn5vkpH8BOY1SHgZv2Ry__sSwkNQxOzIQWCkXZjayq8xEgIR_7jSrY4rldKYYYGWcOAXfzAuoauts3xFwQAtVwt7I3bxNlyTdg1-iawP8zA1caSHWEF-pXyGrtaeqhF9c2TaZIwKJ8jhvajCQ9DcNS3k8o0HrMwHWBgZkLEIuucjipeQmreZ2KQjcllco45j2j88V1IV-miSkeecRzVz5VaIhx9RjqTz7xzysTDojGZ31ryQXehm9h-BJkX4MWpnugFm6xqU219R7ikeFElbWe_xRhO3X5zGQb-2Uk3zslS1A8fZ7QBBSGgBvCZ6g_lbo2MZFWh01sABJ4eneIaCt8zoRJ_5Jq-5W4dybI75BoyX5QfVXhWG9z3d8GWMLmverI4fyqv27gnfmqbXfoA8q8YiGWKkG4XQAt8SVY7Dh1AlzIngfzw3NWOdvDYroL8yr1L--Fnfl9Ukn_HmHYl2HBu3WOUQct5uqZwrgsZWjdYbpiEg=w2104-h1578-no?authuser=0" alt="avatar" class="avatar" width="100" height="90">
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
      
      <table width="100%">
        <tr>
          <th>Cuisine</th>
          <th>Favourites</th>
        </tr>
        <tr>
          <td>Japanese</td>
          <td>Sashimi, Okonomiyaki, Mochi</td>
        </tr>
        <tr>
          <td>Chinese</td>
          <td>Har Gau, Xiao Long Bao, Mala</td>
        </tr>
        <tr>
          <td>Italian</td>
          <td>Aglio Olio, Magherita Pizza, Tiramisu</td>
        </tr>
        <tr>
          <td>Mediterrenean</td>
          <td>Falafel, Shakshuka, Baklava</td>
        </tr>
        <tr>
          <td>Local</td>
          <td>Kway Teow, Orh Lua, Bak Chor Mee</td>
        </tr>
      </table>

    </div>
  </div>
</template>



<style lang="sass" scoped>
  .about-card
    background: #6B514F
    padding: 3em
    border-radius:  10px 
    color: white
    .card-title
      display: flex 
      align-items: center
      background: #916E6C
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
      color: pink
    a:visited
      color: silver
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