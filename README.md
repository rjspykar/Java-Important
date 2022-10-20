# Java-Important
All information regarding JAVA

1. Can main() method be overloaded and overridden ?
  Ans: Yes, main method can be overloaded.
  Eg. We can have 
  public static void main(int ch){
    sysout("Int main() executing");
  }

  public static void main(char ch){
    sysout("char main() executing");
  }

  public static void main(String[] args){
    sysout("Main main() executing");
  }
  Here, on program execution it will only print "Main main() executing". 
  No matter what arguments are there.

  Whereas main method cannot be overridden. 
  Since it is static method, 
  and static methods cannot be overridden 
  coz static methods belong to class 
  and one class cannot have same method defined twice.

2. Functional Interface
  Ans: 



