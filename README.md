# Vehicle-Transportation

A car carrier, which is a large truck that transports new vehicles, can hold:
- **6 SUVs** per carrier, or
- **8 cars** per carrier.

Each car carrier will transport only SUVs or cars, but not both. A car carrier can only be used if it is full. If there are more SUVs or cars than will fit on the car carrier, they will not be transported.

### Your Task
Write a Java program that:
1. Prompts the user for:
   - The number of SUVs to transport
   - The number of cars to transport
2. Calculates:
   - How many **full car carriers** are needed for SUVs and cars
   - How many SUVs and cars will **not be transported** due to lack of space
3. Prints the results.

---

### Example

If there are 35 SUVs and 40 cars to transport, we would need 5 car carriers for the SUVs and 4 for the cars. The program should output:

9 car carriers will be needed

5 SUVs will not be transported

0 cars will not be transported

---

## Requirements
- Your code should be written in the `Main.java` file.
- The program must use **integer division** and the **modulus operator** to determine the number of leftover vehicles.
- Prompt and output messages should be clear and match the example format.
- Use `Scanner` to read user input.

---

## How to Run
1. Open this project in IntelliJ.
2. Write your code in `src/Main.java`.
3. Run the program and test it with different inputs.
