# Assignment 1 - Client site profile
**Company name**: National 10th

**Company industry**: Restaurant/Bar

**Website URL**: 
https://www.ntnl.ca/10th-avenue

**Target audience/customer**: Restaurant and Bar patrons, as well as those there for the recreational activities on site, such as arcade games, bowling, and ping-pong.

**Summary**: National is a restaurant & entertainment venue inspired by North American tastes, with games and events, extraordinary food, and select craft beers. A place filled with Calgarians who embrace being Calgarian, National is the ideal place to unwind with friends, host a private event, or soak up the sun on a patio.

Long, communal tables and ample seating make it the perfect place to meet new people, and to gather with friends for brunch, lunch, or dinner.

Our food menu is big and well-considered, and dishes pair well with our curated selection of craft beers from small North American brewers.

In addition to the food and drinks, you can settle old scores on the ping pong and foosball tables, or head downstairs to bowl a few frames at our 8-lane bowling alley.


## Sitemap - National 10th
![](https://i.imgur.com/OE2bAlj.png)


## Content
#### Content types found on the website;
- Text
- Rich text
- Number
- Email
- Enumeration
- Media
- Password
- JSON
- Relation Fields

## Single Page
### **Homepage**
![](https://i.imgur.com/AqWT4z6.png)

![](https://i.imgur.com/OzMUYyQ.png)

### Content types;
**Nav Menu**: 
- text

**Nav Event bookings**: 
- Text

**Nav Now hiring**: 
- Text

**Nav Locations**: 
- Text

**Nav Gift cards**: 
- Text

**Nav Reserve a table (CTA)**: 
- Text

**Order Delivery (CTA)**: 
- Text

**Homepage Menu**: 
- Rich text content field for the menu
- Collection type: list
- Media content field: CTA button for a menu download. This could also be a one-to-many relation field, as many would download the pdf from this one source.
- Numbers for pricing

## List entry Page
### **Order Pickup**
![](https://i.imgur.com/4Mpa9PL.png)

![](https://i.imgur.com/SzQpe0B.png)

### Content types;
**Buttons to select what restaurant to order from**:
- Text

**Map showing locations**:
- JSON content field

**Menus for pickup**:
- Media content fields; Images of food
- Numbers; price of food
- Enumeration; dropdown menus to swap menu items
- Email and Password; to sign in to your account for ordering
- One-to-one relation field; users with an account email and password will have an account unique to them
- Text; descriptions of menu items
- Collection type: list
- Relation field: Many-to-many; plenty of patrons ordering plenty of options from multiple venues through the webpage

## Item Collection
### **Locations**
![](https://i.imgur.com/mdu1EVz.png)

![](https://i.imgur.com/2kdOp7n.png)

### Content types;
**Locations**:
- Collection type: List of venues with CTA buttons
- Many-to-many relation field; all patrons have the choice of multiple venues here to choose from 

#### **After selecting a venue**:
- JSON map data JS
- Enumeration content fields; dropdown reservation bars
- Text; CTA buttons and venue listings/address
- Numbers; in the dropdown menus to make selections including number of people and time
- Many-to-one relation field; all patrons that have chosen a specific location will be at that specified location only during their reservation

## Item Collection
### **Menus**
![](https://i.imgur.com/PhLAzCM.png)

![](https://i.imgur.com/aTW7h9y.png)

![](https://i.imgur.com/SbO1FPm.png)


### Content types;
#### **Menus**
- Collection type; list
- Text; description of food
- Numbers; price of food
- Rich text
- CTA button with downloadable Media (PDF Menu)
- Many-to-many relation field; All patrons have the choice of any menu items at any given location


#### **Footer**
- Text
- CTA buttons to other web pages/websites; text
- Footer links to other webpages; text
- Email and Password; account signup for benefits
- Many-to-one relation field; any patrons can sign up for an account
- One-to-one relation field; patrons must create an account using a email associated with them, which in turn makes them generate a password, providing them with a unique ID




# Analysis
### Is this site well structured?
I don't think this site is very well structured. Not only are many webpages following different examples of visual hierarchy, they also repeatedly redirect you to other web pages that make you choose the location/venue again that you wish to view.

### Why would someone choose this company over their competition?
I believe that people choose the National venues over other competitors because of a combination of fair pricing for good food and beer selections, as well as the in-venue options to have fun. Whether it's bowling, arcade games, ping-pong, or rooftop patios and live DJ's.

### How will this website relate to your Strapi project?
I would like to use this website and its many linked web pages because of the plethora of options they present, as well as the task of sorting through the jumbled, mismatched pages and non-stop redirections would be good practice. In addition, Concorde may present me with future job opportunities within the tech side of the company, and it would be nice to present them with alternatives and fixes for an otherwise messy navigation experience.
