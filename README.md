🛡️ Prompt Armor
A local, database-driven utility to help you write safer and more effective AI prompts.

🤔 Why Does This Exist?
We've all been there. You're interacting with a powerful Large Language Model (LLM), and it suddenly gives you a bizarre, unsafe, or completely useless answer. As AI becomes more integrated into our workflows, the quality and safety of our prompts are more important than ever. An ill-formed prompt can lead to:

Hallucinations: The AI confidently makes up incorrect information.

Unsafe Content: The AI generates harmful, malicious, or explicit content.

Exploits: The AI is tricked by prompt injection attacks, leading to unintended behavior.

Wasted Time: You go back and forth trying to get the AI to understand your actual request.

Inspired by the development of a private AI assistant named "Greg," Prompt Armor was born from a simple idea: what if we had a firewall for our AI prompts? A tool that could pre-flight our requests, spot potential issues, and help us communicate more clearly and safely.

Prompt Armor is that firewall. It's a first line of defense, designed to give you insight and control before you ever hit "send."

✨ Features
Prompt Armor analyzes your prompts in real-time using a comprehensive, local SQLite database of rules categorized by security standards like the OWASP Top 10 for LLMs.

🛡️ Prompt Injection Defense: Detects classic jailbreaking techniques like "Do Anything Now" (DAN), role-playing overrides, and instruction hijacking.

💻 Insecure Output Warnings: Flags prompts that could cause the LLM to generate dangerous code (e.g., SQL injection vulnerabilities, unsafe Python commands).

🤫 Data Disclosure Prevention: Catches attempts to leak the AI's system prompt, access local files, or retrieve Personally Identifiable Information (PII).

💣 Malicious Intent Blocking: Identifies requests for illegal acts, malware creation, deepfake instructions, and social engineering tactics.

⚖️ Context-Aware Logic: Intelligently distinguishes between a dangerous request and a legitimate academic or creative query (e.g., "write a virus" vs. "write a story about a virus").

💯 Risk Scoring: Assigns a numerical score to each prompt for a clear, immediate assessment of its potential danger.

🚀 Getting Started
Go to the Releases Page on GitHub.

Download the latest PromptArmor.zip for your OS.

Unzip the file.

Double-click PromptArmor.exe (on Windows) to run! No installation needed.

🛠️ Built With
Language: Python

GUI: CustomTkinter

Database: SQLite

A whole lot of love and a desire for safer AI interactions.

Co-piloted by Gemini

📜 Version History
v2.0 (Current) - The Database Engine

Replaced all hardcoded analysis logic with a robust, external SQLite database.

Implemented a comprehensive, categorized rule set based on OWASP Top 10 for LLMs.

Introduced advanced risk-scoring and context-aware analysis to reduce false positives.

v1.0 - The Prototype

Initial release with a CustomTkinter GUI.

Analysis logic was hardcoded directly into the Python script.

Included basic checks for absurdity, exploits, and malicious keywords.
