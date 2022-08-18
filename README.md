# hello-world
A repository about coding
I'm currently an Information Communication Engineer. I'm also very good in graphics design
<!DOCTYPE html>
<head>
  <title>Anna Dowlin</title>
  <style>
    body {
      text-align: center;
      background: url("http://dash.ga.co/assets/anna-bg.png");
      background-size: cover;
      background-position: center;
      color: white;
      font-family: helvetica;
    }
    p {
      font-size: 22px;
    }
    input {
      border: 0;
      padding: 10px;
      font-size: 18px;
    }
    input[type="submit"] {
      background: red;
      color: white;
    }
  </style>
</head>
<body>
  <img src="/assets/anna.png">
  <p>Hi! I'm Anna, a NYC-based marketer. Say hello!</p>
  <input type="email" placeholder="Your email">
  <input type="submit">
</body>
<!DOCTYPE html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
    header {
      text-align: center;
      background: url('http://dash.ga.co/assets/jeff-bg.png');
      background-size: cover;
      color: white;
    }
    a {
      color: white;
    }
    h1 {
      font-size: 70px;
    }
    img {
      margin: 40px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 10px;
      background: rgba(0,0,0,0.5);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width: 500px;
      padding: 20px;
      margin: 0 auto;
    }
    @media (max-width: 500px) {
      h1 {
        font-size: 36px;
        padding: 5px;
      }
      li {
        padding: 5px;
        display: block;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="/assets/jeff.png">
    <h1>Jeff's Blog</h1>
    <ul>
      <li><a href="#">About Me</a></li>
      <li><a href="#">Best Poems</a></li>
      <li><a href="#">Worst Poems</a></li>
    </ul>
  </header>
  <article>
    <h2>VHS umami pop-up trust fund</h2>
    <p>Marfa church-key kitsch bicycle rights, 8-bit mixtape cardigan gentrify Echo Park. Street art swag brunch, next level roof party Schlitz hella organic keffiyeh selfies. You probably haven't heard of them polaroid hashtag +1, meggings biodiesel Portland High Life cray tumblr retro.</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Sartorial synth Echo Park, roof party</h2>
    <p>chambray you probably haven't heard of them pour-over viral selvage umami skateboard VHS post-ironic selfies. Wes Anderson gentrify fanny pack twee, bicycle rights bitters blog keffiyeh plaid flannel. Tonx irony cliche sustainable mlkshk bitters. Four loko leggings chambray Vice.</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Forage food truck keytar master cleanse</h2>
    <p>ethical thundercats sustainable locavore quinoa Neutra. Aesthetic tacky sweater single-origin coffee, bicycle rights organic lo-fi street art american apparel ennui four loko ethnic Brooklyn small batch. Forage YOLO polaroid</p>
    <button>Like</button>
  </article>
  <script>
    $("button").on("click", function() {
      alert("Clicked!");
    });
  </script>
</body>
<!DOCTYPE html>
<head>
<script src="/assets/jquery.js"></script>
<link href='https://fonts.googleapis.com/css?family=Londrina+Shadow' rel='stylesheet' type='text/css'>
<style>
body {
  font-family: helvetica, sans-serif;
  margin: 0 auto;
  max-width: 600px;
  background: #232323;
}
div {
  height: 200px;
  background-size: cover;
  position: relative;
  margin: 40px 0 0 0;
  border-radius: 12px;
}
h1 {
  font-family: 'Londrina Shadow', cursive;
  text-align: center;
  font-size: 75px;
  color: #aaaaaa;
  margin: 60px 0 0 0;
}
h2 {
  text-align: center;
  color: #bbbbbb;
  margin: 0px 0 70px 0;
}
p {
  color: rgba(255,255,255,1);
  background: black;
  background: linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -webkit-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -moz-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  padding: 10px;
  line-height: 28px;
  text-align: justify;
  position: absolute;
  bottom: 0;
  margin: 0;
  height: 30px;
  transition: height .5s;
  -webkit-transition: height .5s;
  -moz-transition: height .5s;
}

small {
  opacity: 0;
}

.show-description p {
  height: 150px;
}

.show-description small {
  opacity: 1;
}

.first{
  background-image: url("http://dash.ga.co/assets/firstcourse.jpg");
}
.second{
  background-image: url("http://dash.ga.co/assets/secondcourse.jpg");
}
.dessert{
  background-image: url("http://dash.ga.co/assets/dessertcourse.jpg");
}
.price {
  float: right;
}
@media (max-width: 500px) {
  h1 {
    font-size: 50px;
    margin-top: 20px;
    line-height: 40px;
  }
  h2 {
    font-size: 20px;
    margin: 20px 0 30px 0;
  }
  div {
    margin: 20px 12px 0 12px;
  }
  p {
    font-size: 20px;
    line-height: 24px;
  }
  small {
    font-size: 16px;
  }
}

</style>

</head>

<body>
<h1>esha's restaurant</h1>
<h2>a New York City eatery</h2>
<div class="first">
  <p>welsh onion soko <span class="price">$14</span><br />
  <small>Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </small></p>
</div>

<div class="second">
  <p>pastrami boudin tongue <span class="price">$22</span><br />
  <small>Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</small></p>
</div>
  
<div class="dessert">
  <p>fruitcake marzipan pudding dragee <span class="price">$8</span><br />
  <small>Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</small></p>
</div>

<script>
  $('div').on('click', function() {
      $(this).toggleClass('show-description');
  });
</script>

</body>
<!DOCTYPE html>

<head>
<script src="/assets/jquery.js"></script>
<style>
</style>
</head>

<body>
<div class="prompt"></div>
<button>Next</button>
<script>
// List of prompts for the user
var prompts = [
	'Type your name',
	'Type an adjective',
	'Type a noun'
   ];

var answers=[];
// Keep track of current prompt we're on
var currentPrompt = 0;

// A function that will call the next prompt
var nextPrompt = function() {
  //if there's no answer in the form
  if (currentPrompt != 0){
    answers.push($('input').val());
  }
	// if there is a next prompt
	if (currentPrompt < prompts.length) {
		// put first prompt in all html elements with class 
		$('.prompt').html(prompts[currentPrompt] +'<br><input type="text">');
		// move the next prompt into variable currentPrompt 
		currentPrompt = currentPrompt + 1;
	}
	//or else if we're at the end of the array
	else {
		// put a new message into the html.
		showFinal();
	}
}

//puts user answers into HTML
var showFinal = function() {
  $('.prompt').html(answers[0]+' '+answers[1]+' '+answers[2]);
}
// run nextPrompt function when button is clicked
$('button').click(function() {
	nextPrompt();
});

// Show the first prompt as soon as js loads
nextPrompt();
</script>

</body>
<!DOCTYPE html>

<head>
<link href='https://fonts.googleapis.com/css?family=Poller+One' rel='stylesheet' type='text/css'>
<script src="/assets/jquery.js"></script>
<style>

.robot {
  position: relative;
  left: 200px;
}

.beep {
  width: 5px;
  height: 0;
  border: 5px solid transparent;
  border-top: 10px solid #777;
  border-bottom: 80px solid #888;
  position: relative;
  left: 140px;
}

@keyframes blink {
  50% {
    background: radial-gradient(circle, red 15%, transparent 40%), #cc5;
  }
}
@-webkit-keyframes blink {
  50% {
    background: -webkit-radial-gradient(circle, red 15%, transparent 40%), #cc5;
  }
}
@-moz-keyframes blink {
  50% {
    background: -moz-radial-gradient(circle, red 15%, transparent 40%), #cc5;
  }
}
.laser {
  animation: blink .5s infinite;
  -webkit-animation: blink .5s infinite;
  -moz-animation: blink .5s infinite;
}
.brain {
  background: radial-gradient(circle, white 15%, transparent 40%), #cc5;
  background: -moz-radial-gradient(circle, white 15%, transparent 40%), #cc5; 
  background: -webkit-radial-gradient(circle, white 15%, transparent 40%), #cc5;
  background-size: 75px 150px;
  height: 150px;
  width: 150px;
  border-radius: 60px 60px 10px 10px;
  border-bottom: 40px solid #666;
  position: relative;
  left: 70px;
}
.torso {
  height: 0;
  width: 140px;
  border-top: 300px solid #bc6;
  border-left: 75px solid transparent;
  border-right: 75px solid transparent;
  border-radius: 20px 20px 100px 100px;
}
.left {
  font-family: 'Poller One', verdana, arial, sans-serif;
  font-weight: bold;
  font-size: 250px;
  color: #666;
  transform: rotate(200deg);
  -webkit-transform: rotate(200deg);
  -moz-transform: rotate(200deg);
  position: relative;
  top: -320px;
  left: -190px;
  z-index: -1;
}
.right {
  font-family: 'Poller One', verdana, arial, sans-serif;
  font-weight: bold;
  font-size: 250px;
  color: #666;
  transform: scaleY(-1) rotate(20deg);
  -webkit-transform: scaleY(-1) rotate(20deg);
  -moz-transform: scaleY(-1) rotate(20deg);
  position: relative;
  top: -620px;
  left: 190px;
  z-index: -1;
}
.foot {
  height: 40px;
  width: 40px;
  background: #ccc;
  border-radius: 40px;
  border: 15px solid #999;
  position: relative;
  left: 110px;
  top: -10px;
  z-index: -1;
}
</style>
</head>

<body>

<div class="robot">
  <div class="beep"></div>
  <div class="brain"></div>
  <div class="torso">
    <div class="left">j</div>
    <div class="right">j</div>
  </div>
  <div class="foot"></div>
</div>

<button class="flash">laser eyes on/off</button>
<button class="color">change color!</button>
<script>
// When eyes button is clicked, toggle laser class on brain
$(".flash").click(function() {
  $(".brain").toggleClass('laser');
});

// When color button is clicked...
$(".color").click(function() {
  // assign each named color a random number 0-255
  var red = Math.floor(Math.random() * 255);
  var green = Math.floor(Math.random() * 255);
  var blue = Math.floor(Math.random() * 255);
  
  //Display the three values in an alert window
  alert(red + "," + green + "," + blue);
});
</script>
</body>
