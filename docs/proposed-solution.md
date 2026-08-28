# Proposed Solution

## Overview

The proposed Smart Legal Metrology Compliance Verification System is a technology-assisted platform designed to support the preliminary verification of mandatory declarations on packaged commodities.

The system combines image processing, Optical Character Recognition (OCR), structured information extraction, and rule-based validation to identify potentially missing or unclear declarations.

## How the Proposed System Works

### 1. Package Image Input

The user provides an image of the packaged commodity.

### 2. Image Processing

The system processes the image to improve text visibility and prepare it for OCR.

### 3. OCR and Text Extraction

OCR is used to extract textual information visible on the package.

Examples may include:

- Product name
- MRP
- Net quantity
- Manufacturer / packer details
- Date-related information
- Consumer care details
- Other relevant declarations

### 4. Information Extraction

The extracted text is organized into structured fields so that individual declarations can be identified.

### 5. Rule-Based Verification

The identified declarations are compared against predefined verification rules applicable to the relevant product category.

### 6. Potential Issue Detection

The system highlights information that appears to be:

- Missing
- Unclear
- Difficult to identify
- Potentially inconsistent

### 7. Verification Summary

The system generates a structured summary showing detected declarations and potential issues.

## System Workflow

```text
Package Image
      ↓
Image Processing
      ↓
OCR / Text Extraction
      ↓
Information Extraction
      ↓
Declaration Identification
      ↓
Rule-Based Verification
      ↓
Potential Issue Detection
      ↓
Verification Summary