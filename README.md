# Ex09 Event Registration Web Application
# Date:25/11/2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:

PAGE1
<div class="android-medium-1">
  <div class="frame-1"></div>
  <img class="sports-1" src="sports-10.png" />
  <img
    class="screenshot-2024-10-13-141850-1"
    src="screenshot-2024-10-13-141850-10.png"
  />
  <div class="saveetha-sports-event">Saveetha Sports Event</div>
  <img class="register-1" src="register-10.png" />
  <div class="register-now">
    Register
    <br />
    Now
  </div>
  <div class="rectangle-1"></div>
</div>
css
.android-medium-1,
.android-medium-1 * {
  box-sizing: border-box;
}
.android-medium-1 {
  background: rgba(162, 234, 248, 0.33);
  height: 852px;
  position: relative;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
  overflow: hidden;
}
.frame-1 {
  width: 100px;
  height: 100px;
  position: absolute;
  left: 216px;
  top: 548px;
  overflow: hidden;
}
.sports-1 {
  width: 393px;
  height: 852px;
  position: absolute;
  left: 0px;
  top: 0px;
  object-fit: cover;
}
.screenshot-2024-10-13-141850-1 {
  width: 393px;
  height: 83px;
  position: absolute;
  left: 0px;
  top: 0px;
  object-fit: cover;
}
.saveetha-sports-event {
  color: var(--miscellaneous-floating-tab-text-selected, #007aff);
  text-align: center;
  font-family: "MartelSans-Regular", sans-serif;
  font-size: 24px;
  font-weight: 400;
  position: absolute;
  left: 0px;
  top: 93px;
  width: 393px;
  height: 57px;
  -webkit-text-stroke: 1px #000000;
}
.register-1 {
  border-radius: 100px;
  width: 76px;
  height: 87px;
  position: absolute;
  left: 168px;
  top: 150px;
  object-fit: cover;
}
.register-now {
  color: var(--miscellaneous-floating-tab-text-selected, #007aff);
  text-align: center;
  font-family: var(
    --m3-display-medium-font-family,
    "Roboto-Regular",
    sans-serif
  );
  font-size: var(--m3-display-medium-font-size, 45px);
  line-height: var(--m3-display-medium-line-height, 52px);
  font-weight: var(--m3-display-medium-font-weight, 400);
  position: absolute;
  left: 48px;
  top: 261px;
  width: 316px;
  height: 90px;
}
.rectangle-1 {
  background: var(--miscellaneous-button-tinted-fill, rgba(0, 122, 255, 0.15));
  width: 224px;
  height: 98px;
  position: absolute;
  left: 92px;
  top: 266px;
}

PAGE2
<div class="android-medium-1">
  <img class="sports-2-1" src="sports-2-10.png" />
  <div class="sports-day-event">SPORTS DAY EVENT</div>
  <div class="football-cricket-kabadi-badminton">
    Football
    <br />
    <br />
    Cricket
    <br />
    <br />
    Kabadi
    <br />
    <br />
    Badminton
  </div>
  <img class="star-1" src="star-10.svg" />
  <img class="star-2" src="star-20.svg" />
  <img class="star-3" src="star-30.svg" />
  <img class="star-4" src="star-40.svg" />
</div>
css
.android-medium-1,
.android-medium-1 * {
  box-sizing: border-box;
}
.android-medium-1 {
  background: #ffffff;
  height: 852px;
  position: relative;
  overflow: hidden;
}
.sports-2-1 {
  width: 742px;
  height: 1515px;
  position: absolute;
  left: -122px;
  top: -476px;
  object-fit: cover;
}
.sports-day-event {
  color: #4a29de;
  text-align: center;
  font-family: "Inter-BoldItalic", sans-serif;
  font-size: 32px;
  font-weight: 700;
  font-style: italic;
  position: absolute;
  left: 27px;
  top: 56px;
  width: 338px;
  height: 32px;
}
.football-cricket-kabadi-badminton {
  color: #000000;
  text-align: left;
  font-family: "Inter-BoldItalic", sans-serif;
  font-size: 32px;
  font-weight: 700;
  font-style: italic;
  position: absolute;
  left: 135px;
  top: 136px;
  width: 323px;
  height: 290px;
}
.star-1 {
  width: 29px;
  height: 31px;
  position: absolute;
  left: 83px;
  top: 136px;
  overflow: visible;
}
.star-2 {
  width: 29px;
  height: 31px;
  position: absolute;
  left: 83px;
  top: 217px;
  overflow: visible;
}
.star-3 {
  width: 29px;
  height: 31px;
  position: absolute;
  left: 83px;
  top: 299px;
  overflow: visible;
}
.star-4 {
  width: 29px;
  height: 31px;
  position: absolute;
  left: 83px;
  top: 379px;
  overflow: visible;
}
PAGE3
<img class="sports-3-1" src="sports-3-1.png" />
css
.sports-3-1,
.sports-3-1 * {
  box-sizing: border-box;
}
.sports-3-1 {
  height: 913px;
  position: relative;
  object-fit: cover;
}
PAGE4
<div class="android-medium-1">
  <img class="sports-1" src="sports-10.png" />
  <div class="thank-you">Thank You</div>
  <div class="we-are-eagerly-waiting-for-your-participation-best-of-luck">
    WE ARE EAGERLY WAITING FOR YOUR PARTICIPATION!!
    <br />
    <br />
    BEST OF LUCK
  </div>
</div>
css
android-medium-1,
.android-medium-1 * {
  box-sizing: border-box;
}
.android-medium-1 {
  background: #ffffff;
  height: 852px;
  position: relative;
  overflow: hidden;
}
.sports-1 {
  width: 393px;
  height: 852px;
  position: absolute;
  left: 0px;
  top: 0px;
  object-fit: cover;
}
.thank-you {
  color: #2ce341;
  text-align: center;
  font-family: "Inter-SemiBoldItalic", sans-serif;
  font-size: 36px;
  font-weight: 600;
  font-style: italic;
  position: absolute;
  left: 82px;
  top: 37px;
  width: 228px;
  height: 43px;
}
.we-are-eagerly-waiting-for-your-participation-best-of-luck {
  color: #000000;
  text-align: center;
  font-family: "PoetsenOne-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 37px;
  top: 113px;
  width: 319px;
  height: 93px;
}

# OUTPUT:
![9th experiment](https://github.com/user-attachments/assets/53757a17-41da-4dc0-80e1-426e55ec568c)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
