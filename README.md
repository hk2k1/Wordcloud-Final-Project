# Wordcloud-Final-Project

This project was done as the final project in Crash Course Python from Google IT Automation Professional Certificate.

   Crash Course on Python
                    By google	

Final Project Overview
Create a dictionary with words and word frequencies that can be passed to the generate_from_frequencies function of the WordCloud class.
Once you have the dictionary, use this code to generate the word cloud image:
1.	cloud = wordcloud.WordCloud()
2.	cloud.generate_from_frequencies(frequencies)
3.	cloud.to_file("myfile.jpg")

•	List learning and content standards here
•	List learning and content standards here
•	List learning and content standards here
Objectives:
•	to create a script that would go through the text and count how many times each word appears
•	prepare a dictionary and use that as a parameter for the word cloud module

Requirements/Task(s):
•	Before processing any text, you need to remove all the punctuation marks. To do this, you can go through each line of text, character-by-character, using the isalpha() method. This will check whether or not the character is a letter.
•	To split a line of text into words, you can use the split() method.
•	Before storing words in the frequency dictionary, check if they’re part of the "uninteresting" set of words (for example: "a", "the", "to", "if"). Make this set a parameter to your function so that you can change it if necessary.

Record your notes/research here:
- punctuation marks, before counting the frequency of the words
- find a way to exclude irrelevant or uninteresting words when processing the text

Outline the steps/plan for your project:
Step-By-Step approach
Understand the problem statement, research available options, 
plan your approach, write your code and finally execute.

Summarize what you learned:
•	Used Conditionals, Loops, Strings, Lists, and even Dictionaries.
•	Created Objects
•	Put it all together to write your very own program, 
•	Applying a process which you might use in your day-to-day IT role

Add the link to your project here:
https://www.coursera.org/learn/python-crash-course/programming/Z5d28/programming-final-project-wordcloud/submission
Link to certificate :
https://www.coursera.org/account/accomplishments/records/M2RGTG3643XH




Output:
 ![image](https://user-images.githubusercontent.com/86213550/126282174-a7e79a83-d9da-4077-8d2e-bc401bccff9e.png)

If your word cloud image did not appear, go back and rework your calculate_frequencies function until you get the desired output. Definitely check that you passed your frequecy count dictionary into the generate_from_frequencies function of wordcloud. Once you have correctly displayed your word cloud image, you are all done with this project. Nice work!
