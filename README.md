# My solutuion to the Quantum Factorization Challenge

This project showcases my solution to the Quantum Factorization Challenge, leveraging quantum algorithms to factor large semiprime integers utilizing the Quantum Rings Simulator. The challenge was hosted by **MIT iQuHACK** and sponsored by Quantum Rings.

# The Challenge

## Challenge: Crack the Code with Quantum Factorization

Sponsored by
![Quantum Rings](./images/quantum-rings-logo.png)

## Overview

Shor's algorithm revolutionized our understanding of computational power, proving that quantum computers could solve problems far beyond the reach of classical systems. Now, in a space where innovation meets legacy—the halls of MIT, where Professor Shor himself still walks—we invite you to push the boundaries of quantum computing.

Welcome to the **Quantum Factorization Challenge**, where your mission is to factor increasingly larger semiprime integers using pure quantum algorithms. With access to the **Quantum Rings Simulator**, capable of simulating circuits with hundreds of qubits and millions of gate operations, all running on the qBraid platform, or on your local developer environment-- this is your chance to demonstrate mastery, ingenuity, and the future of quantum computation.

## Why Does This Matter?

At the heart of this challenge lies one of the most critical problems in modern cryptography: the difficulty of factoring large integers. Semiprime numbers, the product of two prime numbers, form the foundation of encryption methods like RSA. The security of these systems relies on the near impossibility of factoring large semiprimes using classical computers.

Quantum algorithms like Shor’s show that this problem can be solved efficiently in a quantum world, posing both opportunities and challenges for the future of cryptography. By participating in this challenge, you’re not just solving a problem—you’re contributing to advancements that could reshape cybersecurity, data privacy, and computational theory.

---

## What You’ll Be Doing (Requirements)

1. **Factor Large Semiprime Integers**  
   Use quantum algorithms to tackle a prepared list of semiprime integers, from an approachable 8-bit number and growing to numbers beyond sizes that are yet known to have been factored using quantum algorithms.

2. **Leverage the Quantum Rings Simulator**  
   Use any quantum framework, but run all simulations on the Quantum Rings Simulator.

   In the event that you need more compute on qBraid, or more qubits from Quantum Rings, reach out on the [Quantum Rings Discord Channel](https://discord.com/channels/1326009426141777950/1330328378301087804), with evidence that your approach has worked with smaller samples, and we can unlock more resources for you.

3. **Focus on Real Quantum Solutions**  
   Classical optimizations are off the table—this challenge is about harnessing the full power of quantum algorithms.

4. **Demonstrate Universality**  
   Your solution should be capable of factoring multiple numbers of at least the same bit size—not just the one specific integer on the list.

5. **Document Your Approach**  
   Clearly explain your algorithm, its scalability, and provide insights into any learnings or novel approaches applied.

---

## Scoring Breakdown

All submissions must meet the above requirements, and will be ranked by the bit size of the largest number factored.

The largest bit size wins.

In the event that there is a tie, the team with the fastest execution will win.

Before selecting a winner, the source code, execution evidence, and documentation will be reviewed to ensure that the above requirements have been met.

---

## The Numbers You’ll Face

The semiprime integers provided are in a list located in the repository in [semiprimes.py](./semiprimes.py).

As you go, you will want to start small, and scale up. Keep in mind that simulation time may be a bottle neck, so getting a working implementation quickly for smaller numbers is key, so you can estimate the time it will take to run your algorithm on larger numbers.

---

## What you'll Win

In addition to the pride of winning the MIT iQuHack, members of the winning team will receive:

🏆 **A copy of _Fundamentals of Quantum Computing: Theory and Practice_** by Quantum Rings' Co-founder and CTO, **Venkat Kasirajan**. (up to 5 team members)

- If the winning team is based in the U.S., each member will receive a signed copy with a personal note from Venkat.
- If the winning team is outside the U.S., each member will receive a copy of the textbook shipped directly from the publisher.

[📖 Check out the book here.](https://www.google.com/books/edition/Fundamentals_of_Quantum_Computing/NVw0EAAAQBAJ?hl=en&gbpv=0)

Additionally, all participants will receive:

- Access to the Quantum Rings Simulator with 200 qubits for one year after the hackathon (non-commercial use).
- Support from the Quantum Rings community and staff to assist with simulator-related questions during the event.
- Hands-on experience with cutting-edge quantum computing challenges.

---

## Free Access to Best-in-class Simulation

1. Register for free at [www.QuantumRings.com](https://www.quantumrings.com)
2. Confirm your email
3. Select "Manage Keys" and enter Promocode "IQUHACK25"(EXP 02/02/2025) to unlock 200 qubits of simulation for one year
4. Copy the key, and use it to start simulating massive circuits locally! or on the qBraid platform.
