# 🚗 Car Manual RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that integrates vehicle manuals with Large Language Models (LLMs) to provide context-aware explanations of car warning messages and recommended driver actions.

This project demonstrates a proof-of-concept intelligent assistant for in-vehicle systems, where drivers can ask natural language questions about warning indicators and receive accurate, grounded answers based on official documentation.

## Problem Statement

Modern vehicles display numerous warning messages and symbols that may be confusing or misunderstood by drivers, especially while driving. Misinterpreting these warnings can lead to unsafe decisions or vehicle damage.

Traditional LLMs may hallucinate or provide incorrect advice if they are not grounded in authoritative sources.


## Solution

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline that:

- Parses official vehicle documentation (HTML format)
- Retrieves relevant sections of the car manual using semantic search
- Generates accurate, context-aware answers using an LLM
- Ensures responses are grounded in real documentation

The system is designed to be easily extended for **text-to-speech (TTS)** integration in automotive environments.

## How It Works (RAG Architecture)
 ↓ User Question

↓
Text Embedding

↓
Vector Database (Chroma)

↓
Relevant Manual Sections

↓
LLM 

↓
Response 
 

