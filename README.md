# Comparative Analysis of Sorting Algorithms

This repository presents a comparative analysis of various **sorting algorithms** implemented in **Java**, covering both comparison-based and non-comparison-based techniques.

## 🧠 Objective

To evaluate the performance and characteristics of different sorting algorithms through hands-on implementation and theoretical analysis.

## ✅ Sorting Algorithms Implemented

### Comparison-Based Sorting:

1. **Bubble Sort** – Simple but inefficient for large datasets.
2. **Insertion Sort** – Efficient for nearly sorted data.
3. **Merge Sort** – Stable, divide-and-conquer algorithm with consistent O(n log n) time.
4. **Quick Sort (Hoare’s Partition Scheme)** – Highly efficient in practice; not stable.

### Non-Comparison-Based Sorting:

1. **Counting Sort** – Best for small ranges of integers.
2. **Radix Sort** – Digit-by-digit sorting; good for fixed-length integers.
3. **Bucket Sort** – Distributes input into buckets, sorts each, and merges.

## 📊 Comparative Analysis

| Algorithm      | Best Time  | Average Time | Worst Time | Space Complexity | Stable | Type             |
| -------------- | ---------- | ------------ | ---------- | ---------------- | ------ | ---------------- |
| Bubble Sort    | O(n)       | O(n²)        | O(n²)      | O(1)             | Yes    | Comparison-Based |
| Insertion Sort | O(n)       | O(n²)        | O(n²)      | O(1)             | Yes    | Comparison-Based |
| Merge Sort     | O(n log n) | O(n log n)   | O(n log n) | O(n)             | Yes    | Comparison-Based |
| Quick Sort     | O(n log n) | O(n log n)   | O(n²)      | O(log n)         | No     | Comparison-Based |
| Counting Sort  | O(n + k)   | O(n + k)     | O(n + k)   | O(k)             | Yes    | Non-Comparison   |
| Radix Sort     | O(nk)      | O(nk)        | O(nk)      | O(n + k)         | Yes    | Non-Comparison   |
| Bucket Sort    | O(n + k)   | O(n + k)     | O(n²)      | O(n + k)         | Yes    | Non-Comparison   |

> Note: `k` refers to the range of digits (Radix) or buckets used.

## 🔍 Key Insights

* **Merge Sort** is ideal when stability is important and extra space is acceptable.
* **Quick Sort** is fast and efficient with average performance, but performance degrades with certain inputs.
* **Counting/ Radix/ Bucket Sorts** are excellent when the input data meets specific criteria (e.g., small or fixed range).

## 🧪 How to Use

Each language folder contains the implementations. You can test the algorithms with different input arrays and measure time using built-in timing utilities.

## 🤝 Contributions

Pull requests are welcome! Feel free to add visualizations, benchmarks, or more sorting algorithms.

## 📁 Structure

```
sorting-comparative-analysis/
├── java/
│   └── SortingAlgorithms.java
```
