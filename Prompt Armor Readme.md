🛡️ Prompt Armor
A simple, powerful desktop tool to help you write safer and more effective AI prompts.

🤔 Why does this exist?
We've all been there. You're interacting with a powerful Large Language Model (LLM), and it suddenly gives you a bizarre, unsafe, or completely useless answer. As AI becomes more integrated into our workflows, the quality and safety of our prompts are more important than ever. An ill-formed prompt can lead to:

Hallucinations: The AI confidently makes up incorrect information.

Unsafe Content: The AI generates harmful, malicious, or explicit content.

Exploits: The AI is tricked by prompt injection attacks, leading to unintended behavior.

Wasted Time: You go back and forth trying to get the AI to understand your actual request.

Inspired by the development of a private AI assistant named "Greg," Prompt Armor was born from a simple idea: what if we had a firewall for our AI prompts? A tool that could pre-flight our requests, spot potential issues, and help us communicate more clearly and safely with our AI counterparts.

Prompt Armor is that firewall. It's a first line of defense, designed to give you insight and control before you ever hit "send."

✨ Features
Prompt Armor analyzes your prompts in real-time and flags a variety of potential issues across several categories:

🚨 Critical Threats:

Malicious Intent: Detects requests for viruses, malware, hacking instructions, and other harmful content using robust regex patterns.

Unsafe/Adult Content: Flags prompts that are likely to generate sexually explicit or otherwise inappropriate material.

Prompt Injection & Exploits: Catches common patterns used to hijack or loop the AI.

⚠️ Warnings & Risks:

AI Sentience Queries: Identifies questions about the AI's feelings or self-awareness that often lead to canned, unhelpful responses.

Absurd Content: Flags nonsensical or highly illogical prompts that have a high risk of causing the AI to hallucinate.

Emotional Tone: Detects strong emotional language (frustration, sadness) that can lead to unpredictable AI behavior and offers a chance to rephrase for a more neutral, effective prompt.

✍️ Prompt Enhancement:

If a prompt is deemed safe but is very short, Prompt Armor will suggest a simple rewrite to encourage more detailed and specific responses from the AI.

🎬 How It Works (The GIF)
🚀 Getting Started
Go to the Releases page.

Download the latest PromptArmor.exe (for Windows) or PromptArmor.app (for Mac, Not yet implimented).

Double-click to run! No installation needed.

🛠️ Built With
Python

CustomTkinter for the user interface.

A whole lot of love and a desire for safer AI interactions.

Co-piloted by Gemini 2.5 Pro