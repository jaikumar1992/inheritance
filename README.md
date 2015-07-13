# inheritance
inheritance sample program


public class Animal{
}

class Mammal extends Animal{
}

class Reptile extends Animal{
}

class Dog extends Mammal{

public static void main(String args[]){

      Animal a = new Animal();
      Mammal m = new Mammal();
      Dog d = new Dog();
      Animal a1 = new Reptile();

      System.out.println(m instanceof Animal);
      System.out.println(d instanceof Mammal);
      System.out.println(d instanceof Animal);
      System.out.println(a instanceof Reptile);
      System.out.println(a1 instanceof Reptile);
   }
}
