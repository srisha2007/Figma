# Ex09 Event Registration Web Application
## Date:19/12/2024

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
Welcome page
<div style="width: 100%; height: 100%; position: relative; background: rgba(16.77, 15.58, 15.42, 0.99); backdrop-filter: blur(4px)">
    <img style="width: 149.31px; height: 150px; left: 137px; top: 23px; position: absolute; border-radius: 8px" src="https://via.placeholder.com/149x150" />
    <img style="width: 355px; height: 142px; left: 48px; top: 267px; position: absolute; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset; border-radius: 10px; border: 1px black solid" src="https://via.placeholder.com/355x142" />
    <div style="width: 197.85px; height: 47.07px; left: 122.31px; top: 436px; position: absolute; color: #EA2045; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">PRESENTS</div>
    <img style="width: 38px; height: 41px; left: 60px; top: 641px; position: absolute; border-radius: 10px" src="https://via.placeholder.com/38x41" />
    <div style="width: 382px; height: 88px; left: 43px; top: 529px; position: absolute; color: white; font-size: 50px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">TECH FEST 23</div>
    <div style="width: 429.39px; height: 48px; left: 23px; top: 189.86px; position: absolute; color: white; font-size: 28px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Saveetha Engineering college</div>
    <div style="width: 206px; height: 39px; left: 124px; top: 643px; position: absolute; color: white; font-size: 25px; font-family: Inter; font-weight: 600; word-wrap: break-word">Decmber  29th</div>
    <div style="width: 472px; height: 0px; left: 6px; top: 530px; position: absolute; border: 1px #FCF4F4 solid"></div>
    <div style="width: 455px; height: 0px; left: 1px; top: 592.03px; position: absolute; border: 1px #F6ECEC solid"></div>
    <div style="width: 203px; height: 34px; left: 102px; top: 724px; position: absolute; color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Robotic Basics</div>
    <div style="width: 34px; height: 0px; left: 58px; top: 739px; position: absolute; border: 2px #46AB62 solid"></div>
    <div style="width: 36.01px; height: 0px; left: 58px; top: 775px; position: absolute; transform: rotate(-1.59deg); transform-origin: 0 0; border: 2px #46AB62 solid"></div>
    <div style="width: 182px; height: 30px; left: 105px; top: 760px; position: absolute; color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Iot Basics</div>
    <div style="width: 279px; height: 59px; left: 92px; top: 849px; position: absolute; color: #F88532; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Register Now!</div>
</div>

// PRESENTS
color: #EA2045;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// SPORT'S DAY EVENT
color: white;
 font-size: 50px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Saveetha Engineering college
color: white;
 font-size: 28px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Decmber  29th
color: white;
 font-size: 25px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// Robotic Basics
color: white;
 font-size: 25px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Iot Basics
color: white;
 font-size: 25px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Register Now!
color: #F88532;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word

page2
<div style="width: 100%; height: 100%; position: relative; background: #181616">
    <div style="width: 379px; height: 405px; left: 34px; top: 207px; position: absolute; background: rgba(178.80, 151.25, 188.47, 0.75)"></div>
    <div style="width: 340px; height: 52.84px; left: 55.42px; top: 54px; position: absolute; color: white; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Event Registration</div>
    <div style="width: 126px; height: 44px; left: 63px; top: 241px; position: absolute; color: white; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Name: </div>
    <div style="width: 188px; height: 47px; left: 199px; top: 240px; position: absolute; background: #D9D9D9; border-radius: 10px"></div>
    <div style="width: 136px; height: 36px; left: 56px; top: 334px; position: absolute; color: white; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">E-mail:</div>
    <div style="width: 189px; height: 45px; left: 198px; top: 330px; position: absolute; background: #D9D9D9; border-radius: 10px"></div>
    <div style="width: 131px; height: 44px; left: 56px; top: 433px; position: absolute; color: white; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">year    :</div>
    <div style="width: 187px; height: 46px; left: 199px; top: 432px; position: absolute; background: #D9D9D9; border-radius: 10px"></div>
    <div style="width: 142px; height: 41px; left: 50px; top: 532px; position: absolute; color: white; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Branch:</div>
    <div style="width: 187px; height: 46px; left: 198px; top: 528px; position: absolute; background: #D9D9D9; border-radius: 10px"></div>
    <div style="width: 273px; height: 69px; left: 78px; top: 773px; position: absolute; background: #FAFF1F; box-shadow: 4px 4px 4px; border-radius: 9999px; filter: blur(4px)"></div>
    <div style="width: 179px; height: 42px; left: 147px; top: 785px; position: absolute; color: #F5422A; font-size: 35px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Submit</div>
</div>
// Event Registration
color: white;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Name: 
color: white;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// E-mail:
color: white;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// year    :
color: white;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Branch:
color: white;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Submit
color: #F5422A;
 font-size: 35px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
 page3
 <div style="width: 100%; height: 100%; position: relative; background: #1F1616">
    <div style="width: 374px; height: 145px; left: 42px; top: 135px; position: absolute; color: white; font-size: 55px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Thankyou for<br/>Registration<br/></div>
    <div style="width: 424px; height: 150px; left: 15px; top: 801px; position: absolute; color: white; font-size: 65px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">Dont miss it!<br/></div>
</div>
// Thankyou for<br/>Registration<br/>
color: white;
 font-size: 55px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// Dont miss it!<br/>
color: white;
 font-size: 65px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word

```

## OUTPUT:
![Screenshot 2024-12-19 204145](https://github.com/user-attachments/assets/e6c378d8-abd8-45ea-8a8e-027ffad56ff9)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
