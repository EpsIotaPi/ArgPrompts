# README

## 3 High Dimension

System Prompt：You are an annotator in an argument annotation study. Rate each comment according to the criteria given in each task. Whether or not you agree with the author's position on the issue, do not let it influence your rating.

### Section 1. Cogency

Definition：Consider the premises the author's argument rests on, and how those premises relate to the final conclusion. Are the premises that the argument uses worthy of being believed? Can each of them serve as a reason or evidence relevant to the conclusion the author draws? Taken together, are they enough to support drawing the conclusion?

Guardrails：Cogency turns on the reasoning of the argument itself: even where it is plainly or clumsily put, and even where it does little for the discussion of the issue, it can still be cogent.

- **5** — All premises are worthy of being believed and relevant to the conclusion; taken together, they are enough to support it.
- **4** — Between 5 and 3.
- **3** — Some premises are worthy of being believed and relevant to the conclusion, but others are not worthy of being believed or are irrelevant to it; taken together, the premises provide only limited support for the conclusion.
- **2** — Between 3 and 1.
- **1** — Most premises or the key premises are not worthy of being believed or are irrelevant to the conclusion, and the premises provide almost no support for it; or no premise is offered at all.

---

### Section 2. Effectiveness

Definition：Consider how the rhetoric of the text works on the reader. Is the author's language grammatically correct and clearly worded? Are the wording and tone proportionate to the seriousness of the issue and the setting of the discussion? Does the way the text is written make the author seem trustworthy and sufficiently knowledgeable about the issue? Are the components of the argument organized in a sensible order, with suitable transitions between them? Does the text evoke the reader's emotions in a way that makes the reader more willing to accept the author's argument?

Guardrails：Effectiveness turns on how the writing works on the reader: even where its reasoning is weak, and even where it does little for the discussion of the issue, it can still be effective.

- **5** — The language is clear, the wording and tone are appropriate, and the arrangement is sensible; the author seems trustworthy, and the text evokes the reader's emotions in a way that makes the reader more willing to accept the author's argument.
- **4** — Between 5 and 3.
- **3** — The language is broadly clear, the wording and tone are largely appropriate, and the arrangement is largely sensible; the text neither establishes nor undermines the author's credibility, and it evokes no notable emotions.
- **2** — Between 3 and 1.
- **1** — The language is vague or the structure is disordered, getting in the way of the reader's understanding of the author's meaning; the wording and tone are clearly inappropriate; the text undermines the author's credibility; the emotional appeal backfires, making the reader unwilling to accept the author's argument.

---

### Section 3. Reasonableness

Definition：Consider the role the argument plays in the wider discussion of the issue. Would someone who holds the opposing position consider it legitimate to discuss the issue with these premises and in the way the argument is stated? Does the argument raise opposing views and respond to them adequately? Does it help move the issue toward a resolution?

Guardrails：Reasonableness turns on what the argument contributes to the issue as a whole: even where its reasoning is weak, and even where it is plainly or clumsily put, it can still be reasonable.

- **5** — Even someone who holds the opposing position would consider it legitimate to discuss the issue with these premises and in the way the argument is stated; the argument raises opposing views and responds to them adequately, and it helps move the issue toward a resolution.
- **4** — Between 5 and 3.
- **3** — Someone who holds the opposing position would broadly accept discussing the issue with these premises and in the way the argument is stated; the argument does not raise opposing views, or mentions them without responding to them, and does little to advance the discussion.
- **2** — Between 3 and 1.
- **1** — The argument discusses the issue with clearly illegitimate premises or in a clearly illegitimate way; or it is largely irrelevant to the issue under discussion and does almost nothing to advance the discussion.

## 11 Sub-dimension

System Prompt：You are an annotator in an argument annotation study. Rate each comment according to the criteria given in each task. Whether or not you agree with the author's position on the issue, do not let it influence your rating.

### Section 1. Cogency

#### 1.1 Local Acceptability

Definition：Are the premises of the argument worthy of being believed on rational grounds?

