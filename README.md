class Animal {  
    void sound() {
        System.out.println("Animals make sounds");
    }
}
class Dog extends Animal { 
    void bark() {
        System.out.println("Dog barks");
    }
}
class Puppy extends Dog {
    void play() {
        System.out.println("Puppy plays with a ball");
    }
}
public class Main {
    public static void main(String[] args) {
        Puppy puppy = new Puppy();
        puppy.sound();  // Output: Animals make sounds
        puppy.bark(); // Output: Dog barks
        puppy.play();   // Output: Puppy plays with a ball
    }
}
output

Animals make sounds
Dog barks
Puppy plays with a ball

