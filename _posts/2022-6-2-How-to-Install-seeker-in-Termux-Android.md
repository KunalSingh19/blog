---
title: Seeker - Find Geolocation with High Accuracy
desc: Concept behind Seeker is simple, just like we host phishing pages to get credentials why not host a fake page that requests your loction just like many popular location based websites
layout: post
categories:
  - Technology
  - How To
  - Termux
tags:
  - Termux
  - Tool
  - Seeker
  - location
series:
  - Termux
usemathjax: false
---
<h3 class="cyan-text">Seeker - Find Geolocation with High Accuracy</h3>

<h4 class="cyan-text">Introduction</h4>

<div class="content white-text">
  <p>
    Concept behind Seeker is simple, just like we host phishing pages to  get credentials why not host a fake page that requests your loction just  like many popular location based websites.
    Seeker Hosts a fake website on In Built PHP Server and uses Ngrok, website asks for Location Permission and if the user allows it, we can get :
  </p>

  <ul class="browser-default">
    <li>Longitude</li>
    <li>Latitude</li>
    <li>Accuracy</li>
    <li>Altitude - Not always available</li>
    <li>Direction - Only available if user is moving</li>
    <li>Speed - Only available if user is moving</li>
  </ul>

  <p>Along with Location Information we also get Device Information without any permissions :</p>

  <ul class="browser-default">
    <li>Operating System</li>
    <li>Platform</li>
    <li>Number of CPU Cores</li>
    <li>Amount of RAM - Approximate Results</li>
    <li>Screen Resolution</li>
    <li>GPU information</li>
    <li>Browser Name and Version</li>
    <li>Public IP Address</li>
  </ul>

  <p>This tool is a Proof of Concept and is for Educational Purposes  Only, Seeker shows what data a malicious website can gather about you  and your devices and why you should not click on random links and allow  critical permissions such as Location etc.</p>

  <ul class="browser-default">
    <li>Other tools and services offer IP Geolocation which is not very accurate and does not give location of user.</li>
    <li>Generally if a user accepts location permsission, Accuracy of the information recieved is **accurate to approximately 30 meters**.</li>
  </ul>

  <h4 class="cyan-text">Tested On :</h4>

  <ul class="browser-default">
    <li>Kali Linux 2018.2</li>
    <li>Ubuntu 18.04</li>
    <li>Arch Linux based Distro</li>
    <li>Termux</li>
    <li>Kali Linux (WSL)</li>
    <li>Parrot OS</li>
    <li>Zorin OS</li>
  </ul>

  <h4 class="cyan-text">Installation</h4>

  <h5 class="cyan-text">Ubuntu/Kali Linux</h5>

    <pre><code>
    git clone https://github.com/thewhiteh4t/seeker.git
    cd seeker/
    chmod 777 install.sh
    ./install.sh

    #OR using Docker

    # Install docker
    curl -fsSL https://get.docker.com -o get-docker.sh
    sh get-docker.sh

    # Build Seeker
    cd seeker/
    docker build -t seeker .

    # Launch seeker
    docker run -t --rm seeker
    </code></pre>

    <script id="asciicast-195052" src="https://asciinema.org/a/195052.js" async></script>

    <h5 class="cyan-text">Arch Linux Based Distro</h5>

    <pre><code>
    # Install docker
    pacman -Syy pacman -S docker
    systemctl start docker.service

    # Build Seeker
    cd seeker/
    docker build -t seeker .

    # Launch seeker
    docker run -t --rm seeker
    </code></pre>

    <h4 class="cyan-text">Demo</h4>

</div>

  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/ggUGPq4cjSM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
