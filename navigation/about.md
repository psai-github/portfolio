---
layout: post
title: About
permalink: /about/
comments: true
---

<style>
.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 10px;
}

.grid-item {
    text-align: center;
}

.grid-item img {
    width: 100%;
    height: 100px;
    object-fit: contain;
}

.grid-item p {
    margin: 5px 0;
}

.about-photo {
    display: block;
    width: 100%;
    max-width: 600px;
    height: auto;
    margin: 20px auto;
    border-radius: 12px;
}

</style>

## As a Conversation Starter

<div class="grid-container" id="grid_container">
</div>

<script>
    var container = document.getElementById("grid_container");
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";
    var places_lived = [
        {"flag": "a/a4/Flag_of_the_United_States.svg", "greeting": "Hello", "description": "United States"},
        {"flag": "4/41/Flag_of_India.svg", "greeting": "Namaste", "description": "India"}
    ];

    for (const location of places_lived) {
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";

        var img = document.createElement("img");
        img.src = http_source + location.flag;
        img.alt = location.description + " flag";

        var description = document.createElement("p");
        description.textContent = location.description;

        var greeting = document.createElement("p");
        greeting.textContent = location.greeting;

        gridItem.appendChild(img);
        gridItem.appendChild(description);
        gridItem.appendChild(greeting);
        container.appendChild(gridItem);
    }
</script>

Welcome to my About page!

### Journey Through Life

Here is a little about my life so far.

* 👶 Born in **Temecula, California**
* 🏡 Lived in **Temecula** for the first 5 years of my life
* 🏫 Attended **Del Sur Elementary School**
* 🏫 Attended **Black Mountain Middle School**
* 🏫 Currently attend **Del Norte High School**
* 🎂 I am currently **15 years old**

### Family, Friends, and Fun

<img src="{{ site.baseurl }}/images/about/6fbf130d-7f44-4f63-923d-0f7a5c8bb189.JPG"
     alt="Me with my family and friends"
     class="about-photo">

Family is a big part of my life. I have a **twin brother**, and we have grown up together through every stage of our lives.

I was born in Temecula and moved to San Diego when I was five. San Diego has been my home for most of my life, and I've grown up here with my family and friends.

Some of the things I enjoy include:

* 🏀 Playing basketball
* 👨‍👩‍👦 Spending time with my family
* 👥 Hanging out with friends
* 🎮 Playing games
* 🏫 Going to school
* 🌴 Spending time around San Diego
