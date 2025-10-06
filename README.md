# Ex09 Event Registration Web Application
## Date:06.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
page1
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img
        class="millions-of-PNG"
        src="img/millions-of-PNG-images-backgrounds-and-vectors-for-free-download-pngtree-1.png"
      />
      <img class="saveetha-logo" src="img/saveetha-logo-1.png" />
      <div class="text-wrapper">SPORTS DAY EVENTS</div>
      <div class="rectangle"></div>
      <div class="div">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">DESINGED BY: KERVIN.S(25012113)</div>
    </div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
style.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
page2
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="deae-bb-fe" src="img/dea373e8-8b3b-4f0e-b058-a2e433c931b3-1.png" />
      <div class="text-wrapper">SPORTS EVENTS</div>
      <p class="CRICKET-BADMINTON">
        CRICKET<br /><br />BADMINTON<br /><br />VOLLEY BALL<br /><br />100 MTS<br /><br />200 MTS<br /><br />400 MTS<br /><br />4-100
        RELAY
      </p>
      <div class="div">DESINGED BY KERVIN.S(25012113)</div>
    </div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
style.css
.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .deae-bb-fe {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 0.75;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 124px;
  left: 214px;
  width: 397px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #f61317;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .CRICKET-BADMINTON {
  position: absolute;
  top: 206px;
  left: calc(50.00% - 245px);
  width: 479px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #0c85ff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 815px;
  left: 121px;
  width: 546px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #141414;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
page 3
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="element" src="img/1f780420-7612-4578-adeb-26118a896859-1.png" />
      <div class="text-wrapper">REGISTERATION FORM</div>
      <div class="rectangle"></div>
      <div class="div">FIRST NAME</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <img class="img" src="img/rectangle-4.svg" />
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-2">GENDER</div>
      <div class="text-wrapper-3">AGE</div>
      <div class="text-wrapper-4">REGISTER NUMBER</div>
      <div class="text-wrapper-5">DEPARTMENT</div>
      <div class="text-wrapper-6">MOBILE NUMBER</div>
      <div class="text-wrapper-7">EMAIL ID</div>
      <div class="text-wrapper-8">EVENTS TO REGISTER</div>
      <div class="text-wrapper-9">REGISTER</div>
      <div class="text-wrapper-10">DESINGED BY: KERVIN.S(25012113)</div>
    </div>
  </body>
</html>
globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
style.css
.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 671px;
  min-height: 805px;
  position: relative;
}

.android-medium .element {
  position: absolute;
  top: 0;
  left: 0;
  width: 671px;
  height: 805px;
  aspect-ratio: 0.74;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 15px;
  left: 26px;
  width: 470px;
  font-family: "Jacques Francois Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #911991;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 119px;
  left: 28px;
  width: 332px;
  height: 44px;
  background-color: #bfa1a1;
  border-radius: var(--shape-corner-medium);
}

.android-medium .div {
  position: absolute;
  top: 125px;
  left: 38px;
  width: 298px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 185px;
  left: 28px;
  width: 332px;
  height: 44px;
  background-color: #c3a8a8;
  border-radius: var(--shape-corner-medium);
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 251px;
  left: 29px;
  width: 332px;
  height: 43px;
  background-color: #c3aeae;
  border-radius: var(--shape-corner-medium);
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 316px;
  left: 26px;
  width: 330px;
  height: 43px;
  background-color: #c1b6b6;
  border-radius: var(--shape-corner-medium);
}

.android-medium .img {
  position: absolute;
  top: 382px;
  left: 28px;
  width: 332px;
  height: 44px;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 455px;
  left: 28px;
  width: 336px;
  height: 45px;
  background-color: #bda8a8;
  border-radius: var(--shape-corner-medium);
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 522px;
  left: 32px;
  width: 332px;
  height: 47px;
  background-color: #ba9c9c;
  border-radius: var(--shape-corner-medium);
}

.android-medium .rectangle-7 {
  position: absolute;
  top: 591px;
  left: 27px;
  width: 335px;
  height: 45px;
  background-color: #bb9494;
  border-radius: var(--shape-corner-medium);
}

.android-medium .rectangle-8 {
  position: absolute;
  top: 664px;
  left: 254px;
  width: 308px;
  height: 53px;
  background-color: #642222;
  border-radius: var(--shape-corner-medium);
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 187px;
  left: 38px;
  width: 257px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 251px;
  left: 38px;
  width: 225px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 319px;
  left: 32px;
  width: 309px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 388px;
  left: 36px;
  width: 315px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 458px;
  left: 38px;
  width: 281px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 526px;
  left: 41px;
  width: 292px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 594px;
  left: 29px;
  width: 408px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #0a0a0a;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-9 {
  position: absolute;
  top: 668px;
  left: 319px;
  width: 301px;
  font-family: "Tomorrow-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-10 {
  position: absolute;
  top: 769px;
  left: 121px;
  width: 460px;
  font-family: "Tiro Kannada-Regular", Helvetica;
  font-weight: 400;
  color: #0cfff2;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

```
## OUTPUT:
![alt text](<Screenshot 2025-10-06 201333.png>)
![alt text](<Screenshot 2025-10-06 205141.png>)
![alt text](<Screenshot 2025-10-06 211744.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
