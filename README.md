# Birthday Greeting Card App

This is a simple React app that displays a birthday greeting card. When clicked, the card flips open to reveal a personalized birthday message and plays background music.

## Features

- Flip animation for the birthday card
- Personalized birthday message
- Background music support
- Clean and responsive design

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/abinayagoudjandhyala/birthday-greeting-card.git
cd birthday-greeting-card
```

2. Install the dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

Visit `http://localhost:3000` in your browser to see the app.

## Project Structure

```
src/
│
├── components/
│   └── LoveLetter/
│       ├── LoveLetter.js
│       ├── LoveLetter.css
│       └── kushi.mp3
│
├── App.js
├── App.css
├── index.js
└── index.css
```

## Customization

To personalize the card:

- Edit the name, age, and message in `LoveLetter.js`
- Replace `kushi.mp3` with any music of your choice
- Update styles in `LoveLetter.css` to change appearance

## License

This project is open source and available under the MIT License.
