---
title: "Conferences"
date: 2023-09-10T14:19:03+05:30
---

<div class="card">
<h3 class="title">BSidesNoVA, Northern Virginia [Sep 9, 2023]
</h3>
<div class="bar" style="">
    <div class="emptybar" style="width: 410px;"></div>
    <div class="filledbar" ></div>
    <div class="description">
        - attended "Defending Against API Attacks" by Hitesh B and learnt about OWASP's top 10 API threats. <br>
        - participated in the fun class of "Initial Actions on Active Directory Targets" by Tinker Secor and <br> learnt active directory dumps, SYSVOL access and and discovering hidden remnants.<br>
        - Networked with leading cybersecurity professionals and experts from various companies. <br>
        - won a book, 'The Art of Cyberwarfare' for collecting all the stamps.
    </div>
</div>
</div>

<br>


<img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc_YPO85ySOkvLggw9RYidxiUHaFN0tumBHFvK6N41zOyqLN5jPH9fRfLjshIKixH2Jkp9zy25ZsylwabAuRlwIWw-0Z9_ESKQgySWInwYnzkm6EDIdy5eMCOyI2I4zDtFAH2IJy1-7Sj-6sl7u3IoQT=w575-h1024-s-no"  style="width: 10%;">  

<img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc9qwC_lFZSMsnSq8IxVFvJEkWB27ODxZioDA314EsrKis8oLJGPch4v_jm4ZGarJqthDwgMdyXBn1hDr2QTaK1-EDgsONJwjCrpMQk0zZnFM2qJfepHdTA7SnC_X0Eq_YLwmCjifpYkEkI1JhZpc7iQ=w636-h1130-s-no"  style="width: 10%;">

<img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc9av6-k39KjWmr0GUQBvC4GMrppGDicM-AheYlfDbpA2v0lTJXHvxP-4mg1WGDDRyp4gkX7CzjVh6wY7a0EFA-JO87SUR6RJyanESu5AvemsM-yr12DAr5lTVe_-sKb9dM_OK7SNNApoZbUka09CeWQ=w636-h1130-s-no"  style="width: 10%;">

<img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc-5nI3uS_DTZwHf8FtV5eKJMMOdcZWTk44gLh-kbtsMurlM6aj5fN6VyueQkyjbfKfVgo1srRFx_3UH4uiz1g34HqtTBIbB_36BiPN4-Frx_L7zhEcaVnGy91nz1r6gLQ6mc0pBiDj3P0IiNF37TX3d=w636-h1130-s-no"  style="width: 10%;">

<br>




<style>

.container {
  grid-template-columns: auto auto; 
  grid-gap: 20px; 
}

.container img,
.container script {
  vertical-align: top; 
}

.container script {
  margin-top: 105px; 
}

i{
    color: #777;
}

.projecttags{
 margin-top: 95px;
 width: 950px;
}
    
#linkurl{
    vertical-align: middle;
}
.year{
    color: #9F73AB;
    font-size: 13px;
    top: 15px;
}

.card {
  display: flex;
  height: 150px;
  width: 1400px;
  
  border-radius: 10px;
  box-shadow: -1rem 0 3rem #000;
/*   margin-left: -50px; */
  transition: 0.3s ease-out;
  position: relative;
  left: 50px;
}

.card:not(:first-child) {
    margin-left: -50px;
}

.card:hover {
  transform: translateY(-10px);
}

.card:hover .description{
    color: #fac8d2;
}


.title {
  color: white;
  font-weight: 300;
  position: absolute;
  left: 20px;
  top: 15px;
}

.bar {
  position: absolute;
  top: 45px;
  left: 20px;
  height: 5px;
}

.description{
  position: absolute;
  top: 20px;
  height:0px;
  width: 1050px;
  color: grey;
  left: 20px;
  transition: opacity 0.3s ease-out;
}


.emptybar {
  background-color: #2e3033;
  width: 100%;
  height: 100%;
}

.filledbar {
  position: absolute;
  top: 0px;
  z-index: 3;
  width: 0%;
  height: 100%;
  background: rgb(0,154,217);
  background: linear-gradient(90deg, rgba(0,154,217,1) 0%, #ff808c 65%, #ff3045 100%);
  transition: 0.2s ease-out;
}

.card:hover .filledbar {
  width: 100%;
  transition: 0.6s ease-out;
}

.circle {
  position: absolute;
  top: 150px;
  left: calc(50% - 60px);
}

.stroke {
  stroke: white;
  stroke-dasharray: 360;
  stroke-dashoffset: 360;
  transition: 0.6s ease-out;
}


.card:hover .stroke {
  stroke-dashoffset: 100;
  transition: 0.6s ease-out;
}

</style>

<style>
  
    span{
    font-size:15px;
}

img {
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.4), 0px 4px 16px rgba(0, 0, 0, 0.2);
    border-radius: 10px;
    margin-top: 50px;
    margin-left: 40px;
}

p {
    animation-name: fade-in;
    animation-duration: 1s;
    animation-delay: 0s;
    animation-fill-mode: forwards;
    opacity: 0;
}
  
@keyframes fade-in {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
}

#anchor{
    background-color:#000;
    color: #000;
}

#logo {
    transition: transform 0.8s ease-in-out;
  }
  
#logo:hover {
    transform: scale(3);
  }

</style>