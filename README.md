
<html>
<head>
<style>
* {
  box-sizing: border-box;
}
body {
  background-color: white;
}

.header, .footer {
  background-color: grey;
  color: white;
  padding: 20px;
}

.column {
  float: left;
  padding: 20px;
}

.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

.menu {
  width: 25%;
}

.content {
  width: 75%;
}

.menu ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.menu li {
  padding: 8px;
  margin-bottom: 8px;
  background-color: #33b5e5;
  color: #ffffff;
}

.menu li:hover {
  background-color: #0099cc;
}
</style>
</head>
<body>

<div class="header">
  <h1>Energy Usage</h1>
</div>

<div class="clearfix">
  <div class="column menu">
    <ul>
      <li>About</li>
      <li>More Info</li>
      <li>Links</li>
      <li>Settings</li>
    </ul>
  </div>

  <div class="column content">
    <h1>World is changing for the worse because of excessive energy use</h1>
    <h4>With the huge amounts of energy being used, which is the main cause to global warming, scientists have discovered new ways to solve this problem.</h4>
    <img id="Fusion" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQ2JiK_avhhqAYthfayGzJ5VSw9eKAapUmJg&usqp=CAU" width= "382" height="149" class="center">
    <p style="font-size: 16px; text-indent: 31px;">According to NASA, if you have incandescent and halogen lights, “only 10 percent of the energy they use goes toward light; the other 90 percent just generates heat.” In 2020 we used roughly 3 Trillion watts to power the world. 80% of that is fossil fuels, the other 20% are biofuels like wind and sun energy. Electricity demand is expected to increase by 80% by 2050</p>
    <p style="font-size: 16px; text-indent: 31px;">Scientists have been trying to figure out how to find a better way to use nuclear power, a very good clean source of energy. So far they have been using a process called fission, the process of a neutron slamming into a larger atom, forcing it to excite and split into two smaller atoms. Now, they have discovered a new process called fusion, where two light atoms bond together, or fuse, to make a heavier one and obtain a lot of energy. It's also what happens on the sun and other stars. This process might take a few decades to be put into use though.
</p>
<p style="font-size: 16px; text-indent: 31px;">In the last century, the climate has changed about 0.7 degrees celsius. That might not seem like a lot but that is roughly a 10 times the faster rate than normal. This is due to massive use of fossil fuels and the greenhouse gasses it is emitting. 76% of the greenhouse gasses is CO2, and it has increased by nearly 50% in the industrial era. 
</p>
<p style="font-size: 16px; text-indent: 31px;">Instead of depending on scientists, a way anybody else can help is by turning off lights when done using them. Another way is by spending less time in the shower. Keeping shower time to just 4 minutes could save a typical household $115.35 a year on their energy bills. With the energy demands that are soon to happen in the future, saving energy can help both you and everyone else.
</p>
  </div>
</div>

<div class="footer">
  <p>Thanks to https://www.w3schools.com</p>
</div>

</body>
</html>
