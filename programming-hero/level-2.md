# Programming Hero Level 2 Web Development

- day 1 (`Mon 1 May 2023`)

  ```note
  1. TypeScript (https://www.typescriptlang.org)
  2. NVM
  3. https://www.npmjs.com/package/ts-node-dev
  ```

  ```ts
  // What is the output of the following code?

  function generateAdder(a: number): (b: number) => number {
    return function(b: number) {
      return a + b;
    };
  }

  function generateAdder2(a:number) {
      return function (b:number) {
          return a + b;
      };
  }

  const addTwo = generateAdder(2);
  console.log(addTwo(3));
  console.log(addTwo(5));
  ```

---
