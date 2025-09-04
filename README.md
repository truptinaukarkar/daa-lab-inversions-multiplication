# daa-lab-inversions-multiplication
DAA Lab Experiments – Inversion Count &amp; Big Integer Multiplication

## Experiments
1) **Experiment 1 – Inversions**
   - Input: either
     - **Variant A (Two-Year Rankings of the same items)**: Two permutations of the same IDs (e.g., 100 students or 100 course codes) – Year 1 vs Year 2.
     - **Variant B (Per-Student Preferences)**: Each student’s ordered list of course codes; inversions counted vs a reference order.
   - Output: total inversion count, and a histogram of items/students with 0,1,2,3 inversions (and ≥4 if present).

2) **Experiment 2 – Big Integer Multiplication**
   - (i) Brute force (schoolbook) O(n²)
   - (ii) Divide & Conquer (Karatsuba) O(n^1.585)

## How to run
```bash
python src/inversions/inversions.py   # shows examples & results
python src/bigint/bigint_mul.py       # runs unit-like demos
