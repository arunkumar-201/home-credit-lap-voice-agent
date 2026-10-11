# 🏠 Home Credit LAP Qualification Voice Agent

<p align="center">
  <img src="https://img.shields.io/badge/AI-Voice%20Agent-6C63FF?style=for-the-badge&logo=openai&logoColor=white" alt="AI Voice Agent"/>
  <img src="https://img.shields.io/badge/Platform-Bolna%20AI-2563EB?style=for-the-badge" alt="Bolna AI"/>
  <img src="https://img.shields.io/badge/Status-Prototype-16A34A?style=for-the-badge" alt="Prototype"/>
</p>

<p align="center">
  An AI-powered voice agent for preliminary Loan Against Property (LAP) eligibility checks.
</p>

<p align="center">
  <a href="https://bolna.ai/a/b1f17f95-ec6a-48f0-b5b2-94add52f8360">
    <img src="https://img.shields.io/badge/🎙️_Live_Demo-Try_Agent-0F766E?style=for-the-badge" alt="Live Demo"/>
  </a>
  <a href="https://github.com/arunkumar-201/home-credit-lap-voice-agent">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository"/>
  </a>
</p>

---

## ✨ Overview

The **Home Credit LAP Qualification Voice Agent** uses Bolna AI to conduct preliminary customer eligibility conversations for a Loan Against Property offer of up to ₹75 lakhs, subject to eligibility.

The agent, named **Priya**, collects customer information, clarifies ambiguous answers, identifies disqualifying conditions, and routes existing-loan transfer requests appropriately.

> ⚠️ The agent provides preliminary qualification guidance only. Final approval and applicable interest rates are determined by the appropriate Home Credit team.

## 🚀 Key Features

| Icon | Feature | Description |
|---|---|---|
| 🎙️ | Voice Interaction | Natural, professional customer conversations |
| ✅ | Eligibility Checks | Evaluates seven required qualification details |
| 🧠 | Context Handling | Uses previously provided answers and handles out-of-order responses |
| 🔎 | Clarification | Requests clarification instead of guessing |
| ⛔ | Disqualification | Stops the qualification flow when a disqualifying condition is confirmed |
| 🔄 | Loan Transfer Routing | Identifies existing-loan transfer and EMI-reduction requests |
| 📅 | Callback Handling | Asks busy customers for a convenient callback time |
| 🛡️ | Responsible Responses | Does not promise final loan approval |

## 🧰 Technology Stack

<p>
  <img src="https://img.shields.io/badge/Bolna_AI-Voice_Platform-2563EB?style=flat-square" alt="Bolna AI"/>
  <img src="https://img.shields.io/badge/Prompt_Engineering-Conversational_Logic-7C3AED?style=flat-square" alt="Prompt Engineering"/>
  <img src="https://img.shields.io/badge/Markdown-Documentation-000000?style=flat-square&logo=markdown" alt="Markdown"/>
  <img src="https://img.shields.io/badge/GitHub-Version_Control-181717?style=flat-square&logo=github" alt="GitHub"/>
</p>

## 📋 Eligibility Criteria

| Criterion | Rule |
|---|---|
| 🏠 Property Type | Residential, commercial, and industrial accepted; agricultural disqualified |
| 👥 Ownership | Sole or joint ownership accepted |
| 📄 Original Documents | Must be available |
| 💰 Loan Amount | Up to ₹75 lakhs |
| 💼 Employment | Salaried or self-employed |
| 🏦 Income Mode | Bank-received income required; cash-only income disqualified |
| 🏢 Property Value | Collect an estimated current market value; do not invent a minimum |
| 🗓️ Loan Tenure | 3–15 years inclusive |

## 🔄 Conversation Workflow

1. 👋 Greet the customer and check availability.
2. 💬 Explain the offer and request permission to ask preliminary questions.
3. 📝 Collect and validate the seven eligibility details.
4. 🔎 Clarify ambiguous or incomplete responses.
5. ⛔ Stop immediately when a disqualifying condition is confirmed.
6. 🔄 Route existing-loan transfer requests to a loan-transfer specialist.
7. 🎯 Provide a preliminary outcome when all checks are complete.
8. 👋 End the conversation politely.

## 🧪 Testing Summary

| Test Scenario | Status |
|---|---|
| Successful preliminary qualification | Tested |
| Agricultural-property disqualification | Passed |
| Existing-loan transfer routing | Passed |
| Original documents unavailable | Tested |
| Cash-only income disqualification | Passed |
| Busy-customer callback | Passed |
| Ambiguous-response handling | Tested; continue validating edge cases |

Call recordings, transcripts, and logs should be linked as supporting evidence. Report only results supported by the actual test calls.

## 📂 Project Files

- 📘 `README.md` — Project overview and documentation
- 🤖 `system_prompt.txt` — Voice-agent system prompt
- 🧪 `test_cases.md` — Test scenarios and expected behavior
- 🎧 `recordings-and-transcripts/` — Instructions for organizing test evidence

## 🔗 Project Links

- 🎙️ **Live Agent Demo:** [Open Bolna Agent](https://bolna.ai/a/b1f17f95-ec6a-48f0-b5b2-94add52f8360)
- 💻 **GitHub Repository:** [home-credit-lap-voice-agent](https://github.com/arunkumar-201/home-credit-lap-voice-agent)
- 📄 **System Prompt:** `system_prompt.txt`
- 🧪 **Test Cases:** `test_cases.md`

## 👨‍💻 Author

**Arun Kumar Danda**

[![GitHub](https://img.shields.io/badge/GitHub-arunkumar--201-181717?style=flat-square&logo=github)](https://github.com/arunkumar-201)

---

<p align="center">
  <i>Built as an AI voice-agent assessment project, demonstrating conversational workflow design, eligibility validation, and customer-routing logic.</i>
</p>
