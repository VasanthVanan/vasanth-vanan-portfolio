---
title: "Certifications"
date: 2023-05-07T14:18:54+05:30
---

<br>

<div class="certs">
<img id="logo" src="https://github.com/VasanthVanan/vasanth-vanan-portfolio/blob/main/static/certifications2.png?raw=true"  style="width: 18%;">&nbsp;
<img id="logo" src="https://github.com/VasanthVanan/vasanth-vanan-portfolio/blob/main/static/certifications4.png?raw=true"  style="width: 18%;">&nbsp;
<img id="logo" src="https://github.com/VasanthVanan/vasanth-vanan-portfolio/blob/main/static/certifications1.png?raw=true"  style="width: 18%;">&nbsp;
<img id="logo" src="https://github.com/VasanthVanan/vasanth-vanan-portfolio/blob/main/static/certifications3.png?raw=true"  style="width: 18%;">&nbsp;
<img src="https://github.com/VasanthVanan/vasanth-vanan-portfolio/blob/main/static/certifications5.png?raw=true"  style="width: 18%;">&nbsp;

---
CompTIA Network+ (verify: <a>Q85MJ88F734119GZ</a>) <br>
CompTIA Security+ (verify: <a>QGSWZKZP0DFQ19G3</a>) <br>
eLearnSecurity Junior Penetration Tester (eJPT) (verify: <a>6119394</a>) <br>
Certified Ethical Hacker (CEH) (verify: <a>ECC1982743650</a>) <br>
Offensive Security Certified Professional (OSCP) (for the future..)

</div>


<style>
    .certs {
    background: #000; /* Set the background color to white */
    position: relative;
    overflow: hidden;
    }

    .certs:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(
        to bottom,
        rgba(255, 255, 255, 0.2) 0%,
        rgba(255, 255, 255, 0.5) 50%,
        rgba(255, 255, 255, 0.2) 100%
    );
    animation: smoke 5s linear infinite;
    z-index: -1;
    }

    @keyframes smoke {
    0% {
        transform: translateX(-50%) translateY(-50%) rotate(0deg) scale(1);
        opacity: 0;
    }
    50% {
        opacity: 1;
    }
    100% {
        transform: translateX(-50%) translateY(-50%) rotate(360deg) scale(1.2);
        opacity: 0;
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

#logo {
    transition: transform 0.2s ease-in-out;
  }
  
  #logo:hover {
    transform: scale(1.14);
  }

</style>

<div class="footer">
    <font size="1">Image Source: TryHackMe</font>
</div>