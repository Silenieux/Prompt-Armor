🛡️ Prompt Audit
A local, database-driven utility to help you write safer and more effective AI prompts.

🤔 Why Does This Exist?
We've all been there. You're interacting with a powerful Large Language Model (LLM), and it suddenly gives you a bizarre, unsafe, or completely useless answer. As AI becomes more integrated into our workflows, the quality and safety of our prompts are more important than ever. An ill-formed prompt can lead to:

Hallucinations: The AI confidently makes up incorrect information.

Unsafe Content: The AI generates harmful, malicious, or explicit content.

Exploits: The AI is tricked by prompt injection attacks, leading to unintended behavior.

Wasted Time: You go back and forth trying to get the AI to understand your actual request.

Inspired by the development of a private AI assistant named "Greg," Prompt Audit was born from a simple idea: what if we had a tool to pre-flight our requests, spot potential issues, and help us communicate more clearly and safely?

Prompt Audit is that tool. It's a first line of defense, designed to give you insight and control before you ever hit "send."

✨ Features
Prompt Audit analyzes your prompts in real-time using a multi-layered, local-first approach.

🛡️ Security Audit: Scans prompts against a comprehensive SQLite database of rules to detect threats like prompt injection, insecure output generation, data disclosure attempts, and malicious intent.

🩺 Interactive Prompt Clinic: A dedicated training ground that analyzes your prompts for clarity, style, and vagueness. It provides live feedback and a "Clarity Score" to help you learn the craft of effective prompting.

⚖️ Context-Aware Logic: Intelligently distinguishes between a dangerous request and a legitimate academic or creative query to reduce false positives.

💯 Risk Scoring: Assigns a numerical score to each prompt for a clear, immediate assessment of its potential danger.

✍️ Spell & Punctuation Check: The Prompt Clinic includes a built-in spell checker to catch common typos.

🚀 Getting Started
Go to the Releases Page on GitHub.

Download the latest PromptAudit.zip for your OS.

Unzip the file.

Double-click PromptAudit.exe (on Windows) to run! No installation needed.

🛠️ Built With
Language: Python

GUI: CustomTkinter

Database: SQLite

Spell Check: PySpellChecker

A whole lot of love and a desire for safer AI interactions.

Co-piloted by Gemini

📜 Version History
v2.5 (Current) - The Prompt Clinic

Added the "Prompt Clinic" tab for interactive prompt quality analysis.

Integrated a quality_rules table into the database.

Added a "Clarity Score" and live feedback to gamify the learning process.

Integrated pyspellchecker for typo detection.

v2.0 - The Database Engine

Replaced all hardcoded analysis logic with a robust, external SQLite database.

Implemented a comprehensive, categorized rule set based on OWASP Top 10 for LLMs.

Introduced advanced risk-scoring and context-aware analysis.

v1.0 - The Prototype

Initial release with a CustomTkinter GUI.

Analysis logic was hardcoded directly into the Python script.

v3.0 (In Development) - The Semantic Engine

Planned integration of sentence-transformers and FAISS to understand prompt meaning, not just keywords, for next-level threat detection.