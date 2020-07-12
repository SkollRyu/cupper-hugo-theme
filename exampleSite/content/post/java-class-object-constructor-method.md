+++
date = 2020-07-12T21:00:00Z
draft = true
tags = ["Java"]
title = "Java - Class&Object&Constructor&Method"

+++
## 1. Class&Object

### 1.1 Scope of variables

* **Local variables** − _Variables defined **inside methods, constructors or blocks**_ are called local variables. The variable will be _declared and initialized within the method and the variable will be **destroyed when the method has completed**_.
* **Instance variables** − Instance variables are variables **_within a class but outside any method_**. These variables are initialized when the class is instantiated. Instance variables can be **_accessed from inside any method, constructor or blocks of that particular class_**.
* **Class(Static) variables** − Class variables are variables declared within a class, outside any method, **_with the static keyword_**.

       html
      
      public class VariableExample{
      
        int myVariable; // instance var
        static int data = 30; // static var
        
         public static void main(String args[]){
            VariableExample obj = new VariableExample();
      
            System.out.println("Value of instance variable: "+obj.myVariable);
            System.out.println("Value of static variable: "+VariableExample.data);
         }

  }

x