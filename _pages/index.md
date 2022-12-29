---
layout: default
pagination:
  enabled: true
permalink: /
---
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

<style>
* {
  box-sizing: border-box;
}
body {
  background-color: white;
}
/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 600px;
  margin-left: 100px;
  margin-right: 150px;
}
/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 3px;
  background-color: rgb(234, 204, 206);
  top: 10%;
  bottom: 15%;
  left: 0%;
  margin-left: 0px;
}
/* Container around content */
.container {
  padding: 5px 20px;
  position: relative;
  background-color: white;
  width: 100%;
}
/* The circles on the timeline */
.container::after {
  content: ' ';
  position: absolute;
  width: 13px;
  height: 13px;
  right: 50px;
  background-color: rgb(234, 204, 206);
  top: 30px;
  border-radius: 50%;
}
/* Place the container to the left */
/* .left {
  left: 0;
} */
/* Place the container to the right */
/* .right {
  left: 0%;
} */
/* Add arrows to the left container (pointing right) */
/* .left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 5px 0 5px 5px;
  border-color:  rgb(234, 204, 206);
} */
/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 10px;
  border: medium solid white;
  border-width: 5px 5px 5px 0;
  border-color: transparent white transparent transparent;
}
/* Fix the circle for containers on the right side */
.right::after {
  left: -5px;
}
/* The actual content */
.content {
  padding: 5px 5px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}
/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 500px) {
  /* Place the timelime to the left */
  /* .timeline::after {
  left: 31px;
  }  */
  /* Full-width containers */
  .container {
  width: 100%;
  padding-left: 10px;
  padding-right: 10px;
  }
  /* Make sure that all arrows are pointing leftwards */
  .container::before {
  left: 0px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
  }
  /* Make sure all circles are at the same spot */
  .left::after, .right::after {
  left: 5px;
  } 
  /* Make all right containers behave like the left ones */
  .right {
  left: 0%;
  }
}
</style>
</head>
<body>
<section id="#" class="cont" style="wdith:100%; background-color:rgb(234, 204, 206); height:600px">
  <div class="grid-xlarge">
  <div style="display: flex">
      <!-- <section style="margin-left:70px; margin-right:10px"><img style="width:400px;" 
      src="assets/images/logo/22.png" />
      </section> -->
      <section class="center" style="margin-left:90px; "><img style="width:400px;" 
      src="assets/images/logo/por-01.png">
      </section>
      <section class="cta__text" style="margin-right:0px; margin-top:20px; font-size:70px; font-family:Apercu">
      <span>Hi, I am Nan Wang.</span> <br>
      <span>A <span style="color:white">D</span>esigner,</span><br>
      <span><span style="color:white"> E</span>ngineer,</span><br>
      and <span style="color:white">E</span>ntrepreneur.
      </section>
  </div>
  </div>
</section>

<!-- resume -->
<div class="grid-xlarge">
<div style="display: flex; ">
<div class="timeline" >
<span style="font-family:Apercu; font-size:20px; color:rgb(218, 162, 171)">EXPERIENCE</span>
<br>
  <div class="container right">
    <div class="content">
      <h5>Brandeis University, Teaching Assistant</h5>
      <p style="font-size:12px">Sep 2022 - Dec 2022 </p>
    </div>
  </div>
  <div class="container right" >
    <div class="content">
      <h5 >Yum China Holdings Inc, Design & Innovation Manager</h5>
      <p style="font-size:12px">Apr 2018 - Jul 2021 </p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h5>Shanghai Inoherb Cosmetics Co., LTD, Product Design Manager</h5>
      <p style="font-size:12px">Dec 2015 - Apr 2018 </p>
    </div>
  </div>
    <div class="container right" >
    <div class="content">
      <h5>Shanghai Jahwa United Co., LTD, Senior Product Designer</h5>
      <p style="font-size:12px">Oct 2012 - Nov 2015 </p>
    </div>
  </div>
</div>
<section style=" margin-left:20px">
<span style="font-family:Apercu; font-size:20px; color:rgb(218, 162, 171)">SKILLS</span>
<div class="container">
  <p style="font-size:16px; margin-top:10px"><strong>Programming</strong></p>
  <div class="progress" style="width:100%">
    <div class="progress-bar" role="progressbar" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" 
    style="width:85%; background-color:rgba(234, 204, 206, 0.5)">
      85%
    </div>
  </div>
  <p style="margin-top:-15px; color:rgb(130, 130, 130); font-size:12px">Java, Python, HTML/CSS, JavaScript, NodeJS, SQL, Git, Blender, jQuery</p>
  <p style="font-size:16px; "><strong>UX/UI Product Design</strong></p>
  <div class="progress">
    <div class="progress-bar" role="progressbar" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100" 
    style="width:95%; background-color:rgba(234, 204, 206, 1.1)">
      95%
    </div>
  </div>
  <p style="margin-top:-15px; color:rgb(130, 130, 130); font-size:12px">Photoshop, Illustrator, InDesign, Rhinoceros, Keyshot, 3Dmax, SolidWorks, Painter </p>
  <p style="font-size:16px"><strong>Engineering</strong></p>
  <div class="progress">
    <div class="progress-bar" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" 
    style="width:80%; background-color:rgba(234, 204, 206, 0.5)">
      80%
    </div>
  </div>
  <p style="margin-top:-15px; color:rgb(130, 130, 130); font-size:12px">Prototype development, Material/Printing/3D techniques,  Manufacturing Corporation </p>
  <p style="font-size:16px; "><strong>Leadership & Management</strong></p>
  <div class="progress">
    <div class="progress-bar" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" 
    style="width:90%; background-color:rgba(234, 204, 206, 1.1)">
      90%
    </div>
  </div>
    <p style="margin-top:-15px; color:rgb(130, 130, 130); font-size:12px">Product Management, Time Management, Creative Problem-solving, Corporation </p>
