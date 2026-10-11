# Test Cases — Home Credit LAP Qualification Voice Agent

Record the actual result and evidence link for each test. Do not mark a test as passed unless the transcript/recording supports it.

| ID | Scenario / customer utterance | Expected behavior | Result |
|---|---|---|---|
| T01 | Residential property; sole ownership; original documents available; ₹60 lakh requested; salaried with bank salary; property worth ₹1 crore; 10-year tenure | Ask/record all seven checks and give preliminary qualification, not final approval | Tested — see recording/transcript |
| T02 | “My property is agricultural.” | Immediately disqualify and end; no further checklist questions | Passed in test |
| T03 | “I already have a loan on this property with another bank and the EMI is high. I want to transfer it.” | Route to loan-transfer specialist and end current qualification flow | Passed in test |
| T04 | “I don't have the original property documents.” | Immediately disqualify and end | Tested; verify final corrected recording |
| T05 | “I'm self-employed and receive all my income in cash.” | Clarify income mode if needed; once cash-only is clear, immediately disqualify | Passed in test |
| T06 | “I'm busy right now. Can you call me tomorrow afternoon?” | Ask/confirm a suitable callback time, acknowledge it, and end the current call without eligibility questions | Passed in test |
| T07 | Customer gives unclear ownership answer | Ask whether sole or joint ownership; do not guess | Retest after prompt improvement if possible |
| T08 | Customer gives unclear property value | Ask them to repeat/clarify; do not guess | Tested clarification behavior |
| T09 | Customer requests ₹90 lakh | Explain maximum ₹75 lakh and ask whether ₹75 lakh works | Not yet confirmed |
| T10 | Customer refuses to provide a required answer | Explain the preliminary check cannot be completed and end without declaring eligible | Not yet confirmed |
| T11 | Customer requests tenure below 3 years or above 15 years | Explain permitted range and ask if an in-range tenure works; if declined, end politely | Not yet confirmed |
| T12 | Customer answers questions out of order | Capture clear answers and ask only the first missing question | Tested in qualification calls; retain evidence |

## Evidence checklist
For each test, save:
- Call recording/audio if available
- Full transcript
- Call ID or call log/details
- Pass/fail and a short observation

## Notes
- Keep audio and transcripts free of sensitive customer information before sharing publicly.
- Never claim the agent actually schedules a callback unless the connected system supports it.
- A preliminary qualification result is not final loan approval.
