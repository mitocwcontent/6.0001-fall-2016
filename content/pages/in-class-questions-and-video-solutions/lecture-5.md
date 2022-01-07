---
content_type: page
parent_title: In-Class Questions and Video Solutions
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 5
uid: 2d1ecaea-f49e-8ee7-cac3-ea3ce9cbe081
---

1.  ### Tuples
    
      
    
    Examine the code below. What does `always_sunny(('cloudy'), ('cold',))` evaluate to?
    
    ```
    def always_sunny(t1, t2):
    ```
    
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;('sunny', 'cc')&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;('sunny', 'ccold')&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;('sunny', 'cloudycold')&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource c9f180f7-568d-fdb9-55f6-4ae1ae784390 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  ### Simple Lists
    
      
    
    What is the value of L after you run the code below?
    
    ```
    L = ["life", "answer", 42, 0]
    ```
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\["life", "answer", 42, 0\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\["universe", "answer", 42, 0\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\["universe", "everything", 42, 0\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\["life", "everything", 42, 0\]&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource a656e4e2-eac1-6346-167e-90f6ff1be1b8 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
5.  ### List Operations
    
      
    
    What is the value of L3 after you execute all the operations in the code below?
    
    ```
    L1 = ['re']
    ```
    
    {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\['mi', 're', \['fa', 'la'\]\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\['mi', 're', 'fa', 'la'\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\['re', 'mi', \['fa', 'la'\]\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\['do', 'mi', \['fa', 'la'\]\]&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 5b5ce068-2c40-8fcd-e630-aee685a1b530 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
6.  ### List Aliasing/Mutation
    
      
    
    What is the value of brunch after you execute all the operations in the code below?
    
    ```
    L1 = ["bacon", "eggs"]
    ```
    
    {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\['bacon', 'eggs', 'toast', 'jam'\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\['bacon', 'eggs', 'juice', 'toast', 'jam'\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\['bacon', 'eggs', 'juice', \['toast', 'jam'\]\]&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\['bacon', 'eggs', \['toast', 'jam'\]\]&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 22a6fadb-e4f1-343a-e332-e2313ecf66fe >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}