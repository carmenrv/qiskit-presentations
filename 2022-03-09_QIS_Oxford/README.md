# Oxford University Quantum Information Society - Option Pricing Using Quantum Computers

This presentation was hosted by the [Oxford University Quantum Information Society](https://www.facebook.com/events/1079864252579786/), Mar 9th 2022. The presenters were:

 - Amin Karamlou, IBM Quantum and Oxford University
 - Carmen Recio Valcarce, IBM Quantum

## Agenda

 - Introduction to the IBM Quantum and Qiskit Community team
 - Workshop:

{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "be8a31f3",
   "metadata": {},
   "source": [
    "# European Call Option Pricing using Quantum Computers\n",
    "\n",
    "Qiskit tutorial showing European Call Option Pricing + Spin-echo Optimization\n",
    "\n",
    "This tutorial follows the methodology described in <a href=\"https://quantum-journal.org/papers/q-2020-07-06-291/\">Option Pricing using Quantum Computers. Stamatopoulos et al. 2019.</a> to price European Call Options on a gate-based quantum computer. \n",
    "\n",
    "We use Amplitude Estimation (AE), an algorithm which provides a quadratic speedup compared to classical Monte Carlo methods. We put an emphasis on the implementation of the quantum circuits required to build the input states and operators needed by amplitude estimation to price the European call options.\n",
    "\n",
    "1. First, we show simulation results to highlight how the circuit that we implement prices the options.\n",
    "\n",
    "2. Then we simplify the circuit using the spin-echo optimization described in - <a href=\"https://arxiv.org/abs/2005.07711\">Efficient State Preparation for Quantum Amplitude Estimation.\n",
    "Almudena Carrera Vazquez, Stefan Woerner. 2020.</a>  to reduce the number of gates while keeping the same results (simulation only).\n",
    "\n",
    "3. Finally, we examine the performance of the option pricing circuits on quantum hardware using the IBM Q Mumbai quantum device. We employ an error mitigation scheme that allows us to significantly reduce the errors arising from noisy two-qubit gates.\n",
    "\n",
    "\n",
    "\n",
    "\n",
    "\n"
   ]
  }

## Relevant Links
IBM Quantum Services and Account: https://quantum-computing.ibm.com

Qiskit: https://qiskit.org
