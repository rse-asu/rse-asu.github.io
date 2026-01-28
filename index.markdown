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
     <p>
        <i class="fas fa-graduation-cap"></i> <a href="{{ "/code-coffee" }}"><b>Code & Coffee</b> on Monday, February 2, 2026, 11am MST. Mini-tutorial: <i>The GitHub CLI</i></a>
      </p>-->
      <p>
        <i class="fas fa-graduation-cap"></i> No <b>Code & Coffee</b> in August
      </p>
      <!--<p>
         <i class="fas fa-bullhorn"></i> <a href="{{ "/rse-consultation" }}">Free Research Software Engineering Consultation through the end of the summer</a>
      </p>
      <p>
        <i class="fas fa-comments"></i> <a href="{{ "/get-together" }}">ASU-RSE Get-Together on November 24, 2025, 11am MST. Discussion topic: <i>Security of research software (Secure Coding Practices)</i></a>
      </p>
      <p>
       <i class="fas fa-bullhorn"></i> <a href="{{ "/events/2025-10-22-enabling-research-seminar-series.html" }}">The Researcher’s Guide to Including Code Responsibly</a> on January 7, 2026 at 1pm MST. Part of <a href="{{ "/enabling-research-seminar-series" }}">Enabling Research: A Seminar Series on Research Software</a>.
      </p>-->
      <p>
       <i class="fas fa-bullhorn"></i> <a href="{{ "/events/2025-12-19-enabling-research-sheldus.html" }}">SHELDUS</a> on February 4, 2026 at 1pm MST. Part of <a href="{{ "/enabling-research-seminar-series" }}">Enabling Research: A Seminar Series on Research Software</a>. Part of <a href="{{ "/enabling-research-seminar-series" }}">Enabling Research: A Seminar Series on Research Software</a>.
      </p>
      
      </div>
    </div>


    <div class="col-lg-9 col-md-8 mx-auto" style="background-color: #ffdf78; padding: 20px; border-radius: 15px;">
      <h2 class="fw-light"><i class="fas fa-bullhorn"></i>  
New Seminar Series</h2>
        We are pleased to announce a new virtual seminar series, <a href="{{ "/enabling-research-seminar-series" }}">Enabling Research: A Seminar Series on Research Software</a>, organized by ASU-RSE! This seminar series explores how research software drives discovery across disciplines.
      </div>
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
