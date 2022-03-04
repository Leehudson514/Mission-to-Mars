# Mission-to-Mars

## Overview
* Our client had a need for a tool that would scrape information on Mars from multiple sources to gather and then post on their own website to share.

## Results
* The web scraping gathered information and photos from 3 different sites using python and was then posted on a centralized page with html.
    * **Web Scrapping** information included the following:
        * Latest news articles about Mars.
        * Facts comparing Earth to Mars.
        * Featured photo from recent photos taken of mars and or it's moon. 
        * Photos focusing on the different hemispheres of Mars.  

![goals](https://github.com/Leehudson514/Mission-to-Mars/blob/main/app_image.png)

## Summary
* The html code was modified to make the page more visually appealing and mobile responsive.
* **Visual codes change include:**
```
#change button to green
class="btn btn-success"

# Update header background and add gradiant background color
<style>
      h2 {
        background-color: rgb(142, 191, 66);
      }
      body {
        height: 500px;
        background-color: blue;
        background-image: linear-gradient(to right, #1c87c9, #8ebf42);
      }
    </style>
```

![goals](https://github.com/Leehudson514/Mission-to-Mars/blob/main/app_image_modified.png)

* **Code to make the page mobile responsive was then added:**
```
# To ensure proper rendering and touch zooming, add the viewport meta tag to your <head>
<meta name="viewport" content="width=device-width, initial-scale=1">
```

![goals](https://github.com/Leehudson514/Mission-to-Mars/blob/main/mobile_responsive.png)
