Live Netlify Site Link: https://d280-interactive-map.netlify.app/

# D280 APP PA
Student Name: Christopher Whaley

Student ID: 010292135

Angular CLI: 18.0.7

Node: 20.15.0

Package Manager: npm 10.7.0

OS: linux x64

Angular: 18.0.6

## Introduction

This project is used to enhance website functionality using JavaScript programming in conjunction with existing frameworks, assets, and web content. For this, I will be enhancing a website using the Angular JavaScript framework and an application programming interface (API) by creating a visual interface for a scalable vector graphics (SVG) map.

## Whats included in the project

A.   Using an "SVG Map" web link, provide the world map visual interface for this project in the ipplication.

B.   Using the "World Bank API" web link, identifies each of the following six properties for each country:

  1. Country Name (e.g. United States)
  2. Country Capital (e.g. Washington D.C.)
  3. Region (e.g. North America)
  4. Income Level (e.g. High Income)
  5. Longitude (e.g. -77.032)
  6. Latitude (e.g. 38.8895)

C.   Using Angular routing, configures the root component to redirect automatically from the default URL.

D.   Creates an HTML layout with two columns: one column for the map itself and one column to show the required country information from the API in part B.

E.   Uses an event binding, converting the SVG map into an interactive Angular component.

F.   Connects the SVG file to a mouse event handler to transmit data to the component for processing.

G.   Generates an API service using HTTPClient to make HTTP calls and includes the following methods:

  1. one method within the service that accepts a two-letter country code as an input parameter that returns additional information gathered from the API for the selected country
  2. one method within the component that will trigger the service method when a country is selected and set a local variable that will receive the information about the country for display in the appropriate column of the HTML page
