# SimpleProgram
package testClass;

public class Animal {
    Animal(){

        System.out.println("4 legs");
    }
    Animal(int a){
        this();
        System.out.println("two eyes");
    }
}

class Dog extends Animal{
    Dog(){
        this("nik");
        System.out.println("Labra");
    }

    Dog(String s){
        super(3);
        System.out.println("Brown");
    }

    public static void main(String[] args) {
        Dog obj=new Dog("s");
    }
}
