# Neural Network Implementation in C++

This repository contains the source code for a basic neural network implementation in C++, extracted from the tutorial video by **Dave Miller**.

🎥 **Video Tutorial**: [Neural Net Implementation in C++](https://vimeo.com/19569529)

🎥 **Blog Post**: [New Video Tutorial: Make a Neural Net Simulator in C++](https://millermattson.com/dave/?p=54)


---

## 📂 Contents

- `makeTrainingData.cpp` – Generates training data for the neural network.
- `main.cpp` – Core implementation of the neural network.

---

## 🚀 How to Run

### 1. Compile and Run the Training Data Generator
```bash
g++ ./makeTrainingData.cpp -o ./out/makeTrainingData;
./out/makeTrainingData > /tmp/trainingData.txt
```

### 2. Compile and Run the Core Program
```bash
g++ ./main.cpp -o ./out/main;
./out/main > ./out/results.txt
```

**This source code assumes you are using Linux. For Windows please modify it accordingly.**