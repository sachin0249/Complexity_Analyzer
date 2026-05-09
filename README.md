# Complexity Analyzer

A futuristic **static code complexity analyzer** built with pure HTML, CSS, and JavaScript.
It detects algorithmic patterns and estimates:

* **Time Complexity**
* **Space Complexity**
* **Recurrence Relations**
* **Loop Nesting**
* **Recursion Types**
* and more...

🌐 **Live Demo:**
[Complexity Analyzer Live Demo](https://complexity-analyzer-theta.vercel.app/?utm_source=chatgpt.com)

---

## ✨ Features

* ⚡ Instant offline static analysis
* 🧠 Pattern detection engine
* 📊 Complexity visualization bars
* 🔍 Recurrence relation detection
* 🌲 DFS / BFS recognition
* 🔀 Divide & Conquer analysis
* 🪟 Sliding Window detection
* 🔍 Binary Search detection
* 📏 Loop nesting analysis
* 📦 Space complexity estimation
* 🎨 Modern cyberpunk-inspired UI
* 🌐 Works entirely in-browser
* 🚫 No backend required

---

## 📸 Preview

The analyzer provides:

* Interactive code editor
* Multi-language support
* Real-time complexity reports
* Explanation cards
* Pattern trace logs
* Visual complexity indicators

---

## 🛠 Supported Languages

* C++
* Java
* Python
* JavaScript

---

## 🧩 Detected Algorithmic Patterns

| Pattern             | Detection |
| ------------------- | --------- |
| Binary Search       | ✅         |
| BFS                 | ✅         |
| DFS                 | ✅         |
| Sliding Window      | ✅         |
| Two Pointer         | ✅         |
| Dynamic Programming | ✅         |
| Divide and Conquer  | ✅         |
| Linear Recursion    | ✅         |
| Binary Recursion    | ✅         |
| Backtracking        | ✅         |
| Nested Loops        | ✅         |

---

## 🚀 How It Works

The engine performs deterministic static analysis by:

1. Tokenizing source code
2. Extracting lightweight structural information
3. Detecting:

   * loops
   * recursion
   * recursion depth
   * graph traversal patterns
   * DP structures
4. Estimating:

   * best-case complexity
   * average-case complexity
   * worst-case complexity
   * auxiliary space
5. Rendering a visual report

---

## 📂 Project Structure

```bash
complexity-analyzer.html
```

Everything is self-contained in a single HTML file:

* UI
* Styles
* Analysis engine
* Pattern detector
* Complexity calculator

---

## ▶️ Usage

### Run Locally

Simply open the HTML file in your browser:

```bash
double-click complexity-analyzer.html
```

or

```bash
open complexity-analyzer.html
```

---

## 🌐 Deployment

The project is deployed on Vercel:

[Live Production Deployment](https://complexity-analyzer-theta.vercel.app/?utm_source=chatgpt.com)

---

## ⌨️ Keyboard Shortcuts

| Shortcut     | Action             |
| ------------ | ------------------ |
| Ctrl + Enter | Run analysis       |
| Tab          | Insert indentation |

---

## 📊 Example Algorithms Included

* Quick Sort
* Merge Sort
* Binary Search
* BFS
* DFS
* Fibonacci
* Sliding Window
* Bubble Sort
* Factorial

---

## 🧠 Complexity Examples

### Binary Search

```cpp
while(low <= high) {
    int mid = low + (high - low) / 2;
}
```

Detected Complexity:

```text
O(log n)
```

---

### Merge Sort

Recurrence:

```text
T(n) = 2T(n/2) + O(n)
```

Solved Complexity:

```text
O(n log n)
```

---

### Naive Fibonacci

Recurrence:

```text
T(n) = 2T(n-1) + O(1)
```

Solved Complexity:

```text
O(2^n)
```

---

## 🎨 UI Highlights

* Cyberpunk-inspired design
* Animated complexity bars
* Glassmorphism panels
* Monospace code editor
* Responsive layout
* Real-time analysis rendering

---

## 🔬 Static Analysis Capabilities

The analyzer can infer:

* logarithmic loops
* nested iteration depth
* recursion branching
* divide-and-conquer structures
* queue/stack traversal
* amortized traversal patterns
* recursive sorting behavior

---

## ⚠️ Limitations

This is a heuristic static analyzer, not a compiler.

It may not perfectly analyze:

* highly obfuscated code
* meta-programming
* advanced templates/macros
* dynamic runtime behavior
* unconventional syntax

---

## 🏗 Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript

No frameworks. No dependencies.

---

## 🌟 Future Improvements

* AST parser integration
* Syntax highlighting
* Cyclomatic complexity
* Memory profiling
* AI-assisted explanations
* More language support
* Exportable reports
* Live editor collaboration

---

## 📄 License

Apache-2.0 License

---

## 👨‍💻 Author

Built as a deterministic static analysis engine for algorithmic complexity estimation.
