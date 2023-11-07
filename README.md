# Bot Army Management App
This application allows you manage your bot. You can view a collection of bots and add them to your army
You can also remove bots from your army and see the list updated in real-time


# Getting Started with Create React App

Clone the repository and install the depenencies

## Available Scripts
Components
App.js
The main component of the application. It manages the state of the bot army and renders YourBotArmy and BotCollection components.

YourBotArmy.js
This component displays the bots in your army. It receives the botArmy array as a prop and provides a way to delete bots from the army.

BotCollection.js
This component displays the collection of available bots. It allows you to add bots to your army. It receives addBotToArmy and onUpdateBots functions as props to manage the state of the bot army in the parent component.

Functions
addBotToArmy(bot)
This function adds a bot to the army if it is not already present. It checks for the bot's existence in the army based on the id property.

onUpdateBots(updatedBots)
This function updates the state of the bot army with the provided array of bots.

onDelete(botId)
This function removes a bot from the army based on its id.

Technologies Used
React: The application is built using the React library for building user interfaces.
useState Hook: The useState hook is used to manage state within functional components.
Props: Components communicate and share data through props, enabling a modular and flexible structure.
Conditional Rendering: Bots are added or removed from the army based on conditions using JavaScript logic.
Feel free to modify and enhance the application according to your requirements!
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Usage
Upon launching the application a list of bots will appear in the botcolletion component 
You can click a bot and add it to YourBotArmy
You can view your bot army and each bot card has a delete button to remove it from the army

# Components

 # App.js
The main component of the application. It manages the state of the bot army and renders YourBotArmy and BotCollection components.

# YourBotArmy.js
This component displays the bots in your army. It receives the botArmy array as a prop and provides a way to delete bots from the army.

# BotCollection.js
This component displays the collection of available bots. It allows you to add bots to your army. It receives addBotToArmy and onUpdateBots functions as props to manage the state of the bot army in the parent component.

# Functions
# addBotToArmy(bot)
This function adds a bot to the army if it is not already present. It checks for the bot's existence in the army based on the id property.

# onUpdateBots(updatedBots)
This function updates the state of the bot army with the provided array of bots.

# onDelete(botId)
This function removes a bot from the army based on its id.

# Technologies Used
React: The application is built using the React library for building user interfaces.
useState Hook: The useState hook is used to manage state within functional components.
Props: Components communicate and share data through props, enabling a modular and flexible structure.
Conditional Rendering: Bots are added or removed from the army based on conditions using JavaScript logic.
Feel free to modify and enhance the application according to your requirements!
