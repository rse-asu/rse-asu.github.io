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
      <!-- Featured events go below here -->
        <!-- Former event: Code & Coffee -->
        <!--
        <div>
          <p>
            <i class="fas fa-graduation-cap"></i> <a href="{{ "/code-coffee" }}"><b>Code & Coffee</b> on Monday, February 2, 2026, 11am MST. Mini-tutorial: <i>The GitHub CLI</i></a>
          </p>
        </div>
        -->

        <!-- Former notice: No Code & Coffee -->
        <!--
        <div>
          <p>
            <i class="fas fa-graduation-cap"></i> No <b>Code & Coffee</b> in August
          </p>
        </div>
        -->

        <!-- ASU-RSE Get-Together -->
        <div>
          <p>
            <i class="fas fa-comments" aria-hidden="true"></i> <a href="{{ "/get-together" }}"><b>ASU-RSE Get-Together</b></a> on Monday, September 28, 2026, at 11am Arizona time (MST).
          </p>
          <p>
            Join us to plan the semester, discuss possible seminars and meetup topics, and follow up on workgroup business.
          </p>
          <p>
            New to ASU-RSE? You’re welcome to join us!
          </p>
        </div>

        <!-- Former event: The Researcher’s Guide to Including Code Responsibly -->
        <!--
        <div>
          <p>
            <i class="fas fa-bullhorn"></i> <a href="{{ "/events/2025-10-22-enabling-research-seminar-series.html" }}">The Researcher’s Guide to Including Code Responsibly</a> on January 7, 2026 at 1pm MST. Part of <a href="{{ "/enabling-research-seminar-series" }}">Enabling Research: A Seminar Series on Research Software</a>.
          </p>
        </div>
        -->

        <!-- Former event: The Digital Archaeological Record -->
        <!--
        <div>
          <p>
            <i class="fas fa-bullhorn"></i> <a href="{{ "/events/2025-12-19-enabling-research-tdar.html" }}">The past, present, and future of the Digital Archaeological Record: Research computing for the long-term preservation of archaeological data</a> on May 6, 2026 at 1pm MST. Part of <a href="{{ "/enabling-research-seminar-series" }}">Enabling Research: A Seminar Series on Research Software</a>.
          </p>
        </div>
        -->
      </div>
    </div>


    <div class="col-lg-9 col-md-8 mx-auto" style="background-color: #ffdf78; padding: 20px; border-radius: 15px;">
      <h2 class="fw-light"><i class="fas fa-bullhorn"></i>  
New Seminar Series</h2>
        We are pleased to announce a new virtual seminar series, <a href="{{ "/enabling-research-seminar-series" }}">Enabling Research: A Seminar Series on Research Software</a>, organized by ASU-RSE! This seminar series explores how research software drives discovery across disciplines.
      </div>

    <section id="coding-agents-workgroup" class="col-lg-9 col-md-8 mx-auto mt-4 p-4 shadow-sm" style="background-color: #f7edf1; border-top: 5px solid #8d1d3f; border-radius: 15px;" aria-labelledby="coding-agents-heading">
      <p class="fw-bold mb-2" style="color: #8d1d3f;"><i class="fas fa-code me-2" aria-hidden="true"></i>Working Group</p>
      <h2 id="coding-agents-heading" class="fw-light">AI Coding Agents for Research Software Development</h2>
      <p>Sharing experiences, resources, and good practices for using AI coding agents to develop research software.</p>
      <p><i class="far fa-calendar-alt me-2" aria-hidden="true"></i><strong>Third Thursday of every month at 10am Arizona time (MST).</strong></p>
      <a class="btn btn-primary my-1" href="{{ "/coding-agents.html" }}">Workgroup details</a>
      <a class="btn btn-outline-secondary my-1" href="https://github.com/rse-asu/rse-asu-coding-agents"><i class="fab fa-github me-2" aria-hidden="true"></i>Explore workgroup resources</a>
    </section>
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
