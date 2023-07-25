---
title: ""
date: 2023-05-07T13:11:57+05:30
---



<center><img src="https://lh3.googleusercontent.com/pw/AIL4fc9roB195nVJQlTOelIDWWYoqUFz-7MPWv0Kca4voAwPB6vKQu7sO48qu6fu7TJonzSSbFOE5BIEvNoK8ZQNO0RwJzNJ6SXsWQSYPqqAU5ocRR4x7sLg0KUVhG7i3hC81Pb8f-DQvG15cq8vL-dQRbXa=w420-h420-s-no?authuser=1" style="width: 22%;"></center>




<center><span style="font-size:50px;color:#f5897f;font-family:MyFont;">Meet Vasanth Vanan</span><br><br><br>

**CybSec Graduate Student | Penetration Tester | Software Developer** 

Welcome to my Space. I often go by <a id="nameContainer"></a></center>

<br>
<center>
<span style="color:grey;">-- Find me more on --</span>
<br><br>

<p><a href="https://tryhackme.com/p/vasanth.vanan" id="anchor" target="_blank"><img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc-fjnCUqtvqeynh7FkHFSxPcQzcV-Nkz3g3TEhenubD_jXzbApCsoaAc11g0QPoIGsuC6ldiDkDEiQAo06Z8Wos23Q3OGgZpu2HxqV0y19Toqe6c7ZdOPj_HDSTXB0pa9_HOjqU9Kh45lodv3d5JRxQ=w803-h804-s-no" alt="TryHackMe" style="width: 3.6%;"></a>&nbsp;&nbsp;
   <a href="https://twitter.com/vasanth__vanan" id="anchor" target="_blank"><img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc-fcJnwRTrqlEApovHhXfge_yJTxOvKtnjoNzObdhOjhZBAR0cJGZF9_ykhwLUDZJG5GvN1gYw1N1pQ8WOocmlcWD_Dq4eJl4V3qNarpex7-Qct_swvutkv_WtGCpMhCLA8w6Y8nX64564q06OcmUmm=w803-h804-s-no" alt="Twitter" style="width: 3.6%;"></a>&nbsp;&nbsp;
   <a href="https://github.com/VasanthVanan" id="anchor" target="_blank"><img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc_3-Z7zxUvstUN8xxdy1OSGpZOfcxbxoKvJ5PF-dKwRkUWSIZ2U5CZAy1OO7Vtp-dRKnS7nC6app6UiIiwFoY1S6ju5lZEKlxWF8Fd9xxnAgVBHh5mNSlLxQioHmcGwvidXksZjRgqyICspK83FZzEO=w803-h804-s-no" alt="Github" style="width: 3.6%;"></a>&nbsp;&nbsp;
   <a href="https://www.linkedin.com/in/vasanthavanan/" id="anchor" target="_blank"><img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc8Aiy2yWXxiKoT3hHouNklHsYdeAyblx90n9TvNqxpsRi40SVrY8KmcrzZDLbiFL5GIhS8g5vpXi3Lm8e9t_4AV0QHvS8ud4Tum_bL3O5etO1NvtFTW_tQ2HyhuNzS2Wn-zRAHkFLM4SLS-i41wcYDl=w803-h804-s-no" alt="LinkedIn" style="width: 3.6%;"></a>&nbsp;&nbsp;
      <a href="https://medium.com/@vasanthavanan" id="anchor" target="_blank"><img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc90lRZyKOIdzA0J_hwOQh0UcV7FWQWzx0YNLxvlYQ3IWKdquIlTK0dXpkcbv_eNnTZcCLihtPrhCThriTuX0l_XGmSdUKT3e0crzz_Nv_j0kU_uij0W1jdq2uY9lsrTQPnLVeNW3Nu-F1WmJXQiPYJD=w803-h804-s-no" alt="Medium" style="width: 3.6%;"></a>&nbsp;&nbsp;
   <a href="https://www.instagram.com/vasanth_vanan/" id="anchor" target="_blank"><img id="logo" src="https://lh3.googleusercontent.com/pw/AIL4fc9kCtVPrnw7lrmLO7DePuq0sQxOf6NHMkt186r576eZcu3PFEBWVhgxun0mdne_MFxvYs-G-odJg7q_MjAgrXv7TFUnVvuRJ5JVx9Vr8Yq3Tw2_DdbU1PFlj3xdswWqhKGVuJFwscSCWUuISquhoDSE=w803-h804-s-no" alt="Instagram" style="width: 3.6%;"></a>
   </center>

<script>
  const names = ["vasanth_vanan", "vasanth.vanan", "vasanth__vanan", "VasanthVanan", "vasanthavanan", "busterbayliss8"];
let currentIndex = 0;

function shuffleArray(array) {
  for (let i = array.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [array[i], array[j]] = [array[j], array[i]];
  }
}

function displayNames() {
  shuffleArray(names);

  const nameContainer = document.getElementById("nameContainer");
  nameContainer.innerHTML = '';

  const nameElement = document.createElement("div");
  nameElement.classList.add("name");
  nameElement.textContent = `${names[0]}`;
  nameContainer.appendChild(nameElement);

  names = names.slice(1).concat(names[0]);
}

setInterval(displayNames, 1100);
</script>

<style>

@font-face {
  font-family: 'MyFont';
  src: url('/Amoitar.ttf') format('truetype');
}

@keyframes flicker {
  0%, 100% {
    opacity: 1;
  }
  50% {
    opacity: 0.6;
  }
}
    span{
    font-size:15px;
}

img {
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.4), 0px 4px 16px rgba(0, 0, 0, 0.2);
    border-radius: 10px;
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
    transition: transform 0.1s ease-in-out;
  }
  
  #logo:hover {
    transform: scale(1.3);
  }
</style>