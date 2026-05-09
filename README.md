# TrustTilt 🛡️

AI-assisted cybersecurity platform for website trust analysis, phishing detection, and browser security awareness.

## Overview

TrustTilt is a cybersecurity-focused software project designed to help users evaluate website safety in real time and improve awareness of online threats.

The platform combines browser-based website analysis, phishing detection logic, risk scoring, and interactive user guidance to provide a safer browsing experience.

TrustTilt is being developed as both an academic software engineering project and a foundation for future product expansion.

---

## Problem Statement

Many users unknowingly interact with phishing websites, suspicious login pages, and deceptive domains that imitate legitimate services.

Common risks include:

- credential theft
- phishing attacks
- malicious redirects
- fake payment/login pages
- social engineering scams

Most users do not have the technical knowledge to recognize these threats quickly.

TrustTilt aims to simplify this decision-making process.

---

## Current MVP Scope

The first implementation focuses on building a functional minimum viable product (MVP).

### Browser Extension
Features:

- analyze currently visited websites
- calculate trust/risk score
- identify suspicious URL patterns
- display safe / warning / danger indicators
- provide risk explanations

---

### Web Dashboard
Features:

- scan history overview
- detailed threat analysis view
- chatbot interface for cybersecurity guidance
- simple security analytics

---

### TrustCore (C++ Detection Engine)
Core analysis module built using object-oriented C++.

Responsibilities:

- URL parsing
- phishing keyword detection
- suspicious TLD analysis
- HTTPS verification
- heuristic risk scoring
- threat report generation

---

## Planned Architecture

```text
Browser Extension
        ↓
Web Dashboard
        ↓
Threat Analysis Engine (TrustCore C++)
        ↓
Risk Scoring System
        ↓
Security Guidance / Chatbot
```

## Technology Stack

### Frontend / Web Technologies
- HTML
- CSS
- JavaScript
- Chrome Extension APIs

### Core Engine
- C++

### Future Expansion
- backend API integration
- AI assistant
- persistent scan storage
- advanced phishing intelligence

---

## Academic Goals

This project is designed to demonstrate:

### Web Technologies
- frontend development
- browser APIs
- DOM manipulation
- user interface design
- dashboard development

### Object-Oriented Programming (C++)
- encapsulation
- inheritance
- polymorphism
- constructors
- file handling
- modular architecture

---

## Project Structure

```text
trusttilt/
│
├── trustcore-cpp/
├── extension/
├── dashboard/
├── docs/
└── README.md
```

---

## Roadmap

### Phase 1
- TrustCore C++ detection engine
- browser extension MVP
- dashboard UI
- chatbot prototype

### Phase 2
- improved threat analysis
- persistent scan history
- smarter scoring logic

### Phase 3
- AI-powered explanations
- enterprise dashboard concepts
- advanced threat intelligence

---

## Status

🚧 In active development
