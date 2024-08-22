# Movie Recommendations Project

This project is a Netflix Based Movie Recommendations web application that allows users to search for movie recommendations based on inputted movie titles. The application leverages a machine learning model to suggest movies similar to the user's input.

## Features

- **Search Functionality**: Users can input a movie title, and the system will provide recommendations based on the entered title.
- **Autocomplete**: As users type in the search bar, movie title suggestions will be displayed.
- **Responsive Design**: The application is designed to be responsive and works well on different screen sizes.

## Technologies Used

- **HTML/CSS**: For structuring and styling the webpage.
- **Bootstrap**: For responsive design and pre-built UI components.
- **JavaScript**: For dynamic behavior on the webpage.
- **Jinja2**: Used in combination with Flask for templating.
- **Font Awesome**: For icons.
- **Google Fonts**: For custom fonts.
- **AutoComplete.js**: For providing autocomplete suggestions in the search bar.

## Setup and Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/Movie-Recommendations-Project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Movie-Recommendations-Project
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   python main.py
   ```

5. Open your web browser and go to `http://localhost:5000` to access the application.

## Usage

- **Search for a Movie**: Type the name of a movie in the search bar and press the "Search" button. The system will display recommended movies based on your input.
- **Autocomplete**: As you type, the system will suggest movie titles. You can select a title from the dropdown to auto-fill the search bar.

## Project Structure

- `main.py`: The Flask application file that handles routing and backend logic.
- `home.html`: The main HTML file for the webpage.
- `static/`: Directory containing static files such as CSS and JavaScript.
- `templates/`: Directory containing the HTML templates used by Flask.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [Dr Briit](https://github.com/MrBriit) for the inspiration and initial project setup.
