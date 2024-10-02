
# Dart Notes

## Switch Expressions

```dart
final temp = 20;
  
final status = switch (temp) {
  <10 => 'Lower',
  >= 10 && < 20 => 'Medium',
  >=20 => 'Power',
  _ => 'Not defined'
};

print(status); ```
## Positional Optional Parameters

### Example Functions

````dart
add(int x, int y) => x + y;

remove(int x, [int y = 0]) => x * y;

sign([int x = 20, int y = 100]) => x + 2 * y; `````

### Example Calls

````dart
sign();         // returns 220
sign(12);       // returns 212
sign(12, 30);   // returns 72

remove(3);      // returns 0
remove(3, 2);   // returns 6

````

## Named Optional Parameters

### Example Functions
```` dart
calculateArea({double width = 0.0, double height = 0.0}) => width * height;

calculate({required double width, required double height}) => width * height;

````
### Example Calls

````dart
calculateArea(150.0);                 // Error: Must specify named parameters
calculateArea(width: 150.0);           // OK
calculateArea(129.9, 190.9);           // Error
calculateArea(width: 129.9, height: 8929.2);  // OK

calculate();                           // Error: Missing required parameters
calculate(width: 12, height: 39);      // OK

````
## Lambda Functions

````dart
void something() => print("something");

Function f = something;

Function f1 = () {
  print("do something");
};

````
## Class Object and Constructor
````dart
void main() {
  Student s1 = Student('John', 2367367, 'CSE');
  print('${s1.name} ${s1.id} ${s1.departement}');
}

class Student {
  String name;
  int id;
  String departement;

  Student(this.name, this.id, this.departement);
}

````

## Named Constructor
````dart
class Student {
  String? name;
  int? id;
  String? departement;
  String? email;

  Student(this.name, this.id, this.departement);
  Student.concat(this.email);
}

````
## Inheritance in Dart
````dart
class Car {
  String name;
  Car(this.name);

  void drive() => print("Driving a car");
}

class ElectricCar extends Car {
  double capacity;

  ElectricCar(this.capacity, String name) : super(name);

  @override
  void drive() => print("Driving with an Electric car");
}

````
## Mixin in Dart
````dart
mixin Multimedia {
  void playAudio() => print("playing audio");
}

class ElectricCar extends Car with Multimedia {
  double capacity;

  ElectricCar(this.capacity, String name) : super(name);

  @override
  void drive() => print("Driving with an Electric car");
}

````

## Final and Static Components

### Final Class Example
````dart
final class Animal {}

// Error: Cannot extend a final class
class Cat extends Animal {} 

// Correct: Base class allows inheritance
base class Cat extends Animal {}

````