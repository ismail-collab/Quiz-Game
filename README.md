# API Quiz Game

This is a simple and interactive Quiz Game that pulls trivia questions from an API and presents them to the user in a fun, engaging, and responsive interface. The project demonstrates the use of external API data, dynamic user interface updates, and basic game mechanics to create a seamless user experience.

## Features

- Fetches trivia questions in real-time from an external API.
- User-friendly interface with a score-tracking system.
- Multiple question categories and difficulty levels to choose from.
- Immediate feedback on correct and incorrect answers.

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Trivia API (Open Trivia DB)

## Here you go 

![Screenshot of the API Quiz Game](./Quiz-pic.png)



### API Reference

This game uses the [Open Trivia Database API](https://opentdb.com/api_config.php) to fetch trivia questions.

- **Endpoint**: `https://opentdb.com/api.php`
- **Parameters**:
  - `amount`: Number of questions
  - `category`: Category of questions
  - `difficulty`: Difficulty level (easy, medium, hard)

Example API call:

```bash
https://opentdb.com/api.php?amount=10&category=9&difficulty=medium
