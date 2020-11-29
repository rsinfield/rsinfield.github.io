

## Robert Sinfield test reel  



### Arcgis online 

<button class="tablink" onclick="openPage('Home', this, 'red')">Home</button>
<button class="tablink" onclick="openPage('News', this, 'green')" id="defaultOpen">News</button>
<button class="tablink" onclick="openPage('Contact', this, 'blue')">Contact</button>
<button class="tablink" onclick="openPage('About', this, 'orange')">About</button>

<div id="Home" class="tabcontent">
  <h3>Home</h3>
  <p>Home is where the heart is..</p>
</div>

<div id="News" class="tabcontent">
  <h3>News</h3>
  <p>Some news this fine day!</p>
</div>

<div id="Contact" class="tabcontent">
  <h3>Contact</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>




<style>
.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}

.testiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}

.rsiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>



<div id="About"  class="resp-container">
    <iframe class="testiframe" src="https://nelcsu.maps.arcgis.com/apps/webappviewer/index.html?id=771aca46caeb43a388dcf21beced7814">
      Fallback text here for unsupporting browsers, of which there are scant few.
    </iframe>
</div>



