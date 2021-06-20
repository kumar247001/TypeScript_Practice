# TypeScript_Practice

TypeScript is a free and open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing and class-based object-oriented programming to the language.

TypeScript has following benefits.

1.It helps in code structuring.
2.Use class based object oriented programming.
3.Impose coding guidelines.
4.Offers type checking.
5.Compile time error checking.
6.Intellisense.

# Built-in data types - Primitives

## Number

it is used to represent number type values and represents double precision floating point values.

`let age:Number = 35;`

## String

it represents a sequence of characters stored as Unicode UTF-16 code. It is the same as JavaScript primitive type.

`let userName:string = "Kumar Gaurav";`

## Boolean

in Typescript, it is used to represent a logical value. When we use the Boolean type, we get output only in true or false. It is also the same as JavaScript primitive type.

`let isValid:boolean = true;`

# Type Inference

If we declare a variable and assign a value.TypeScript infers its type. like:

`let a = 10;`

Now a can have only Numbers. this is called inference.

If we firstly declare a variable without assignment. It becomes :any and we can assign any value like:

`let b;`
`b = 10;`
`b = "text";`
`b = true;`

Above lines don't give any error.
