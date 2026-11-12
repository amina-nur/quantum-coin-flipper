 <div align="center">

# QUANTUM COIN FLIPPER

### Beyond 0 and 1.

*An exploration of quantum probability, superposition and measurement.*

[![Open in Colab](https://img.shields.io/badge/ENTER_THE_QUANTUM_LAB-OPEN_IN_COLAB-8B70FF?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/amina-nur/quantum-coin-flipper/blob/main/Quantum_Coin_Flipper_Group5.ipynb)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat-square)
![Aer Simulator](https://img.shields.io/badge/Aer_Simulator-202040?style=flat-square)
![Status](https://img.shields.io/badge/PROJECT-COMPLETE-38BDF8?style=flat-square)

</div>

---

<div align="center">

**01 — SUPERPOSITION** &nbsp; · &nbsp; **02 — ROTATION** &nbsp; · &nbsp; **03 — MEASUREMENT**

</div>

## THE EXPERIMENT

What happens when a coin flip enters the quantum world?

Instead of assigning a fixed outcome, we use a qubit and quantum gates to create and control the probabilities of measurement.

## THREE WAYS TO FLIP

<details>
<summary><strong>01 / THE FAIR COIN</strong> — Equal probability</summary>

A Hadamard gate places the qubit into an equal superposition of 0 and 1.

| Expected | Actual |
|:---:|:---:|
| 50 / 50 | 42.5 / 57.5 |

**Gate:** Hadamard (H)

</details>

<details>
<summary><strong>02 / THE BIASED COIN</strong> — Controlled probability</summary>

An RY rotation changes the qubit's state, producing an uneven probability distribution.

| Expected | Actual |
|:---:|:---:|
| 75 / 25 | 72.3 / 27.7 |

**Gate:** RY rotation (π/3)

</details>

<details>
<summary><strong>03 / THE ADJUSTABLE COIN</strong> — Your probability</summary>

Choose your desired Heads probability using the interactive slider in the notebook. The circuit calculates the rotation angle required.

| Selected | Actual |
|:---:|:---:|
| 90 / 10 | 88.9 / 11.1 |

**Your control:** 0%–100% Heads probability.

</details>

## RESULTS / 001

| Experiment | Heads | Tails |
|:---|---:|---:|
| Fair | 42.5% | 57.5% |
| Biased | 72.3% | 27.7% |
| Adjustable | 88.9% | 11.1% |

<sub>Each experiment uses 1,000 simulated measurements. Results vary between runs.</sub>

## INSIDE THE CIRCUIT

```text
       QUBIT
         |
    QUANTUM GATE
         |
     MEASUREMENT
         |
    CLASSICAL BIT
         |
    0 OR 1 RESULT
```

The project uses:

- **Hadamard gate:** creates equal superposition.
- **RY gate:** controls measurement probabilities.
- **Measurement:** converts the quantum state into a classical result.
- **Qiskit Aer:** simulates the quantum circuits.

## TECHNOLOGY

[Python](https://www.python.org/) · [Qiskit](https://www.ibm.com/quantum/qiskit) · [Qiskit Aer](https://github.com/Qiskit/qiskit-aer) · [Matplotlib](https://matplotlib.org/) · [Google Colab](https://colab.research.google.com/)

---

<div align="center">

### THE QUANTUM LAB IS OPEN.

**Change the probability. Run the circuit. Observe the outcome.**

[![LAUNCH EXPERIMENT](https://img.shields.io/badge/LAUNCH_EXPERIMENT-8B70FF?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/amina-nur/quantum-coin-flipper/blob/main/Quantum_Coin_Flipper_Group5.ipynb)

*Qiskit Fall Fest 2026 · Amina Nur*

</div>
