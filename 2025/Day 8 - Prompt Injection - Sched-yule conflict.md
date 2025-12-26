# Day 8 - Prompt Injection - Sched-yule conflict
## Overview
Day 8's task revolved around engagement with minipulation of AI chatbots and LLM, by exploiting the AI's Chain of Thought (CoT).
## Objective and What I Did
I began Day 8 by engaging with the AI chatbot on the Wareville Calendar on the TryHackMe AttackBox. Upon sending messages to the AI bot, I was able to view its CoT, which allowed me to read leaked information that led to fixing the error in the website's calendar.
## Key Takeaway
It is imperative to note that exposing an AI agent’s internal reasoning (chain-of-thought) and tool usage can leak sensitive operational details—like hidden function names and access tokens—that an attacker can then weaponize to gain unauthorized access or actions.
