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

<div id="header" markdown="1">

<div id="header-inner" class="header-image" markdown="1">


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

<div id="news-out" class="page-section cut1">
  <div id="news">
    <div class="section-title">Latest News</div>
    <div id="news-subtitle"></div>
    <div id="news-logos">
      {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
      {% endfor %}

    </div>
  </div>
</div>

<div class="cut-buffer aboutus-buffer"></div>

<div id="aboutus-out" class="page-section grey-section cut2">
  <div id="aboutus">
    <div class="section-title">About Us</div>
    <div id="aboutus-text">
      JV Sports was founded in 2021. James Vowles started working in Formula 1 in 2001, gaining experience in both Race and Test Engineering alongside Race Strategy. Around the busy Formula 1 calendar James has raced around Europe in a mixture of series, from single seaters to LMP3. The goal of JV Sports is to drive with the very best teams, and win Lemans in the newly introduced GT3 category.
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
