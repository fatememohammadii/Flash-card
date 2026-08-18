🇫🇷 French Flash Card App

A simple and interactive **French vocabulary learning application** built with Python, Tkinter, and Pandas.

The application displays French words as flashcards and automatically flips them after 3 seconds to reveal their English translations. Users can mark words as **known** or continue learning them later.

## 🚀 Features

* 🎴 Displays random French vocabulary flashcards
* ⏱️ Automatically flips the card after 3 seconds
* 🇫🇷 Shows the French word on the front
* 🇬🇧 Shows the English translation on the back
* ✅ Mark words you already know
* ❌ Keep unknown words for future practice
* 💾 Saves your learning progress automatically
* 🔀 Randomly selects a new word after each card

## 🛠️ Technologies Used

* **Python**
* **Tkinter** – for the graphical user interface
* **Pandas** – for reading and saving vocabulary data
* **Random** – for selecting random flashcards

## 📂 Project Structure

```text
French-Flash-Card-App/
│
├── main.py
│
├── data/
│   ├── french_words.csv
│   └── words_to_learn.csv
│
└── images/
    ├── card_front.png
    ├── card_back.png
    ├── right.png
    └── wrong.png
```

## ▶️ How It Works

1. A random French word is displayed.
2. After **3 seconds**, the card automatically flips.
3. The English translation is displayed.
4. Click the **✔️ button** if you know the word.
5. The known word is removed from the learning list.
6. Your progress is saved in `words_to_learn.csv`.
7. Click the **❌ button** if you don't know the word and want to continue practicing it.

## 💻 Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project folder:

```bash
cd French-Flash-Card-App
```

Install the required dependency:

```bash
pip install pandas
```

Run the application:

```bash
python main.py
```


---

⭐ If you like this project, feel free to give it a star!
