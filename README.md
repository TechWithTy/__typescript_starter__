# __typescript_starter__
starter repo for typescript 

TypeScript Cheat Sheet
Basic Types
typescript
Copy code
let name: string = 'Ty';
let age: number = 25;
let isDeveloper: boolean = true;
Arrays
typescript
Copy code
let numbers: number[] = [1, 2, 3, 4, 5];
let names: Array<string> = ['Ty', 'Dave', 'John'];
Functions
typescript
Copy code
function greet(name: string): void {
  console.log(`Hello, ${name}!`);
}

const add = (x: number, y: number): number => x + y;
Interfaces
typescript
Copy code
interface Person {
  name: string;
  age: number;
  isDeveloper: boolean;
}

let ty: Person = {
  name: 'Ty',
  age: 25,
  isDeveloper: true,
};
Classes
typescript
Copy code
class Car {
  brand: string;
  model: string;
  year: number;

  constructor(brand: string, model: string, year: number) {
    this.brand = brand;
    this.model = model;
    this.year = year;
  }

  getInfo(): string {
    return `This is a ${this.brand} ${this.model} from ${this.year}.`;
  }
}

let myCar: Car = new Car('Toyota', 'Corolla', 2021);
console.log(myCar.getInfo()); // This is a Toyota Corolla from 2021.
Type Aliases
typescript
Copy code
type RGB = [number, number, number];

let red: RGB = [255, 0, 0];
let green: RGB = [0, 255, 0];
let blue: RGB = [0, 0, 255];
Generics
typescript
Copy code
function identity<T>(arg: T): T {
  return arg;
}

let myNumber: number = identity(10);
let myString: string = identity('Hello');
Enums
typescript
Copy code
enum Color {
  Red,
  Green,
  Blue,
}

let myColor: Color = Color.Green;
console.log(myColor); // 1
Type Assertions
typescript
Copy code
let someValue: any = 'Hello, world!';
let strLength: number = (<string>someValue).length;
Optional Chaining
typescript
Copy code
let person = {
  name: 'Ty',
  age: 25,
};

let city = person?.address?.city;
console.log(city); // undefined