Guardrails：This dimension evaluates only the premises themselves, one by one. Do not consider: whether the premises support the conclusion, whether someone who holds the opposing position would accept these premises, or the credibility of the author as conveyed by the text.

- **5** — All premises are worthy of being believed.
- **4** — Between 5 and 3.
- **3** — Some premises are worthy of being believed, but others are not; or the premises are only barely worthy of being believed.
- **2** — Between 3 and 1.
- **1** — Most premises or the key premises are not worthy of being believed.

#### 1.2 Local Relevance

Definition：Assuming the premises are true, can they all serve as reasons or evidence relevant to the conclusion?

Guardrails：This dimension evaluates only the relation between each premise and the conclusion. Do not consider: whether the premises are worthy of being believed, whether the support for the conclusion is sufficient, or whether the argument advances the discussion of the issue as a whole.

- **5** — All premises can serve as reasons or evidence relevant to the conclusion.
- **4** — Between 5 and 3.
- **3** — Some premises can serve as reasons or evidence relevant to the conclusion, but others are irrelevant to it.
- **2** — Between 3 and 1.
- **1** — Most premises or the key premises are irrelevant to the conclusion.

#### 1.3 Local Sufficiency

Definition：Assuming the premises are true, do they together provide enough support to make it rational to accept the conclusion?

Guardrails：This dimension evaluates only whether the premises together provide enough support for the conclusion. Do not consider: whether the premises are worthy of being believed, whether the argument responds to opposing views, or premises that are irrelevant to the conclusion.

- **5** — The premises together provide enough support to make it rational to accept the conclusion.
- **4** — Between 5 and 3.
- **3** — The premises provide limited support for the conclusion. They support only a weaker conclusion than the one stated. Further important premises are needed.
- **2** — Between 3 and 1.
- **1** — The premises provide almost no support for the conclusion; there is an obvious leap from the premises to the conclusion.

---

### Section 2. Effectiveness

#### 2.1 Credibility

Definition：Does the way that the argument is expressed make the author seem trustworthy and sufficiently knowledgeable about the issue?

Guardrails：This dimension evaluates only the image of the author conveyed by the text. Do not consider: whether the premises themselves are worthy of being believed, whether the language is clear and unambiguous, or whether the wording and tone are appropriate.

- **5** — The text makes the author seem trustworthy and sufficiently knowledgeable about the issue, e.g., by providing concrete sources.
- **4** — Between 5 and 3.
- **3** — The text neither establishes nor undermines the author's credibility.
- **2** — Between 3 and 1.
- **1** — The text undermines the author's credibility, e.g., by revealing the author's misunderstanding of the issue or bias about it.

#### 2.2 Emotional Appeal

Definition：Does the argument evoke the reader's emotions in a way that makes the reader more willing to accept the author's argument?

Guardrails：This dimension evaluates only how the emotions evoked by the text affect the reader's willingness to accept the argument. Do not consider: whether emotions can serve as legitimate reasons for the conclusion, or whether the reader is ultimately persuaded.

- **5** — The text successfully evokes the reader's emotions, making the reader more willing to accept the author's argument.
- **4** — Between 5 and 3.
- **3** — The text evokes no notable emotions, or the emotions it evokes neither increase nor decrease the reader's willingness to accept the argument.
- **2** — Between 3 and 1.
- **1** — The emotional appeal backfires, making the reader more resistant to the author's argument, e.g., through inflammatory or intimidating appeals.

#### 2.3 Clarity

Definition：Is the language of the argument clear, so that the reader can understand exactly what the author claims and how the author argues for it?

Guardrails：This dimension evaluates only whether the language makes the text easy for the reader to understand. Do not consider: whether the wording and tone are appropriate, or whether the structure of the argument and the transitions between its components are sensible.

- **5** — The language is correct, concise, and unambiguous; the reader can understand without doubt what the author claims and how the author argues for it.
- **4** — Between 5 and 3.
- **3** — The reader can broadly understand the author's claim and how the author argues for it, but some language errors, vagueness, or redundancy get in the way of reading.
- **2** — Between 3 and 1.
- **1** — The language is erroneous, convoluted, or ambiguous; the reader has difficulty determining what the author claims or how the author argues for it.

