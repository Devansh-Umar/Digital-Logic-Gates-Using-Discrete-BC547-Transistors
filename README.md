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
| NOT | Y = A` |
| NOR | Y = (A+B)` |
| OR | Y = A+B |
| NAND | Y = (A.B)` |
| AND | Y = A.B |
| XOR | Y = A ⊕ B |
| XNOR | Y = (A ⊕ B)`|

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

The BC547 is an NPN bipolar junction transistor.

For the logic circuits transistor is operated primarily as a switching device.

When the base voltage is sufficiently low -

```text
Base LOW
    ↓
Transistor OFF
    ↓
Collector current ≈ 0
    ↓
Collector resistor pulls output HIGH

Therefore,

VOUT​ ≈ VCC​
```

When the base receives a sufficiently high voltage -

```text
Base HIGH
    ↓
Transistor ON
    ↓
Collector current flows
    ↓
Output is pulled toward GND

Therefore,

VOUT​ ≈ 0V
```

This switching behavior is the fundamental principle used to construct the logic gates.


See the full project report -
[Logic_Gates_(BC547)_Report.pdf](Logic_Gates_(BC547)_Report.pdf)
