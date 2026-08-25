---

layout: post
title: About
permalink: /about/
comments: true
--------------

## As a conversation Starter

Here are some places I have lived.

<comment>
Flags are made using Wikipedia images
</comment>

<style>
    /* Style looks pretty compact, 
       - grid-container and grid-item are referenced the code 
    */
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Dynamic columns */
        gap: 10px;
    }
    .grid-item {
        text-align: center;
    }
    .grid-item img {
        width: 100%;
        height: 100px; /* Fixed height for uniformity */
        object-fit: contain; /* Ensure the image fits within the fixed height */
    }
    .grid-item p {
        margin: 5px 0; /* Add some margin for spacing */
    }

    .image-gallery {
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
        gap: 10px;
        }

    .image-gallery img {
        max-height: 150px;
        object-fit: cover;
        border-radius: 5px;
    }
</style>

<!-- This grid_container class is used by CSS styling and the id is used by JavaScript connection -->

<div class="grid-container" id="grid_container">
    <!-- content will be added here by JavaScript -->
</div>

<script>
    // 1. Make a connection to the HTML container defined in the HTML div
    var container = document.getElementById("grid_container");

    // 2. Define our image source and data for the places I have lived
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";
    var places_lived = [
        {"flag": "2/28/Flag_of_California.svg", "greeting": "Hey", "description": "Temecula - born here"},
        {"flag": "2/28/Flag_of_California.svg", "greeting": "Hey", "description": "San Diego - home"}
    ];

    // 3. Build grid items inside of our container
    for (const location of places_lived) {
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";

        var img = document.createElement("img");
        img.src = http_source + location.flag;
        img.alt = location.flag + " Flag";

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

### Journey through Life

Here is a little about my life so far.

* 👶 Born in **Temecula, California**
* 🏡 Lived in **Temecula** for the first 5 years of my life
* 🏫 Attended **Del Sur Elementary School**
* 🏫 Attended **Black Mountain Middle School**
* 🏫 Currently attend **Del Norte High School**
* 🎂 I am currently **15 years old**

### Family, Friends, and Fun

Family is a big part of my life. I have a **twin brother**, and we have grown up together through every stage of our lives.

I was born in Temecula and moved to San Diego when I was five. San Diego has been my home for most of my life, and I've grown up here with my family and friends.

Some of the things I enjoy include:

* 🏀 Playing basketball
* 👨‍👩‍👦 Spending time with my family
* 👥 Hanging out with friends
* 🎮 Playing games
* 🏫 Going to school
* 🌴 Spending time around San Diego
