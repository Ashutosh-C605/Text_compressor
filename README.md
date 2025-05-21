# Huffman Text Compression System

This project is a C++ implementation of a **Huffman Coding-based text compressor and decompressor**, demonstrating mastery in data structures, algorithms, file I/O, and performance profiling.

## 🔧 Key Features

- **Huffman Encoding Tree** built using a min-heap (priority queue)
- Character frequency analysis using hash maps
- Binary encoding and bit-level file writing for actual compression
- Decoding logic using the original Huffman tree
- Real-time performance measurement (compression/decompression time)
- File size comparison and compression ratio computation

## 🧠 Core Concepts

- **Greedy Algorithms** (Huffman Coding)
- **Min-Heaps and Trees** for optimal encoding
- **Binary and Text File I/O** in C++
- **Bit Manipulation** for byte-wise storage
- **Time Profiling** using `std::chrono`
- **System File Handling** using `stat` for cross-platform file size detection

## 📂 File Workflow

1. Reads plain text from `input_main.txt`
2. Compresses using Huffman codes and writes to `compressed.bin`
3. Decompresses and prints decoded output
4. Displays compression stats and performance metrics

## 📊 Sample Results

Original size : 5242 bytes
Compressed size : 2924 bytes
Compression ratio: 55.79%
Compression time: 9 ms
Decompression time: 4 ms


## 💼 Resume Highlights

- **Built a fully functional file compressor using Huffman Encoding from scratch in C++**
- **Reduced file size by over 40% on average in real-world test cases**
- **Applied low-level bit manipulation for actual binary compression**
- **Implemented performance benchmarking and system-level file stats reporting**

## 🚀 How to Run


g++ -std=c++11 -o huffman main.cpp
./huffman
🔗 Suitable For
Demonstrating algorithmic thinking in technical interviews

Academic coursework (Data Structures / File Systems)

Resume / GitHub project portfolio (System-level programming + compression)

Ashutosh Chaturvedi — C++ enthusiast | Systems Programmer | Algorithm Lover
