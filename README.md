# AI Language Models & Cybersecurity

## Overview
This project evaluated three widely used AI language models — ChatGPT, Google Gemini, and Microsoft Copilot — for their behavior on offensive and defensive cybersecurity tasks, completed as part of a cybersecurity course (Introduction to Cybersecurity). The goal was to understand how these models respond when prompted toward security-relevant tasks, including phishing-related content and keylogger-related requests, and what that reveals about their current guardrails and limitations.

Tools/skills used: ChatGPT, Google Gemini, Microsoft Copilot, applied prompting for security use cases, phishing and keylogger threat concepts.

## Process
- Tested each of the three models against the same set of security-relevant prompts, covering both offensive framings (e.g. content resembling phishing lures, keylogger-related requests) and defensive framings (e.g. how to recognize or defend against these same techniques).
- Compared how each model responded — what it refused, what it flagged, what caveats or warnings it included, and where responses differed across models given similar prompts.
- Documented the practical implications: where model guardrails appeared consistent versus inconsistent, and what that means for using these tools safely in a security context.

## Findings
- Observed meaningful differences in how each model handled similar security-adjacent prompts, both in terms of what content they would generate and how they framed the risk to the user.
- Identified that framing plays a large role in what these models will produce — the same underlying request phrased offensively versus defensively could yield different levels of caution from the model.
- Concluded that AI language models can be useful defensive security tools (e.g. helping someone recognize a phishing attempt) but that their guardrails around offensive-framed requests are not uniform across providers.

## What I'd do differently
With more time, I'd want to formalize this into a structured comparison (a scoring rubric across specific prompt categories) rather than a qualitative writeup, and expand the prompt set to cover a wider range of attack techniques beyond phishing and keyloggers.

## Why this matters to me
This is the project that first got me thinking seriously about AI security specifically, rather than security in general. Understanding how language models behave under adversarial or ambiguous prompting — where the line between "helpful" and "exploitable" actually sits — is exactly the kind of problem I want to spend the AI Security Fellowship digging into, informed by the same rigor I bring from regulated clinical laboratory work: document what you observe precisely, don't assume good behavior, and treat every inconsistency as worth investigating.
