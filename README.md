public class SLP {
    public static void main(String args[]){
        Dog d=new Dog();
        d.bark();
        d.eat();
    }
}
class Animal{
    void eat(){
        System.out.println("Eating");
    }
}
class Dog extends Animal{
    void bark(){
        System.out.println("Barking");
    }
}
