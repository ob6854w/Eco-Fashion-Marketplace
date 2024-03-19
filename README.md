# Project Title
Eco-Fashion Marketplace
## Overview

Eco-Fashion Marketplace is a place to access brands that use eco-friendly materials for their fashion styles.

### Problem

Among the world's most polluting businesses is the fashion industry. The environment is harmed during the clothes manufacture process. This has compelled a lot of fashion businesses to use eco-friendly production techniques. Many of these fashion labels use organic cotton and upcycled resources to create high-end, eco-friendly apparel. 

Consumers, interested in purchasing sustainable fashion invest significant time  and effort into researching brands and their practices. They often resort to searching through various online platforms, reading product descriptions, and checking customer reviews to assess a brand's sustainability credentials. 

### User Profile

- Fashion enthusiasts:
    - looking for a sustainable fashion brands
    - looking for detailed information about each brand's sustainability initiatives
    - looking for desired fashion styles made from eco-friendly materials
    

### Features

- As a user, I want to be able to access different sustainable fashion brands
- As a user, I want to be able to have detailed information for each sustainable fashion brand including information about their mission, values, and their supply chain transparency
- As a user, I want to be able to get a desired fashion styles made from eco-friendly materials
- As a user, I want to be able to create an account 
- As a user, I want to be able to login into my account
- As a user, I want to be able to use the search and filter options to narrow down brands
- As a user, I want to be able to leave reviews and ratings for brands they have purchased from, helping to build trust and credibility 
- As a user, I want to be able to use this app on various devices and screen sizes to have a seamless user experience across desktop, tablet, and mobile devices

## Implementation

### Tech Stack

- React js
- SASS
- Node js
- MySQL

- Client libraries:
    - react
    - react-router
    - axios

- Server libraries:
    - Knex js
    - Express 
    
### APIs

- No external APIs will be used

### Sitemap

- Home page
- About Us page
- Contact page
- Fashion brand detailed page
- Sign Up
- Login

### Mockups

### Home Page
![](homepage.png)

### Sign Up Page
![](signup.png)

### Login Page
![](loginpage.png)

### About Us Page
![](aboutus.png)

### Contact Us Page
![](contactus.png)

### Fashion Brand Detailed Page
![](detailedpage.png)


### Data

![](sql-diagram.png)

### Endpoints

List endpoints that your server will implement, including HTTP methods, parameters, and example responses.

**GET /brands**
  - Returns lists of brands

  **GET /brands/:id**
    - Returns a lists of brands with a specific ID.

 **POST /brands**
    - creates and returns the new brands created

 **PUT /brands/:id**
    - updates the brand with specific ID and returns the updated brand

 **DELETE /brands/:id**
    - deletes the brand with specific ID

### Auth

- JWT auth (JSON WEB TOKEN)
    - After a user signs up by providing personal information
    - User authenticates by providing neccessary credentials for login
    - After successful authentication, the server will generate token
    - The token information will be sent to the client
    - The token is later stored in local storage by the client
    - The token is discarded when the user logged out

## Roadmap

- Create the folder structure for client
    - Set up the client side using React js by creating components, routes and pages
    - Implement the html layout and styling

- Create the folder structure for server
    - Set up the server side using Node js with express framework
    -  Gather sample data for different fashion brands that use eco-friendly materials
    - Set up the routing and controllers
    - Set up migrations 
    - Set up seeds with sample of data

- Feature: detailed page of each fashion brands
    - Create a GET request from the server to populate the client side



## Nice-to-haves

Your project will be marked based on what you committed to in the above document. Under nice-to-haves, you can list any additional features you may complete if you have extra time, or after finishing.

