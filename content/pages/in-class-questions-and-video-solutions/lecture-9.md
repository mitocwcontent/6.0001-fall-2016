---
content_type: page
parent_title: In-Class Questions and Video Solutions
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 9
uid: d168b144-bfeb-0cd9-daf8-c345966e90d4
---

1.  ### Getters and Setters
    
      
    
    Which of the below is a getter method for the number of wheels?
    
    ```
    ----------------------------------
    ```
    
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;```
    def get_wheels():
    ``` &nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;```
    def get_wheels():
    ``` &nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;```
    def get_wheels(self):
    ``` &nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;```
    def get_wheels(self):
    ``` &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource c4e79feb-d329-f620-2a0b-250ea3c746aa >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  ### Subclass
    
      
    
    Whate line could replace `____blank____` to create a class that inherets from `Animal` in the code below?
    
    ```
    ____blank____
    ```
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;class Dog(Animal):&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;class Animal(Dog):&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;class Dog(object)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
    
  

With this definition of Dog, you run a program with line1, line2, and line3 above. What happens? Refer to the lecture slides for the code making up the "Animal" class.

{{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;Error on (line1) because Dog does not have an \_\_init\_\_&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Uses the \_\_init\_\_ from Animal, but then an error (line2) because Dog does not have a set\_name method.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Uses the \_\_init\_\_ and set\_name from Animal, but then an error (line3) because all methods must return something.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;Runs, creates a Dog object with age=7 and name="Ruffles", and prints "ruff ruff"&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}{{< resource 3132d269-6354-5a69-3b6e-44be988225f9 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}