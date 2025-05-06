---
title: "Supercharge GitHub Copilot with Prompt Boost in VS Code"
date: 2025-05-06
categories: 
  - GitHub Copilot
  - VS Code
tags:
  - Prompt Boost
  - AI Tools
  - Productivity
read_time: true
author_profile: true
---

If you're using GitHub Copilot in Visual Studio Code, you already know how transformative AI can be for your development workflow. But what if you could make Copilot even smarter—without doing any heavy lifting?

**Prompt Boost** is a free VS Code extension that takes your basic prompts and *supercharges* them with detailed, context-rich instructions. The result? Copilot responses that are clearer, more accurate, and much closer to what you actually want.

---

## 🚀 What Is Prompt Boost?

[Prompt Boost](https://marketplace.visualstudio.com/items?itemName=chrisdias.promptboost), created by [Chris Dias](https://github.com/chrisdias), is an AI prompt enhancer. It's designed to improve how you interact with GitHub Copilot by rewriting vague prompts into detailed, high-context instructions using your editor’s current content.

Think of it like a copy editor for your Copilot inputs—automatically turning _“generate login page”_ into something closer to:

> “Generate a responsive login page using React, with email and password fields, form validation, and Tailwind CSS for styling.”

Copilot now has way more to work with—and you get results you actually want.

![Prompt Boost Demo](/assets/images/prompt-boost-demo.gif)


---

## ✨ Key Features

- **One-click prompt boosting**  
  Highlight a line or block of text, press `Ctrl+I` (or `Cmd+I` on Mac), and Prompt Boost turns it into a high-quality instruction.

- **Context-aware**  
  It takes your file name, content, and cursor position into account to generate better prompts.

- **Copilot-compatible**  
  It works seamlessly with GitHub Copilot Chat—you can insert boosted prompts directly into the chat panel.

- **Customizable prompt templates**  
  Advanced users can define their own rewrite templates to fine-tune prompt style and tone.

---

## 🛠 How to Use Prompt Boost

1. **Install the extension**  
   [Install from VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=chrisdias.promptboost)

2. **Highlight your input**  
   Select a vague comment or task description.

3. **Press `Ctrl+I` or use the Command Palette**  
   Choose “Boost Prompt” — Prompt Boost will rewrite your instruction in real-time.

4. **Send it to Copilot Chat**  
   You can optionally insert the boosted prompt into Copilot Chat to get refined results.

---

## 💡 Example

Let’s say you write this comment:

// create a rest api for user login


Prompt Boost transforms it into:

> “Write a Node.js Express REST API endpoint that handles user login. It should accept a POST request with email and password, validate inputs, and return a JWT on success. Use bcrypt for password comparison and proper error handling.”

Now *that’s* something Copilot can work with.

---

## 🧠 Why It Matters

AI tools are only as good as the input they receive. Many developers struggle with writing prompts that are specific, detailed, and actionable. Prompt Boost removes that burden—it helps you talk to Copilot in a language it understands, without changing your workflow.

---

## 🧪 Final Thoughts

Prompt Boost is a small extension with a big impact. If you're serious about getting the most from GitHub Copilot, this tool is a no-brainer. It's free, open-source, and backed by a clear vision: **better prompts = better code**.

👉 [Install Prompt Boost](https://marketplace.visualstudio.com/items?itemName=chrisdias.promptboost) and let your code speak for itself.
