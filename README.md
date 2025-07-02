# 🧠 Mealy and Moore Machine FSMs in Logisim Evolution

This project demonstrates the design and implementation of **Mealy** and **Moore** finite state machines (FSMs) using [Logisim Evolution]. These are foundational models in digital logic design and automata theory.

## 📌 Overview

Finite State Machines are essential in digital system design for tasks like:
- Control systems
- Protocol recognition
- Sequence detectors
- State-dependent outputs

This repository includes:
- A **Mealy Machine**, where outputs depend on the **current state and input**
- A **Moore Machine**, where outputs depend only on the **current state**

Both designs are implemented as circuit schematics in Logisim Evolution and can be tested using simulation input stimuli.

---

## 🛠 Requirements

- **Logisim Evolution**  
  You can download the tool from the [official repository](https://github.com/reds-heig/logisim-evolution).

---

## 📁 Files Included

| File Name          | Description |
|--------------------|-------------|
| `Mealy_Machine.circ` | Logisim Evolution circuit file for the Mealy FSM |
| `Moore_Machine.circ` | Logisim Evolution circuit file for the Moore FSM |

---

## ▶️ How to Use

1. Open Logisim Evolution.
2. Load either `Mealy_Machine.circ` or `Moore_Machine.circ`.
3. Use the **Input/Clock buttons** to simulate transitions.
4. Observe how the output differs between the two FSM types:
   - **Mealy**: Output can change immediately based on input.
   - **Moore**: Output only changes after a state transition.

---

## 🔍 Differences Between Mealy and Moore

| Feature        | Mealy Machine                  | Moore Machine                   |
|----------------|--------------------------------|---------------------------------|
| Output Depends | State **and** Input            | Only on **State**               |
| Output Timing  | Can change **mid-state**       | Changes **on state transition** |
| Circuit Size   | Usually smaller (fewer states) | Often requires more states      |
| Reactivity     | Faster reaction to inputs      | More predictable output timing  |


---

## 👤 Author

**Abdus'Samad Bhadmus**  

---

## 📄 License

This project is open for educational use. Feel free to fork, explore, and modify.

---

## 🔗 References

- [Digital Design and Computer Architecture – Harris & Harris](https://www.amazon.com/Digital-Design-Computer-Architecture-Harris/dp/0128200650/)
- [Logisim Evolution GitHub](https://github.com/reds-heig/logisim-evolution)