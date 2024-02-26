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




###8)
- To get rid of conceptual errors in which a very broad method could not complile due to different types.

### 9)
- Erasure changes all the type parameters in a generic class to ones related to the object at hand.
- The code changes all the type parameters into strings!

### 10)

