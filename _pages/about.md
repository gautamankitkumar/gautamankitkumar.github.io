---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm Ankit, a final-year graduate student at the University of Illinois Urbana-Champaign, passionate about leveraging computational tools to design advanced materials and molecules.

My expertise lies in first-principles methods like Density-Functional Theory and *ab initio* thermodynamics. My goal is to make quantum-mechanical calculations more accessible and efficient for accelerating in-silico materials design.

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Timeline Example</title>
    <style>
        .timeline {
            position: relative;
            max-width: 600px;
            margin: 50px auto;
        }

        .timeline::after {
            content: '';
            position: absolute;
            width: 2px;
            background-color: #ddd;
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -1px;
        }

        .container {
            padding: 10px 20px;
            position: relative;
            background-color: inherit;
            width: 50%;
        }

        .container::after {
            content: '';
            position: absolute;
            width: 16px;
            height: 16px;
            right: -8px;
            background-color: white;
            border: 2px solid #4CAF50;
            top: 10px;
            border-radius: 50%;
            z-index: 1;
        }

        .left {
            left: 0;
        }

        .right {
            left: 50%;
        }

        .content {
            background-color: white;
            padding: 10px 15px;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .content h2 {
            margin: 0 0 5px 0;
            font-size: 1em;
            color: #4CAF50;
        }

        .content p {
            margin: 0;
            font-size: 0.9em;
        }

        @media screen and (max-width: 600px) {
            .timeline::after {
                left: 16px;
            }

            .container {
                width: 100%;
                padding-left: 40px;
                padding-right: 15px;
            }

            .container::after {
                left: 8px;
            }

            .left {
                left: 0%;
            }
        }
    </style>
</head>
<body>

    <div class="timeline">
        <div class="container left">
            <div class="content">
                <h2>2017</h2>
                <p>Event description.</p>
            </div>
        </div>
        <div class="container right">
            <div class="content">
                <h2>2018</h2>
                <p>Another event description.</p>
            </div>
        </div>
        <div class="container left">
            <div class="content">
                <h2>2019</h2>
                <p>More details here.</p>
            </div>
        </div>
        <div class="container right">
            <div class="content">
                <h2>2020</h2>
                <p>Something happened.</p>
            </div>
        </div>
    </div>

</body>
</html>
```