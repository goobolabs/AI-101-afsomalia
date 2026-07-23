# 🪙 Episode 03: What are Tokens?

> **Series:** AI 101 Af-Soomaali

---

# ❓ Frequently Asked Questions (FAQ)

### Q1. What is a Token?

A token is the smallest unit of text that an AI language model processes.

---

### Q2. Is a token the same as a word?

No.

A word may contain one token, multiple tokens, or even part of a token depending on the tokenizer.

---

### Q3. Why doesn't AI read words directly?

Computers process numbers, not words. Text is first broken into tokens, then converted into numbers before the model can understand it.

---

### Q4. What is Tokenization?

Tokenization is the process of splitting text into tokens.

---

### Q5. Why are tokens important?

Every Large Language Model, including ChatGPT, GPT, Claude, Gemini, and Llama, processes tokens instead of raw text.

---

# 🎯 Learning Objectives

By the end of this lesson, you will understand:

* What a token is
* Why AI uses tokens
* Token vs Word
* How tokenization works
* Token IDs


---

# What is a Token?

A token is a small piece of text that an AI model processes.

Instead of reading an entire sentence at once, AI first breaks the sentence into smaller pieces called **tokens**.

The model processes these tokens one by one.

---

# Simple Example

Sentence:

```
I love Somalia.
```

Possible tokens:

```
["I", "love", "Somalia", "."]
```

Each piece is a token.

---

# Tokens Are Not Always Words

Many beginners think:

> One Word = One Token

That is not always true.

Example:

```
Playing
```

may become

```
["Play", "ing"]
```

Another example:

```
Unbelievable
```

may become

```
["Un", "believ", "able"]
```

Different tokenizers may split text differently.

---

# Why Does AI Use Tokens?

AI models work with numbers, not text.

Breaking text into tokens makes it easier to:

* Understand language
* Learn patterns
* Predict the next token
* Handle different languages efficiently

---

# How Tokenization Works

```
Text
   ↓
Tokenizer
   ↓
Tokens
   ↓
Token IDs
   ↓
Embeddings
   ↓
Transformer
   ↓
Prediction
```

Every language model follows this pipeline.

---

# Token IDs

The model does not actually see words.

It sees numbers.

Example:

```
Hello

↓

15496
```

```
World

↓

995
```

Each token has a unique numerical identifier called a **Token ID**.

---

# Real Example

Input:

```
Artificial Intelligence is amazing.
```

Possible tokens:

```
Artificial
Intelligence
is
amazing
.
```

Each token receives its own Token ID before entering the model.

---



# Real-World Analogy

Imagine building a house with LEGO bricks.

The complete house is like a sentence.

Each LEGO brick is like a token.

The AI builds understanding one token at a time, just as you build a house one brick at a time.

---

# Where Are Tokens Used?

Tokens are used in:

* ChatGPT
* Claude
* Gemini
* Llama
* Qwen
* DeepSeek
* Every Large Language Model

Without tokens, language models cannot process text.

---

# Common Misconceptions

❌ A token is always one word.

✔️ A token can be a word, part of a word, punctuation, or even a space, depending on the tokenizer.

---

❌ AI reads sentences directly.

✔️ AI first converts sentences into tokens.

---

❌ Tokens are the same as characters.

✔️ Characters and tokens are different. One token may contain several characters.

---

# Key Takeaways

✅ Tokens are the basic units AI language models process.

✅ Text must be tokenized before entering the model.

✅ Every token becomes a Token ID.

✅ Token IDs are converted into embeddings.

✅ Context windows are measured in tokens, not words.

---

# Summary

Tokens are the language that AI models understand.

Before ChatGPT answers your question, your text is broken into tokens, converted into numbers, transformed into embeddings, and then processed by the model.

Understanding tokens is the foundation for learning how Large Language Models work.

---

