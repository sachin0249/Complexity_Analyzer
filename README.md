# ⚡ ComplexiScan — Deterministic Time Complexity Analyzer

> A fully offline static analysis engine that estimates algorithmic **Time & Space Complexity** using deterministic rule-based analysis.

ComplexiScan is a lightweight browser-based complexity analyzer inspired by compiler analysis systems. It performs structural parsing and symbolic traversal to detect algorithmic patterns without relying on AI or cloud APIs.

---

# 🚀 Features

## ✅ Deterministic Static Analysis
- No AI dependency
- No probabilistic guessing
- Rule-based complexity inference
- Transparent analysis trace

---

## 🌐 Multi-Language Support
Supports:
- JavaScript
- Python
- Java
- C++

---

## 🧠 Pattern Recognition Engine

Automatically detects:

### Iterative Patterns
- Single loops → `O(n)`
- Nested loops → `O(n²)`, `O(n³)`

### Logarithmic Patterns
- Binary Search
- Geometric loop progression
- Halving strategies

### Recursive Patterns
- Linear Recursion
- Binary Recursion
- Divide & Conquer
- Exponential Recursion

### Advanced Algorithms
- Sliding Window
- Two Pointers
- BFS / DFS
- Dynamic Programming
- Backtracking
- Queue Amortization

---

# 🔬 How It Works

## 1. Symbolic Parsing Layer

The engine scans code structure using:
- loop detection
- recursion mapping
- nesting analysis
- control-flow inspired traversal

Instead of a full compiler AST, ComplexiScan uses a lightweight:
> **Control Flow Tree (CFT)** inspired parser

for maximum speed and low memory usage.

---

## 2. Rule-Based Complexity Engine

The analysis engine applies deterministic rules such as:

### Loop Rules
```js
for(let i = 0; i < n; i++)
```

→ `O(n)`

### Nested Loops
```js
for(i)
  for(j)
```

→ `O(n²)`

### Logarithmic Detection
```js
i *= 2
```

→ `O(log n)`

### Recurrence Detection
```js
fib(n-1) + fib(n-2)
```

→ `O(2ⁿ)`

---

# 🎨 UI Philosophy

ComplexiScan follows a:
> **Geometric Balance Design System**

Inspired by:
- modern IDEs
- diagnostic terminals
- compiler tooling

### UI Features
- Monochrome cyber aesthetic
- Real-time analysis feedback
- Syntax-aware visualization
- Complexity scale indicator
- Interactive analysis trace

---

# 📊 Analysis Output

The analyzer provides:

- Time Complexity
- Space Complexity
- Detected Algorithmic Patterns
- Complexity Explanation
- Internal Analysis Trace

---

# 🔒 Privacy First

ComplexiScan is fully offline.

✅ No cloud APIs  
✅ No telemetry  
✅ No external processing  
✅ Your code never leaves the browser

---

# ⚡ Performance

Optimized for speed:
- Sub-100ms analysis
- Lightweight parser
- Low memory usage
- Zero backend dependency

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | UI Design |
| Vanilla JavaScript | Analysis Engine |
| Symbolic Parsing | Structural Analysis |
| Rule Engine | Complexity Inference |

---

# 📂 Project Structure

```bash
ComplexiScan/
│
├── complexity-analyzer.html
├── README.md
└── assets/
```

---

# 🚀 Getting Started

## Prerequisites

- Modern Browser
- Optional: Node.js (for local hosting)

---

## Run Locally

Simply open:

```bash
complexity-analyzer.html
```

in your browser.

---

## Optional Local Server

```bash
npm install
npm run dev
```

---

# 🧪 Example Supported Algorithms

## Binary Search
```js
while(left <= right)
```

→ `O(log n)`

---

## Sliding Window
```js
for(let i = k; i < arr.length; i++)
```

→ `O(n)`

---

## Merge Sort
```js
T(n)=2T(n/2)+O(n)
```

→ `O(n log n)`

---

## Fibonacci Recursion
```js
fib(n-1)+fib(n-2)
```

→ `O(2ⁿ)`

---

# 🧠 Design Philosophy

> “Static analysis should be deterministic, explainable, and fast.”

ComplexiScan behaves like a lightweight compiler analysis system rather than an AI prediction tool.

The engine focuses on:
- correctness
- transparency
- speed
- deterministic reasoning

---

# 🎯 Future Roadmap

- Full AST integration
- CFG visualization
- Cyclomatic complexity metrics
- VS Code extension
- WebAssembly optimization
- Memory profiling
- Competitive programming mode

---

# 🤝 Contributing

Contributions are welcome.

Possible improvements:
- More language support
- Better recursion modeling
- Advanced CFG analysis
- UI enhancements
- Additional algorithm detection rules

---

# 📜 License

Licensed under the Apache License 2.0

```text
Copyright 2026 ComplexiScan

Licensed under the Apache License, Version 2.0
http://www.apache.org/licenses/LICENSE-2.0
```

---

# ⭐ Final Note

ComplexiScan proves that:
> deterministic static complexity analysis can be fast, reliable, and completely offline.

No AI.
No cloud.
Just pure structural analysis.
