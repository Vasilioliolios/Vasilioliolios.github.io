<html><head><title>A Look Inside.</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inconsolata">
<style>
body, html {
    height: 100%;
    font-family: "Inconsolata", sans-serif;
}
.bgimg {
    background-position: center;
    background-size: cover;
    background-image: url("w3images/coffelaptop.jpeg");
    min-height: 75%;
}

</style>
</head><body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-black">HOME</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-black">ABOUT</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-black">UTILITY BELT</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-black">WHERE</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">

  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white" style="font-size:90px"><br></span>
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
    <span class="w3-text-white"></span>
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">About Me</span></h5>
    <p>My name is Vasilios Kostakis, I was born in the summer of 1993, in Flushing NY.  My interest for programming came from a young age, but it was not until I was older that I acted on these interests.  I am decently fresh when it comes to the coding world,  but I have a fervor in constatnly learning new things and increase the tools on my belt.</p>
    <p>The current languages that I am comfortable with and know are for web development, but I do not plan to stop there and only to expand my horizons.  I have many goals, but one goal is to hopefully be able to use my knowledge in the game industry.</p>
    <div class="w3-panel w3-leftbar w3-light-grey">
      <p><i>"There is nothing permanent, except change." </i></p>
      <p>Heraclitus of Ephesus</p>
    </div>
    <img src="w3images/smoking.gif" style="width:100%;max-width:1000px" class="w3-margin-top">
    <p><strong></strong></p>
    <p><strong></strong></p>
  </div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">

    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">Skills and Hobbies</span></h5>

    <div class="w3-row w3-center w3-card w3-padding">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Eat');" id="myLink">
        <div class="w3-col s6 tablink">Skills</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Drinks');">
        <div class="w3-col s6 tablink">Hobbies</div>
      </a>
    </div>

    <div id="Eat" class="w3-container menu w3-padding-48 w3-card">
      <h5>HTML</h5>
      <p class="w3-text-grey">Well versed in html and comfortable with anything.</p><br>

      <h5>CSS</h5>
      <p class="w3-text-grey">I understand CSS quite well even if I do find it a bit tedious.</p><br>

      <h5>Javascript</h5>
      <p class="w3-text-grey">I am very confident in my ability of javascript, and do enjoy learning new things.</p><br>

      <h5>PHP and Ajax</h5>
      <p class="w3-text-grey">Pursuing to increase my usage of PHP, I only have a basic level of PHP and Ajax.</p><br>

      <h5>jQuery</h5>
      <p class="w3-text-grey">A good foundation because of my usage of javascript.</p>
    </div>

    <div id="Drinks" class="w3-container menu w3-padding-48 w3-card">
      <h5>Gaming</h5>
      <p class="w3-text-grey">Can not deny my favorite and first hobby.  Learning code has only made my perception grow, where once if some anomaly happened in game I would brush it off, but now I question what caused that reaction.</p><br>

      <h5>Networking/Socializing</h5>
      <p class="w3-text-grey">I enjoy meeting new people, especially other programmers.  Everytime I discuss code with someone it's a learning experience.</p><br>

      <h5>Programming</h5>
      <p class="w3-text-grey">Every time I read or write code, I feel as if im doing a puzzle.  I just need to put the right pieces in the right places.</p><br>

      <h5>Sleeping</h5>
      <p class="w3-text-grey">Who doesn't love a good nap.</p><br>

      <h5>Learning</h5>
      <p class="w3-text-grey">Getting the opportunity to learn code has lit a fire where I thought, had burned out, I constantly want to learn new things, be it languages or tips and tricks.</p>
    </div>
    <img src="w3images/racoon.jpeg" style="width:100%;max-width:1000px;margin-top:32px;">
  </div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">Where to find me.</span></h5>
    <p>I like to tell myself I'm approachable, so please feel free to contact me.</p>
    <img src="w3images/nycanime.png" class="w3-image" style="width:100%">
    <p><span class="w3-tag"></span></p>
    <p><strong></strong></p>
    <form action="mailto:vasilioskostakis93@gmail.com" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required="" name="Name"></p>
      <p></p>
      <p></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message" required="" name="Message"></p>
      <p><button class="w3-button w3-black" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
</div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">

</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
     tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>



</body></html>
