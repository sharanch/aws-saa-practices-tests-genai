# AWS SAA Practice Tests (GenAI Assisted)

This repository contains interactive practice tests for the AWS Certified Solutions Architect – Associate (SAA-C03) exam. These tests were developed with the assistance of Generative AI models, including Claude and Gemini, to provide high-quality scenario-based questions and technical explanations.

## Overview

Preparing for the AWS Solutions Architect Associate exam requires consistent practice with complex architectural scenarios. This project provides a browser-based interface to test knowledge across the core exam domains:
1. Design Resilient Architectures
2. Design High-Performing Architectures
3. Design Secure Applications and Architectures
4. Design Cost-Optimized Architectures

## Project Structure

The repository consists of standalone HTML files that integrate question logic, styling, and the interactive user interface:

* **aws-saa-practice-test.html**: The initial version of the practice exam.
* **aws-saa-practice-test-v2.html**: An updated version featuring refined questions and improved UI/UX.
* **README.md**: Project documentation and instructions.

## GenAI Integration

The technical content within these tests—including the scenarios, multiple-choice options, and justifications—was generated and refined using Anthropic Claude and Google Gemini. 

By leveraging Large Language Models, this project aims to:
* Replicate the tone and complexity of actual AWS exam questions.
* Provide immediate feedback including "Why this is correct" and "Why other options are incorrect."
* Ensure broad coverage of AWS services such as EC2, S3, RDS, Lambda, and VPC.

## Usage Instructions

Because the tests are built using standard web technologies (HTML, CSS, and JavaScript), no complex environment setup is required:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/sharanch/aws-saa-practices-tests-genai.git
    ```
2.  **Access the tests:**
    * Navigate to the project directory.
    * Open `aws-saa-practice-test-v2.html` (or the v1 version) in any modern web browser (Chrome, Firefox, Safari, or Brave).
3.  **Take the Test:** Select your answers and use the interactive elements to check your score and review the provided explanations.

## Features

* **Scenario-Based Learning:** Focuses on real-world architecture problems rather than simple rote memorization.
* **Zero Dependencies:** No local servers, databases, or software installations are needed.
* **Instant Feedback:** Receive immediate results to reinforce learning and identify knowledge gaps.

## Contributing

To suggest improvements, fix technical inaccuracies, or add new questions:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Open a Pull Request for review.

---
*Disclaimer: These tests are intended for supplemental practice and are not official AWS certification materials.*
