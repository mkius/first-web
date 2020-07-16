# first-web
<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title> personal website</title>
  <link rel="stylesheet" href="css/styles.css">
  <link rel="icon" href="pencil logo.ai">
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300&family=Montserrat:ital,wght@1,600&family=Sacramento&display=swap" rel="stylesheet">
</head>

<body>
  <div class="top">
    <img class="top-cloud" src="image/cloud.png" alt="cloud-image">
    <h1><em>I'm usman</em></h1>
    <h2>a web designer</h2>
    <img class="bottom-cloud" src="image/cloud.png" alt="cloud-image">
    <img class="cartoon-img" src="image/mountain.png" alt="mountain-image">

  </div>
  <!.....2nd div contanir .>
  <br><br>
  <div class="middle">
    <div class="middle-container">
      <div class="profile">
        <img src="image/person.png" alt="person-img">
        <h2>Hello.</h2>
        <p class="intro">Hy, I am syed usman.I started this project one month ago.It is my first project.</p>
      </div>
      <hr>
      <div class="skills-row">
        <h2 class="my-skill">My Skills.</h2>
        <div class="skill-row">
          <img class="pc-img" src="image/pc.png" alt="pc-img">
          <h3>Design and Development</h3>
          <p>“Learning to write programs stretches your mind, and helps you think better,<br> creates a way of thinking about things that I think is helpful in all domains.”</p>
        </div>
        <div class="skill-row">
          <img class="coding-img" src="image/coding.png" alt="coding-img">
          <p>"The future belongs to those who believe in the beauty of their dreams." </p>

        </div>
      </div>
      <br><br>
      <hr>

  </div>

<!....3nd link...>
  <div class="bottom">
    <div class="contact-me">
      <h2>Get In Touch</h2><br><br>
      <a class="btn" href="mailto:name@email.com">CONTACT ME</a><br><br><br>
    </div>
    <div class="my-para">
      <p>" I started this project three month ago with friends that we  make a own website .
      one month we try to made a website with google site,word press etc but we not built it.
     So we decide to made a website with devolper. He made it but I did not like develper website.
  Than I decide that i would be made own website.About one month i lean adobe illusted then at last made a logo own website.know i learning html and css.
After five week afect a made this web .If you decide than nothing impossible " </p>

    </div>
  </div>

<br><br>

  <div class="bottom-container">
    <br>
    <a  href="https://www.linkedin.com/">LinkedIn</a>
    <a  href="https://twitter.com/">Twitter</a>
    <a  href="https://www.app.co/">Website</a>

    <p>© 2020 Name :SYED USMAN.</p>
  </div>
  </div>

</body>

</html>
body{
  color:#40514E;
  background-color:#e4f9f5;
  margin: 0;
  text-align:center;
font-family: 'Merriweather', serif;

}
h1{
  color: #66BFBF;
  margin-top: 0 ;
font-family: 'Sacramento', cursive;
font-size: 90px;
}
h2{
  color: #66BFBF;
  font-family: 'Montserrat', sans-serif;
  font-weight: normal;
  font-size: 30px;

}
h3{
  color: #11999E;
  font-family: 'Montserrat', sans-serif;
}
.top{
  background-color:#e4f9f5;
  position: relative;
  padding-top: 100px;
}

.bottom-cloud{
  position: absolute;
}
.top-cloud{
position: relative;
left: 300px;
top:10px;
}
.skill-row{
  width: 50%;
  margin: 100px auto 100px auto;
  text-align: left;

}
p{
  line-height: 2;
}
hr{
  border:dotted 6px;
  border-bottom: none;
  width: 4%;
  margin: 50px auto;
}
.pc-img{
  width: 25%;
  float: left;
  margin-right: 50px;
}
.coding-img{
  width: 25%;
  float: right;
  margin-right: 70px;
  margin-left: 50px;
  margin-bottom: 80px;
}
.intro{
  width:30%;
  margin: auto;
}
.bottom-container{
  background-color: #66BFBF;
  padding: 50px 0 20px;
}

a
{
 text-decoration: none;
 margin: 10px 20px;

}
a:hover{
  color: #e84545;
}
.my-skill{
  width: 60%;
}

.btn {
  background: #11CDD4;
  background-image: -webkit-linear-gradient(top, #11CDD4, #11999E);
  background-image: -moz-linear-gradient(top, #11CDD4, #11999E);
  background-image: -ms-linear-gradient(top, #11CDD4, #11999E);
  background-image: -o-linear-gradient(top, #11CDD4, #11999E);
  background-image: linear-gradient(to bottom, #11CDD4, #11999E);
  -webkit-border-radius: 9;
  -moz-border-radius: 9;
  border-radius: 9px;
  font-family: 'Merriweather', serif;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  border: solid #1f628d 2px;
  text-decoration: none;
}

.btn:hover {
  background: #30e3cb;
  background-image: -webkit-linear-gradient(top, #30e3cb, #2cb4ad);
  background-image: -moz-linear-gradient(top, #30e3cb, #2cb4ad);
  background-image: -ms-linear-gradient(top, #30e3cb, #2cb4ad);
  background-image: -o-linear-gradient(top, #30e3cb, #2cb4ad);
  background-image: linear-gradient(to bottom, #30e3cb, #2cb4ad);
  text-decoration: none;
}
.my-para{
  width: 60%;
  margin-left: 300px;
}
