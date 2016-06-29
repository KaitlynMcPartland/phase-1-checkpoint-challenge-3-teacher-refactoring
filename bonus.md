# Super Crazy Bonus Release

Edit this file to answer the following questions. Give examples. You may need to do a bit of research. :)

1. Why is Hash.fetch useful?
  Hash.fetch is useful because it ensures that the given key is in the hash and it also allows you to set a default value if the value is missing.

2. What is the disadvantage of single inheritance, and what's a possible solution to that problem?
  The disadvantage of single inheritance is that there may be more then 1 class the the sub class can belong to, it might want the properties of two super classes. A possible solution to this problem is adding modules.

3. Why are these classes initialized with an options hash?
  Initializing the classes with an options hash eliminates argument order dependency, that made it easier to utilize sub and super classes for the initialization arguments which in turn make the code easier to update and maintain.

4. What is the purpose of the private keyword in a class? What does it protect you from and why is that valuable?
Private means that everything below it is not accessible outside of the class. This is good because it means that anything outside of the class that has no business changing a classes method can't change it, or access it. You wouldn't want it to be possible for someone to change a method that verifies secure information.


5. Why are concepts like encapsulation, single responsibility, and abstraction important? Now that you've been programming for a while, have you seen any advantages for yourself, or can you imagine them in the future?
All three of those things make code maintenance much easier. When you need to change something these things make knowing where the issue or thing you want to update is and then you dont need to change it in multiple places.
