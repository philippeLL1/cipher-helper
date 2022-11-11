# cipher-helper

## Welcome to my GUI for Assignment 2!

After completing the Solitaire Cipher assignment, I tought it would be fun to make a Graphical User Interface because it would let us appreciate the final result. Normally this would be slightly complicated, but Java's portability can be used to make forms that will be displayed on any device running the JDK (provided there is graphical output). I have written instructions below on how to import the GUI into your project. Note that the GUI will use the ouput of your `Deck.java` and `SolitaireCipher.java`, so it acts as a main() method, in a sense.

## How to Import the GUI
1. Make sure the `Deck.java` and `SolitaireCipher.java` files are located in the `assignment2` package.
2. Download the following classes and forms. Place these directly into your `assignment2` directory.
    - `main.java`
    - `textInput.java`
    - `main.form`
    - `textInput.form`
3. [Optional]: Download the `images` directory and place it into `assignment2`. This provides icons for the pop-up window that displays the result

## How to Use the GUI
1. Run main.java
2. Fill in the following text boxes
  - message: A string that you would like to use as input
  - seed: An int to use as the seed
  - shuffles: An int to choose how many time to shuffle the deck before generating keystream values
  - number of cards: An int between 1 and 13 (inclusively) to choose the number of cards per suit in the deck
  - number of suits: An int between 1 and 4 (inclusively) to choose the number of suits in the deck
3. From the toggle menu, choose Encode or Decode and press "Go!"
4. Alternatively, you can press "input from text", which will open another window
5. This window lets you enter parameters in a single paragraph, one parameter per line
6. Use the following format:
  1. message
  2. seed
  3. shuffles
  4. number of cards
  5. number of suits
6. Example (from ed):
  SEOMLURAMOKISHS
  11012022
  1
  13
  2
7. This allows you to quickly copy & paste examples that you would like to try. You can use this to text your code on the fly without having to retype parameters individually. All you have to do is re-run main.java, click "input from text" and paste the paragraph

## Warnings
- This GUI does some input validation, but doesn't help your code in any other way
  - It only validate the integer values, because without this the GUI would crash very easily.
  - It does not validate the "message" text box, as this is part of the assignment
- Use this GUI at your own risk. I ran multiple examples, and I had correct results each time. However, I cannot guarantee that my code is 100% accurate. If using my GUI somehow leads to you missing a bug in your code (I highly doubt this would happen), I unfortunately cannot be held responsible.
- It might crash! The GUI is generally stable, but the code is still messy, and it might crash on some inputs.
- I coded this on Intellij. I'm pretty sure it'll work on any IDE, but I haven't tested this yet.
  
