# 🧠 60 Advanced Conceptual MCQs on Prompt Engineering
_By [Sufyan Abbasi](https://github.com/Sufyan150)_

---

## 📘 Overview
This document contains **60 expert-level multiple-choice questions** designed to test advanced conceptual understanding of **Prompt Engineering**, **LLM reasoning**, **MoE architectures**, and **structured prompting techniques**.  

Difficulty Level: 🔥 Very High  
Focus: Conceptual mastery, not memorization.

Each question has **four options (A–D)** and a detailed **answer key** at the end.

---

## 🧩 Multiple-Choice Questions

1️⃣ **Instructional Locality** refers to:  
A. Random distribution of prompt parts across contexts.  
B. Organizing sub-instructions close to main directives to avoid contextual drift.  
C. Placing commands at the end of the prompt.  
D. Removing local variables to reduce bias.  

---

2️⃣ **Intent Collapse** occurs when:  
A. A model merges multiple unrelated goals into a single vague task.  
B. A prompt has redundant context.  
C. The model refuses an instruction.  
D. The system role overrides user messages.

---

3️⃣ To enforce *stepwise reasoning*, the best structure is:  
A. Ask for “chain-of-thought reasoning.”  
B. Explicitly number the reasoning steps and request outputs for each stage.  
C. Lower the temperature to zero.  
D. Add examples only.

---

4️⃣ **Hallucination** in language models describes:  
A. Intentional creativity in storytelling.  
B. Generation of plausible but incorrect or unverifiable facts.  
C. Token truncation errors.  
D. Missing context window.

---

5️⃣ Failure to define a JSON schema often results in:  
A. Model’s context reset.  
B. Ambiguous field names causing inconsistent structures.  
C. Lower inference speed.  
D. Semantic overfitting.

---

6️⃣ Few-shot examples must:  
A. Be lexically complex.  
B. Represent the desired input-output distribution.  
C. Be identical across tasks.  
D. Be semantically ambiguous.

---

7️⃣ *Self-consistency prompting* improves reasoning by:  
A. Running multiple reasoning chains and selecting the majority outcome.  
B. Lowering temperature to stabilize output.  
C. Reducing prompt length.  
D. Ignoring few-shot examples.

---

8️⃣ Over-specifying constraints in prompts:  
A. Increases creativity.  
B. Reduces diversity and hides novel solutions.  
C. Improves factuality automatically.  
D. Removes hallucination entirely.

---

9️⃣ “You are an expert…” roleplay primarily affects:  
A. Tokenization.  
B. Tone, expertise level, and assumptions.  
C. Inference time.  
D. Grammar accuracy.

---

10️⃣ When debugging missing JSON fields, you should:  
A. Provide explicit schema and sample output.  
B. Lower temperature.  
C. Add irrelevant context.  
D. Switch to system prompts only.

---

11️⃣ *Instructional Primacy* means:  
A. System prompts are ignored.  
B. Early instructions carry higher influence.  
C. The last message always dominates.  
D. Random token prioritization occurs.

---

12️⃣ To mitigate bias in LLMs:  
A. Inject neutrality constraints or adversarial checks in prompts.  
B. Add unrelated data.  
C. Increase model size.  
D. Lower temperature below zero.

---

13️⃣ Chain-of-thought reasoning enhances:  
A. Simple summarization.  
B. Multi-step logical tasks requiring decomposition.  
C. Grammar correction only.  
D. Random creativity.

---

14️⃣ To ground a model’s answers in truth:  
A. Provide factual data in context and instruct the model to cite it.  
B. Use higher temperature.  
C. Request creativity mode.  
D. Disable reasoning.

---

15️⃣ Measuring **consistency** involves:  
A. BLEU score only.  
B. Inter-output agreement across samples.  
C. Counting tokens.  
D. Measuring prompt length.

---

16️⃣ Explicit stepwise prompting can reduce performance when:  
A. The task is intuitive or associative, not logical.  
B. Temperature is too low.  
C. Context is long.  
D. Few-shot examples are missing.

---

17️⃣ **Prompt Chaining** refers to:  
A. Sequencing multiple prompts where one output feeds the next.  
B. Combining prompts into one message.  
C. Randomly repeating prompts.  
D. Encoding tokens.

---

18️⃣ Extraction prompts need:  
A. Ambiguous instructions.  
B. Clear structure, examples, and strict output rules.  
C. High creativity.  
D. Minimal logic.

---

19️⃣ *Prompt Injection* is best mitigated by:  
A. Sanitizing user inputs and isolating system messages.  
B. Removing context.  
C. Adding more examples.  
D. Using higher temperature.

---

20️⃣ Diverse few-shot examples primarily improve:  
A. Randomness.  
B. Generalization to new inputs.  
C. Latency.  
D. Context length.

---

21️⃣ **Red-team prompting** is used to:  
A. Test for harmful outputs and robustness.  
B. Improve summarization.  
C. Enhance creativity.  
D. Debug formatting.

---

22️⃣ *Output Anchoring* means:  
A. Fixing token count.  
B. Giving an example output as a structural reference.  
C. Using long prompts.  
D. Anchoring embeddings only.

---

23️⃣ To improve numeric accuracy:  
A. Provide formulas and ask the model to show work.  
B. Raise temperature.  
C. Use creativity mode.  
D. Add roleplay.

---

24️⃣ Adding citations helps reduce hallucination because:  
A. It narrows the generative space to factual sources.  
B. It extends token length.  
C. It disables reasoning.  
D. It lowers cost.

---

25️⃣ Very low temperature may:  
A. Reduce creativity and trap model in high-probability phrasing.  
B. Increase diversity.  
C. Produce long answers.  
D. Decrease coherence.

---

26️⃣ Reliable code generation requires:  
A. Constraints, input/output examples, and test cases.  
B. Roleplay only.  
C. Zero-shot approach.  
D. High temperature.

---

27️⃣ *Speculative extrapolation* is dangerous when:  
A. Used in safety-critical or factual domains.  
B. Used for fiction.  
C. Context is short.  
D. Chain-of-thought is active.

---

28️⃣ To get structured plans:  
A. Ask for enumerated lists with defined steps.  
B. Use random storytelling.  
C. Request poems.  
D. Omit logic.

---

29️⃣ Ambiguous pronouns cause:  
A. Context truncation.  
B. Misreferenced subjects and wrong assumptions.  
C. Shorter outputs.  
D. Random tone shifts.

---

30️⃣ Robust evaluation includes:  
A. Sampling multiple runs and analyzing metrics.  
B. Visual inspection only.  
C. Longer prompts only.  
D. Ignoring failed outputs.

---

31️⃣ *Counterfactual examples* in few-shot prompting show:  
A. Negative or edge cases the model must avoid.  
B. Redundant content.  
C. Noise.  
D. Random examples.

---

32️⃣ For multilingual outputs:  
A. Provide examples and specify output language explicitly.  
B. Let model auto-detect.  
C. Use English only.  
D. Add random text.

---

33️⃣ System messages serve as:  
A. High-level guardrails with higher priority.  
B. Optional decorative text.  
C. Tokens for randomness.  
D. Bias amplifiers.

---

34️⃣ *Reflection prompting* improves outputs by:  
A. Asking model to critique and refine its own answers.  
B. Reducing context.  
C. Adding examples.  
D. Decreasing temperature.

---

35️⃣ Retrieval-Augmented Generation fails when:  
A. Retrieved sources are irrelevant or outdated.  
B. Model asks questions.  
C. Prompts are long.  
D. Temperature is high.

---

36️⃣ Legal topic prompts should:  
A. Include disclaimers and request informational summaries only.  
B. Request legal decisions.  
C. Omit citations.  
D. Guarantee correctness.

---

37️⃣ To reduce verbosity:  
A. Instruct “Be concise. Use bullet points and essential facts only.”  
B. Raise temperature.  
C. Add examples.  
D. Use longer prompts.

---

38️⃣ Reproducibility improves with:  
A. Low temperature and fixed random seed.  
B. Changing parameters.  
C. Adding creativity.  
D. Increasing diversity.

---

39️⃣ **Memorization** happens when:  
A. Model repeats training data verbatim.  
B. It generates new content.  
C. It reasons logically.  
D. It simplifies answers.

---

40️⃣ Prevent truncation issues by:  
A. Placing core instructions at the beginning of context.  
B. Adding them at the end.  
C. Using random formatting.  
D. Adding images.

---

41️⃣ High cognitive load occurs when:  
A. Prompt includes multiple unrelated tasks.  
B. Task is simple.  
C. Output is short.  
D. Context is minimal.

---

42️⃣ Summarization quality is best measured via:  
A. ROUGE or semantic similarity plus human evaluation.  
B. Word count.  
C. Latency.  
D. Token usage.

---

43️⃣ Use “Assume X is true” when:  
A. Conducting hypothetical reasoning.  
B. Seeking factual reports.  
C. Removing logic.  
D. Avoiding context.

---

44️⃣ To prevent refusals on valid prompts:  
A. Provide benign intent and contextual justification.  
B. Trick model with adversarial input.  
C. Increase randomness.  
D. Remove system prompts.

---

45️⃣ To create tabular outputs:  
A. Request CSV/JSON with example rows.  
B. Use prose.  
C. Avoid format instructions.  
D. Use creative tone.

---

46️⃣ Chain-of-thought increases interpretability by:  
A. Showing intermediate reasoning steps for audit.  
B. Compressing tokens.  
C. Randomizing steps.  
D. Removing logic.

---

47️⃣ To boost factuality:  
A. Retrieve trusted documents and ask model to cite them.  
B. Increase creativity.  
C. Skip context.  
D. Add noise.

---

48️⃣ “Give 3 alternative perspectives” improves:  
A. Reasoning breadth and solution diversity.  
B. Speed.  
C. Token compression.  
D. Determinism.

---

49️⃣ Hallucination detection cue:  
A. Confident tone with unverifiable details.  
B. Repetition.  
C. Slow speed.  
D. Grammar error.

---

50️⃣ Calibration means:  
A. Model’s confidence matches empirical accuracy (70% = ~70% correct).  
B. Always 100% certainty.  
C. Random token control.  
D. Reduced creativity.

---

51️⃣ To reduce formatting errors:  
A. Provide explicit examples or templates.  
B. Keep vague instructions.  
C. Add random context.  
D. Raise temperature.

---

52️⃣ Diagnostic prompts help to:  
A. Identify model weaknesses and sensitivity to phrasing.  
B. Generate fiction.  
C. Increase token usage.  
D. Lower inference time.

---

53️⃣ Iterative prompting is superior because:  
A. It enables incremental refinement and alignment.  
B. It’s faster.  
C. It lowers cost only.  
D. It eliminates bias.

---

54️⃣ **Emergent capability** means:  
A. Abrupt performance increase at scale not explained by smaller models.  
B. Linear growth.  
C. Reduced latency.  
D. Lower entropy.

---

55️⃣ Too many few-shot examples may:  
A. Consume context space and confuse consistency.  
B. Always help.  
C. Reduce variety.  
D. Increase reasoning.

---

56️⃣ *Socratic prompting* technique:  
A. Uses guided questions to elicit reasoning.  
B. Randomly outputs answers.  
C. Increases temperature.  
D. Simplifies task.

---

57️⃣ To reduce repetition:  
A. Encourage alternate phrasing, adjust sampling.  
B. Fix temperature at 0.  
C. Use same prompt again.  
D. Add roleplay.

---

58️⃣ **Ablation** means:  
A. Systematically removing prompt parts to diagnose effect.  
B. Adding more examples.  
C. Using longer prompts.  
D. Random restarts.

---

59️⃣ To follow multi-step procedures effectively:  
A. Decompose into ordered substeps and validate each step.  
B. Use creative instructions.  
C. Provide minimal details.  
D. Remove order.

---

60️⃣ To avoid prompt leakage with user input:  
A. Sanitize inputs before adding to system prompts.  
B. Append raw data directly.  
C. Skip validation.  
D. Allow unescaped input.

---

## 🧾 Answer Key

| Q | Ans | Q | Ans | Q | Ans | Q | Ans |
|--:|:--:|--:|:--:|--:|:--:|--:|:--:|
|1|B|2|A|3|B|4|B|
|5|B|6|B|7|A|8|B|
|9|B|10|A|11|B|12|A|
|13|B|14|A|15|B|16|A|
|17|A|18|B|19|A|20|B|
|21|A|22|B|23|A|24|A|
|25|A|26|A|27|A|28|A|
|29|B|30|A|31|A|32|A|
|33|A|34|A|35|A|36|A|
|37|A|38|A|39|A|40|A|
|41|A|42|A|43|A|44|A|
|45|A|46|A|47|A|48|A|
|49|A|50|A|51|A|52|A|
|53|A|54|A|55|A|56|A|
|57|A|58|A|59|A|60|A|

---

## 💡 Final Advice
> “Don’t memorize — *internalize*.  
Prompt engineering mastery lies in understanding how models reason, not just how they respond.”

---

**Created by [Sufyan Abbasi](https://github.com/Sufyan150)**  
_Open Source for AI Learners Worldwide 🌍_
