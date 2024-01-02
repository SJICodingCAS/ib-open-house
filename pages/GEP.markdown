---
layout: default
permalink: /GEP/
title: Global Education Programme
banner-image-url: ../assets/images/banners/gep.jpeg
---
<style>
    .GEP-column-container {
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        gap: 7px;  
    }

    .GEP-column-item {
        flex-grow: 1;
        flex: 1;
        text-align: center;
        min-width: 200px;
    }

    #GEP-column-item-middle {
        border-left: 2px solid #00664F;
        padding-left: 0.25rem;
        border-right: 2px solid #00664F;
        padding-right: 0.25rem;
    }

    .gep-image {
        max-width: 100%;
        height: auto;
        object-fit: contain;
    }

    .gep-testimonial {
        border: 2px solid #00664F;
        margin-bottom: 2rem;
        padding: 10px;
    }

    .flex-container {
        display: flex;
        gap: 1vw;
        margin: auto;
        flex-wrap: wrap;
        justify-content: center;
        overflow: hidden;
    }

    @media only screen and (max-width: 500px) {
        .GEP-column-container {
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            gap: 7px;  
            flex-wrap: wrap;
        }

        .img-GEP {
            max-width: 100%;
            width: auto;
            height: auto;
            object-fit: contain;
        }

        #GEP-column-item-middle {
            border-left: 0px solid #00664F;
            padding-left: 0rem;
            border-right: 0px solid #00664F;
            padding-right: 0rem;
        }
    }

</style>

# About the Programme

GEP provides Year 5 Josephians with opportunities for physical challenges, cultural engagement and community service outside Singapore. The aim is for students to acquire the knowledge base and understanding of global issues and develop skills to take action towards creating a better world. The programme embraces both SJI and IB's vision of developing caring global citizens who will be a catalyst for change and to make a difference to the world.

In addition, the GEP leverages on the innovative programmes and dynamic learning environments which the IB programme offers for an easy and effective alignment to SDGs challenging Josephians to make a significant impact on the SDGs. Through the [Creativity, Activity, Service (CAS)](https://www.sji.edu.sg/programmes/student-development-programmes/creativity-activity-service-cas/) programme, students are challenged to make a difference in the lives of others.

---

<div class="GEP-column-container">
    <div class="GEP-column-item">
        <img src="../assets/images/gep/international-trips.jpeg" class="gep-image">
        <h2>International Trips</h2>
        <p>Our end-of-year trips allow our Year 5 students to travel to various countries in the region and learn more about their cultures as well engage themselves in various unique and fulfilling experiences</p>
    </div>
    <div class="GEP-column-item" id="GEP-column-item-middle">
        <img src="../assets/images/gep/cura.jpeg"  class="gep-image">
        <h2>CURA</h2>
        <p>Organised by our school, CURA is an online international exchange program focused on the United Nations Sustainable Development Goals. Students from schools across the globe come together to share unique and interesting ideas to target current and future issues which the world may face</p>
    </div>
    <div class="GEP-column-item">
        <img src="../assets/images/gep/exchange-programs.jpeg" class="gep-image">
        <h2>Exchange Programme</h2>
        <p>SJI regularly hosts exchange programmes with students from across the globe, such as from Japan, Israel, Kazakhstan and many more countries, which allow our students to interact and gain unique perspectives from peers around the world and hence increasing their global awareness</p>
    </div>
</div>

---

# Join Us on Our Field Trips in 2023!
Join our Josephians vicariously on our various field trips to different countries in 2023!

{% include components/gep-trip.html %}