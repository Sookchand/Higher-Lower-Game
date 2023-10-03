
#  Higher or Lower {Python Game}
The game in the code is a guessing game where the player has to guess which celebrity has more followers. Here’s a brief description of how it works:

The game starts by randomly selecting two celebrities from a list of celebrities (the data list). Each celebrity is represented as a dictionary with keys such as ‘name’, ‘description’, ‘country’, and ‘follower_count’.

The game displays the information about the two celebrities to the player. The player has to guess which celebrity has more followers by typing ‘A’ or ‘B’.

The game checks if the player’s guess is correct. If the guess is correct, the player’s score is incremented by 1, and the game continues with a new pair of celebrities. If the guess is incorrect, the game displays the final score and exits.

The game keeps running in a loop until the player guesses incorrectly.

This game tests the player’s knowledge about celebrities and their popularity on social media. It’s a fun way to learn more about different celebrities while also challenging your intuition and guessing skills.
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![Higher_lower](https://github.com/Sookchand/Higher-Lower-Game/assets/34344439/0156b336-fda3-4c3a-b314-304283fd5d78)


## Tech Stack
The game in the provided code is developed using Python, which is a popular high-level programming language known for its simplicity and readability. Here are the specific Python features and modules used:

1. **Python's built-in functions**: The game uses several built-in Python functions such as `print()` for displaying messages, `input()` for getting user input, and `exit()` for terminating the program.

2. **Python's random module**: The `choice()` function from Python's `random` module is used to randomly select a celebrity from the list of celebrities.

3. **Python's while loop and if-else statements**: The game logic is controlled using a `while` loop and `if-else` statements. The `while` loop keeps the game running until the user guesses incorrectly, and the `if-else` statements are used to check the user's guess and update the score.

4. **Python's global keyword**: The `global` keyword is used to indicate that the `score` variable is a global variable that can be accessed and modified inside the `check_answer()` function.

5. **Custom Python functions**: The game defines several custom functions such as `get_new_celebrity()`, `format_celebrity()`, and `check_answer()` to organize the code and make it more modular and readable.

6. **Python's string formatting**: The game uses f-strings, a feature introduced in Python 3.6, to embed expressions inside string literals for formatting.

7. **Python's list data structure**: The list of celebrities (`data`) is represented as a list of dictionaries in Python.

8. **Python's dictionary data structure**: Each celebrity is represented as a dictionary with keys such as 'name', 'description', 'country', and 'follower_count'.

Please note that this code also references some external modules (`game_data`, `art`) which are not included in the provided code snippet. These modules contain additional data and functionality used by the game. 😊
## Documentation
Here are the documentations for the technologies you asked for:

- **Python**: You can find the official Python documentation [here](^1^). It provides comprehensive information about Python's built-in functions, data structures, modules, and more².
- **Python's built-in functions**: The official Python documentation provides detailed information about Python's built-in functions⁴.
- **Python's random module**: The official Python documentation provides a detailed guide on Python's random module⁷.
- **Python's while loop and if-else statements**: The official Python documentation provides a detailed guide on Python's compound statements, including while loop and if-else statements¹².
- **Python's global keyword**: The official Python documentation provides a detailed guide on Python's global keyword³¹.
- **Python's custom functions**: The official Python documentation provides a detailed guide on defining your own Python function²⁴.
- **Python's string formatting**: The official Python documentation provides a detailed guide on string formatting in Python[^20^].
- **Python's list data structure**: The official Python documentation provides a detailed guide on list data structure in Python¹⁵.
- **Python's dictionary data structure**: The official Python documentation provides a detailed guide on dictionary data structure in Python¹⁵.

Please note that these are the official documentations and they provide the most accurate and up-to-date information about these topics. However, there are also many other resources and tutorials available online that can help you understand these topics better. Always make sure to use reliable sources to ensure the accuracy of the information. Happy learning! 😊

Source: Conversation with Bing, 10/3/2023
(1) Our Documentation | Python.org. https://www.python.org/doc/.
(2) Python 3.11.5 documentation. https://docs.python.org/.
(3) Built-in Functions — Python 3.11.5 documentation. https://docs.python.org/3/library/functions.html.
(4) random — Generate pseudo-random numbers — Python 3.11.5 documentation. https://docs.python.org/3/library/random.html.
(5) 8. Compound statements — Python 3.11.5 documentation. https://docs.python.org/3/reference/compound_stmts.html.
(6) 7. Simple statements — Python 3.11.5 documentation. https://docs.python.org/3/reference/simple_stmts.html.
(7) Defining Your Own Python Function – Real Python. https://realpython.com/defining-your-own-python-function/.
(8) string — Common string operations — Python 3.11.5 documentation. https://docs.python.org/3/library/string.html.
(9) 5. Data Structures — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/datastructures.html.
(10) The Python Tutorial — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/index.html.
(11) builtins — Built-in objects — Python 3.11.5 documentation. https://docs.python.org/3/library/builtins.html.
(12) The Python Standard Library — Python 3.11.5 documentation. https://docs.python.org/3/library/index.html.
(13) Python Random Module - W3Schools. https://www.w3schools.com/python/module_random.asp.
(14) random – generate random numbers — MicroPython latest documentation. https://docs.micropython.org/en/latest/library/random.html.
(15) Python Random Module: Generate Random Numbers and Data - PYnative. https://pynative.com/python/random/.
(16) 4. More Control Flow Tools — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/controlflow.html.
(17) 6. Conditionals and Loops — PyMan 0.9.31 documentation. https://physics.nyu.edu/pine/pymanual/html/chap6/chap6_loopsconds.html.
(18) syntax - Else clause on Python while statement - Stack Overflow. https://stackoverflow.com/questions/3295938/else-clause-on-python-while-statement.
(19) Everything About Python Dictionary Data Structure: Beginner's Guide. https://pyshark.com/python-dictionary-data-structure/.
(20) Python data structures, dictionary? - Stack Overflow. https://stackoverflow.com/questions/2028723/python-data-structures-dictionary.
(21) Dictionaries in Python – Real Python. https://realpython.com/python-dicts/.
(22) Data Structures (Part II): Dictionaries - Python Like You Mean It. https://www.pythonlikeyoumeanit.com/Module2_EssentialsOfPython/DataStructures_II_Dictionaries.html.
(23) Python String Formatting Best Practices – Real Python. https://realpython.com/python-string-formatting/.
(24) Python String Formatting - W3Schools. https://www.w3schools.com/python/python_string_formatting.asp.
(25) Python f-string tips & cheat sheets - Python Morsels. https://www.pythonmorsels.com/string-formatting/.
(26) How to document python function parameter types?. https://stackoverflow.com/questions/7690220/how-to-document-python-function-parameter-types.
(27) GitHub - TomSchimansky/CustomTkinter: A modern and customizable python .... https://github.com/TomSchimansky/CustomTkinter.
(28) Common Python Data Structures (Guide) – Real Python. https://realpython.com/python-data-structures/.
(29) Using the List Data Structure in Python - Section. https://www.section.io/engineering-education/list-data-structure-python/.
(30) Python Data Structures Cheat Sheet: The Essential Guide - StationX. https://www.stationx.net/python-data-structures-cheat-sheet/.
(31) Lists, Tuples and Dictionaries - Python 101 1.0 documentation. https://python101.pythonlibrary.org/chapter3_lists_dicts.html.
(32) Python Global Keyword (With Examples) - Programiz. https://www.programiz.com/python-programming/global-keyword.
(33) Python | Keywords | global | Codecademy. https://www.codecademy.com/resources/docs/python/keywords/global.
(34) Global keyword in Python - GeeksforGeeks. https://www.geeksforgeeks.org/global-keyword-in-python/.
(35) Python Keywords With Examples – PYnative. https://pynative.com/python-keywords/.
(36) undefined. https://customtkinter.tomschimansky.com/documentation.
(37) undefined. http://docs.python.org/tutorial/datastructures.html.
## Lessons Learned
Some possible lessons learnt from building this game are:

- How to use Python's built-in functions, data structures, and modules to create a simple and fun game.
- How to use PyGame, a popular library for game development in Python, to handle graphics, sound, events, and more.
- How to use object-oriented programming principles to design and organize game objects and logic.
- How to use loops, conditional statements, and functions to control the game flow and implement game rules.
- How to use random module to generate random choices and add variety to the game.
- How to use string formatting to display information and messages in a clear and attractive way.
- How to use input function to get user input and validate it.
- How to use global keyword to access and modify global variables inside functions.
- How to create custom functions to modularize and reuse code.

# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.
