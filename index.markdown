---
layout: home
title: Home
---

<section class="py-5 text-center container">
    <div class="row py-lg-5">
      <div class="col-lg-9 col-md-8 mx-auto" style="background-color: #ebebeb; padding: 20px; border-radius: 15px; padding-top: 60px">
        <h1 class="fw-light">Research Software Engineers at ASU</h1>
        <p class="lead text-muted">We are a group of Research Software Engineers (RSEs) at Arizona State University. Do you do RSE work at ASU? Come join us!</p>
        <p>
        Do you want to get informed about our events and what is happening at ASU in regards to research software engineering?  
        </p>
        <p><a class="btn btn-primary my-2" href="https://forms.gle/pUaWvRWuxTWEX1VG6" target="_blank">Sign up for our mailing list!</a>
        </p>
        <p>
          Do you have questions? <a href="mailto:jdamerow@asu.edu">Send us an email!</a>
        </p>
      </div>
    
      <div class="col-lg-3 col-md-8 mx-auto" style="padding: 20px; padding-top: 40px">
      <h3>Upcoming Events</h3>
      <!--<p>
        <i class="fas fa-graduation-cap"></i> <a href="{{ "/code-coffee" }}"><b>Code & Coffee</b> on Monday, October 21, 2024, 11am MST. Mini-tutorial: <i>Issue Tracking with GitHub</i></a>
      </p>
      <p>
       <i class="fas fa-bullhorn"></i> <a href="{{ "event/2024/07/09/raming-talk.html" }}"><b>ASU-RSE Seminar Series with Dr. Wren Raming</b> on Thursday, September 19, 2024, 11am MST.</a>
      </p>-->
      <p>
        <i class="fas fa-comments"></i> <a href="{{ "/get-together" }}">ASU-RSE Get-Together on October 28, 2024, 11am MST. Discussion topic: <i>Teaching Research Software Engineering</i></a>
      </p>
      </div>
    </div>

<!--
    <div class="col-lg-9 col-md-8 mx-auto" style="background-color: #ffdf78; padding: 20px; border-radius: 15px;">
      <h2 class="fw-light"><i class="fas fa-bullhorn"></i>  ASU-RSE Seminar Series: Dr. Wren Raming</h2>
        Join us on Thursday, <i>September 19, 2024, 11am MST</i> for the <a href="{{ "event/2024/07/09/raming-talk.html" }}">ASU-RSE Seminar Series</a> with Dr. Wren Raming.
      </div>-->
  </section>

  <div class="bg-light py-5 album">
    <div class="container">
    <h1 style="padding-bottom: 0.5em"><a href="/news.html">News</a></h1>
    {% for post in site.posts limit:1 %}
    <h4><a style="text-decoration:none" href="{{ post.url }}">{{ post.title }}</a></h4>
    <p>
    {% if post.image %}
    <img src="{{post.image}}" style="border-radius: 5px; float:left; width:150px; margin-right: 20px; margin-bottom: 20px;">
    {% endif %}
    {{post.excerpt}}
    <a href="{{ post.url }}">Read more...</a>
    </p>
    {% endfor %}
    </div>
  </div>

  <div class="album py-5" style="clear:both">
    <div class="container">

      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
        <div class="col">
          <div class="card shadow-sm">
            <img src="{{ "/assets/images/code-coffee-pic.jpg" }}" />

            <div class="card-body">
              <p class="card-text">Code & Coffee</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="{{ "/code-coffee" }}" class="btn btn-sm btn-outline-secondary">More...</a>
                </div>
                <small class="text-muted"></small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="{{ "/assets/images/multiple-computers.jpeg" }}" />


            <div class="card-body">
              <p class="card-text">ASU-RSE Get-Together</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="{{ "/get-together" }}" class="btn btn-sm btn-outline-secondary">More...</a>
                </div>
                <small class="text-muted"></small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="{{ "/assets/images/computer-cat.jpeg" }}" />

            <div class="card-body">
              <p class="card-text">Other Events</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <a href="{{ "/events" }}" class="btn btn-sm btn-outline-secondary">More...</a>
                </div>
                <small class="text-muted"></small>
              </div>
            </div>
          </div>
        </div>

    </div>
  </div>
