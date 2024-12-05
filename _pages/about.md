---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a first-year master's student in Data Science at NYU. Previously, I majored in Computer Science and Mathematics as an undergraduate at NYU.


# Research
<div class="content">
    <video class="video" width="250" muted autoplay playsinline loop>
        <source src="files/robot-utility-models.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <div class="text-container">
        <h3>Robot Utility Models: General Policies for Zero-Shot Deployment in New Environments</h3>
        <p>Haritheja Etukuru, Norihito Naka, <b>Zijin Hu</b>*, Seungjae Lee, Julian Mehu, Aaron Edsinger, Chris Paxton, Soumith Chintala, Lerrel Pinto, Nur Muhammad “Mahi” Shafiullah*</p>
        <div>
            <a href="https://robotutilitymodels.com/mfiles/paper/Robot_Utility_Models.pdf" class="button">Paper</a>
            <a href="https://github.com/haritheja-e/robot-utility-models/" class="button">Code</a>
            <a href="https://robotutilitymodels.com" class="button">Project Site</a>
        </div>
    </div>
</div>

<style>
    .content {
        display: flex;
        align-items: flex-start;
        flex-direction: row;
        margin-top: 0; /* Remove extra margin on top */
    }

    .video {
        align-self: center; /* Align video vertically with text */
    }

    .text-container {
        margin-left: 20px;
        margin-top: 0; /* Remove margin-top to reduce space above the text */
    }

    .button-container {
        margin-top: 10px; /* Add space between text and buttons */
    }

    .button {
        padding: 8px 12px;
        background-color: #e0e0e0;
        text-decoration: none;
        margin-right: 5px;
        border-radius: 3px;
        margin-bottom: 10px; /* Add space below each button */
    }

    /* For smaller screens or portrait mode */
    @media (max-width: 600px), (orientation: portrait) {
        .content {
            flex-direction: column;
            align-items: center;
        }

        .video {
            margin-top: 10px;
            margin-bottom: 0px; /* Add more space below the video in portrait */
            width: 300px;
        }

        .text-container {
            margin-left: 0;
            margin-top: 0px;
            margin-bottom: 50px; /* Add extra space below the text container */
        }

        .button-container {
            margin-top: 20px; /* Add more space between text and buttons */
        }
    }
</style>
