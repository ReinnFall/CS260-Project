### CS260-Project
![Rough Sketch of my Startup](/startupImage.jpg)
## Elevator Pitch
If you are an avid Pokemon Go player, you have definitely run into the issue of knowing which Pokemon you keep and which ones to transfer. With such limited and storage and there being over 1000 of these creatures it can be tough to know which ones are valuable. My project is to provide an easy way to access this information across other databases so you can have confidence that the ones you keep are the cream of the crop.
## Key Features

-Ability to see how your Pokemon ranks as an overall Attacker and by its Type

-Access to 100% IV CP for common levels such as raids, field research and eggs

-Access to PVP rankings for each League (Great, Ultra, Master)

-Perfect IVs for each League

Note: This information will be taken from other databases that already exist such as Gamepress and Stadium Go.

## Technologies
# HTML
Organization of Pokemon image, search bar, links to evolution line, and inforamtion about its atacking and PVP rating.
# CSS
Make slick looking website that isn't distracting. The main pokemon will take most of the screen while the other information will be neatly organized underneath. The evolution line will be moving up and down when you scroll over them like they do in the main series games.

# Javascript
I want to be able to toggle between the Pokemon and its shiny form by clicking on the image. I'd also like to be able to switch the Pokemon by clicking on a miniture image of its evolved or pre - evolved forms.

# Web Service
This website will access information from other popular Pokemon Go websites such as Gamepress and Stadium Go. 

# Authentication
By logging in, you will have access to your own Pokemon Database.
# Database Persistence
There will be a feature where you can click a button that will add that Pokemon into your Inventory. Each person will have their own collection.
# Web Socket
There will be a show-off tab where you can post your cool finds in Pokemon Go. You can also message others in a public channel.
# Web Framework
My website will include React.

### Startup HTML


## HTML Pages
I currently have 2 html pages: a home page that asks for a login and to choose a Pokemon and a Ratings page that will include ratings for each Pokemon in Pokemon Go.

## HTML Tags
My HTML files include the necessary tags.
## Links
My naviagtion links are at the top of each of my HTML files.
## Application Textual Content
To be completely honest, I don't know what this is referring to. I hope I did it!
## Placeholder for 3rd party Service Calls
All my data for "Attacker and PvP Rankings" "Max IV CP Value" "Rank 1 CP Values" come from different websites. For now, I have manually added the data for Charizard.
## Application Images
Right now I have manually linked Charizard's images in the ratings section. Eventually I would like to dynamically access a database with every Pokemon.
## Login Placeholder
The placeholder is found in my home page. As of right now it brings the user to ratings. Eventually I would like it to keep the user on the home page and only go to Ratings when a Pokemon is selected.
## Database Data Placeholder

## WebSocket Data Placeholder
My home page has a section called "Recent Catches" that will display the user's name and the rare Pokemon that they caught. This action will be initaited when they press the "Got it" button in Ratings. (This is not implemented)




