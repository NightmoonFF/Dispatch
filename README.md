# Dispatch (Java)
Fetches methods in a class starting with "print", and prompts user about executing them
I used the keyword print, since my intent was to quickly and easily print out
test methods for excersises at school

# How to use:
* Add the files to your project (Like a utility package)
* Make the class that contains the methods implement Dispatchable
   ( ex: public class Assignments implements Dispatchable { } )

* Create a new instance of the class in your main method, and call .dispatch() on it
  ( ex: new Assignments().dispatch(); )

Thats it!
