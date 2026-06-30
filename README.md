# dld-3bit-parity-generator-checker
"A 3-bit even parity generator and checker circuit project — designed in Logisim and TinkerCAD with full documentation."
# 3-Bit Even Parity Generator and Checker

Ek Digital Logic Design project jo 3-bit even parity generator aur checker circuits ko design aur simulate karta hai. Yeh project data transmission mein error detection ke basic concept ko demonstrate karta hai using XOR-based logic gates.

## Overview

Parity bits data integrity check karne ke liye use hote hain. Yeh project dikhata hai ke kaise ek 3-bit binary input ke liye even parity bit generate ki jati hai (generator circuit), aur phir transmission ke baad us parity ko verify kiya jata hai (checker circuit) taake pata chale data mein koi error to nahi aaya.

## Components

- **Parity Generator** — 3-bit input lekar even parity bit generate karta hai using XOR gates
- **Parity Checker** — 4-bit input (3 data bits + 1 parity bit) lekar verify karta hai ke parity sahi hai ya error hai
- Logic gates used: XOR, XNOR

## Tools Used

- **Logisim** — circuit simulation aur logic verification ke liye
- **TinkerCAD** — circuit design aur visualization ke liye
- **Microsoft PowerPoint** — project presentation
- **Microsoft Word** — detailed project report

## Project Files

- `DLD_Parity_Presentation.pptx` — project explanation slides
- `DLD_Parity_Report.docx` — detailed written report with truth tables and circuit diagrams
- Logisim circuit file(s)
- TinkerCAD circuit diagram(s)

## How It Works

1. 3-bit binary data input diya jata hai generator circuit ko
2. XOR gates use karke ek parity bit calculate hoti hai jo total number of 1s ko even rakhti hai
3. Yeh 4-bit data (3 bits + parity bit) transmit ki jati hai
4. Checker circuit receiving end par data verify karta hai — agar parity match nahi karti to error detect ho jata hai

## What I Learned

Is project se mujhe combinational logic design, XOR-based error detection techniques, aur Logisim/TinkerCAD jaise simulation tools ka practical use samajh aaya.

## Team

Group project — prepared with classmates for Digital Logic Design course (Air University Islamabad).