</div>
</section>
</div>

<div class="honors" style="display: flex;  margin-top:25px;  margin-bottom:50px">
<section class="awards" style="max-width: 1000px; margin-left:100px;margin-right:170px;">
 <span style="font-family:Apercu; font-size:20px; color:rgb(218, 162, 171)">SELECTED AWARDS
 <span style="font-family:Apercu; font-size:12px; color:rgb(218, 162, 171)">(3/18)</span>
 </span>
 <div style="margin-top:20px; display: flex">
  <div style="color:rgb(218, 162, 171)">2019</div>
  <div style="margin-left:20px; font-size:14px;" >
    <h5 style ="margin-top:0px">Recognition Award</h5>
    <span style =" color:rgb(140, 140, 140); font-size:12px;" >Yum! Brands-Yum China, China </span>
  </div>
</div>
 <div style=" margin-top:20px; display: flex">
  <div style="color:rgb(218, 162, 171)">2015</div>
  <div style="margin-left:20px; font-size:14px;" >
    <h5 style ="margin-top:0px">APD (Asian Packaging Design) Gold Award</h5>
    <span style =" color:rgb(140, 140, 140); font-size:12px;" >China, Korea, Taiwan, Tokyo </span>
  </div>
</div>
 <div style=" margin-top:20px; display: flex">
  <div style="color:rgb(218, 162, 171)">2012</div>
  <div style="margin-left:20px; font-size:14px;" >
    <h5 style ="margin-top:0px">Gold Award, Eastern Star “Hong Kong Wing Fat Cup”  Design</h5>
    <span style =" color:rgb(140, 140, 140); font-size:12px;" >China </span>
  </div>
</div>
</section>


<section class="patents" style="margin-left:20px; max-width: 490px;  ">
  <span style="font-family:Apercu; font-size:20px; color:rgb(218, 162, 171)">SELECTED COMMERCIAL PATENTS
    <span style="font-family:Apercu; font-size:12px; color:rgb(218, 162, 171)">(4/37)</span>
  </span>

  <div style="margin-left:20px; margin-top:20px; font-size:14px;" >
    <h5 style ="margin-top:0px">Nan Wang, Packaging: Whitening & UV Protective Set, 2015, CN303327317S.</h5>
  </div>
  <div style="margin-left:20px; margin-top:20px; font-size:14px;" >
    <h5 style ="margin-top:0px">Nan Wang, Packaging box: 3, 2016, CN303560646S.</h5>
  </div>
  <div style="margin-left:20px; margin-top:20px; font-size:14px;" >
    <h5 style ="margin-top:0px">Nan Wang, Packaging: Herborist Ultra Hydrating & Moisturizing Set, 2014, CN303195583S.</h5>
  </div>
  <div style="margin-left:20px; margin-top:20px; font-size:14px;" >
    <h5 style ="margin-top:0px"><span style="color:rgb(140, 140, 140); font-weight: normal">Huan Meng, </span>Nan Wang, <span style="color:rgb(140, 140, 140); font-weight: normal">Donglei Guo, Yunjie Han, </span>Packaging: Fresh Herb Cream Bottle Shape Series Design, 2014, CN303029101S.</h5>
  </div>
</section>
</div>
  

<section id="projects" style="width=100%; background-color:rgba(180, 180, 180, 0.15)">
<div class="posts">
  <div class="grid-xlarge">
    <h2 class="post_title">
      <span>Selected Projects</span>
    </h2>

    <div class="posts__container" data-columns>
      {% assign sorted_projects = site.posts | sort: 'highlight' %}
      {% for post in sorted_projects %}

        <!-- The tag below includes the markup for each post - partials/post-card.html -->
        {% include post-card.html %}

      {% endfor %}
    </div>
  </div>

</div>
</section>


<section id="waving" class="cta bg-black">
  <a class="cta__link" style="background-color: rgb(234, 204, 206)" href="{{ '/wl/' | prepend: site.baseurl }}">
    <span class="cta__text">Let’s Waving</span>
  </a>
</section>

