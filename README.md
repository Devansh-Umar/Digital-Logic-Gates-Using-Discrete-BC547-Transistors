# Digital-Logic-Gates-Using-Discrete-BC547-Transistors

> Designing and implementation of all 7 logic gates using discrete BC547B transistors, with LTspice simulation and physically built-up on breadboard. 
---

## Why I Built This 😂

This project actually started with an exam question.

During my 4th semester in **Microprocessors and Interfacing**, one question kept appearing in different papers -

> **"Design AND, NAND, OR, RAM and ROM using discrete components."**

It appeared in our internal exam, external exam and even in older question paper.

During the internal exam, I made the mistake of representing the gates using their standard symbols instead of actually designing them using discrete components. My teacher caught the mistake and deducted marks.

By the external exam, I understood what the question actually meant and implemented it correctly.

And now as I had a few **BC547 transistors** in my box my greedy mind is saying:

> **If I can design the gates using discrete components on paper, why not actually build them? 😂**

And that's how this project started.

---

## Project Objective

The aim was to understand how basic digital logic can be implemented using **actual transistor switching**, rather than simply using ready-made logic ICs or ideal gate symbols.

The project covers:

- Transistor-level circuit design
- LTspice simulation
- Truth-table verification
- Physical breadboard implementation
- Comparison of simulation and hardware behavior

---

## Logic Gates Implemented

| Gate | Boolean Expression |
|---|---|
| NOT | `Y = A̅` |
| AND | `Y = A·B` |
| NAND | `Y = (A·B)̅` |
| OR | `Y = A+B` |
| NOR | `Y = (A+B)̅` |
| XOR | `Y = A ⊕ B` |
| XNOR | `Y = (A ⊕ B)̅` |

---

## Components

### Hardware

- BC547B NPN transistors
- 10 kΩ resistors
- 3V Coin Cell
- Breadboard
- Hookup wires
- LED

### Software

- LTspice

---

## Basic Principle

I've used the BC547B as a switching device.

### Transistor OFF

```text
Input LOW
    ↓
Transistor OFF
    ↓
Collector resistor pulls output HIGH
