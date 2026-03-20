# Framing in Data Link Layer

## Introduction

Framing is the process of dividing data into smaller units called frames at the Data Link Layer.

It helps in organizing and transmitting data efficiently between devices.

---

## What is a Frame?

A frame is a structured unit of data that contains:

- Header (addressing information)
- Data (payload)
- Trailer (error detection)

---

## Why Framing is Important

- Organizes data into manageable units
- Helps in error detection
- Enables proper data delivery
- Supports reliable communication

---

## Types of Framing

### 1. Fixed-Size Framing
- Frames have a constant size
- Simple but may waste space

---

### 2. Variable-Size Framing
- Frames can have different sizes
- More efficient but complex

---

## Framing Techniques

### 1. Byte-Oriented (Character-Oriented)

- Uses special characters to mark frame boundaries
- Example: Start and End characters

---

### 2. Bit-Oriented

- Uses bit patterns to define frames
- Example: 01111110 as flag

---

### 3. Length-Based Framing

- Frame length is specified in header
- Receiver reads exact number of bytes

---

## What I Learned

Today I learned about framing, its purpose, types, and techniques used in the Data Link Layer to structure and transmit data efficiently.
