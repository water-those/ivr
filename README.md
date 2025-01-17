﻿# Xylem Challenge IVR Backend

Based off of [Twilio's IVR Example](https://www.twilio.com/docs/tutorials/walkthrough/ivr-phone-tree/node/express)! 
<br>
This IVR + SMS system is a part of AquaFlo and submitted to the [2022 Xylem Global Student Ignite Innovation Challenge](https://xyleminnovationchallenge.bemyapp.com/) winning Grand Prize!

## IVR and SMS Demo
💦 [**Video Demo of AquaFlo's IVR and SMS**](https://drive.google.com/file/u/1/d/1pLDBj1_BllvA7Zys-oK93jW9aK4nT5Vl/view) 💦

![](https://user-images.githubusercontent.com/38355190/165388074-c4cc22d8-3b25-4e01-b5ad-133a50b6a8d9.png)

## Local Development

1. First clone this repository and `cd` into it.

   ```bash
   git clone git@github.com:water-those/ivr.git \
   cd ivr
   ```
1. Install project's dependencies.

   ```bash
   npm install
   ```

1. Make sure the tests succeed.

   ```bash
   npm test
   ```

1. Start the development server.

   ```bash
   npm start
   ```

1. Check it out at [http://localhost:3000](http://localhost:3000).


## Code Structure

`public/stylesheets`
CSS

`scripts`
Contains one-off scripts related to managing IVR data. 

`src`
Source code files.

Each directory contains logic for handling their associated url. 
e.g. `src/ivr` contains code for handling any requests to `/ivr/.../`
