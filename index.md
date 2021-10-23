---
layout: base
title: "JV Sports | Competitive FIA Bronze Racing Driver"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index.js
ext-js:
  - //cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js
---

<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

# JV Sports {#title}

## James Vowles {#subtitle}

#### FIA Bronze Racing Driver {#sub-subtitle}

<a href="/contact" class="actionbtn">
  <span class="far fa-envelope" aria-hidden="true"></span>
  Contact Us
</a>
{: .actionbtn-out :}

</div>

<div id="main-sections">

<div id="services-out" class="page-section cut1">
  <div id="services">
    <div class="section-title">JV Sports - Services</div>
    <div id="services-list">
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/raceready.jpg" />
        <div class="service-text">Competitive, race ready FIA International C & FIA Bronze driver</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/team.jpg" />
        <div class="service-text">Winning knowhow; with 16 Formula 1 World Championships, and over 100 race wins achieved to date</div>
      </div>
      <div id="services-break"></div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/amg.jpg" />
        <div class="service-text">Rare combination of elite sport engineering, racing and driving experience</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/steeringwheel.jpg" />
        <div class="service-text">Performance under pressure at the highest level</div>
      </div>
    </div>

    <a href="/contact" class="actionbtn">
      <span class="far fa-envelope" aria-hidden="true"></span>
      Contact Us
    </a>
  </div>
</div>

<div class="cut-buffer aboutus-buffer"></div>

<div id="aboutus-out" class="page-section grey-section cut2">
  <div id="aboutus">
    <div class="section-title">About Us</div>
    <div id="aboutus-text">
      AttaliTech was launched in 2016 as the world's <b>first</b> Shiny consulting firm. The goal was simple: provide a one-stop shop for any and all of your Shiny needs, while adhering to the <b>highest standards</b>. Today, AttaliTech is a <b>global leader</b> in providing top quality R/Shiny services and is trusted by over 100 companies worldwide. We take pride in knowing you won't get better quality anywhere else.<br/><br/><b>We're certain of it.</b>
    </div>
  </div>
</div>

<div id="partners-out" class="page-section cut1">
  <div id="partners">
    <div class="section-title">Partners</div>
    <div id="partners-subtitle"></div>
    <div id="partners-logos">
      {% for partners in site.data.partners %}
        <a class="partners-img" href="{{ partners.url }}" title="{{ partners.name }}">
          <img alt="{{ partners.name }}" src="/assets/img/logos/{{ partners.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="aboutme-section-out" class="page-section grey-section cut2">
  <div id="aboutme-section">
    <div class="section-title">James Vowles</div>
	<div id="aboutme-list" markdown="1">
{% for info in site.data.main_info %}
{% if info.icon %}<span class="about-icon fa-fw {{ info.icon }}" aria-hidden="true"></span>{% endif info.icon %}
<span class="about-content">{{ info.content }}</span>
{: .about-text }
{% endfor %}
</div>
  </div>
</div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title">Contact us today to see what services are available</div><br/>
  </div>
  <a href="/contact" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Contact Us
  </a>
</div>

</div>
