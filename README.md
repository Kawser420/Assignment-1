# Interview Questions - Blog Task:

1.What are some differences between interfaces and types in TypeScript?

# Blog-01:

1. interface and type looks like similar. interface can use for declaration merging, extends and implement perfectly and
   other side, type can not do it. type can do it Unions and tuples very well and interface can do it. interface readability very well and type readability type is good. this two topic summary look like same but some deferent.

# Blog-02:

2.What is the use of the keyof keyword in TypeScript? Provide an example.

2. Blog Article: firstly understanding type of typescript and typescript keyof type.
   keyof role in making my code more type safe and expressive. it is solid type key of typescript.
   here is some example:
   interface User {
   id: number;
   name: string;
   isProgrammer: boolean;
   }
   type UserKeys = keyof User;
   and summary of keyof: make typescript building dynamic forms and it means type is 100 percent solid and valid.
   and it works safeguarding APIs object keys and values.
   and valid prop names.

# Blog-03:

3.Explain the difference between any, unknown, and never types in TypeScript.
3.Answer: there are difference difference type understanding. the any type accepts any value and can not safely use and can not requires type checking and disable type checking.
and the unknown accepts any value and can be safely used and requires type. it is flexible , and safe use.
and he never can not value , can not require type and can be safely used.
the summary of there difference, any might seem convenient and bugs and confusion.
and unknown safety and never more predictable and error free logic. and the perfect
language.
