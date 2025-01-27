# YnovBot - Chatbot

A lightweight and responsive chatbot interface built using AlpineJS and TailwindCSS. The chatbot is capable of responding to user inputs with predefined prompts and replies.

## Features

- **Dynamic Chat Interface**: User and bot messages are styled and displayed in a conversational format.
- **Predefined Responses**: The chatbot uses preset prompts and replies to provide engaging interactions.
- **Typing Indicator**: Simulates a bot typing animation for a more realistic chat experience.
- **Responsive Design**: Built with TailwindCSS to ensure responsiveness across devices.

## Technologies Used

- **HTML5**: Structure of the application.
- **CSS**: Styled with TailwindCSS for modern and responsive design.
- **JavaScript**: Functionality powered by AlpineJS.

## File Structure

- `index.html`: Main HTML file containing the structure of the chatbot interface.
- `style.css`: Optional file for custom styles (not included in this setup).
- `script.js`: JavaScript file handling chatbot logic and interactions.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.).
- Basic knowledge of HTML and JavaScript to customize if needed.

### Installation

1. Clone this repository or download the project files.
   ```bash
   git clone https://github.com/KACHOURElmehdi/YnovBot
   ```
2. Navigate to the project directory.
   ```bash
   cd YnovBot
   ```
3. Open `index.html` in your browser to view the chatbot in action.

### Usage

1. Start typing in the input box and press Enter to send a message.
2. The bot will respond with predefined replies based on your input.
3. Messages and responses will appear in a conversational format.

## Customization

### Adding Prompts and Replies

Modify the `prompts` and `replies` arrays in the `script.js` file to add your own questions and answers:

```javascript
prompts: [
    ["hi", "hello"],
    ["how are you"],
],
replies: [
    ["Hello!", "Hi there!"],
    ["I'm doing great, thanks for asking!"],
]
```

### Styling

Customize the design by editing the TailwindCSS classes in `index.html`.

## Demo

Run the project locally or deploy it on your preferred hosting platform to see the chatbot in action.

## Contributions

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- [AlpineJS](https://alpinejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [Material Design Icons](https://materialdesignicons.com/)
