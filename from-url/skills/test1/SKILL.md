---
name: text-summarizer
description: Summarize long text into concise key points.
version: 1.0.0
author: test
tags:
  - text
  - summary
---

# Text Summarizer

## Overview

This skill summarizes long text and extracts the most important information.

It can be used for:

- Article summaries
- Meeting notes
- Technical document summaries
- News summaries
- Long-form text compression

## Instructions

When the user provides text that needs to be summarized:

1. Read the complete input text.
2. Identify the main topic.
3. Extract important facts and conclusions.
4. Remove repetitive or unimportant information.
5. Return a concise summary.

The summary should preserve important numbers, names, dates, and conclusions.

## Input

The input should contain the text to summarize.

Example:

> Please summarize the following text:
>
> Artificial intelligence is transforming software development...

## Output

Return the result using the following structure:

### Summary

A concise summary of the original text.

### Key Points

- Key point 1
- Key point 2
- Key point 3

## Constraints

- Do not invent information.
- Do not change the meaning of the original text.
- Preserve important technical terminology.
- Keep the summary concise.