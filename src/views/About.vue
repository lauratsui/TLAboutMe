<template>
  <div class="about-card">
    <div class="card-title">
      <img src="https://lh3.googleusercontent.com/fQwrdBZIxUDploR1wQFx3KmbXDRQhM0gz8ngcfcTChPSIF31VvtX6Q0LDQ904CS8LLYUw0nElZ1awiHSW0T8xf7foQiFqBm_n4U2bIRurOjlTwRa77EcunxPwX_okRKuvVH80gXC4Yrhxqg3tQtaw8SiCyjm6p6Y4yaZu3-q3N3hXTuJJiul3roH6eaM_P6S3N9qoD-vdMdkvKsn5vkpH8BOY1SHgZv2Ry__sSwkNQxOzIQWCkXZjayq8xEgIR_7jSrY4rldKYYYGWcOAXfzAuoauts3xFwQAtVwt7I3bxNlyTdg1-iawP8zA1caSHWEF-pXyGrtaeqhF9c2TaZIwKJ8jhvajCQ9DcNS3k8o0HrMwHWBgZkLEIuucjipeQmreZ2KQjcllco45j2j88V1IV-miSkeecRzVz5VaIhx9RjqTz7xzysTDojGZ31ryQXehm9h-BJkX4MWpnugFm6xqU219R7ikeFElbWe_xRhO3X5zGQb-2Uk3zslS1A8fZ7QBBSGgBvCZ6g_lbo2MZFWh01sABJ4eneIaCt8zoRJ_5Jq-5W4dybI75BoyX5QfVXhWG9z3d8GWMLmverI4fyqv27gnfmqbXfoA8q8YiGWKkG4XQAt8SVY7Dh1AlzIngfzw3NWOdvDYroL8yr1L--Fnfl9Ukn_HmHYl2HBu3WOUQct5uqZwrgsZWjdYbpiEg=w2104-h1578-no?authuser=0" alt="avatar" class="avatar" width="100" height="90">
      <div class="title-text-content">
        <p> About Me</p>
        <h2> TofuGirl</h2>
      </div>
    </div>
    <div class="card-content">

      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, labore dicta. Delectus voluptates sequi voluptatum, minus porro aspernatur labore officia nemo deleniti deserunt architecto nesciunt, eveniet pariatur, sunt error tenetur maxime aliquam laudantium culpa id magni provident! Fugiat, quos. Vel molestias illo consequuntur nisi eligendi deserunt repellendus temporibus, provident laudantium.</p>

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

      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia, ipsum ab quae voluptatum ea adipisci earum qui vel provident vitae reprehenderit porro architecto totam magni aliquam sed explicabo aliquid laborum?</p>

      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Exercitationem amet fugiat neque expedita? Nemo itaque, aperiam totam cum consectetur quibusdam exercitationem, magni laudantium sint impedit incidunt quis! Animi, debitis hic.</p>
    </div>
  </div>
</template>

<style lang="sass" scoped>
  .about-card
    background: #333
    padding: 3em
    border-radius:  10px 
    color: white
    .card-title
      display: flex 
      align-items: center
      background: #222
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