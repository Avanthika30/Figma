# Ex09 Event Registration Web Application
## Date:21.05.2025

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
Home page

<div style="width: 412px; height: 917px; position: relative; background: #F3F9BF; overflow: hidden">
  <img style="width: 626px; height: 1113px; left: 0px; top: -98px; position: absolute" src="https://placehold.co/626x1113" />
  <div style="width: 475px; height: 59px; left: 626px; top: 429px; position: absolute; color: black; font-size: 48px; font-family: Joti One; font-weight: 400; word-wrap: break-word">Creō 2025</div>
  <img style="width: 397.40px; height: 80px; left: 6px; top: 12px; position: absolute" src="https://placehold.co/397x80" />
  <img style="width: 174px; height: 174px; left: 119px; top: 125px; position: absolute" src="https://placehold.co/174x174" />
  <div style="width: 275px; height: 67px; left: 77px; top: 421px; position: absolute; background: #EED1CF; backdrop-filter: blur(2px)"></div>
  <div style="width: 157px; height: 31px; left: 136px; top: 439px; position: absolute; color: #2D474C; font-size: 32px; font-family: Inter; font-weight: 700; word-wrap: break-word">REGISTER</div>
  <div style="width: 275px; height: 63px; left: 77px; top: 568px; position: absolute; background: #D9D9D9"></div>
  <div style="width: 275px; height: 67px; left: 77px; top: 564px; position: absolute; background: #EED1CF; backdrop-filter: blur(2px)"></div>
  <div style="width: 157px; height: 31px; left: 162px; top: 582px; position: absolute; color: #2D474C; font-size: 32px; font-family: Inter; font-weight: 700; word-wrap: break-word">LOGIN</div>
</div>

import React from "react";
import styled from "styled-components";

const StyledImage3 = styled.img`
  width: 626px;
  height: 1113px;
  left: 0px;
  top: -98px;
  position: absolute;
`;

const StyledCre2025span = styled.span`
  color: black;
  font-size: 48px;
  font-family: Joti One;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledSeclogo01as11 = styled.div`
  width: 397.40px;
  height: 80px;
  left: 6px;
  top: 12px;
  position: absolute;
`;

const StyledImage1 = styled.img`
  width: 174px;
  height: 174px;
  left: 119px;
  top: 125px;
  position: absolute;
`;

const StyledRectangle1 = styled.div`
  width: 275px;
  height: 67px;
  left: 77px;
  top: 421px;
  position: absolute;
  background: #EED1CF;
  backdrop-filter: blur(2px);
`;

const StyledRegisterspan = styled.span`
  color: #2D474C;
  font-size: 32px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledRectangle2 = styled.div`
  width: 275px;
  height: 63px;
  left: 77px;
  top: 568px;
  position: absolute;
  background: #D9D9D9;
`;

const StyledRectangle3 = styled.div`
  width: 275px;
  height: 67px;
  left: 77px;
  top: 564px;
  position: absolute;
  background: #EED1CF;
  backdrop-filter: blur(2px);
`;

const StyledLoginspan = styled.span`
  color: #2D474C;
  font-size: 32px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledAndroidMedium1 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #F3F9BF;
  overflow: hidden;
`;

export const AndroidMedium1 = () => {
  return (
    <StyledAndroidMedium1>
      <StyledImage3  src="https://placehold.co/626x1113"/>
      <StyledCre2025>Creō 2025</StyledCre2025>
      <StyledSeclogo01as11  src="https://placehold.co/397x80"/>
      <StyledImage1  src="https://placehold.co/174x174"/>
      <StyledRectangle1 />
      <StyledREGISTER>REGISTER</StyledREGISTER>
      <StyledRectangle2 />
      <StyledRectangle3 />
      <StyledLOGIN>LOGIN</StyledLOGIN>
    </StyledAndroidMedium1>
  );
};
```
Page 2
```
<div style="width: 412px; height: 917px; position: relative; background: #E2C1E7; overflow: hidden">
  <img style="width: 626px; height: 1113px; left: -107px; top: -98px; position: absolute" src="https://placehold.co/626x1113" />
  <div style="width: 275px; height: 48px; left: 51px; top: 145px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">🎨 Visual Arts</div>
  <div style="width: 308px; height: 69px; left: 51px; top: 28px; position: absolute"><span style="color: black; font-size: 36px; font-family: Inter; font-weight: 700; word-wrap: break-word">🌟</span><span style="color: black; font-size: 36px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word"> Creō 2025 –<br/></span><span style="color: black; font-size: 24px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word"> Event Categories & Ideas</span></div>
  <div style="width: 378px; height: 55px; left: 51px; top: 232px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">📸 Photography & Film</div>
  <div style="width: 457px; height: 45px; left: 51px; top: 319px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">🎭 Stage & Performing Arts</div>
  <div style="width: 378px; height: 53px; left: 51px; top: 406px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">✍️ Literary & Expressive Arts</div>
  <div style="width: 275px; height: 48px; left: 51px; top: 493px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">🎨🎶 Fusion Events</div>
  <div style="width: 102.09px; height: 110px; left: 274px; top: 721px; position: absolute"></div>
