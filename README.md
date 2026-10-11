# python

Project Overview

The Survey Feedback Analyzer is a Python project that helps analyze customer feedback. It uses basic Python concepts to clean text, count words, calculate average ratings, and find useful insights from feedback data.

Objectives

* Store feedback data using a dictionary of lists.
* Add new feedback entries from user input.
* Clean feedback text by removing punctuation, extra spaces, and uppercase letters.
* Count feedbacks containing specific words.
* Calculate the average rating.
* Find the feedback with the longest comment.
* Identify unique words used across all feedbacks.
* Sort feedbacks by rating from highest to lowest.

Tools and Technologies

* Python
* Jupyter Notebook

Project Steps

Step 1: Preloaded Feedbacks

Created a dictionary of lists containing serial numbers, customer names, feedback comments, and ratings for 10 customers.

Step 2: Add More Feedbacks

Allowed users to enter additional customer names, written feedback, and ratings. Automatically generated serial numbers and appended the new data to the dictionary.

Step 3: Text Cleaning

Cleaned feedback comments by:

* Removing punctuation such as ., ,, !, and ?
* Replacing multiple spaces with a single space
* Removing leading and trailing spaces
* Converting text to lowercase

Step 4: Word Count Insights

Created a function called count_word_in_feedbacks(word) to count feedback entries containing specific words, including:

* good
* poor
* excellent

Step 5: Final Summary and Insights

* Displayed the final cleaned feedback data.
* Calculated the average customer rating.
* Found the feedback with the longest comment by word count.
* Identified unique words across all feedback comments.
* Sorted feedback entries by rating from highest to lowest.

Python Concepts Used

* Dictionary of Lists
* Variables and Data Types
* User Input
* Loops (for)
* Conditional Statements (if)
* Functions (def, return)
* String Methods (replace(), split(), join(), lower())
* Lists and Sets
* Built-in Functions (sum(), len(), max(), sorted())
* zip() for sorting related feedback data

Conclusion

This project helped me practice basic Python programming, text cleaning, functions, loops, and data analysis. It demonstrates how customer feedback can be organized and analyzed to identify useful insights.

Project Title: Survey Feedback Analyzer
Language: Python
Environment: Jupyter Notebook-end-Assignment
