# Shopping-Agent-Eval

A framework for evaluating open-ended responses from AI shopping assistants
where no single ground-truth answer exists.

## Overview

Generative AI shopping assistants can produce multiple valid responses
for the same user request, making traditional exact-match evaluation difficult.

This project explores how to evaluate the quality of these responses
and how such evaluation can be automated and used to compare different
models or system versions.

## Week 1: Response Analysis

The first phase focuses on observing how different LLMs respond to
the same shopping scenarios before defining a formal evaluation framework.

### Goals

1. Define controlled shopping scenarios using synthetic product and user data.
2. Generate responses from multiple LLMs using identical inputs.
3. Compare differences between model responses.
4. Identify abnormal, low-quality, or ambiguous responses.
5. Use other LLMs to critique these responses and suggest improvements.
6. Analyze recurring response-quality issues.

## Current Scope

The initial experiments focus on shopping decision-support tasks such as:

- Product recommendation
- Product comparison
- Purchase decision support

Order management, payment, cancellation, and other transactional tasks
are currently outside the scope.

## Future Work

- Define response quality dimensions based on prior research.
- Develop an evaluation rubric for shopping-assistant responses.
- Build a human-labeled evaluation set.
- Develop and validate an LLM-as-a-Judge evaluator.
- Evaluate critical failures and response-quality stability.
- Compare different models, prompts, and system versions.
