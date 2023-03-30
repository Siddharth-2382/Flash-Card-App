# Flash Card App
This is a simple flash card app built with Python and Tkinter that allows users to learn new words in a foreign language. The app displays a French word and after a short while, the user is supposed to check if they know the correct English word for that. If the user answers correctly, they should click on the correct button, or if wrong, they should click the incorrect button. The app uses two CSV files: `french_words.csv` and `words_to_learn.csv`. The `french_words.csv` file contains the initial list of French words that the user will learn, and the `words_to_learn.csv` file contains the words that the user answered incorrectly and needs to review.

## Prerequisites
The following libraries are required to run this application:

- pandas
- tkinter

## How to run the app
1. Clone the repository to your local machine.

        git clone https://github.com/Siddharth-2382/Flash-Card-App.git
2. Install the required libraries using pip.

        cd Flash-Card-App
        pip install -r requirements.txt
3. Navigate to the project directory and run the flash_card_app.py file using Python.

        python main.py
The app will launch, and you can start using it to learn new words in French.

## How to use the app
1. When the app launches, a French word will be displayed on the screen.
2. After a short while, the English translation will be displayed.
3. If you knew the correct translation, click the "Right" button. A new word will be displayed.
4. If you didn't know the correct translation, click the "Wrong" button. The word will be added to the `words_to_learn.csv` file, and a new word will be displayed.
5. The app will continue to display words until all words in the french_words.csv file have been learned.

## Acknowledgments
This project was built by me and completed using Python, Tkinter and Pandas.

## Demo
![demo](https://user-images.githubusercontent.com/94699055/228343455-15189d39-2ae7-4a98-b3d9-a469f71ba46f.gif)
