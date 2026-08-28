# System Architecture

## Overview

The proposed system follows a modular architecture in which package images are processed, relevant information is extracted, and predefined verification rules are applied to generate a structured verification summary.

## Architecture

```text
                    USER
                      │
                      ▼
              ┌───────────────┐
              │ Web Interface │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ Image Upload  │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │Image Processing│
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ OCR / Text    │
              │ Extraction    │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ Information   │
              │ Extraction    │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ Compliance    │
              │ Rule Engine   │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ Verification  │
              │ Results       │
              └───────┬───────┘
                      │
              ┌───────┴────────┐
              ▼                ▼
       ┌────────────┐   ┌──────────────┐
       │ Dashboard  │   │ Verification │
       │            │   │    Report    │
       └────────────┘   └──────────────┘