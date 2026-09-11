# PNG Parser Notes

## Overview

PNG is a structured image format containing multiple chunks.
Image parsers must validate and process these structures safely.

## Research Focus

This study focuses on:

- PNG chunk parsing
- Image decoder behavior
- Metadata handling
- Error handling in parsers
- Regression testing methodology

## Security Perspective

Parser vulnerabilities can occur when software incorrectly handles:

- input validation
- memory management
- unexpected file structures

## Research Approach

The analysis is performed in a controlled local environment.

The goal is to understand software behavior and improve defensive testing practices.
