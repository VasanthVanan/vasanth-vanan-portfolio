---
title: "Projects"
date: 2023-05-07T18:47:43+05:30
---

<br>

<div class="card">
<h3 class="title">Data Model Standardisation using Blockchain
</h3>
<div class="bar" style="width: 415px;">
    <div class="emptybar"></div>
    <div class="filledbar"></div>
    <div class="description">
    This project focused on a smart Hyperledger Fabric-based blockchain network ensuring data model integrity across FMS modules (IBM-SIS) with attribute rules, facilitating consistent and valid database table structures.<br>
    </div>
    <div class="projecttags"> Tags: <i>hyperledger,</i> <i>rest-api,</i> <i>data-integrity</i> </div>
</div>
</div>

---
  
<div class="card">
<h3 class="title">ZeroHunger - Ethereum Blockchain
<img src="/icon-link.png" alt="URL" style="width: 4%;" id="linkurl">
<a href="https://github.com/VasanthVanan/ZeroHunger-Ethereum-Blockchain" target="_blank">(github)</a>
</h3>
<div class="bar" style="width: 310px;">
    <div class="emptybar"></div>
    <div class="filledbar"></div>
    <div class="description">
    The main goal of this project is to reduce food waste, promote sustainable food systems, distribute food to the needy, and enhance cashless transfers using decentralised blockchain technology.
    </div>
    <div class="projecttags"> Tags: <i>ethereum,</i> <i>solidity,</i> <i>web3.js</i></div>
</div>
</div>


---
  
<div class="card">
<h3 class="title">AR-Bots using Augmented Reality</h3>
<div class="bar" style="width: 300px;">
    <div class="emptybar"></div>
    <div class="filledbar"></div>
    <div class="description">
    'AR-Bots' is an AR tour-guide android app with an augmented character, chatbot, and image recognition. It uses Vuforia, Unity, Tensor Flow, and IBM Watson to provide speech-based information sharing.
    </div>
    <div class="projecttags"> Tags: <i>unity,</i> <i>tenson-flow,</i> <i>ibm-watson</i></div>
</div>
</div>


<style>

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
  width: 1000px;
  
  border-radius: 10px;
  box-shadow: -1rem 0 3rem #000;
/*   margin-left: -50px; */
  transition: 0.3s ease-out;
  position: relative;
  left: 100px;
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
  width: 950px;
  color: grey;
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

