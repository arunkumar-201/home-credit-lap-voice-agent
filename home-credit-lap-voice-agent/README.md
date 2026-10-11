# Home Credit LAP Qualification Voice Agent

## Project Overview
This project documents a voice agent configured in Bolna AI for preliminary qualification conversations for Home Credit's Loan Against Property (LAP) offer.

**Agent name:** Home Credit LAP Qualification Agent  
**Voice persona:** Priya  
**Platform:** Bolna AI  
**Published agent link:** https://bolna.ai/a/b1f17f95-ec6a-48f0-b5b2-94add52f8360

The agent conducts a conversational preliminary check using the assignment's stated eligibility criteria. It must not promise final loan approval or invent interest rates or product conditions.

## Main Features
- Greets the customer and checks whether it is a good time to talk.
- Explains the offer as up to ₹75 lakh, subject to eligibility.
- Collects seven qualification details:
  1. Property type
  2. Ownership
  3. Availability of original property documents
  4. Requested loan amount
  5. Employment type and income receipt method
  6. Estimated current property market value
  7. Requested loan tenure
- Clarifies unclear or ambiguous answers instead of guessing.
- Handles answers given out of order without repeatedly asking already answered questions.
- Immediately stops qualification when a disqualifying condition is confirmed.
- Recognizes existing-loan/EMI-reduction or loan-transfer requests and routes them to a loan-transfer specialist.
- Handles busy customers by asking for a convenient callback time.
- Gives a polite closing and describes any positive outcome as preliminary, not final approval.

## Eligibility Rules Implemented
- Property types accepted: residential, commercial, industrial.
- Agricultural property: disqualify.
- Sole and joint ownership: accepted.
- Original property documents must be available; if unavailable, disqualify.
- Maximum requested loan amount: ₹75 lakh. If a customer requests more, explain the limit and ask whether the maximum would work.
- Employment: salaried or self-employed; income must be received through a bank account. Cash-only income: disqualify.
- Property market value: ask for an estimate; do not invent a minimum value.
- Tenure: 3–15 years inclusive. If outside the range, offer the permitted range and end politely if the customer declines.
- Existing loan on the property with a request to transfer/reduce EMI: route to a loan-transfer specialist and end the current qualification flow.

## Testing Summary
The following scenarios were tested in conversational calls. Keep the recording/transcript evidence for each test alongside this repository or in a shared folder.

- Successful preliminary qualification with a residential property, ₹60 lakh requested loan, bank-received income, ₹1 crore estimated property value, and 10-year tenure.
- Agricultural property: immediate disqualification.
- Existing property loan with high EMI / transfer request: specialist routing and end of current flow.
- Original property documents unavailable: disqualification; an earlier call also showed an ownership misunderstanding that was corrected in subsequent prompt guidance.
- Cash-only income: clarification followed by immediate disqualification.
- Busy customer: asked for a preferred callback time and ended the current call.

Only report scenarios as passed when the corresponding recording confirms the expected behavior. The callback statement should not imply an appointment is actually scheduled unless the system can schedule it.

## Repository Contents
- `system_prompt.txt` — system prompt template to use/reconcile with the exact prompt configured in Bolna.
- `test_cases.md` — test scenarios and expected behavior.
- `submission_links.txt` — links to fill in before submitting.
- `recordings-and-transcripts/README.md` — instructions for adding call evidence.

## Important Notes
This repository documents the project; it does not contain Bolna's proprietary source code. Do not commit API keys, credentials, private customer information, or recordings containing sensitive data without authorization.
