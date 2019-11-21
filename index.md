---
layout: default
header: Volly Unite 2020
nav: index
---

<section class="pycon-banner wrapper">
  {% asset banner-image alt="" class="banner-img bg" %}
  {% asset sun.png alt="" class="circle loading bg" %}
  {% asset cloud-small.png alt="" class="cloud1 bg" %}
  {% asset cloud-small.png alt="" class="cloud-1 bg" %}
  {% asset cloud-long.png alt="" class="cloud2 bg" %}
  {% asset wind.png alt="" class="wind bg" %}
  {% asset wind.png alt="" class="wind_1 bg" %}

  <div class="container">
    <div class="row">
      <div class="col-md-6"></div>
      <div class="col-md-6">
        <div class="pycon-banner-text">
          <div class="text-center conference">
            <h1>{% asset logonew-01.png title="Volly Unite 2020" alt="Volly Unite 2020" width="60%" %}</h1>
            <p>
              <!--The premier conference in India on using and
              developing the python programming language. Stay tuned
              for further updates by <a
              href="https://goo.gl/forms/GdtTebWL7mn3oKtW2">subscribing
              to our announcements</a>.-->
              25th and 26th January 2020 BENGALURU

              
            </p>
          </div>
	  
          <div class="text-center pycon-speakers-img dwd-buyticket" style="position: relative;">
            <a target="_blank" rel="noopener"
               href="https://photos.app.goo.gl/RbMp67jSLjr5SrzVA" class="dwd-link">
               <strong>REGISTER NOW</strong>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
  {% asset tunnel-blue-entry.png alt="" class="tunnel2 bg" style="bottom: -5px;" %}
</section>

<section class="pycon-counter wrapper">
  <div class="counter">
    <div class="container">
      <div class="row text-center wow fadeInDown">
          <div class="col-md-4 text-center">
            <div class="con">
              {% asset bracket-left.png class="sbac1" alt="" %}
              <h3><strong>Initial Mock up</strong></h3>
              <h4></h4>
              <h5 style="font-weight: 500">Volley Unite</h5>
              {% asset bracket-right.png class="sbac2" alt="" %}
            </div>
          </div>

          <div class="col-md-4 text-center">
            <div class="con">
              {% asset bracket-left.png class="sbac1" alt="" %}
              <h3><strong>Venue</strong></h3>
              <h4>25-26 January</h4>
              <h5 style="font-weight: 500">Somewhere</h5>
              {% asset bracket-right.png class="sbac2" alt="" %}
            </div>
          </div>


            <div class="col-md-4 text-center">
            <div class="con">
              {% asset bracket-left.png class="sbac1" alt="" %}
              <h3><strong>Developed</strong></h3>
              <h4></h4>
              <h5 style="font-weight: 500"></h5>
              {% asset bracket-right.png class="sbac2" alt="" %}
            </div>
          </div>

      </div>
    </div>
  </div>

  {% asset yellowwind.png alt="" class="wind-1 bg" %}
</section>

{% include keynote-speakers.html %}

{% include schedule.html %}

{% include tickets.html %}

{% include sponsors.html %}

<section class="latest-updates wrapper">
  <div class="wow fadeIn">
    <div class="col-md-12 text-center">
      <h2><strong>LATEST UPDATES</strong></h2>
    </div>
  </div>
  <br />
  <div class="container">
    <div class="row wow fadeIn">
      <div class="col-md-10 col-md-offset-1">
        <div class="col-md-6">
          <div class="updates">
            <!-- <h4>Tweets</h4> -->
            {% include twitter-feed.html %}
          </div>
        </div>
        <div class="col-md-6">
          {% include blog-feed.html %}
        </div>
      </div>
    </div>
  </div>
  {% asset tunnel-white-exit.png alt="" class="tunnel1 bg" %}
  {% asset temple-tower-small.png alt="" class="ratinum bg" style="z-index: -1" %}
  {% asset tunnel-white-entry.png alt="" class="tunnel2 tunnel4 bg" style="bottom: -5px;" %}
</section>

<section class="events-venue wrapper pycon-tab" >
  {% asset bluewind.png alt="" class="bluewind bg" style="left: 27%;top: -53px; z-index: 9999;" %}
  <div class="row wow fadeIn">
    <div class="col-md-12 text-center">
      <h2><strong>EVENT VENUE</strong></h2>
    </div>
  </div>
  <br /><br /><br />
  <div class="container">
    <div class="row wow fadeIn">
      <div class="col-md-10 col-md-offset-1">
        <div class="col-md-6">
          <div class="event-venue trade1 text-center">
            {% asset ctc.jpg alt="Chennai Trade Center" width="90%" %}
            <div class="bg-color"></div>
          </div>
          <div class="address">
            <h4><strong>CHENNAI TRADE CENTER</strong></h4>
            <p>OCTOBER 12, 13</p>
            <span>CTC Complex,<br /> Mount Poonamalle High Rd, Nandambakkam, Chennai, Tamil Nadu 600089</span>
            <div style="position: relative;">
              <a href="https://goo.gl/maps/SC9dmKXTpQSyKFPL8" class="dwd-link">VIEW LOCATION</a>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="event-venue trade2 text-center">
            {% asset iitm.jpg alt="IIT Madras" width="90%" %}
            <div class="bg-color"></div>
          </div>
          <div class="address">
            <h4><strong>IITM RESEARCH PARK</strong></h4>
            <p>OCTOBER 14, 15</p>
            <span>Kanagam Road, 32, Tharamani,<br />Chennai, Tamil Nadu 600113</span>
            <div style="position: relative;">
              <a href="https://goo.gl/maps/EpycaA2UhZG7V3uL6" class="dwd-link">VIEW LOCATION</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  {% asset light-house.png alt="" class="auto bg" %}
</section>
