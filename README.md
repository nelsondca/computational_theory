# Computational Theory Tasks

This project explores various concepts in computational theory through a series of tasks implemented in a Python Jupyter Notebook ([tasks.ipynb](tasks.ipynb)).

## Tasks Overview

The [tasks.ipynb](tasks.ipynb) notebook covers the following topics:

1.  **Binary Representations:** Implementation and explanation of bitwise operations like left rotation (`rotatel`), right rotation (`rotater`), choice (`ch`), and majority (`maj`).
2.  **Hash Functions:** A simple string hashing function (`unsigned_hash`) demonstrating basic hashing principles.
3.  **SHA-256 Padding:** A function (`sha256_padding`) to calculate the necessary padding for a message according to the SHA-256 standard, using [abc.txt](abc.txt) as an example input.
4.  **Prime Numbers:** Generation of the first 100 prime numbers using two different algorithms: Trial Division (`is_prime`, `first_100_primes_trial`) and the Sieve of Eratosthenes (`sieve_primes`).
5.  **Roots for SHA-256 Constants:** Calculation of the first 32 bits of the fractional parts of the square roots of the first 100 primes (`fractional_bits`), as used in SHA-256 constant generation.
6.  **SHA-256 Word Analysis:** Finding English words from [words.txt](words.txt) whose SHA-256 hash has the maximum number of leading zero bits (`sha256_hash`, `count_leading_zero_bits`).
7.  **Turing Machine Simulation:** A simple Turing Machine simulation (`add_one_turing`) designed to add 1 to a binary number represented on the tape.
8.  **Computational Complexity (Bubble Sort):** Implementation of the Bubble Sort algorithm (`bubble_sort`, `bubble_sort_with_comparisons`) modified to count the number of comparisons, analyzed over all permutations of a small list.

## Files

*   [tasks.ipynb](tasks.ipynb): The main Jupyter Notebook containing all task implementations and explanations.
*   [abc.txt](abc.txt): A sample input file containing "abc", used for the SHA-256 padding task.
*   [words.txt](words.txt): A list of English words used for the SHA-256 word analysis task.
*   [.gitignore](.gitignore): Standard Python gitignore file.
*   [README.md](README.md): This file.

## Running the Notebook

To run the code, you need a Python environment with Jupyter Notebook or JupyterLab installed. Open [tasks.ipynb](tasks.ipynb) and execute the cells sequentially.

## Dependencies

*   Python 3.x
*   Jupyter Notebook or JupyterLab
*   Standard Python libraries: `math`, `hashlib`, `itertools` (typically included with Python)

## References

The implementations and explanations in the notebook draw upon concepts from the following resources:

*   **Binary Representations & Bitwise Operations:**
    *   [ianmcloughlin/computational\_theory - binary\_representations.ipynb](https://github.com/ianmcloughlin/computational_theory/blob/main/materials/binary_representations.ipynb)
*   **Prime Numbers:**
    *   [ianmcloughlin/computational\_theory - prime\_numbers.ipynb](https://github.com/ianmcloughlin/computational_theory/blob/main/materials/prime_numbers.ipynb)
    *   [Khan Academy - Trial Division](https://www.khanacademy.org/computing/computer-science/cryptography/comp-number-theory/a/trial-division)
    *   [Wikipedia - Sieve of Eratosthenes](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)
    *   [Wikipedia - Trial Division](https://en.wikipedia.org/wiki/Trial_division)
*   **SHA-256:**
    *   [NIST FIPS PUB 180-4: Secure Hash Standard (SHS)](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf) (Sections on padding, constants, `ch`, `maj`)
    *   [ianmcloughlin/computational\_theory - sha256.ipynb](https://github.com/ianmcloughlin/computational_theory/blob/main/materials/sha256.ipynb)
*   **Hashing & Hash Functions:**
    *   [ianmcloughlin/computational\_theory - hash\_functions.ipynb](https://github.com/ianmcloughlin/computational_theory/blob/main/materials/hash_functions.ipynb)
    *   [Python Docs - hashlib](https://docs.python.org/3/library/hashlib.html)
    *   [Python Docs - bin()](https://docs.python.org/3/library/functions.html#bin)
*   **Turing Machines:**
    *   [ianmcloughlin/computational\_theory - turing\_machines.ipynb](https://github.com/ianmcloughlin/computational_theory/blob/main/materials/turing_machines.ipynb)
*   **Sorting Algorithms & Complexity:**
    *   [ianmcloughlin/computational\_theory - sorting.ipynb](https://github.com/ianmcloughlin/computational_theory/blob/main/materials/sorting.ipynb)
    *   [GeeksforGeeks - Bubble Sort](https://www.geeksforgeeks.org/bubble-sort-algorithm/)
    *   [Wikipedia - Bubble Sort](https://en.wikipedia.org/wiki/Bubble_sort)
*   **Dictionaries (for Task 6 Proof):**
    *   [Merriam-Webster](https://www.merriam-webster.com/dictionary/mirror) (Example used for proof)