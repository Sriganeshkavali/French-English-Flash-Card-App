# French-English-Flash-Card-App
A GUI-based flashcard application built with Python and Tkinter to help users learn French vocabulary. The app displays a French word, waits for 3 seconds, and then flips the card to reveal the English translation.
## Features
Interactive Flashcards: Displays a French word and automatically flips to English after a 3-second delay.

Progress Tracking:

* **Known (Check Button)**: Removes the current word from the list and saves the remaining words to to_learn.csv so you don't study them again.

* **Unknown (Cross Button)**: Skips the card but keeps it in the learning pool for future review.

Data Persistence: Uses pandas to read and write CSV files to track learning progress.

### Technologies Used
Python 3.x

Tkinter (GUI Framework)

Pandas (Data manipulation)

CSV (Data storage)

### Project Structure
To run this script, ensure your project directory looks like this:
Project_Folder/
│
├── main.py                # The python script provided

├── data/

│   ├── french_words.csv   # Source data

│   └── to_learn.csv       # Generated automatically (progress file)

└── images/

    ├── card_front.png
    
    ├── card_back.png
    
    ├── right.png
    
    └── wrong.png
### How to Use
Launch the app. A card with a French word will appear.

Try to guess the meaning.

Wait 3 seconds for the card to flip and show the English answer.

Click the Check Mark if you knew the word (it won't be shown again).

Click the Cross if you didn't know it (it will remain in the deck).
