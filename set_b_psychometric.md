# Question Set B — Behavioral Narrative

**Philosophy:** Open-ended storytelling prompts designed to feel like a conversation, not a form. Workers answer in their own words. Domain, role, and working style bleed through naturally in the details — vocabulary, tools mentioned, stakes described, people referenced. Each question is designed to surface specific features an LLM needs to personalize its responses.

**Design goal:** Extract the same signal as Set A through narrative rather than direct elicitation — more engaging, harder to answer dishonestly, richer semantic content in the embedding space.

**Target features per question listed below each prompt.**

---

**B1.** Tell me about something you worked on recently that you're proud of — what was it, and what made it feel like a win?

`targets: domain, role level, what good looks like`

---

**B2.** What's the fastest way for someone to waste your time when they're trying to help you?

`targets: communication density, vocabulary level, what to avoid`

---

**B3.** Walk me through the last time you had to figure something out that nobody around you knew either.

`targets: how they learn, confidence level, handling ambiguity`

---

**B4.** Tell me about a time someone pushed back on how you were doing something. How did it land and what did you do with it?

`targets: feedback tolerance, decision-making style, tone preference`

---

**B5.** What does a genuinely frustrating day at work look like for you? Walk me through it.

`targets: domain, role level, what to avoid`

---

**B6.** When you have more to do than you can possibly finish, how do you decide what gets done and what gets dropped?

`targets: decision-making style, time pressure, handling ambiguity`

---

**B7.** Describe how you put together something you have to hand off — a report, a plan, a document, whatever that looks like in your job.

`targets: communication density, output format preference, how much context they give`

---

**B8.** What kind of work puts you in a groove where time disappears and you feel like you're doing exactly what you're good at?

`targets: confidence level, tone preference, what good looks like`

---

**B9.** What's something about how you work that you wish the people around you understood better?

`targets: vocabulary level, role level, feedback tolerance`

---

**B10.** Tell me about the last time you got a request that wasn't clear enough to act on. What did you do?

`targets: how they learn, handling ambiguity, how much context they give`

---

## Feature Coverage

| Feature | Questions |
|---------|-----------|
| Communication density | B2, B7 |
| Vocabulary level | B2, B9 |
| Domain / profession | B1, B5 |
| Role level | B1, B5, B9 |
| How they learn | B3, B10 |
| Feedback tolerance | B4, B9 |
| Decision-making style | B4, B6 |
| Confidence level | B3, B8 |
| Time pressure | B6 |
| Handling ambiguity | B3, B6, B10 |
| Output format preference | B7 |
| Tone preference | B4, B8 |
| What to avoid | B2, B5 |
| How much context they give | B7, B10 |
| What good looks like | B1, B8 |
