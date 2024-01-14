# TechneuroInternship_WordCounter_Python
Task 3:
Word Counter

Write a Python script that counts the number of words in a sentence. It's a useful project to start understanding string manipulation in Python

Code Explanation: 

1. The program starts with a print statement, displaying some information about the program and the author:

   print('WORD COUNTER python program by SHRUTI GODSE :-\n')
   This line prints a header for the word counter program.

2. Next, there is a function definition for word_count:

    def word_count(sentence):
       words = sentence.split()
       return len(words)
    
    The word_count function takes a sentence as input, splits it into words using the split method, and returns the count of words in that sentence.

    The program enters a while loop with the condition while True: This creates an infinite loop that will continue until the user decides to exit by entering the word 'exit'.
   
4. Inside the loop, the user is prompted to enter a sentence:

   user_input = input("\nEnter a sentence (or type 'exit' to end):")

5. The program checks if the user entered 'exit' (case-insensitive). If so, it prints a farewell message and breaks out of the loop, effectively ending the program:

   if user_input.lower() == 'exit':
      print("Exiting the word counter. Goodbye!")
      break

6. If the user didn't enter 'exit', the program calls the word_count function with the user's input and prints the result:

   count = word_count(user_input)
   print(f"\nNumber of words in the sentence: {count}")

   This line calculates the word count using the word_count function and displays the result.

   The loop repeats, prompting the user to enter another sentence until the user decides to exit.

So, when you run the program, it continuously prompts the user to input sentences, counts the number of words in each sentence, and display
