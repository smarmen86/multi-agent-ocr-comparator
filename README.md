# Multi-Agent OCR Comparator

This project is a multi-agent system using ChatGPT and OCR tools (Tesseract, Google Vision, AWS Textract) to extract and compare text from images. It includes:

- Individual OCR agents with dedicated roles
- A coordinator agent to evaluate and recommend the best result
- Structured JSON output
- Optional API tool integration

## Agents
1. Tesseract OCR Agent
2. Google Vision OCR Agent
3. AWS Textract OCR Agent
4. Coordinator Agent

## Tool Support
- Each agent is paired with a tool (function) to handle image input
- Tools support base64-encoded images

