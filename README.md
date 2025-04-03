# BCPU-MCPU-HCPU

Explanations about the 3 processors and releases

## BCPU (Basic Central Processing Unit):

- **The BCPU is the simplest processor in this line, designed primarily for educational purposes, testing, and as a foundational example of processor architecture. It typically has a 4-bit architecture and a low clock frequency. The objective of the BCPU is to demonstrate basic processing concepts and execute simple operations, such as the Fibonacci sequence.**
- **Only the BCPU has fixed instructions, which are predefined by the opcode itself, rather than being dynamically selected through buses. Instead of general-purpose instructions like `MOV [ADDR] TO [ADDR]`, the BCPU uses predefined instructions such as `MOV R1 TO R2`, each represented by a specific opcode.**

## MCPU (Medium Central Processing Unit):

- **The MCPU is designed to be a more focused processor compared to the BCPU. With its 8-bit architecture and reasonable clock frequency, the MCPU is capable of handling user input and interacting with graphical output. Its objective is to allow more dynamic and interactive operations.**
- **Unlike the BCPU, the MCPU introduces dynamic instruction handling, where a single opcode can represent multiple instructions by using buses to select which operation to execute. This allows for much more flexibility in programming and handling complex tasks.**

## HCPU (High Central Processing Unit):

- **The HCPU is the most powerful processor in this line, featuring a 16-bit architecture and a high clock frequency. It is designed to handle complex applications and can be capable of executing simple games such as Snake, Tic Tac Toe, and Pong.**
- **The HCPU uses the same dynamic instruction technology as the MCPU, allowing complex operations and flexibility through the use of buses also.**

---

