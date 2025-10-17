# Hugging_face_test_workflow
---
title: Text Summarizer Demo
emoji: 📝
colorFrom: blue
colorTo: purple
sdk: gradio
sdk_version: 4.12.0
app_file: app.py
pinned: false
---

# Text Summarizer

A demo application that summarizes text using DistilBART model.

## Description

This Space provides text summarization capabilities using the `sshleifer/distilbart-cnn-12-6` model. Enter any long text and get a concise summary.

## How to Use

1. Enter your text in the input box
2. Click the "Summarize" button
3. Get your summarized text in the output box

## Model

- **Model**: `sshleifer/distilbart-cnn-12-6`
- **Task**: Text summarization
- **Framework**: PyTorch

## Requirements

- gradio
- transformers
- torch