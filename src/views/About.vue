<template>
  <div class="about-card">
    <div class="card-title">
      <img src="https://scontent.fsin1-1.fna.fbcdn.net/v/t1.0-9/97989406_10157327716973634_5040229548755517440_n.jpg?_nc_cat=111&_nc_sid=09cbfe&_nc_ohc=LmnMWqIn10UAX-bU_lk&_nc_ht=scontent.fsin1-1.fna&oh=98ebc242030104032bd04209ce7a0b58&oe=5F5C697D" alt="avatar" class="avatar" width="100" height="100">
      <div class="title-text-content">
        <p> About Me</p>
        <h2>Laura Tsui</h2>
      </div>
    </div>
    <div class="card-content">

      <p>Hello! My name is Laura Tsui, and here's my entry for the <a href="https://github.com/TechLadies/bootcamp6-info/blob/master/tech_task.md?fbclid=IwAR3fa3gES-_fnitpBE63c6-WcxxHyVDhVMLDdV6WhXaqONye4GvCa_nftrE"> Techladies Bootcamp Technical Task </a>(frontend).</p>

      <p>I'm applying for the bootcamp because I think it's a great programme to do my part to give back to society through creating products for non-profits, while being able able to upskill myself. I'm concurrently building up some skills in UX Design through a <a href="https://generalassemb.ly/education/user-experience-design/singapore?&topic=&mkt_account_id=1056949875&mkt_campaign_id=1590842852&mkt_ad_group_id=59060306854&mkt_device_type=c&mkt_keyword=%2Bux%20%2Bgeneral%20%2Bassembly&mkt_matchtype=b&mkt_placement=&mkt_ad_id=417677038278&mkt_network=g&mkt_target_id=kwd-303464578014&mkt_feed_item_id=&utm_source=google&utm_medium=paid-search-bra&utm_campaign=TS:TX:BRA:SNG:BRTP:DES:UserExperience:GeneralAssembly&utm_content=campus-lead-lander&utm_term=%2Bux%20%2Bgeneral%20%2Bassembly&gclid=Cj0KCQjwyJn5BRDrARIsADZ9ykFrJTHpLLu9U9oBFReb_33ldhzro5wUkizhz16CWCt3Lcv_skq25mwaArXyEALw_wcB">General Assembly UX Course</a>, and am hoping to bring some of those skills to the table. It also looks like an amazing and fun community to be a part of - with many incredible ladies across Asia. </p>

      <p>A little bit about myself - my work experience has largely been in Singapore's public service in the design and healthcare sectors. I'm currently a manager at <a href="http://designsingapore.org">DesignSingapore Council (Dsg)</a>, the national agency that oversees the design sector in Singapore. I oversee programmes to help non-design companies adopt design thinking, and am also leading the rollout of an internal organization-wide dashboard. Prior to joining Dsg, I was in the <a href="http://edb.gov.sg">Economic Development Board's (EDB)</a> Healthcare team. I did my undergrad in UC Berkeley in Economics.</p>
      
      <p>My hobbies include yoga, rock climbing, doing some <a href="https://vsco.co/lauratmy/gallery">amateur photography</a> and scrolling through instagram for cat photos.</p>
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

  
</style>