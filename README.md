# Java Guides
Java syntax and useful information

## Simple program

Create file `Hello.java`:

```java
public class Hello {
  public static void main(String[] args) {
    System.out.println("Java was born in 1995");

    // Sun Microsystems announced the release of Java in 1995
    
    System.out.println("You were created by James Gosling");
    
		/* James Gosling is a Canadian engineer who 
		created Java while working at Sun Microsystems.
    */
  }
} 
```

Compile this file:

```bash
javac Hello.java
```

File `Hello.class` will be created. It contains Java bytecode, ready to be executed by the Java Virtual Machine.

Run compiled file:

```bash
java Hello
```
