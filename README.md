print("==============PYTHON TUTORIAL==============")
print(" =================WELCOME================= ")
print("")
input("Full Name:")
print("")
choice = input("Are You Ready?:")
if choice == "yes":
   print("Ediwow, Sana all T - T")
else:
   print("Di pwede")
         
while True:

    print("")
    print("============================================")
    print(" >>>>>>>>>>>>>>>>>>>START<<<<<<<<<<<<<<<<<< ")
    print("============================================")
    print("===============LESSON CHOICES===============")
    print("")
    # PRELIM
    print("1. INTRODUCTION TO PROGRAMMING")
    print("2. PYTHON BASIC SYNTAX")
    print("3. ARITHMETIC OPERATORS AND EXPRESSION")
    print("4. BASIC INPUT AND OUTPUT IN PYTHON")
    # MIDTERM
    print("5. CONDITIONAL STATEMENTS IN PYTHON")
    print("6. LOGICAL OPERATORS")
    # FINALS
    print("7. INTRODUCTION TO ITERATION AND LOOPS")
    print("8. EXIT")

    choice = int(input("Choose a lesson (0-8): "))

    # EXIT
    if choice == 0 or choice == 8:
        print("THANK YOU FOR USING PYTHON TUTORIAL!")
        break

    # CHOICES
    elif choice == 1:
        print("========INTRODUCTION TO PROGRAMMING========")
        print(""" Python is a high-level, interpreted, and general-purpose programming language created by
    Dutch software engineer Guido van Rossum in 1991.
    It is simple, readable, and easy to learn, making it beginner-friendly because its syntax looks almost like English. 
    Python is widely used in artificial intelligence, web development, automation, and game development, 
    and it has a large community that provides tutorials, support, and libraries.""")

        print("")
        print("==========Exercise Question==========")

        score = 0

        # QUESTION 1
        print("\n1. Who created Python?")
        print("A. Bill Gates")
        print("B. Guido van Rossum")
        print("C. Mark Zuckerberg")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 2
        print("\n2. In what year was Python created?")
        print("A. 1991 ")
        print("B. 2000 ")
        print("C. 2010 ")

        answer = input("Your answer: ")

        if answer.lower() == "a":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is A.")

        # QUESTION 3
        print("\n3. Where is Python commonly used?")
        print("A. Cooking ")
        print("B. Painting ")
        print("C. Artificial Intelligence ")

        answer = input("Your answer: ")

        if answer.lower() == "c":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is C.")

        # TOTAL SCORE
        print("\n===== QUIZ RESULT =====")
        print("Your Total Score:", score, "/ 3")

        if score == 3:
            print("Excellent! Perfect Score!")
        elif score == 2:
            print("Good Job! Keep Learning!")
        elif score == 1:
            print("Nice Try! Keep Practicing!")
        else:
            print("Don't Give Up! Try Again!")

    elif choice == 2:
        print("========PYTHON BASIC SYNTAX========")
        print(""" Python uses variables to store data, such as names, numbers, and other values. 
        For example, student_name is a variable that can store a student's name. 
        We can assign values to variables using the equal sign (=). 
        When creating variables, we must follow naming rules, such as using letters, numbers, and underscores, and avoiding spaces or starting with a number.
        Python also uses the print() statement to display information on the screen, while comments are used to explain the code and are ignored by Python. 
        These basic concepts help us understand Python and create simple programs more easily. """)

        print("")
        print("==========Exercise Question==========")

        score = 0

        # QUESTION 1
        print("\n1. What is the purpose of print() function in python?")
        print("A. To store data ")
        print("B. To display information on the screen ")
        print("C. To create comments ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 2
        print("\n2. Which of the following is a correct variable name?")
        print("A. 123name ")
        print("B. student_name ")
        print("C. name123 ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 3
        print("\n3. What is the assignment operator in python?")
        print("A. = ")
        print("B. # ")
        print("C. () ")

        answer = input("Your answer: ")

        if answer.lower() == "a":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is A.")

        # TOTAL SCORE
        print("\n===== QUIZ RESULT =====")
        print("Your Total Score:", score, "/ 3")

        if score == 3:
            print("Excellent! Perfect Score!")
        elif score == 2:
            print("Good Job! Keep Learning!")
        elif score == 1:
            print("Nice Try! Keep Practicing!")
        else:
            print("Don't Give Up! Try Again!")
            
    elif choice == 3:
        print("========ARITHMETIC OPERATORS AND EXPRESSION========")
        print(""" Arithmetic operators are symbols used to perform mathematical calculations on numbers in Python.
        These include addition (+), subtraction (-), multiplication (*), division (/), floor division (//), modulus (%), and exponentiation (**). 
        Expressions are combinations of values, variables, and operators that produce a result.
        Python follows the order of operations called PEMDAS, which means parentheses, exponents, multiplication, division, addition, and subtraction. 
        Variables can be used in expressions to calculate values, such as adding two numbers or finding the average of grades. 
        These operators and expressions help us solve mathematical problems and perform calculations using Python.""")

        print("")
        print("==========Exercise Question==========")

        score = 0

        # QUESTION 1
        print("\n1. Which operator is used to get the remainder of a division?")
        print("A. // ")
        print("B. % ")
        print("C. ** ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 2
        print("""\n2. What is the output of this Python code?
        
              a=2
              b=3
              c=4
                                                   
              print(a + b * c) """)
              
        print("A. 20 ")
        print("B. 14 ")
        print("C. 24 ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 3
        print("\n3. What is the average of 90, 85, and 88?")
        print("A. 87.67 ")
        print("B. 90 ")
        print("C. 85 ")

        answer = input("Your answer: ")

        if answer.lower() == "a":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is A.")

        # TOTAL SCORE
        print("\n===== QUIZ RESULT =====")
        print("Your Total Score:", score, "/ 3")

        if score == 3:
            print("Excellent! Perfect Score!")
        elif score == 2:
            print("Good Job! Keep Learning!")
        elif score == 1:
            print("Nice Try! Keep Practicing!")
        else:
            print("Don't Give Up! Try Again!")
            
    elif choice == 4:
        print("========BASIC INPUT AND OUTPUT IN PYTHON========")
        print(""" In Python, the input() function is used to get information from the user.
        It allows the program to ask questions, such as a person's name or age, and store their answers in variables.
        The input is a string by default, so int() is used to convert it into a whole number, while float() is used for decimal numbers.
        Boolean values can also be created using conditions, which result in either True or False.
        We can use commas in print() to display different values together, making the output easier to read.
        These functions help us create interactive programs, such as a simple student information or grade calculator. """)

        print("")
        print("==========Exercise Question==========")

        score = 0

        # QUESTION 1
        print("\n1. What function is used to get input from the user in Python?")
        print("A. print() ")
        print("B. input() ")
        print("C. float() ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 2
        print("\n2. What function is used to convert input into a decimal number?")
        print("A. int() ")
        print("B. str() ")
        print("C. float() ")

        answer = input("Your answer: ")

        if answer.lower() == "c":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is C.")

        # QUESTION 3
        print("\n3. What are the two possible Boolean values in Python?")
        print("A. True and False ")
        print("B. Yes and No ")
        print("C. 1 and 2 ")

        answer = input("Your answer: ")

        if answer.lower() == "a":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is A.")

        # TOTAL SCORE
        print("\n===== QUIZ RESULT =====")
        print("Your Total Score:", score, "/ 3")

        if score == 3:
            print("Excellent! Perfect Score!")
        elif score == 2:
            print("Good Job! Keep Learning!")
        elif score == 1:
            print("Nice Try! Keep Practicing!")
        else:
            print("Don't Give Up! Try Again!")
            
    elif choice == 5:
        print("========CONDITIOAL STATEMENTS IN PYTHON========")
        print(""" Conditional statements in Python allow programs to make decisions based on whether conditions evaluate to True or False 
        using relational operators such as ==, !=, >, <, >=, and <=. An if statement runs an indented block only when its condition is True, while an if-else statement adds an alternative block 
        that executes when the condition is False. When multiple options exist, an if-elif-else structure checks conditions from top to bottom and runs only the first block that is True,
        skipping the rest. Programmers can also use nested conditions to place one conditional statement inside another so the inner condition is checked only if the outer condition is True. 
        These structures power practical programs like age classifiers and store checkout systems that compute subtotals, discounts, taxes, and change.
        Writing reliable conditional code requires proper indentation, logical condition ordering, and input validation to avoid errors. """)

        print("")
        print("==========Exercise Question==========")

        score = 0

        # QUESTION 1
        print("\n1. In an if-elif-else structure, what happens once Python finds a condition that is True?")
        print("A. It runs that block and skips the remaining blocks. ")
        print("B. It runs all remaining blocks regardless of their conditions. ")
        print("C. It immediately jumps to the else block after finishing. ")

        answer = input("Your answer: ")

        if answer.lower() == "a":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is A.")

        # QUESTION 2
        print("\n2. When is the inner condition checked in a nested condition?")
        print("A. Only if the outer condition is True. ")
        print("B. Only if the outer condition is False. ")
        print("C. Before the outer condition is evaluated. ")

        answer = input("Your answer: ")

        if answer.lower() == "a":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is A.")

        # QUESTION 3
        print("\n3. Which practice is mentioned for writing reliable conditional code?")
        print("A. Skipping input validation to keep code shorter. ")
        print("B. Using proper indentation and logical condition ordering. ")
        print("C. Checking conditions from bottom to top only. ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # TOTAL SCORE
        print("\n===== QUIZ RESULT =====")
        print("Your Total Score:", score, "/ 3")

        if score == 3:
            print("Excellent! Perfect Score!")
        elif score == 2:
            print("Good Job! Keep Learning!")
        elif score == 1:
            print("Nice Try! Keep Practicing!")
        else:
            print("Don't Give Up! Try Again!")
            
    elif choice == 6:
        print("========LOGICAL OPERATORS========")
        print(""" Logical operators in Python are used to combine or reverse conditions in statements like if, elif, and else. 
        The and operator returns True only when all conditions are True, and False otherwise.
        The or operator returns True when at least one condition is True, only returning False if all conditions are False. 
        Meanwhile, the not operator reverses a condition's result, turning True into False and False into True. 
        These operators let Python evaluate multiple rules at once, such as checking age limits with a valid ID, weekend days, or whether it is not raining.
        Understanding how and, or, and not behave helps programmers write clear decision-making logic across their code. """)

        print("")
        print("==========Exercise Question==========")

        score = 0

        # QUESTION 1
        print("\n1. When does the and operator return True?")
        print("A. When at least one condition is True. ")
        print("B. Only when all conditions are True. ")
        print("C. Whenever it reverses a False result. ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 2
        print("\n2. What does the or operator return when both conditions are False?")
        print("A. True ")
        print("B. False ")
        print("C. It reverses the result. ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 3
        print("\n3. What does the not operator do to a condition's result?")
        print("A. It requires both conditions to be True. ")
        print("B. It checks if at least one condition is True. ")
        print("C. It reverses the result, turning True into False and False into True. ")

        answer = input("Your answer: ")

        if answer.lower() == "c":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is C.")

        # TOTAL SCORE
        print("\n===== QUIZ RESULT =====")
        print("Your Total Score:", score, "/ 3")

        if score == 3:
            print("Excellent! Perfect Score!")
        elif score == 2:
            print("Good Job! Keep Learning!")
        elif score == 1:
            print("Nice Try! Keep Practicing!")
        else:
            print("Don't Give Up! Try Again!")
            
    elif choice == 7:
        print("========INTRODUCTION TO ITERATION AND LOOPS========")
        print(""" Iteration in Python repeats a set of instructions so programmers can perform tasks multiple times without writing repetitive code.
        A for loop repeats instructions for each item in a sequence—such as a range() with start, stop, and step values—and is ideal when the number of repetitions is known. 
        A while loop repeats instructions as long as a condition remains True, making it useful when repetition depends on a condition that updates each iteration. 
        Both loop types can count upward or downward and require a colon after the loop header along with properly indented loop body statements. 
        Using loops makes programs shorter, cleaner, and much easier to modify when changing how many times a task runs. """)

        print("")
        print("==========Exercise Question==========")

        score = 0

        # QUESTION 1
        print("\n1. When is a for loop especially useful in Python?")
        print("A. When the number of repetitions is known. ")
        print("B. Only when counting downward from 5 to 1. ")
        print("C. Whenever a program has no indented statements. ")

        answer = input("Your answer: ")

        if answer.lower() == "a":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is A.")

        # QUESTION 2
        print("\n2. How does a while loop decide whether to keep repeating?")
        print("A. It always runs a fixed number of times regardless of conditions. ")
        print("B. It repeats instructions while a condition remains True. ")
        print("C. It skips the loop header and runs without a colon. ")

        answer = input("Your answer: ")

        if answer.lower() == "b":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is B.")

        # QUESTION 3
        print("\n3. What benefit does using a loop provide over repeating instructions manually?")
        print("A. It prevents the program from ever stopping. ")
        print("B. It removes the need to indent code blocks. ")
        print("C. It makes the program shorter and easier to modify. ")

        answer = input("Your answer: ")

        if answer.lower() == "c":
            print("Correct!")
            score = score + 1
        else:
            print("Wrong! The correct answer is C.")

        # TOTAL SCORE
        print("\n===== QUIZ RESULT =====")
        print("Your Total Score:", score, "/ 3")

        if score == 3:
            print("Excellent! Perfect Score!")
        elif score == 2:
            print("Good Job! Keep Learning!")
        elif score == 1:
            print("Nice Try! Keep Practicing!")
        else:
            print("Don't Give Up! Try Again!")
            
            # PROCEED OPTION
    if choice >= 1 and choice <= 7:
        print("")
        print("============================================")
        proceed = input("Do you want to proceed to another lesson? (yes/no): ")

        if proceed.lower() == "no":
            print("")
            print("THANK YOU FOR USING PYTHON TUTORIAL!")
            break
        elif proceed.lower() == "yes":
            print("")
            print("Returning to lesson choices")
