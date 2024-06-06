# Coding issues

## Issue 1

Make the red-pin-icon fly over the map and stick it on a specific part of the map-image (country Germany) as soon as the webpage scrolls over that location.

Extra: create more than 1 pin-icon and place it on specific countries.

**relevant css-selectors**

.pinIcon {
position: absolute;

<!-- change position to fixed to make it fly -->

top: 260px;
}

.worldMap {
border-radius: 45%;
}

**relevant html-elements**

<div class="stationsLife">

**info**

- already asked ChatGPT
  - JavaScript needed to make it sticky at a certain point of scrolling
