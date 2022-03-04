# react-starlink-eric-li

This is a create-react-app project based on react and react-dom.

Operated by SpaceX, Starlink is satellite internet constellation that provides satellite internet access across the globe. Specifically, over 1700 Starlink satellites havn been deployed by the end of last year. This program allows users to search for Starlink satellites fitting the input parameters (including longitude, latitide, elevation, altitude, and duration) and visualize the real-time locations of the target satellites.

To visualize the full functionality of the program, run the program locally through the following steps:

  1. downlaod the package
  2. create project using "npx create-react-app@latest starlink cd starlink"
  3. In the starlink folder created, paste each file from the downloaded package and replace all files with the same name
  4. install the following
      I. "npm install --save antd@3"
      II. "npm install --save axios"
      III. "npm install --save topojson-client"
      IV. "npm install --save d3-geo"
      V. "npm install --save d3-geo-projection"
      VI. "npm install --save d3-selection"
      VII. "npm install --save d3-time-format"
      VIII. "npm install --save d3-scale"
      IX. "npm install --save d3-scale-chromatic"
  5. locate the starlink folder and use "npm start" to open the program

Alternatively, view the preliminary interface design through stackblitz using the following link. 

[Edit on StackBlitz](https://stackblitz.com/edit/react-starlink-eric-li)