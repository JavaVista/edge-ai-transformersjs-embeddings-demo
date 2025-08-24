# Embeddings + Tiny Semantic Search (transformers.js)

This is a lightweight demo showing how to run **embeddings** and **tiny semantic search** directly in the browser using [transformers.js](https://xenova.github.io/transformers.js/).

A privacy-first demo using `@xenova/transformers` in the browser.  
It embeds text **on-device** and ranks documents by cosine similarity — no server required.

## 🔥 Live Demo
👉 [View it on GitHub Pages](https://javavista.github.io/edge-ai-transformersjs-embeddings-demo/)

## 🚀 Features
- Runs **fully client-side** (no server required)
- Uses [Xenova/gte-small](https://huggingface.co/Xenova/gte-small) embedding model
- Privacy-first: embeddings + cosine similarity are done on-device
- Example: Tiny semantic search ranking documents by meaning

## 📂 How it works
- Enter your **documents** (one per line)  
- Provide a **query**  
- The app embeds text and finds the most semantically similar matches  
- The **top match** is labeled as:  
  > 🔥 Most likely match

## 🛠️ Tech Stack
- [transformers.js](https://github.com/xenova/transformers.js)
- JavaScript (ES modules)
- Pure client-side HTML + CSS
