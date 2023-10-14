# Activity 1 Notes

# Introducing How Computers Work

## What makes a computer, a computer?

A *thinking machine* or a computer must be able to perform 4 tasks:

1. Input information
2. Store said information
3. Process stored information
4. Output processed information

The earliest computers are made of wood and metal, with levers and gears. However, they started using electrical components.

Early computers were also very large, able to occupy rooms, but also really slow. They also started as basic calculators.  

No matter the era your computer was in, they still need to perform the 4 basic tasks of a computer.

### Input

Basic forms of input include the mouse, keyboard, microphone, etc., but also include heart-rate monitors, camera, haptics such as touchscreens, and more.

### Storage and Processing

User input is stored in memory, which the processor accesses and manipulates using an *algorithm*, a series of commands, and stores the resulting data in the memory (again). When ready, the information will be outputted.

### Output

Output can differ based on what the computer is designed to do, output include display of text, images, videos, even signals.

Through the internet, a computer’s output might be another one’s input.

## Binary & Data

Computers work using a series of 1s and 0s, but working with them directly is the thing of the past.

**Wires & Circuits** are used to carry information inside a computer.

However, a wire can only *have* electricity, or *no* electricity. a 1 or a 0, true or false, yes or no, on or off.

1 wire is called a **bit**, the smallest piece of information a computer can store. By increasing the number of wires, the information gets more complex.

### Binary Number System

We normally use the decimal number system (10), but computers use binary, composed of only 2 digits, 1 and 0.

| 1 | 0 | 1 | 0 |
| --- | --- | --- | --- |
| 2^3 | 2^2 | 2^1 | 2^0 |

The number above is 10, as there are:

$$

1 \times 2^3 + 0 \times 2^2 + 1 \times 2^1 + 0 \times 2^0

$$

Any number can be represented using the binary system, or in a computer’s case, any number of wires can represent any number.

Using 8 bits, a computer can store 256 values, from 0 - 255. This is called a byte.

4 bytes or 32 bits can store 4 billion numbers.

However, it only seems that a computer can only store numbers. But other types of information like text, images, and sound can also be represented with numbers too. 

### Text

The Latin alphabet, a-z, can be stored using numbers by assigning a number for each letter. For example: a = 1, b = 2, c = 3, and so on.

### Images

Images and video in computers have these small squares called *pixels*. Pixels have color, and these colors can be represented with combinations of values like RGB, HSV, etc.

### Sound

Sound is a series of vibrations, and these vibrations are waves which can be stored in waveform. The graph of a waveform simply consists of numbers, and therefore, sound can be stored as a series of numbers.

The higher the bit of the audio, the higher its quality is, as there are a larger range of numbers.

All these 1s and 0s are how data is represented in computers. It is the backbone of how computers work, how our input is represented, how the data is stored, how its processed, and how its returned to the user.

## Circuits & Logic

Inputs and outputs of computers are information, represented by an on or off, using electrical signals. 

Computers uses circuits, composed of millions of small electrical components.

An example of a simple circuit is:

> A circuit takes a signal (input) and flips it. ON → OFF and vice versa. This is called a **NOT** circuit.
> 

Other more complicated circuits take multiple signals and combine them.

> **AND** circuits take 2 inputs, if either of the inputs is a 0, it will output a 0. An AND circuit can only output a 1 if **both** the inputs are 1.
> 

These are called logic gates. Other examples are NAND, NOT, NOR, OR, XOR. By combining logic gates, the circuit will be able to perform more complicated tasks.

> An **adder** is composed of 2 logic gates, AND and XOR. An adder takes 2 bits and adds them together, and uses to bits as an output. By combining multiple adders, you can now add larger numbers.
> 

Adders are not alone, there also exists circuits for subtraction, multiplication, etc. These tasks might be able to be performed by humans, but the difference in speed is substantial. 

Past computers are large, but modern ones are now smaller, with circuits even microscopic. Smaller computers are faster simply because by decreasing the distance the electrical signal will travel, the faster it can get to its destination. Modern circuits can perform billions of calculations per second because electricity travels close to the speed of light. 

Any task you can do with technology need lots of information that needs to be processed quickly, and circuits are the solution to that. No matter how large a task is, all you need are small circuits. 

## CPU, Memory, Input & Output

These are the 4 basic tasks of a computer. 

1. Input devices convert physical information to binary information
2. Memory stores this information
3. The CPU or Central Processing Unit calculates information
4. Output devices convert binary information to physical information

> Example: 

The keyboard converts the pressed key into binary data, The CPU calculates how to display the key, by requesting steps from the memory, and stores the resulting information into the memory. This information is sent to the display or screen, the output device.
> 

This may seem instant, but a computer runs thousands of instructions just to complete these series of steps. 

Most modern computers run fairly complicated tasks, and some of those need multiples CPUs and large amounts of memory. 

## Hardware & Software

Hardware is the things inside the computer: circuits, chips, wires, speakers, plugs, etc. But there are things that can’t be seen called software. 

The CPU controls all the other parts of the computer, the *master chip*. The CPU has multiple smaller circuits inside, and the CPU knows what to use and when to use these circuits. 

Commands are used to instruct the CPU what circuit to use. For example, and add command instructs the CPU to use its adder. 

Commands are stored in memory, and the CPU gets and executes these commands in a sequence. 

Binary code is the simplest form of software and controls all hardware. However, writing in binary code is not done today, as we have programming languages that are more human-friendly to write in.

**Software** tells the CPU what to do. 

An **operating system** is the master program that manages how software uses the hardware of the computer.  

By having multiple programs open at once, the CPU does not run all those programs simultaneously, it is the operating system that manages software which quickly switch programs, therefore sharing the CPU for fractions of a second over and over again.