#### 2.4 Appropriateness

Definition：Are the wording and tone of the argument appropriate and proportionate to the seriousness of the issue and the setting of the discussion?

Guardrails：This dimension evaluates only the wording and tone themselves. Do not consider: whether the author seems credible, or whether someone who holds the opposing position would consider the way the argument is stated legitimate.

- **5** — The wording and tone are appropriate and proportionate to the seriousness of the issue and the setting of the discussion.
- **4** — Between 5 and 3.
- **3** — The wording and tone are largely appropriate, but some expressions are inappropriate or out of proportion to the seriousness of the issue or the setting of the discussion.
- **2** — Between 3 and 1.
- **1** — The wording or tone is clearly inappropriate, e.g., insulting or vulgar language, or a flippant treatment of a serious issue.

#### 2.5 Arrangement

Definition：Does the argument organize the issue, premises, conclusion, and other components in a sensible order, with suitable transitions between them?

Guardrails：This dimension evaluates only whether the structure of the argument and the transitions between its components are sensible. Depending on the setting of the discussion, the issue and other components that are already clear may be left implicit. Do not consider: whether the language is clear and unambiguous.

- **5** — The arrangement is sensible, and the transitions between the components are natural.
- **4** — Between 5 and 3.
- **3** — The overall structure is recognizable, but some components are out of order or lack transitions.
- **2** — Between 3 and 1.
- **1** — There is no recognizable structure; premises and conclusion are piled together haphazardly, with no transitions between the components.

---

### Section 3. Reasonableness

#### 3.1 Global Acceptability

Definition：Would someone who holds the opposing position also accept the author discussing the issue with these premises and in this way?

Guardrails：This dimension evaluates only whether someone who holds the opposing position would consider it legitimate to discuss the issue with these premises and in the way the argument is stated, not whether they would agree with the premises or the author's conclusion. Do not consider: whether the premises themselves are worthy of being believed, whether the argument responds adequately to opposing views, or whether the wording and tone themselves are appropriate.

- **5** — Even someone who holds the opposing position would consider it legitimate to discuss the issue with these premises and in the way the argument is stated.
- **4** — Between 5 and 3.
- **3** — Someone who holds the opposing position would consider most premises and the way the argument is stated largely legitimate, but would consider some premises or some aspects of how the argument is stated illegitimate.
- **2** — Between 3 and 1.
- **1** — Someone who holds the opposing position would consider most premises or the key premises illegitimate, or would clearly find the way the argument is stated unacceptable.

#### 3.2 Global Relevance

Definition：Is the argument relevant to the issue under discussion, and does it help move the issue toward a resolution?

Guardrails：This dimension evaluates only the relation between the argument and the issue under discussion. Do not consider: whether the premises are worthy of being believed, whether the premises are relevant to the conclusion, or whether the premises are enough to support the conclusion.

- **5** — The argument stays focused on the core controversy of the issue, and the premises or information it provides substantively advance the discussion.
- **4** — Between 5 and 3.
- **3** — The argument is relevant to the issue under discussion, but touches only on minor or peripheral aspects of it, doing little to advance the discussion.
- **2** — Between 3 and 1.
- **1** — The argument is largely irrelevant to the issue under discussion, or does almost nothing to advance the discussion, e.g., by straying from the topic, merely restating its position, or dwelling on trivial details.

#### 3.3 Global Sufficiency

Definition：Does the argument raise opposing views and respond to them adequately (including implicit responses)?

Guardrails：This dimension evaluates only how the argument responds to opposing views. Do not consider: whether the premises are enough to support the author's conclusion, or whether the argument as a whole advances the discussion.

- **5** — The argument raises opposing views and rebuts them adequately.
- **4** — Between 5 and 3.
- **3** — The argument does not raise opposing views, or mentions them without responding to them.
- **2** — Between 3 and 1.
- **1** — The argument presents or responds to opposing views in an improper way, e.g., by misrepresenting them or by substituting ridicule for substantive rebuttal.
