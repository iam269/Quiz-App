# Quiz App

A comprehensive and interactive quiz application built with vanilla HTML, CSS, and JavaScript. This web-based quiz challenges users with a series of multiple-choice questions covering various topics including geography, science, literature, and general knowledge. The application provides immediate feedback on answers, tracks user scores, and offers a clean, responsive interface suitable for educational purposes or casual knowledge testing.

## Live Demo

Experience the quiz live: [https://iam269.github.io/Quiz-App/](https://iam269.github.io/Quiz-App/)

## Features

### Core Functionality
- **10 Pre-loaded Questions**: A curated set of multiple-choice questions across diverse categories
- **Real-time Scoring**: Automatic score calculation with instant feedback on correct/incorrect answers
- **Visual Feedback**: Color-coded responses (green for correct, red for incorrect) to enhance user experience
- **Progress Tracking**: Sequential question navigation with clear progress indication

### User Interface
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Intuitive Navigation**: Simple "Next" button to progress through questions
- **Clean Aesthetics**: Modern blue-themed design with smooth hover effects and transitions
- **Accessibility**: Proper semantic HTML structure and keyboard-friendly interactions

### Technical Features
- **Vanilla JavaScript**: No external dependencies, ensuring fast load times and broad compatibility
- **Modular Code Structure**: Well-organized JavaScript with clear separation of concerns
- **Dynamic Content Rendering**: Questions and answers generated programmatically from a data array
- **State Management**: Efficient handling of quiz state, score, and question progression

## How It Works

1. **Quiz Initialization**: The application starts with the first question displayed
2. **Answer Selection**: Users click on one of four multiple-choice options
3. **Immediate Feedback**: Correct answers are highlighted in green, incorrect ones in red, with the correct answer revealed if wrong
4. **Score Tracking**: Correct answers increment the user's score
5. **Progression**: Users click "Next" to proceed to subsequent questions
6. **Completion**: After the final question, a summary screen shows the total score

## Question Categories

The quiz includes questions on:
- Geography (capitals, continents)
- Astronomy (planets)
- Literature (authors, works)
- Mathematics (prime numbers)
- Biology (largest mammals)
- Chemistry (elements)
- Physics (boiling points)
- Art (famous paintings)
- Languages (spoken in countries)

## Customization

The quiz is easily extensible:
- Add new questions by modifying the `questions` array in `script.js`
- Customize styling by editing `style.css`
- Update the title and branding in `index.html`

## How to Run Locally

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)

### Running the Application
1. Download or clone this repository to your local machine
2. Navigate to the project directory
3. Open `index.html` in your preferred web browser
4. Begin taking the quiz by selecting answers and clicking "Next"

No server setup or additional software installation required - it's a pure client-side application!

## Project Structure

```
Quiz App/
├── index.html      # Main HTML structure
├── style.css       # Application styling
├── script.js       # Quiz logic and question data
├── question.png    # Favicon icon
└── README.md       # This file
```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Responsive styling with modern features like Flexbox and transitions
- **JavaScript (ES6)**: Core functionality including arrow functions, template literals, and DOM manipulation

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Contributing

Contributions are welcome! To add new questions or improve the application:

1. Fork the repository
2. Create a feature branch
3. Add your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Future Enhancements

Potential improvements for future versions:
- Timer functionality for time-limited quizzes
- Question categories with filtering options
- High score persistence using localStorage
- Multiple quiz modes (practice, timed, etc.)
- Question randomization
- Progress saving and resuming