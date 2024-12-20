Spell Check and Auto-Correction App
===================================

This project is a student buildout of a basic spell-checking application built with React. The app detects misspelled words and suggests corrections based on a custom dictionary. Users can enter text, and if a word does not match the custom dictionary, a corrected version is suggested.

Table of Contents
-----------------
1. Features
2. Technologies Used
3. Getting Started
4. Usage

Features
--------
- Detects misspelled words as the user types and suggests corrections.
- Customizable dictionary for adding additional word corrections.
- Currently limited to a predefined set of words, making it a manageable buildout project for practicing React and JavaScript fundamentals.

Technologies Used
-----------------
- React (for building the UI)
- JavaScript (for implementing the spell-checking logic)

Getting Started
---------------
### Prerequisites
Make sure you have the following installed:
- Node.js (v14 or higher)
- npm (Node Package Manager)

### Installation
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/Sai-Karthik9113/XSpellCheck.git
   ```

2. Navigate to the project directory:
   ```
   cd XSpellCheck
   ```

3. Install dependencies:
   ```
   npm install
   ```

### Running the Application
1. Start the development server:
   ```
   npm start
   ```

2. Open your browser and go to `http://localhost:3000` to use the app.

## Screenshots

Below are screenshots showcasing the app on load and while performing spell-check:

![Flag Cards Grid][on page load]
![Flag Cards Grid][spell check]

## Usage
1. Enter text in the provided text area.
2. If a misspelled word from the custom dictionary is found, the app will display a suggestion for correction.
3. The app uses a predefined dictionary of words (such as "teh" for "the" and "exampl" for "example"). This dictionary can be customized by adding more word-correction pairs in the `customDictionary` object within the `SpellCheckApp` component.

---------------------------------------------------------------------------------------------------------------------------------------------------
Thank you for exploring this buildout project!

[on page load]: src/assets/images/onPageLoad.png
[spell check]: src/assets/images/spellCheck.png