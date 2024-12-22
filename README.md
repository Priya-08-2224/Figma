# Ex09 Event Registration Web Application
# Date:24\10\2024
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
```
HOME PAGE 
HTML
<div class="container--0-">
<div class="text-0-1-2">
    CAT SHOW <br />
    EVENTS
  </div>
  <svg
    width="273"
    height="76"
    viewBox="0 0 273 76"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_5_7)">
      <path d="M1 1H272V75H1V1Z" fill="#738997"></path>
    </g>
    <path
      d="M1 0.5H0.5V1V75V75.5H1H272H272.5V75V1V0.5H272H1Z"
      stroke="black"
    ></path>
    <defs>
      <filter
        id="filter0_i_5_7"
        x="0"
        y="0"
        width="273"
        height="80"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_5_7"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-4">LOGIN</div>
  <svg
    width="275"
    height="82"
    viewBox="0 0 275 82"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_5_15)">
      <rect x="1" y="1" width="273" height="80" fill="#738997"></rect>
    </g>
    <rect x="0.5" y="0.5" width="274" height="81" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_5_15"
        x="0"
        y="0"
        width="275"
        height="86"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_5_15"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-6">REGISTER</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: -149px;
  top: -6142px;
  width: 440px;
  height: 956px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 394px;
  height: 46px;
  color: #0f3139;
  font-size: 36px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 150px;
  height: 58px;
  color: #0f3139;
  font-size: 48px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 238px;
  height: 58px;
  color: #0f3139;
  font-size: 48px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

EVENT REGISTRATION
HTML
<div class="container--0-">
<div class="text-0-1-1">
    CAT SHOW<br />
    EVENTS
  </div>
  <div class="text-0-1-2">BEST IN SHOW</div>
  <svg
    width="38"
    height="46"
    viewBox="0 0 38 46"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M19 0L22.1488 15.7407L33.8548 9.03624L26.0754 21.9601L37.5236 29.3405L24.674 29.7156L27.2438 45.6233L19 33.1672L10.7562 45.6233L13.326 29.7156L0.47637 29.3405L11.9246 21.9601L4.1452 9.03624L15.8512 15.7407L19 0Z"
      fill="#293258"
    ></path></svg
  ><svg
    width="35"
    height="48"
    viewBox="0 0 35 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M17.5 0L20.4003 16.3965L31.1821 9.41276L24.0168 22.8751L34.5612 30.563L22.7261 30.9538L25.093 47.5242L17.5 34.5491L9.90703 47.5242L12.2739 30.9538L0.438761 30.563L10.9832 22.8751L3.81795 9.41276L14.5997 16.3965L17.5 0Z"
      fill="#293258"
    ></path></svg
  ><svg
    width="35"
    height="48"
    viewBox="0 0 35 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M17.0612 0L19.9615 16.3965L30.7433 9.41276L23.5781 22.8751L34.1225 30.563L22.2873 30.9538L24.6542 47.5242L17.0612 34.5491L9.46827 47.5242L11.8352 30.9538L0 30.563L10.5444 22.8751L3.37919 9.41276L14.161 16.3965L17.0612 0Z"
      fill="#293258"
    ></path></svg
  ><svg
    width="35"
    height="48"
    viewBox="0 0 35 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M17.0612 0L19.9615 16.3965L30.7433 9.41276L23.5781 22.8751L34.1225 30.563L22.2873 30.9538L24.6542 47.5242L17.0612 34.5491L9.46827 47.5242L11.8352 30.9538L0 30.563L10.5444 22.8751L3.37919 9.41276L14.161 16.3965L17.0612 0Z"
      fill="#293258"
    ></path></svg
  ><svg
    width="35"
    height="48"
    viewBox="0 0 35 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M17.0612 0L19.9615 16.3965L30.7433 9.41276L23.5781 22.8751L34.1225 30.563L22.2873 30.9538L24.6542 47.5242L17.0612 34.5491L9.46827 47.5242L11.8352 30.9538L0 30.563L10.5444 22.8751L3.37919 9.41276L14.161 16.3965L17.0612 0Z"
      fill="#293258"
    ></path></svg
  ><svg
    width="35"
    height="48"
    viewBox="0 0 35 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M17.0612 0L19.9615 16.3965L30.7433 9.41276L23.5781 22.8751L34.1225 30.563L22.2873 30.9538L24.6542 47.5242L17.0612 34.5491L9.46827 47.5242L11.8352 30.9538L0 30.563L10.5444 22.8751L3.37919 9.41276L14.161 16.3965L17.0612 0Z"
      fill="#293258"
    ></path></svg
  ><svg
    width="35"
    height="48"
    viewBox="0 0 35 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M17.0612 0L19.9615 16.3965L30.7433 9.41276L23.5781 22.8751L34.1225 30.563L22.2873 30.9538L24.6542 47.5242L17.0612 34.5491L9.46827 47.5242L11.8352 30.9538L0 30.563L10.5444 22.8751L3.37919 9.41276L14.161 16.3965L17.0612 0Z"
      fill="#293258"
    ></path>
  </svg>
  <div class="text-0-1-11">KITTEN CLASS</div>
  <div class="text-0-1-12">COSTUMECONTESTS</div>
  <div class="text-0-1-13">AGILITY</div>
  <div class="text-0-1-14">CAT BREEDER</div>
  <div class="text-0-1-15">VETERAN CAT</div>
  <div class="text-0-1-16">HOUSEHOLD PET</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: 331px;
  top: -6137px;
  width: 451px;
  height: 951px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 261px;
  height: 116px;
  color: #000000;
  font-size: 48px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 232px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 231px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 338px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-13 {
  width: 126px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 218px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-15 {
  width: 224px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-16 {
  width: 272px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}

FORM
HTML
<div class="container--0-">
 <div class="text-0-1-1">
    EVENT REGISTRATION <br />
    FORM<br />
    fill the details
  </div>
  <svg
    width="250"
    height="41"
    viewBox="0 0 250 41"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_94)">
      <rect x="1" y="1" width="248" height="39" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="249" height="40" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_13_94"
        x="0"
        y="0"
        width="250"
        height="45"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_94"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-3">Full Name</div>
  <svg
    width="238"
    height="39"
    viewBox="0 0 238 39"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_97)">
      <rect x="1" y="1" width="236" height="37" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="237" height="38" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_13_97"
        x="0"
        y="0"
        width="238"
        height="43"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_97"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-5">Gender</div>
  <svg
    width="133"
    height="44"
    viewBox="0 0 133 44"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_102)">
      <rect x="1" y="1" width="131" height="42" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="132" height="43" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_13_102"
        x="0"
        y="0"
        width="133"
        height="48"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_102"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-7">Age</div>
  <svg
    width="289"
    height="48"
    viewBox="0 0 289 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_104)">
      <path d="M1 1H288V47H1V1Z" fill="#D9D9D9"></path>
    </g>
    <path
      d="M1 0.5H0.5V1V47V47.5H1H288H288.5V47V1V0.5H288H1Z"
      stroke="black"
    ></path>
    <defs>
      <filter
        id="filter0_i_13_104"
        x="0"
        y="0"
        width="289"
        height="52"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_104"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-9">Register Number</div>
  <svg
    width="229"
    height="46"
    viewBox="0 0 229 46"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_107)">
      <rect x="1" y="1" width="227" height="44" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="228" height="45" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_13_107"
        x="0"
        y="0"
        width="229"
        height="50"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_107"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-11">Department</div>
  <svg
    width="273"
    height="47"
    viewBox="0 0 273 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_112)">
      <rect x="1" y="1" width="271" height="45" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="272" height="46" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_13_112"
        x="0"
        y="0"
        width="273"
        height="51"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_112"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-13">Mobile Number</div>
  <svg
    width="235"
    height="50"
    viewBox="0 0 235 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_114)">
      <rect x="1" y="1" width="233" height="48" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="234" height="49" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_13_114"
        x="0"
        y="0"
        width="235"
        height="54"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_114"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-15">Email ID</div>
  <svg
    width="323"
    height="50"
    viewBox="0 0 323 50"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_116)">
      <rect x="1" y="1" width="321" height="48" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="322" height="49" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_13_116"
        x="0"
        y="0"
        width="323"
        height="54"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_116"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-17">Events To Register</div>
  <svg
    width="246"
    height="69"
    viewBox="0 0 246 69"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_13_118)">
      <rect
        x="1"
        y="1"
        width="244"
        height="67"
        fill="#496D2B"
        fill-opacity="0.56"
      ></rect>
    </g>
    <rect x="0.5" y="0.5" width="245" height="68" stroke="black"></rect>
    <rect
      x="0.5"
      y="0.5"
      width="245"
      height="68"
      stroke="black"
      stroke-opacity="0.2"
    ></rect>
    <defs>
      <filter
        id="filter0_i_13_118"
        x="0"
        y="0"
        width="246"
        height="73"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_13_118"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-19">REGISTER</div>
</div>


CSS
.container--0- {
  position: absolute;
  left: 828px;
  top: -6117px;
  width: 434px;
  height: 963px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 358px;
  height: 105px;
  color: #0f3139;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 143px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 108px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 58px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 245px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 175px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-13 {
  width: 222px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-15 {
  width: 116px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-17 {
  width: 271px;
  height: 36px;
  color: #000000;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-19 {
  width: 146px;
  height: 36px;
  color: #ffffff;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}

THANK YOU
HTML
<div class="container--0-">
<div class="text-0-1-2">THANK YOU</div>
  <div class="text-0-1-3">
    we are all eagerly waiting<br />
    for your participation in<br />
    the cat show event
  </div>
  <div class="text-0-1-4">contact us<br /></div>
  <div class="text-0-1-5">E-mail</div>
  <div class="text-0-1-6">saveetha engineering@gmail.com</div>
  <div class="text-0-1-7">phone</div>
  <div class="text-0-1-8">8838512605</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: 1308px;
  top: -6110px;
  width: 440px;
  height: 956px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 303px;
  height: 61px;
  color: #410606;
  font-size: 50px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 367px;
  height: 108px;
  color: #410606;
  font-size: 30px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 205px;
  height: 96px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 74px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 395px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 74px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
.text-0-1-8 {
  width: 151px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Semi Bold";
  font-weight: 600;
  text-align: left;
  vertical-align: top;
}
```
# OUTPUT:
![alt text](<Screenshot 2024-12-22 100141.png>)
![alt text](<Screenshot 2024-12-22 100155.png>)
![alt text](<Screenshot 2024-12-22 100208.png>)
![alt text](<Screenshot 2024-12-22 100217.png>)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
