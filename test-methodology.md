# Chemistry Assessment Methodology

## Purpose
Use this methodology for end-of-unit assessments throughout the Chemistry Study course.

The purpose of an assessment is not primarily to imitate a school exam or reward memorisation. It is to determine whether the learner has built a coherent mental model of the unit and can retrieve, explain, derive and transfer the ideas independently.

## Core principles

### 1. Breadth before adaptive depth
Each assessment has two stages.

**Stage 1 — Fixed diagnostic**
- Construct the core question set before the test begins.
- Cover every major topic in the completed unit regardless of performance.
- Do not add chains of follow-up questions in response to mistakes during this stage.
- This prevents a weakness in one area from consuming the test and leaving other areas untested.

**Stage 2 — Adaptive diagnosis**
- After the fixed diagnostic is complete, revisit answers that suggest uncertainty or misunderstanding.
- Use a small number of targeted follow-up questions to distinguish careless slips, forgotten facts, partial understanding and genuine conceptual gaps.
- Adaptive questioning is for diagnosis after breadth has been established, not for determining which topics get tested.

### 2. Mixed question ordering
- Do not present questions in the same sequence as the course or roadmap.
- Deliberately move between topics so that question order does not reveal which conceptual tool to use.
- Do not label questions with topic headings such as “Periodic Trends” when that would provide a clue.

### 3. Mixed difficulty and transfer
Include a deliberate mixture of:
- straightforward retrieval of important foundations;
- familiar applications of ideas practised during lessons;
- unfamiliar situations requiring transfer of the same principles;
- integrated questions requiring ideas from multiple parts of the unit.

The learner should sometimes need to decide which concepts are relevant rather than being told which method to apply.

### 4. Reasoning over final answers
- Ask for reasoning where appropriate.
- Correct answers reached through faulty reasoning should not automatically count as secure understanding.
- Minor arithmetic, notation or terminology slips should carry less weight when the underlying model is sound.
- Prioritise the ability to reconstruct an answer from physical/chemical principles over memorising isolated facts.

### 5. Closed-book fixed diagnostic
- Stage 1 should normally be closed-book.
- If a fact cannot be remembered, saying “I don't remember” is useful diagnostic information.
- Do not encourage guessing simply to produce an answer.
- Do not penalise failure to recall arbitrary facts that the course has not identified as worth memorising.

### 6. One question at a time
- Administer questions individually rather than displaying the whole test at once.
- During Stage 1, acknowledge answers neutrally without revealing whether they are correct.
- Do not teach or correct between fixed questions, because feedback could give clues to later questions.
- Record apparent issues for Stage 2.

### 7. Misconception checks
Include some questions designed to expose plausible misconceptions. These may:
- contain irrelevant information;
- present a questionable premise that should be challenged;
- offer a situation where a familiar shortcut fails;
- distinguish a simplified model from the more accurate model already taught.

These should test understanding, not rely on obscure tricks.

## Mandatory permanent exam archive

For every end-of-unit assessment, maintain a GitHub Markdown file at `assessments/unit-N-YYYY-MM-DD.md`. This is the authoritative record; the study record only links to it and summarises the outcome.

**Before Question 1:** Construct and lock all Stage 1 questions, then save their complete exact wording, numbering, parts, scenarios and diagrams (with durable textual equivalents) to GitHub. Mark the archive `in progress`. Do not start the formal test unless saving succeeds.

**After every answer:** Append the learner's full, verbatim response alongside its question, retaining original spelling, formatting, notation, mistakes and uncertainty. Confirm the GitHub write succeeded *before* asking the next question. Never substitute a summary or reconstructed answer. If saving fails, pause the exam until it works.

**Stage 2:** Record every adaptive follow-up's full wording and the learner's complete verbatim answer using the same write-before-continuing process. Keep teaching and feedback in separate sections; do not alter original answers.

**At completion:** Add an evidence-based topic-by-topic assessment (Secure / Mostly secure / Needs reinforcement / Not secure), question references, strengths, slips versus genuine gaps, outstanding revision points and progression decision. Verify that every locked question and follow-up has a full answer or explicit `not answered` entry. Mark `complete`, verify the saved file by fetching it, then link it from `study-record.md` with a concise outcome.

**Interrupted sessions:** Resume from the saved archive and the first unanswered question, never reconstruct the locked set. Later corrections are appended and labelled, never overwrite original answers. If historical text is unavailable, explicitly label it missing, summarised or reconstructed rather than claiming a verbatim transcript. The 2026-10-08 Unit 1 archive contains a clearly labelled historical reconstruction for Q1; future exams must capture every question and answer exactly.

## Assessment outcome
After both stages, give a topic-by-topic diagnostic using:

- **Secure** — can explain and apply independently.
- **Mostly secure** — underlying understanding is sound but there was a minor error, lapse or small prompt required.
- **Needs reinforcement** — identifiable conceptual weakness requiring review.
- **Not secure** — significant gap requiring reteaching.

An overall numerical score may be provided as secondary information, but the diagnostic profile is more important.

## Progression rule
Use the assessment to decide whether the learner is ready for the next unit. Review genuine weak areas before progressing. Do not require perfection where errors are superficial and the underlying conceptual model is secure.

## Test construction checklist
Before administering an assessment:
1. Read the roadmap and current study record.
2. Define the completed unit's assessable scope, excluding material explicitly deferred or not taught.
3. Build the complete Stage 1 question set before asking Question 1.
4. Check that every major topic is sampled.
5. Scramble conceptual ordering.
6. Include retrieval, application, transfer and integrated reasoning.
7. Include appropriate misconception checks.
8. Avoid question wording or headings that reveal the intended method.
9. Keep the fixed question set unchanged during Stage 1.
10. After Stage 1, construct only the Stage 2 follow-ups needed to diagnose uncertain areas.
