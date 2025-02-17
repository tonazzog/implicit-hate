<strong>An Evaluation of the Tree of Thoughts Prompting Strategy for Implicit Hate Speech Detection</strong>

Implicit hate speech detection is a significant challenge in natural language processing. While large language models have demonstrated success in explicit hate speech detection, their effectiveness in identifying implicit hate speech is still an open question. In this study, we explore the application of the Tree of Thoughts (ToT) prompting strategy to improve LLM performance in detecting implicit hate speech. We conducted three experiments using Mistral LLM: (1) integrating ToT into prompting, (2) implementing a graph-based solution aligned with ToT methodology, and (3) optimizing prompts with the DSPY library. Our results indicate that ToT strategies improve binary classification performance compared to baseline models. However, for fine-grained classification and target identification, ToT introduces complexity that sometimes reduces accuracy. Optimized prompting, combining ToT with fine-tuned examples, gives the best performance in all tasks. A qualitative analysis highlights that the model frequently relies on linguistic cues, struggling to go beyond the literal meaning, and shows bias in the classification of target groups. 


[Paper](https://github.com/tonazzog/implicit-hate/blob/main/Project_NLP_SocialMedia_Tonazzo_5216819.pdf)


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tonazzog/implicit-hate/HEAD)
