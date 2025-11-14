# Ex09 Event Registration Web Application
## Date: 13-11-2025

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

Page 1

```
# HTML:


<!DOCTYPE html>
<html>
<head>
    <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet" />
    <link href="style.css" rel="stylesheet" />
    <title>Document</title>
</head>

<body>
    <div class="container">
        <div class="bg-top"></div>
        <div class="bg-middle"></div>
        <div class="bg-bottom"></div>

        <h1 class="title">SPORTS DAY EVENTS</h1>

        <button class="btn login">LOGIN</button>
        <button class="btn register">REGISTER</button>
    </div>
</body>
</html>

# CSS:

* {
  box-sizing: border-box;
}
body {
  font-size: 14px;
}
.v1_2383 {
  width: 452px;
  height: 840px;
  background: rgba(29,237,206,1);
  opacity: 1;
  position: absolute;
  top: 0px;
  left: 0px;
  overflow: hidden;
}
.v4_6 {
  width: 508px;
  height: 764px;
  background: url("../images/v4_6.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 87px;
  left: 28px;
  overflow: hidden;
}
.v2_3 {
  width: 432px;
  height: 87px;
  background: url("../images/v2_3.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 0px;
  left: 10px;
  overflow: hidden;
}
.v4_9 {
  width: 188px;
  height: 181px;
  background: url("../images/v4_9.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 118px;
  left: 132px;
  border-top-left-radius: 100px;
  border-top-right-radius: 100px;
  border-bottom-left-radius: 100px;
  border-bottom-right-radius: 100px;
  overflow: hidden;
}
.v4_12 {
  width: 385px;
  color: rgba(255,255,255,1);
  position: absolute;
  top: 318px;
  left: 95px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v5_3 {
  width: 151px;
  height: 65px;
  background: rgba(255,128,10,1);
  opacity: 1;
  position: absolute;
  top: 482px;
  left: 152px;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  overflow: hidden;
}
.v5_4 {
  width: 151px;
  height: 65px;
  background: rgba(255,128,10,1);
  opacity: 1;
  position: absolute;
  top: 577px;
  left: 152px;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  overflow: hidden;
}
.v5_9 {
  width: 225px;
  color: rgba(0,0,0,1);
  position: absolute;
  top: 499px;
  left: 190px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v5_10 {
  width: 215px;
  color: rgba(0,0,0,1);
  position: absolute;
  top: 592px;
  left: 169px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}

```

Page 2

```
# HTML:

<!DOCTYPE html>
<html>
<head>
    <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet" />
    <link href="./css/main.css" rel="stylesheet" />
    <title>Sports Events</title>
</head>

<body>
    <div class="container">
        <h1 class="title">SPORTS DAY EVENTS</h1>

        <ul class="event-list">
            <li>CRICKET</li>
            <li>VOLLEY BALL</li>
            <li>FOOT BALL</li>
            <li>BADMINTON</li>
            <li>KABADDI</li>
        </ul>
    </div>
</body>
</html>

# CSS:

* {
  box-sizing: border-box;
}
body {
  font-size: 14px;
}
.v5_12 {
  width: 530px;
  height: 859px;
  background: rgba(255,255,255,1);
  opacity: 1;
  position: relative;
  top: 0px;
  left: 0px;
  overflow: hidden;
}
.v6_14 {
  width: 530px;
  height: 943px;
  background: url("../images/v6_14.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 42px;
  left: 0px;
  overflow: hidden;
}
.v6_16 {
  width: 385px;
  color: rgba(255,0,0,1);
  position: absolute;
  top: 168px;
  left: 66px;
  font-family: Inter;
  font-weight: Black Italic;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.name {
  color: #fff;
}
.name {
  color: #fff;
}
.name {
  color: #fff;
}
.name {
  color: #fff;
}
.name {
  color: #fff;
}
.v6_27 {
  width: 202px;
  color: rgba(21,0,255,1);
  position: absolute;
  top: 258px;
  left: 120px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v6_29 {
  width: 229px;
  color: rgba(21,0,255,1);
  position: absolute;
  top: 313px;
  left: 120px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v6_30 {
  width: 212px;
  color: rgba(21,0,255,1);
  position: absolute;
  top: 365px;
  left: 120px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v6_31 {
  width: 216px;
  color: rgba(21,0,255,1);
  position: absolute;
  top: 417px;
  left: 120px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v6_32 {
  width: 206px;
  color: rgba(21,0,255,1);
  position: absolute;
  top: 469px;
  left: 120px;
  font-family: Inter;
  font-weight: Extra Bold;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}

```

Page 3

```
# HTML:

<!DOCTYPE html>
<html>
<head>
    <link href="./css/main.css" rel="stylesheet" />
    <title>Document</title>
</head>

<body>
    <div class="box-42"></div>
</body>
</html>


# CSS:

* {
  box-sizing: border-box;
}
body {
  font-size: 14px;
}
.v6:42 {
  background: background-image: url('./images/"v6:42.png')};
  width: 580px;
  height: 870px;
}

```

Page 4

```
# HTML:

<!DOCTYPE html>
<html>
<head>
    <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet" />
    <link href="./css/main.css" rel="stylesheet" />
    <title>Registration Status</title>
</head>

<body>
    <div class="success-box">
        <h2 class="line1">YOUR REGISTRATION IS</h2>
        <h2 class="line2">SUCCESSFULLY SAVED</h2>
    </div>
</body>
</html>


# CSS:

* {
  box-sizing: border-box;
}
body {
  font-size: 14px;
}
.v7_32 {
  width: 580px;
  height: 870px;
  background: rgba(255,255,255,1);
  opacity: 1;
  position: relative;
  top: 0px;
  left: 0px;
  overflow: hidden;
}
.v9_43 {
  width: 640px;
  height: 960px;
  background: url("../images/v9_43.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 45px;
  left: 0px;
  overflow: hidden;
}
.v7_34 {
  width: 580px;
  height: 117px;
  background: url("../images/v7_34.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: relative;
  top: 0px;
  left: 0px;
  overflow: hidden;
}
.v9_45 {
  width: 389px;
  color: rgba(122,29,96,1);
  position: absolute;
  top: 179px;
  left: 76px;
  font-family: Inter;
  font-weight: Black Italic;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v9_46 {
  width: 330px;
  color: rgba(89,24,103,1);
  position: absolute;
  top: 223px;
  left: 155px;
  font-family: Inter;
  font-weight: Black Italic;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.v9_48 {
  width: 222px;
  height: 222px;
  background: url("../images/v9_48.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 283px;
  left: 320px;
  border-top-left-radius: 50px;
  border-top-right-radius: 50px;
  border-bottom-left-radius: 50px;
  border-bottom-right-radius: 50px;
  overflow: hidden;
}

```


## OUTPUT:

![alt text](<Screenshot 2025-11-14 020655.png>)

<img width="1919" height="904" alt="Screenshot 2025-11-14 114108" src="https://github.com/user-attachments/assets/4d9d3121-cb94-4e1d-b964-d218854125a9" />

<img width="825" height="861" alt="Screenshot 2025-11-14 122338" src="https://github.com/user-attachments/assets/ef9a0320-98de-4532-a228-ad6ba02265c5" />

<img width="734" height="832" alt="Screenshot 2025-11-14 122459" src="https://github.com/user-attachments/assets/b2d34006-17fe-43a7-b2db-cbc2c8e7f642" />

<img width="626" height="832" alt="Screenshot 2025-11-14 122833" src="https://github.com/user-attachments/assets/30ff7ee6-0a20-48f7-a05f-f6971268508d" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
