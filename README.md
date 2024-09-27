# BanuittMTG
BanuittMTG is a custom-built Discord app that integrates with the Scryfall API to provide real-time access to Magic: The Gathering card data, rulings, and effects. Inspired by a lifetime of playing MTG since its release in 1993, this project is designed to enhance the gaming experience, especially for informal games of all formats.

The app allows players to quickly search for and understand how abilities, triggers, and rulings affect gameplay, enabling informed decisions on the spot. Whether you're playing with old friends or sharing the game with a new generation of MTG fans, BanuittMTG aims to be your go-to assistant for all things MTG.

## Features
- **Quick Card Lookup**: Instantly search for Magic: The Gathering cards by name and retrieve relevant data, including images, card types, and set information.
- **Real-Time Rulings**: Access up-to-date rulings and clarifications on how specific card interactions work.
- **Scryfall Integration**: Powered by the Scryfall API, ensuring accurate and comprehensive data.

## Usage
In your Discord server, you can interact with the bot using a simple command structure:
`!card [Card Name]`
For example:
`!card Black Lotus`

The bot will return the card's details, including its image and any applicable rulings.

## Setup Instructions
To get BanuittMTG up and running in your own server, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/banuitt.git

2. **Navigate to the MTG folder:**
   ```bash
   cd banuitt/MTG

3. **Install dependencies:**
   Make sure you have [Node.js](https://nodejs.org/) installed, then run:
   ```bash
   npm install

4. **Set up environment variables:**
   Create a `.env` file in the project directory with the following content:
   ```plaintext
   DISCORD_TOKEN=your_discord_bot_token

5. **Run the bot locally:**

   ```bash
   node index.js

## Future Plans
- **Advanced Card Search**: Add the ability to search by card type, mana cost, or set.
- **Commander Mode**: Implement features specific to Commander format games, such as deck-building tools or multiplayer rulings.
- **Voice Integration**: Consider adding voice command integration for seamless gameplay without typing.
- **Expanded Rulings**: Pull rulings for more obscure cards and interactions, expanding the bot's usefulness for both casual and tournament play.

## License
This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for more details.
