---
layout: page
title: Links
#background_style: bg-info
background_image: url('assets/img/backgrounds/image-from-rawpixel-id-1199650-jpeg.jpg')
# Add a link to the the top menu
menus:
  header:
    title: Links
    weight: 2

sections:
- type: address.html
  section_id: address
  title: Meeting Place
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3976.2242327746623!2d-74.0858771!3d4.6359018!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb696cd67a04b98e9!2sFacultad+De+Ingenieria+-+UNIVERSIDAD+NACIONAL+DE+COLOMBIA!5e0!3m2!1ses!2sbg!4v1690475641347!5m2!1ses!2sbg
  address:
    title: Address
    text: >
      Ave Cra 30 #45-3,<br/>
      Bogota D.C,<br/>
      Colombia
  phone:
    title: Phones
    text: >
      +57 312 5164057, Alejandro Ojeda (CEO)<br/>
      +57 302 2189408, Christian Hoffman (CTO)
- type: paragraph.html
  section_id: help
  title: Project Links
  text: >+
    Here there are some projects done by our group members:

    * [Automatic Time Racing Dashboard - Liftoff](LINK DE LOOKERSTUDIO).

    * [1S LiPo battery charger adapter](https://es.linkedin.com/posts/dacunar_x-wings-btl-a4-v10-adaptador-para-cargador-activity-7195534585336582144-T63z)
---
<style>
  .slider-wrapper{
      overflow: hidden;
      max-width: 1200px;
      margin: 0 70px 55px;
  }
  .card-list .card-item{
      
      user-select: none;
      color: #000000;
      width: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      flex-direction: column;
      padding: 35px;
      border-radius: 8px;
      background: rgba(255, 255, 255, 0.2);
      border: 1px solid rgba(255, 255, 255, 0.5);
      min-height: 500px;
  }
  .card-list .card-item .flip-card-inner .project-image{
      text-align: center;
      object-fit: cover;
  }
  .card-list .card-item h2{
      display: block;
      margin-top: 0;
      font-size: 1.25em;
      margin-bottom: 0.67em;
      font-weight: bold;
      color: #000000;
  }
  .card-list .card-item .project-image{
      width:100px;
      height: 100px;
      border-radius: 50%;
  }
  .card-list .card-item .project-author{
      font-size: 1.15rem;
      color: #000000;
      font-weight: 500;
      margin: 14px 0 40px;
  }
  .card-list .card-item .message-button{
      font-size: 1.25rem;
      padding: 10px 35px;
      color: #030728;
      border-radius: 6px;
      font-weight: 500;
      cursor: pointer;
      border: 1px solid transparent;
      transition: 0.2s;
  }

  .card-list .card-item .message-button:hover{
      background: rgba(255, 255, 255, 0.1);
      border: 1px solid #000000;
      color: #000000;
  }
  .containter .swiper-slide-button{
      color: #000000;
      margin-top: -50px;
      transition: 0.2s ease;
  }

  .containter .swiper-slide-button:hover{
      color:#4658ff
  };
  @media (max-width: 768px){
      .slider-wrapper{
          margin: 0 10px 40px;
      }
      .slider-wrapper .swiper-slide-button{
          display: none;
      }
  }
</style>
<div class="containter swiper">
    <div class="slider-wrapper">
        <div class="card-list swiper-wrapper">
            <div class="card-item swiper-slide">
                <div class="flip-card-inner">
                    <div class="flip-card-front">
                        <h2>Automatic Time Racing Dashboard - Liftoff</h2>
                        <img src="images/dashboard.png" alt="Project Image" class="project-image">
                        <p class="project-author">Santiago, Juan Pablo, Alejandro</p>
                    </div>
                    <div class="flip-card-back">
                        <h2>Automatic Time Racing Dashboard - Liftoff</h2>
                        <p>This project includes an automation tool that reads data from any race in Liftoff. Using a Google API, the data is extracted, processed, and visualized on a Looker Studio dashboard. This allows for statistical analysis on an individual pilot basis and by track type, as well as comprehensive analysis of all races.</p>
                        <button class="message-button">Go</button>
                    </div>
                </div>
            </div> 
            <div class="card-item swiper-slide">
                <div class="flip-card-inner">
                    <div class="flip-card-front">
                        <h2>1S LiPo battery charger adapter</h2>
                        <img src="images/pcb.png" alt="Project Image" class="project-image">
                        <p class="project-author">Davinson Camilo</p>
                    </div>
                    <div class="flip-card-back">
                        <p>In collaboration with the X-Wings FPV Drone Racing Team, a new adapter for 1S batteries has been developed over the past few months. The chargers currently in use do not offer a Storage mode option for the 1S batteries used by Tiny drones, which significantly reduces their lifespan. Noting that the available market options were prohibitively expensive, the team decided to create their own technology. This innovative solution aims to extend battery life and is now available as an initial prototype.</p>
                        <button class="message-button">Go</button>
                    </div>
                </div>
            </div> 
            <div class="card-item swiper-slide">
                <div class="flip-card-inner">
                    <div class="flip-card-front">
                        <h2>1S LiPo battery charger adapter</h2>
                        <img src="images/pcb.png" alt="Project Image" class="project-image">
                        <p class="project-author">Davinson Camilo</p>
                    </div>
                    <div class="flip-card-back">
                        <p>In collaboration with the X-Wings FPV Drone Racing Team, a new adapter for 1S batteries has been developed over the past few months. The chargers currently in use do not offer a Storage mode option for the 1S batteries used by Tiny drones, which significantly reduces their lifespan. Noting that the available market options were prohibitively expensive, the team decided to create their own technology. This innovative solution aims to extend battery life and is now available as an initial prototype.</p>
                        <button class="message-button">Go</button>
                    </div>
                </div>
            </div> 
        </div>
    </div>   
    <div class="swiper-pagination"></div>
    <div class="swiper-slide-button swiper-button-prev"></div>
    <div class="swiper-slide-button swiper-button-next"></div>
    <script>
        const swiper = new Swiper('.slider-wrapper', {
        loop: true,
        grabCursor:true,
        spaceBetween:30,
        // If we need pagination
        pagination: {
          el: '.swiper-pagination',
          clickable:true,
          dynamicBullets:true
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
        },
        //Responsive breakpoints
        breakpoints:{
            0:{
                slidesPerView:1
            },
            768:{
                slidesPerView:2
            }
        }
      });
    </script>
</div>

<!-- <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script> -->
<!-- <script src="scripts.js"></script> -->
