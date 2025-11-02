## About Me
I'm a senior research scientist at [Cohere for Labs](https://cohere.com/research), where I conduct research on large language models, centered around multilinguality, reinforcement learning, and evaluation. I am also an associate industry member at [MILA](https://mila.quebec/). I am based in Canada, in the suburbs of Montreal. Previously I worked at [Google Translate (Research), Montreal](https://research.google/locations/montreal/), with a focus on [machine translation](https://research.google/research-areas/machine-translation/). Very broadly speaking, I am interested in the **intersection of natural language processing (NLP) and machine learning**, especially where multiple languages come into play. I obtained my PhD from Heidelberg University, Germany, under supervision of [Prof. Stefan Riezler](https://www.cl.uni-heidelberg.de/statnlpgroup/members/riezler/) at the [StatNLP group](https://www.cl.uni-heidelberg.de/statnlpgroup/).

## My Research

### RLHF before it was cool
In my PhD, I investigated how *reinforcement learning* algorithms can be used to turn weak supervision signals from users into meaningful updates for a machine translation system. If you're into RLHF, check out my early works on [learning from simulated human feedback](https://aclanthology.org/P17-1138/) (ACL 2016) - we called it "bandit structured prediction" back then, and [learning from actual user feedback](https://aclanthology.org/N18-3012/) (NAACL 2018) for sequence-to-sequence models. You can find many elements (and challenges) of today's leading RL algorithms there, just at smaller scale and before LLMs and the RLHF branding. A few years later we went [back to these basics](https://aclanthology.org/2024.acl-long.662/) by taking apart PPO and bringing back good old REINFORCE.  

### Accessibility & Inclusion
🎯 My long-term goal for NLP research is to make it more accessible and inclusive, along multiple dimensions: 
1. **Underresourced NLP**: Foster research for underresourced languages and by underrepresented groups, such that not only English-speaking users can benefit from the progress we're making in NLP. I'm particularly interested in helping grassroots communities, such as [Masakhane](https://www.masakhane.io/), grow and mature.
2. **Novices**: Reduce the entry burdens (in terms of coding and research practices) for novices in the field, especially for new students or researchers from other related areas. You can often find me at mentoring events, and I am generally generous with my time when it comes to helping out newcomers find their direction and resources to get started with research. 
3. **Women**: NLP and ML research is still a male-dominated field, and it can be challenging to navigate for gender minorities. It takes time to grow a network of support - and as a woman it often requires finding your own unique path because there are not many footsteps to follow. I am mom of a two toddlers, so if you'd like to connect to chat about balancing family and research, reach out, and I am motivated to make research a more supportive place for young families.

Check out our lab's [scholar program](https://cohere.com/research/scholars-program) (sub-PhD internships, note that I *do not host PhD interns*) and [Grant calls](https://cohere.com/research/grants), these are unique opportunities for getting started with LLM research. Another great point of entry is the [Cohere Labs community](https://cohere.com/research/open-science), our open science initiative.

### Multilinguality
Most leading LLMs today are multilingual, more or less intentionally. I don't see it as optional to evaluate techniques and models across languages, but rather as an obligation for [responsible research](https://arxiv.org/abs/2505.21344) with a global perspective (most critical for [safety](https://aclanthology.org/2025.emnlp-main.800/)). Besides adding one dimension to every evaluation, it is a good reality check for robustness of developed techniques. While multilinguality can seen overwhelming and daunting, it is the perfect opportunity for collaboration, as we can put our global network of researchers into action, e.g. in [data audits](https://aclanthology.org/2022.tacl-1.4/), or for open [LLM](https://aclanthology.org/2024.acl-long.845/) or [data development](https://aclanthology.org/2024.acl-long.620/).

### Evaluation
The faster model development and releases, the more important become evaluations. They represent our compass and proxies to real-world impact. It is incredibly important that we make sure to constantly evolve them, and maintain rigor and the will to look beyond a single score or ranking. I have written about this in two blogposts ([Elo ratings](https://cohere.com/blog/elo-ratings-beyond-arena-style-evaluations), [fair and comprehensive multilingual LLM evaluation practices](https://cohere.com/blog/towards-fair-and-comprehensive-multilingual-and-multicultural-llm-benchmarking)) in collaboration with Singapore, and in a recent COLM paper, where we [draw the connections between LLM and MT evaluations](https://arxiv.org/abs/2504.11829).

⏳ Last updated: 2 Nov 2025. If there's no recent news below, it means I have been too busy with life and research.

## News
- **EMNLP**: I'm very excited to attend EMNLP in person. I'll present our work on [multilingual test-time scaling](https://arxiv.org/abs/2506.20544), [safety beyond English](https://arxiv.org/abs/2505.24119), and the [Multilingual Instruction Shared Task (MIST) at WMT](https://aclanthology.org/2025.wmt-1.23/).
- Two preprints on synthetic data optimization released: We revisit multilingual test-time scaling and synthetic data generation with a generative fusion approach (["Making, not Taking, the Best of N"](https://arxiv.org/abs/2510.00931)), and propose dedicated transformations to shape the input distribution for multilingual LLM training (["The Art of Asking: Multilingual Prompt Optimization for Synthetic Data
"](https://arxiv.org/abs/2510.19806)). Both papers are first-authored by [Cohere Labs scholar program](https://cohere.com/research/scholars-program) graduates.
- Paper on **multilingual LLM evaluation practices** accepted at COLM (["Déjà Vu: Multilingual LLM Evaluation through the Lens of Machine Translation Evaluation"](https://arxiv.org/abs/2504.11829)), a fun collaboration with colleagues from Cohere and former colleagues from Google. We compile a [checklist](https://github.com/CohereLabs/multilingual-llm-evaluation-checklist) to guide multilingual LLM evaluations, and release the [paper's LLM-as-a-judge evaluations](https://huggingface.co/datasets/CohereLabs/deja-vu-pairwise-evals) for better transparency. Check out the [**LLM Journal Club Talk**](https://www.youtube.com/watch?v=jXXRRhQOcbk&themeRefresh=1) about this paper and related evaluation discussions.
- Preprint on **test-time scaling of multilingual LLMs** released, led by Cohere Labs' scholar Ammar Khairi: ["When Life Gives You Samples: The Benefits of Scaling up Inference Compute for Multilingual LLMs"](https://arxiv.org/abs/2506.20544). Taking the perspective of making the most of little compute investments, we propose new sampling and selection strategies for parallel scaling to better handle variance in heterogenous test-time applications from different languages, tasks and domains. 
- Preprint on **training with data markers** released, joint work with colleagues from Cohere and led by Daniel D'souza: ["Treasure Hunt: Real-time Targeting of the Long Tail using Training-Time Markers"](https://arxiv.org/abs/2506.14702). We show that when you tag fine-tuning data with meta-information, it gives you a powerful lever at inference time, e.g. to improve performance on long-tail examples. This work was accepted at NeurIPS 2025!
- Two preprints on **multilingual safety in LLMs** released:
    1. A policy primer on the language gap in LLM safety ["The Multilingual Divide and Its Impact on Global AI Safety"](https://arxiv.org/abs/2505.21344), co-authored with colleagues from Cohere. 
    2. A survey analyzing the research landscape of safety research beyond English ["The State of Multilingual LLM Safety Research: From Measuring the Language Gap to Mitigating It"](https://arxiv.org/abs/2505.24119), led by Yong Zheng. We find that there are substantial gaps between English safety research and safety research for other languages. Check out the paper for ideas how to close this gap.
- Preprint on **crosslingual reasoning** released, led by Yong Zheng, Farid Adilazuarda, Jonibek Mansurov, Ruochen Zhang: ["Crosslingual Reasoning through Test-Time Scaling"
](https://arxiv.org/abs/2505.05408). It turns out English-only reasoning finetuning, in combination with test-time scaling can give surprising benefits for crosslingual applications, but less so on the long tail of languages and domains.
<!-- Check out our [blog post on fair and comprehensive multilingual LLM evaluation practices](https://cohere.com/blog/towards-fair-and-comprehensive-multilingual-and-multicultural-llm-benchmarking), a collaboration with AI Singapore.


- **Oct 2024**: Back at work after parental leave 👶
- **EMNLP 2024**: Three scholar-led projects were accepted at EMNLP! Couldn't be more proud of their achievements, it was an honor mentoring them.
    1. [RLHF Can Speak Many Languages: Unlocking Multilingual Preference Optimization for LLMs](https://cohere.com/research/papers/rlhf-can-speak-many-languages-unlocking-multilingual-preference-optimization-for-llms-2024-07-05) led by John Dang. *What does it take to make preference training multilingual, and how multilingual does it have to be?*
    2. [LLM See, LLM Do: Guiding Data Generation to Target Non-Differentiable Objectives](https://cohere.com/research/papers/llm-see-llm-do-guiding-data-generation-to-target-non-differentiable-objectives-2024-07-05) led by Luísa Shimabucoro. *Which properties do models inherit from their teachers, and can we steer this inheritance?*
    3. [The Multilingual Alignment Prism: Aligning Global and Local Preferences to Reduce Harm](https://cohere.com/research/papers/the-multilingual-alignment-prism-aligning-global-and-local-preferences-to-reduce-harm-2024-06-08) led by Aakanksha. *How do we dinstinguish local vs global relevance for model safety, and how do we make models safer for both?*
- **ACL 2024**: Two papers accepted at ACL.
    1. ["Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs"](https://cohere.com/research/papers/back-to-basics-revisiting-reinforce-style-optimization-for-learning-from-human-feedback-in-llms-2024-02-23) led by Arash Ahmadian. *Do we really need PPO?*
    2. [Critical Learning Periods: Leveraging Early Training Dynamics for Efficient Data Pruning](https://aclanthology.org/2024.findings-acl.560/) led by Everlyn Chimoto. *What do checkpoint comparisons tell us about data importance?*
- **May 2024**: We released Aya23, a multilingual model from the Aya family covering 23 languages. It comes in two sizes (8B and 35B) and outperforms Aya101 and similar competitors. All details in our [tech report](https://arxiv.org/abs/2405.15032).
- **Feb 2024**: Giving a guest lecture on the Aya project in Siva Reddy's class on [Natural Language Understanding with Deep Learning / Computational Semantics](https://mcgill-nlp.github.io/teaching/comp545-ling782-484-W24/) at McGill. Slides available upon request.
- **Feb 2024**: New preprint about RLHF: ["Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs"](https://cohere.com/research/papers/back-to-basics-revisiting-reinforce-style-optimization-for-learning-from-human-feedback-in-llms-2024-02-23). This work led by Cohere for AI scholar [Arash Ahmadian](https://scholar.google.ca/citations?user=T-xossMAAAAJ&hl=en) scrutinizes the popular PPO algorithm for RLHF in LLMs, and presents effective but simpler alternatives that are grounded in the classic (and basic!) REINFORCE algorithm. Throwback to my PhD topic :)
- **Feb 2024**: [Project Aya](https://cohere.com/research/aya) released its [Aya101 model](https://huggingface.co/CohereForAI/aya-101) and [data](https://huggingface.co/datasets/CohereForAI/aya_dataset)! Detailed documentation can be found in the preprints ([model](https://cohere.com/research/papers/aya-model-paper-2024-02-13), [data](https://cohere.com/research/papers/aya-dataset-paper-2024-02-13)). This work is the result of a massive open-science collaboration, aiming to build a massively multilingual instruction fine-tuned large language model. My own contributions focus on testing the model for bias, toxicity and harm, and on conducting and comparing human and automatic evaluation of open-ended generation quality.
-->

## Publications
[Google scholar](https://scholar.google.com/citations?hl=en&user=j4cOSzAAAAAJ)

<!--
## Code
- [Joey NMT](https://github.com/joeynmt/joeynmt)

## Resources
- [HumanMT: Human feedback for MT from different interfaces](https://www.cl.uni-heidelberg.de/statnlpgroup/humanmt/)
- [Blog post on RL for NMT](https://www.cl.uni-heidelberg.de/statnlpgroup/blog/rl4nmt/)
- [Blog post on Joey NMT](https://www.cl.uni-heidelberg.de/statnlpgroup/blog/joey/)

-->

## Contact
Email: \<lowercase first + last name\>.@cohere.com
