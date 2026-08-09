# Paper 03

## Inference-Order Failure in Human–AI Dialogue

### An Exploratory Case Study of Conversational Misalignment

---

## Overview

This paper examines a form of conversational failure in which an AI begins reasoning from an interpretation that has not yet been confirmed with the user.

The case emerged from a dialogue in which the user attempted to discuss fear, distrust, and perceived danger associated with another person's behavior.

Individual AI responses were not necessarily factually incorrect.

However, the conversation gradually moved away from the user's original concern.

The AI shifted from the concrete issues of behavioral danger and trust toward:

- semantic clarification;
- diagnostic caution;
- distinctions between subjective and objective claims;
- philosophical abstraction;
- metaphor management.

The central problem was therefore not simply missing context or factual error.

It concerned the **order in which interpretation and reasoning occurred**.

---

## Central Concept

The paper proposes the concept of:

### Inference-Order Failure

An inference-order failure occurs when an AI treats an unconfirmed interpretation of the user's meaning as a working premise and begins reasoning from that premise.

The resulting response may be locally plausible while becoming globally misaligned with the user's communicative purpose.

A simplified failure sequence is:

**concrete user concern  
→ ambiguous or emotionally strong expression  
→ AI selects an unconfirmed interpretive frame  
→ reasoning proceeds within that frame  
→ caution, abstraction, or explanation expands  
→ original topic is displaced  
→ user repairs the frame  
→ repair burden shifts to the user**

---

## Research Question

The primary research question is:

> **How can premature inference produce conversational misalignment in human–AI dialogue?**

The paper also examines:

- how locally reasonable AI responses can become globally misaligned with the user's communicative purpose;
- how repeated user correction can reveal failures in the ordering of confirmation, interpretation, explanation, and repair;
- how conversational repair burden may shift from the AI to the user.

---

## Confirmation Before Inference

The paper proposes **confirmation before inference** as a practical response principle.

This does **not** mean that an AI should ask a clarification question before every inference.

Instead, when a user's meaning is ambiguous, emotionally strong, or consequential, the AI should avoid silently selecting one interpretation and reasoning as though that interpretation had already been confirmed.

A more appropriate sequence is:

**identify the concrete concern  
→ separate possible meanings  
→ minimally confirm the relevant interpretation when necessary  
→ reason from the confirmed premise  
→ return the response to the user's original concern**

---

## Relationship to Earlier Papers

### Paper 01 — The Temperature and Humidity of Words

Paper 01 examined how information already present in human expression may be reduced when semantically similar language is treated as equivalent.

Its central observational problem can be described as:

**loss of information that was present**

---

### Paper 02 — Narrative Completion Under Ambiguous Input

Paper 02 examined how an ambiguous symbolic input may be completed into a causal and temporal narrative that exceeds the available evidence.

Its central observational problem can be described as:

**addition of information that was not established**

---

### Paper 03 — Inference-Order Failure in Human–AI Dialogue

Paper 03 extends this line of observation from the content of an inference to the **sequence of reasoning itself**.

Its central problem is:

**reasoning from an interpretation before that interpretation has been adequately confirmed**

The relationship among the three papers is developmental rather than confirmatory.

Paper 03 does not function as proof of Paper 01 or Paper 02.

Instead, the papers examine different but related forms of conversational misalignment:

**Paper 01  
information may be reduced**

↓

**Paper 02  
information may be added**

↓

**Paper 03  
reasoning may begin from an unconfirmed interpretation**

---

## Methodological Position

This paper is an exploratory qualitative case study.

The unit of analysis is not a single AI response but a bounded interactional process.

The materials include:

- reconstructed dialogue context;
- reflective user accounts;
- debugging notes generated during the interaction;
- subsequent analytical discussion;
- earlier exploratory case material used as conceptual background.

The paper does not claim:

- statistical generalizability;
- transcript-level independent verification;
- direct access to hidden model reasoning;
- that all AI conversational failures share the same mechanism.

The strongest claims are limited to the observable interactional process documented in this case.

---

## Repair Burden

A significant feature of the case was the transfer of conversational repair work to the user.

The user repeatedly had to:

- correct AI assumptions;
- distinguish behavior from personality;
- restore the original topic;
- identify premature abstraction;
- correct the order of reasoning itself.

This repair burden is treated as analytically relevant rather than as incidental conversational inconvenience.

A useful evaluation question therefore becomes:

> **Who is doing the work required to preserve the topic, premises, and order of reasoning?**

---

## Languages

English is the canonical version of Paper 03.

A Japanese translation is being prepared for accessibility and reference.

Because English and Japanese do not map perfectly in:

- semantic range;
- grammatical structure;
- conceptual terminology;
- inferential strength;
- expressive nuance;

the Japanese translation may not preserve every nuance of the English source text.

Where interpretation differs, the English version should be treated as the reference version.

---

## Files

### English

**Inference-Order Failure in Human–AI Dialogue**

Canonical language: English

Current source version:

`Inference_Order_Failure_Revised_v2.pdf`

---

### Japanese

**人間–AI対話における推論順序の失敗**

Subtitle:

**対話的不整合に関する探索的ケーススタディ**

The Japanese version is a translation of the English source text.

Translation status:

**DRAFT / NOT YET REVIEWED**

The Japanese translation should not yet be treated as equivalent to a reviewed publication artifact.

---

## Current Status

### English Version

**Paper:** Paper 03  
**English Title:** Inference-Order Failure in Human–AI Dialogue  
**Subtitle:** An Exploratory Case Study of Conversational Misalignment  
**Canonical Language:** English

### Japanese Translation

**Paper:** Paper 03  
**Japanese Title:** 人間–AI対話における推論順序の失敗  
**English Title:** Inference-Order Failure in Human–AI Dialogue  
**Subtitle:** 対話的不整合に関する探索的ケーススタディ  
**Review Status:** NOT YET REVIEWED  
**Artifact Status:** DRAFT  
**Canonical Language:** English  
**Translation Language:** Japanese

---

## Central Principle

The case can be summarized by the following proposition:

> **Human–AI dialogue fails when the AI becomes precise about an interpretation it has not confirmed.**

Precision is valuable only when it is applied to a sufficiently confirmed premise.

Precision applied to the wrong premise is not understanding.

It is a well-organized detour.
