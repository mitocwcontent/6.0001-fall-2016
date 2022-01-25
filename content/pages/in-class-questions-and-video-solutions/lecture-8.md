---
content_type: page
parent_title: In-Class Questions and Video Solutions
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 8
uid: ffd17f7b-b232-3aab-9bf4-1b8697c77ccd
---

1.  ### Class Definition
    
      
    
    Which of the following is a good and valid definition for a class representing a car?
    
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;`def class Car(object):`&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;`class Car(object):`&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;`def Car(object):`&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;`class A(object)`&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 60c82174-3d50-865a-1e3a-3835d4ffc1f1 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  ### Class Instance
    
      
    
    Using the class definition below, which line creates a new Car object with 4 wheels and 2 doors?
    
    ```
    class Car(object):
    ```
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;`Car(mycar, 4, 2)`&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;`mycar = Car(4, 2, "white")`&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;`mycar = Car(4, 2)`&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;`mycar = Car(2, 4)`&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 34ab63b8-2a9d-3db4-12f7-efbf3523f7f2 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
5.  ### Methods
    
      
    
    Which of the following methods changes the color of the car, based on the definition below?
    
    ```
    class Car(object):
    ```
    
    {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; ```
     def paint(c):
    ``` &nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;```
    def paint(self, c):
    ``` &nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;```
    def paint(c):
    ``` &nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;```
    def paint(self, c):
    ``` &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource b93ae723-a689-f41a-9536-414ea54960e7 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
7.  ### Method Call
    
      
    
    You create a car with `mycar = Car(4, 2)`. Which is a line of code to change the color of mycar to "red"?
    
    ```
    class Car(object):
    ```
    
    {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;Car.paint("red")&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;mycar.paint(red)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;mycar.paint("red")&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;mycar.paint(Car, "red")&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 3081a61e-871f-bb60-35b4-014be75c3392 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
9.  ### Special Methods
    
      
    
    With the code below, what does the line `print(mycar == yourcar)` print?
    
    ```
    class Car(object):
    ```
    
    {{< quiz_multiple_choice questionId="Q5_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;True&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;False&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;An error&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource a51a0e44-3261-1cef-4e80-e8543993142c >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}