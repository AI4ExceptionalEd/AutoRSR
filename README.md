# AutoRSR

A program that automates transcription, alignment, error analysis, and scoring of speech responses, designed for Redmond Sentence Recall (RSR). However, this is easily adaptable for use in other sentence recall tasks.

It uses WhisperX for transcription, and BertAlign / custom fuzzy alignment and A*-based edit distance for error analysis, and age/percentile-based thresholds for pass/fail decisions.

---