</div>

import React from "react";
import styled from "styled-components";

const StyledImage2 = styled.img`
  width: 626px;
  height: 1113px;
  left: -107px;
  top: -98px;
  position: absolute;
`;

const StyledVisualartsspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledCre2025eventcategoriesideasspan01 = styled.span`
  color: black;
  font-size: 36px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledCre2025eventcategoriesideasspan02 = styled.span`
  color: black;
  font-size: 36px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledCre2025eventcategoriesideasspan03 = styled.span`
  color: black;
  font-size: 24px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledPhotographyfilmspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledStageperformingartsspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledLiteraryexpressiveartsspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledFusioneventsspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: Inter;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledStar5 = styled.div`
  width: 102.09px;
  height: 110px;
  left: 274px;
  top: 721px;
  position: absolute;
`;

const StyledAndroidMedium2 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #E2C1E7;
  overflow: hidden;
`;

export const AndroidMedium2 = () => {
  return (
    <StyledAndroidMedium2>
      <StyledImage2  src="https://placehold.co/626x1113"/>
      <StyledVisualArts>🎨 Visual Arts</StyledVisualArts>
      <StyledCre2025EventCategoriesIdeas><StyledCre2025eventcategoriesideasspan01>🌟</StyledCre2025eventcategoriesideasspan01><StyledCre2025eventcategoriesideasspan02> Creō 2025 –<br/></StyledCre2025eventcategoriesideasspan02><StyledCre2025eventcategoriesideasspan03> Event Categories & Ideas</StyledCre2025eventcategoriesideasspan03></StyledCre2025EventCategoriesIdeas>
      <StyledPhotographyFilm>📸 Photography & Film</StyledPhotographyFilm>
      <StyledStagePerformingArts>🎭 Stage & Performing Arts</StyledStagePerformingArts>
      <StyledLiteraryExpressiveArts>✍️ Literary & Expressive Arts</StyledLiteraryExpressiveArts>
      <StyledFusionEvents>🎨🎶 Fusion Events</StyledFusionEvents>
      <StyledStar5 />
    </StyledAndroidMedium2>
  );
};
```
Page 3
```
<div style="width: 412px; height: 917px; position: relative; background: #E2C1E7; overflow: hidden">
  <img style="width: 626px; height: 1113px; left: -188px; top: -98px; position: absolute" src="https://placehold.co/626x1113" />
  <div style="width: 358px; height: 62px; left: 28px; top: 42px; position: absolute; color: black; font-size: 24px; font-family: Inknut Antiqua; font-weight: 700; word-wrap: break-word">Event Registration Form<br/></div>
  <div style="width: 261px; height: 40px; left: 75px; top: 242px; position: absolute; background: #E7DBDB"></div>
  <div style="width: 261px; height: 40px; left: 76px; top: 337px; position: absolute; background: #E7DBDB"></div>
  <div style="width: 261px; height: 40px; left: 75px; top: 428px; position: absolute; background: #E7DBDB"></div>
  <div style="width: 261px; height: 40px; left: 75px; top: 528px; position: absolute; background: #E7DBDB"></div>
  <div style="width: 261px; height: 40px; left: 75px; top: 632px; position: absolute; background: #E7DBDB"></div>
  <div style="width: 261px; height: 40px; left: 76px; top: 155px; position: absolute; background: #E7DBDB"></div>
  <div style="width: 164px; height: 23px; left: 125px; top: 163px; position: absolute; color: black; font-size: 24px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word">FULL NAME</div>
  <div style="width: 164px; height: 23px; left: 124px; top: 254px; position: absolute; color: black; font-size: 24px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word">GENDER</div>
  <div style="width: 232px; height: 31px; left: 105px; top: 346px; position: absolute; color: black; font-size: 24px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word">REGISTER NUMBER</div>
  <div style="width: 164px; height: 23px; left: 125px; top: 436px; position: absolute; color: black; font-size: 24px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word">DEPARTMENT</div>
  <div style="width: 164px; height: 23px; left: 125px; top: 538px; position: absolute; color: black; font-size: 24px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word">EMAIL ID</div>
  <div style="width: 212px; height: 41px; left: 105px; top: 638px; position: absolute; color: black; font-size: 24px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word">MOBILE NUMBER</div>
</div>

import React from "react";
import styled from "styled-components";

const StyledImage2 = styled.img`
  width: 626px;
  height: 1113px;
  left: -188px;
  top: -98px;
  position: absolute;
`;

const StyledEventregistrationformspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: Inknut Antiqua;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledRectangle5 = styled.div`
  width: 261px;
  height: 40px;
  left: 75px;
  top: 242px;
  position: absolute;
  background: #E7DBDB;
`;

const StyledRectangle9 = styled.div`
  width: 261px;
  height: 40px;
  left: 76px;
  top: 337px;
  position: absolute;
  background: #E7DBDB;
`;

const StyledRectangle11 = styled.div`
  width: 261px;
  height: 40px;
  left: 75px;
  top: 428px;
  position: absolute;
  background: #E7DBDB;
`;

const StyledRectangle12 = styled.div`
  width: 261px;
  height: 40px;
  left: 75px;
  top: 528px;
  position: absolute;
  background: #E7DBDB;
`;

const StyledRectangle13 = styled.div`
  width: 261px;
  height: 40px;
  left: 75px;
  top: 632px;
  position: absolute;
  background: #E7DBDB;
`;

const StyledRectangle10 = styled.div`
  width: 261px;
  height: 40px;
  left: 76px;
  top: 155px;
  position: absolute;
  background: #E7DBDB;
`;

const StyledFullnamespan = styled.span`
  color: black;
  font-size: 24px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledGenderspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledRegisternumberspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledDepartmentspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledEmailidspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledMobilenumberspan = styled.span`
  color: black;
  font-size: 24px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledAndroidMedium3 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #E2C1E7;
  overflow: hidden;
`;

export const AndroidMedium3 = () => {
  return (
    <StyledAndroidMedium3>
      <StyledImage2  src="https://placehold.co/626x1113"/>
      <StyledEventRegistrationForm>Event Registration Form<br/></StyledEventRegistrationForm>
      <StyledRectangle5 />
      <StyledRectangle9 />
      <StyledRectangle11 />
      <StyledRectangle12 />
      <StyledRectangle13 />
      <StyledRectangle10 />
      <StyledFULLNAME>FULL NAME</StyledFULLNAME>
      <StyledGENDER>GENDER</StyledGENDER>
      <StyledREGISTERNUMBER>REGISTER NUMBER</StyledREGISTERNUMBER>
      <StyledDEPARTMENT>DEPARTMENT</StyledDEPARTMENT>
      <StyledEMAILID>EMAIL ID</StyledEMAILID>
      <StyledMOBILENUMBER>MOBILE NUMBER</StyledMOBILENUMBER>
    </StyledAndroidMedium3>
  );
};
```
Page 4
```
<div style="width: 412px; height: 917px; position: relative; background: #E2C1E7; overflow: hidden">
  <img style="width: 626px; height: 1113px; left: -188px; top: -98px; position: absolute" src="https://placehold.co/626x1113" />
  <img style="width: 399px; height: 80px; left: 6px; top: 12px; position: absolute" src="https://placehold.co/399x80" />
  <div style="left: 71px; top: 262px; position: absolute; color: black; font-size: 48px; font-family: JejuHallasan; font-weight: 400; word-wrap: break-word">THANK YOU</div>
  <div style="width: 316px; height: 97px; left: 48px; top: 333px; position: absolute; color: black; font-size: 32px; font-family: Ingrid Darling; font-weight: 400; word-wrap: break-word">"Thank you for registering! Gear up to innovate and inspire."</div>
</div>

import React from "react";
import styled from "styled-components";

const StyledImage2 = styled.img`
  width: 626px;
  height: 1113px;
  left: -188px;
  top: -98px;
  position: absolute;
`;

const StyledSeclogo01as11 = styled.div`
  width: 399px;
  height: 80px;
  left: 6px;
  top: 12px;
  position: absolute;
`;

const StyledThankyouspan = styled.span`
  color: black;
  font-size: 48px;
  font-family: JejuHallasan;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledThankyouforregisteringgearuptoinnovateandinspirespan = styled.span`
  color: black;
  font-size: 32px;
  font-family: Ingrid Darling;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledAndroidMedium4 = styled.div`
  width: 412px;
  height: 917px;
  position: relative;
  background: #E2C1E7;
  overflow: hidden;
`;

export const AndroidMedium4 = () => {
  return (
    <StyledAndroidMedium4>
      <StyledImage2  src="https://placehold.co/626x1113"/>
      <StyledSeclogo01as11  src="https://placehold.co/399x80"/>
      <StyledTHANKYOU>THANK YOU</StyledTHANKYOU>
      <StyledThankyouforregisteringGearuptoinnovateandinspire>"Thank you for registering! Gear up to innovate and inspire."</StyledThankyouforregisteringGearuptoinnovateandinspire>
    </StyledAndroidMedium4>
  );
};
```
## OUTPUT:
![alt text](<Screenshot (41).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
