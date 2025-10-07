# Ex09 Event Registration Web Application
## Date:07.10.2025

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
page 1 :
HTML code:
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
      <img class="saveetha-logo" src="img/saveetha-logo-1.png" />
      <img class="physical-edu" src="img/physical-edu-1.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">LOGIN</div>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER NOW</div>
    </div>
  </body>
</html>

CSS code:
.android-medium {
  background-color: #ffffff;
  border: 20px solid;
  border-color: #151212;
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  position: relative;
}

.android-medium .saveetha-logo {
  position: absolute;
  top: 37px;
  left: 342px;
  width: 396px;
  height: 396px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .physical-edu {
  position: absolute;
  top: 483px;
  left: 184px;
  width: 670px;
  height: 352px;
  aspect-ratio: 1.9;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 1028px;
  left: 443px;
  width: 241px;
  height: 104px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 1057px;
  left: 469px;
  width: 156px;
  transform: rotate(-0.64deg);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 1250px;
  left: 322px;
  width: 435px;
  height: 150px;
  background-color: #4729ab;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 1296px;
  left: 359px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

Page 2:
HTML code:
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
      <div class="text-wrapper">USERNAME</div>
      <img class="rectangle" src="img/rectangle-4.svg" />
      <div class="div"></div>
      <div class="text-wrapper-2">PASSWORD</div>
      <img class="img" src="img/rectangle-5.svg" />
      <div class="text-wrapper-3">Already log in</div>
    </div>
  </body>
</html>

CSS code:
.android-medium {
  background-color: #ffffff;
  border: 20px solid;
  border-color: #000000;
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  display: flex;
  flex-direction: column;
}

.android-medium .text-wrapper {
  margin-left: 299px;
  width: 532px;
  height: 116px;
  margin-top: 398px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  margin-left: 265px;
  width: 566px;
  height: 138px;
  margin-top: 29px;
}

.android-medium .div {
  margin-left: 282px;
  width: 17px;
  height: 1px;
  margin-top: 104px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-2 {
  margin-left: 277px;
  width: 576px;
  height: 116px;
  margin-top: 81px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  margin-left: 242px;
  width: 635px;
  height: 151px;
  margin-top: 40.5px;
}

.android-medium .text-wrapper-3 {
  margin-left: 249px;
  width: 622px;
  height: 113px;
  margin-top: 126.5px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

Page 3:
HTML code:
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
      <div class="text-wrapper">EVENT FOR RESIGRATION</div>
      <div class="div">Cricket</div>
      <div class="text-wrapper-2">Kabadi</div>
      <div class="text-wrapper-3">Kho Kho</div>
      <div class="text-wrapper-4">Tennis</div>
      <div class="text-wrapper-5">Silambam</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-5.svg" />
      <img class="star-2" src="img/star-2.svg" />
      <img class="star-3" src="img/star-3.svg" />
      <img class="star-4" src="img/star-4.svg" />
    </div>
  </body>
</html>

CSS code:
.android-medium {
  background-color: #ffffff;
  border: 20px solid;
  border-color: #000000;
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  position: relative;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 271px;
  left: 40px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 520px;
  left: 407px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 652px;
  left: 407px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 769px;
  left: 407px;
  width: 304px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 902px;
  left: 407px;
  width: 240px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 1050px;
  left: 407px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star {
  top: 585px;
  left: 326px;
  height: 40px;
  position: absolute;
  width: 47px;
}

.android-medium .img {
  top: 1115px;
  left: 325px;
  height: 40px;
  position: absolute;
  width: 47px;
}

.android-medium .star-2 {
  top: 717px;
  left: 326px;
  height: 40px;
  position: absolute;
  width: 47px;
}

.android-medium .star-3 {
  top: 830px;
  left: 326px;
  height: 40px;
  position: absolute;
  width: 47px;
}

.android-medium .star-4 {
  top: 585px;
  left: 326px;
  height: 418px;
  position: absolute;
  width: 47px;
}

Page 4:
HTML code:
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
        class="congratulation"
        src="img/congratulation-vintage-lettering-handwritten-vector-illustration-for-greeting-1.png"
      />
      <div class="text-wrapper">Thank you for registering</div>
    </div>
  </body>
</html>

CSS code:
.android-medium {
  background-color: #ffffff;
  border: 20px solid;
  border-color: #000000;
  width: 100%;
  min-width: 1080px;
  min-height: 1920px;
  display: flex;
  flex-direction: column;
  gap: 319px;
}

.android-medium .congratulation {
  margin-left: 97px;
  width: 886px;
  height: 332px;
  margin-top: 355px;
  aspect-ratio: 2.67;
  object-fit: cover;
}

.android-medium .text-wrapper {
  margin-left: 83px;
  width: 900px;
  height: 128px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}
```


## OUTPUT:
![alt text](<Screenshot 2025-10-07 111928.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
