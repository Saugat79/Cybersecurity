# OSI Layer 2 – Data Link Layer

## Introduction

The Data Link Layer is the second layer of the OSI model.  
It is responsible for reliable data transfer between two directly connected devices.

It ensures that data is transferred without errors over the physical layer.

---

## Main Functions of Data Link Layer

- Framing (dividing data into frames)
- Error detection and correction
- Flow control
- MAC addressing
- Reliable data transfer

---

## Services Provided by Data Link Layer

### 1. Unacknowledged Connectionless Service
- No acknowledgment is sent
- Faster but less reliable

### 2. Acknowledged Connectionless Service
- Acknowledgment is sent for each frame
- More reliable

### 3. Acknowledged Connection-Oriented Service
- Connection is established before transmission
- High reliability

---

## Sublayers of Data Link Layer

### 1. Logical Link Control (LLC)

- Manages communication between devices
- Provides error control and flow control

---

### 2. Media Access Control (MAC)

- Controls access to the physical medium
- Uses MAC addresses
- Handles frame transmission

---

## What is a Frame?

A frame is a unit of data at the Data Link Layer.

It contains:
- Source MAC address
- Destination MAC address
- Data
- Error detection (CRC)

---

## What I Learned

Today I learned about the Data Link Layer, its functions, services, and sublayers (LLC and MAC). I also understood how data is framed and transmitted between devices.

---

## Physical Layer vs Data Link Layer

| Feature | Physical Layer | Data Link Layer |
|--------|--------|--------|
| Layer | Layer 1 | Layer 2 |
| Data Unit | Bits | Frames |
| Addressing | None | MAC Address |
| Function | Signal transmission | Error-free data transfer |
