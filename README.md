## justinpdostal-worksheet-J4

### 1) 
- You may only extend one class, whuch would cause this to fail
- I would make of of the classes an interface since you can implement an infinite amount of interfaces

### 2)
- An abstract class has a constructor while the interface does not.

### 3)
push(int v){
addToBack(v);
}
pop(int v){
rmFromBack();
}
enqueue(int v){
addToBack(v);
}
denqueue(int v){
rmFromFront();
}
peek(){
return list.get(0);
}

### 4) 

public interface Stack<T> {
public void add(T v);
public T pop();
public T peek();
}

public interface Queue<T> {
public void enqueue(T v);
public T dequeue();
public T peek();
}

### 5)
IntegerCalc:

Integer add(Integer a, Integer B){
return a + b;
}

Integer Multiplier(Integer a, Integer b){
return a*b;
}

FloatCalc:
Float add(Float a, Float B){
return a + b;
}

Float Multiplier(Float a, Float b){
return a*b;
}


### 7)
HashMap<String,String. fab four = new HasMap<String,String>

String fullName = fabFour.get("Ringo");


### 8)
- To get rid of conceptual errors in which a very broad method could not complile due to different types.

### 9)
- Erasure changes all the type parameters in a generic class to ones related to the object at hand.
- The code changes all the type parameters into strings! Instead of objects

### 10)
Shelf<String> famCharacters = new Shelf<String>("Shakespeare Characters");
famCharacters.add("Hamlet");
famCharacters.add("Othello");
famCharacters.add("Cordelia");
famCharacters.add("Juliet");

Shelf<Integer> numbers = new Shelf<Integer>("integers");
numbers.add(13);
numbers.add(23);
numbers.add(42);
numbers.add(1729);

famCharacters.printShelf();
numbers.printShelf();

### 11)
- It is in O(n^2) time since it must iterate through all the items in the LinkdedList everytime to find ll.get(i), which is linear, and bad :(. Then it must also
- print out all the different values which also takes n. n * n = n^2

### 12)
- There is a form of pointer that knows where the desired information is in the list making it more effecient as it doesn't have to go through all the items.
- It already knows i's value in ll so it doesn't have to iterate all the way through!

### 13) 
- Since comparable doesn't need or want a constructor as it is just a single method using other objects, it is a interface.
- Also allows a class to extend one class and use the comparable interface in the same system.

### 14) 
 public int compareTo(Car other) {
       int speed1 = this.getTopSpeed();
        int speed2 = other.getTopSpeed();
         if(speed1 < speed2) 
            return -1;
         else if (speed1 > speed2) 
            return 1;
         else 
            return 0;        
    }    


