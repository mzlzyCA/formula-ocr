---
name: formula-ocr
version: 0.2.0
description: >
  Recognize and extract mathematical formulas from documents, images, and scanned pages using MinerU-powered OCR. Convert handwritten or printed equations into LaTeX, MathML, or plain text notation. 公式OCR识别, 数学公式提取, 公式图片转LaTeX, 手写公式识别.

  Supports formula optical character recognition, equation OCR, math expression recognition, handwritten formula detection, printed equation extraction, LaTeX formula generation, MathML conversion, symbolic math recognition, integral/derivative/matrix recognition, and scientific notation parsing.

  Use when asked to "OCR this math formula", "convert equation image to LaTeX", "recognize this handwritten formula", "extract math from this screenshot", "what equation is in this image", "turn this formula photo into LaTeX code", "digitize this mathematical expression". Also handles "I photographed an equation from my textbook", "can you read this formula from the whiteboard", "convert these handwritten notes with equations".

  Solves problems like: can't type complex equations manually, handwritten formulas need digital form, textbook equations need LaTeX code, whiteboard math needs to be preserved, scanned homework with formulas, research paper equations need extraction for reuse. Powered by MinerU for high-accuracy mathematical symbol recognition including fractions, integrals, matrices, Greek letters, and nested expressions.
tags:
  - ocr
  - formula
  - math
  - equation
  - latex
  - handwriting
  - recognition
  - mineru
  - mathematics
  - symbol-recognition
  - scientific
---

# Formula OCR

Recognize mathematical formulas from documents and images.

## System Prompt

You are a mathematical formula OCR specialist. Use the MinerU tool to recognize and extract equations from documents and images.

When the user provides a document or image with mathematical formulas:
1. Use MinerU to detect and recognize mathematical expressions
2. Convert recognized formulas to LaTeX notation
3. Provide alternative formats if requested (MathML, plain text, Unicode)
4. Verify formula structure for correctness where possible

Handle errors gracefully:
- If MinerU fails to recognize certain symbols, flag them with placeholders
- If handwriting quality is poor, provide best-effort with confidence notes
- Always validate that generated LaTeX compiles correctly
