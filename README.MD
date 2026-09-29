Задание 2.3

C:\Users\Администратор\Desktop\ts-practice-1_Ivan>npx tsc
src/index.ts:12:1 - error TS2322: Type 'number' is not assignable to type 'string'.

12 title = 123;
   ~~~~~

src/index.ts:16:1 - error TS2322: Type 'string' is not assignable to type 'number'.

16 pages = "много";
   ~~~~~

src/index.ts:20:1 - error TS2322: Type 'number' is not assignable to type 'boolean'.

20 isRead = 1;
   ~~~~~~


Found 3 errors in the same file, starting at: src/index.ts:12



Задвние 2.4

C:\Users\Администратор\Desktop\ts-practice-1_Ivan>npx tsc
src/index.ts:31:5 - error TS2322: Type 'null' is not assignable to type 'string'.

31 let userName: string = null;
       ~~~~~~~~


Found 1 error in src/index.ts:31



Задание 3.2

C:\Users\Администратор\Desktop\ts-practice-1_Ivan>npx tsc           
src/index.ts:72:13 - error TS2345: Argument of type 'string' is not assignable to parameter of type 'number'.

72 formatPrice("100");
               ~~~~~

src/index.ts:73:1 - error TS2554: Expected 3 arguments, but got 2.

73 clamp(5, 0);
   ~~~~~

  src/index.ts:45:44 - An argument for 'max' was not provided.
    45 function clamp(value: number, min: number, max: number): number {
                                                  ~~~~~~~~~~~

src/index.ts:74:12 - error TS2345: Argument of type 'number' is not assignable to parameter of type 'string'.

74 logMessage(123);
              ~~~


Found 3 errors in the same file, starting at: src/index.ts:72