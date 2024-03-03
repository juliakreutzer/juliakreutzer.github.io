## About Me
I'm a research scientist at [Cohere for AI](https://cohere.for.ai/), where I conduct research on large language models, centered around multilinguality, reinforcement learning, and evaluation. Previously I worked at [Google Research, Montreal](https://research.google/locations/montreal/), with a focus on [machine translation](https://research.google/research-areas/machine-translation/). Very broadly speaking, I am interested in the **intersection of natural language processing (NLP) and machine learning**, especially where multiple languages come into play.

In my PhD (Heidelberg University, Germany) I investigated how *reinforcement learning* algorithms can be used to turn weak supervision signals from users into meaningful updates for a machine translation system (=RLHF before it was cool).
More recently, I have focused on improving *multilinguality, language diversity and data quality* in machine translation and related applications.

My long-term goal for NLP research is to make it more accessible, along multiple dimensions: 
1. **Underresourced NLP**: Foster research for underresourced languages and by underrepresented groups, such that not only English-speaking users can benefit from the progress we're making in NLP. 
2. **Novices**: Reduce the entry burdens (in terms of coding and research practices)  for novices in the field, especially for new students or researchers from other related areas.
3. **Science outreach**: Get the general public, especially highschool students, more interested in research in machine learning to grow a better understanding of what our current methods look like and where their limitations are.

<!--I host research interns at Google (usually in the summer) and also supervise students externally, and I love collaborating across continents/cultures/disciplines/companies/..., so please drop me an email with details about the collaboration you're looking for and we'll have a chat.-->

## News
- **Feb 2024**: Giving a guest lecture on the Aya project in Siva Reddy's class on [Natural Language Understanding with Deep Learning / Computational Semantics](https://mcgill-nlp.github.io/teaching/comp545-ling782-484-W24/) at McGill. Slides available upon request.
- **Feb 2024**: New preprint about RLHF: ["Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs"](https://cohere.com/research/papers/back-to-basics-revisiting-reinforce-style-optimization-for-learning-from-human-feedback-in-llms-2024-02-23). This work led by Cohere for AI scholar [Arash Ahmadian](https://scholar.google.ca/citations?user=T-xossMAAAAJ&hl=en) scrutinizes the popular PPO algorithm for RLHF in LLMs, and presents effective but simpler alternatives that are grounded in the classic (and basic!) REINFORCE algorithm. Throwback to my PhD topic :)
- **Feb 2024**: [Project Aya](https://cohere.com/research/aya) released its [model](https://huggingface.co/CohereForAI/aya-101) and [data](https://huggingface.co/datasets/CohereForAI/aya_dataset)! Detailed documentation can be found in the preprints ([model](https://cohere.com/research/papers/aya-model-paper-2024-02-13), [data](https://cohere.com/research/papers/aya-dataset-paper-2024-02-13)). This work is the result of a massive open-science collaboration, aiming to build a massively multilingual instruction fine-tuned large language model. My own contributions focus on testing the model for bias, toxicity and harm, and on conducting and comparing human and automatic evaluation of open-ended generation quality.
- **Oct 2023**: Joining the [Cohere for AI](https://cohere.com/research) lab after one year of parental leave.
 
<!--
- **Mar 2021**:
  - *2 accepted papers at AfricaNLP, and one at NAACL-HLT.* Details to come :)  
- **Feb 2021**:
  - [PyData Montreal talk](https://www.meetup.com/PyData-MTL/) about "Learning to translate with JoeyNMT". [Slides](https://www.slideshare.net/juliaaakreutzer/learning-to-translate-with-joey-nmt-243430521) and [recording](https://www.youtube.com/watch?v=RG-yV5zgqjQ) are available. The notebook that was used in the demo is [here](https://github.com/joeynmt/joeynmt/blob/master/joey_demo.ipynb). It trains and evaluates a Transformer on Tatoeba data for a language pair of choice.
- **Jan 2021**: 
  - [MeMentor session](https://mementor.net/#/session/600b178c6e2ab623d88be06c) on NLP Paper Writing. Contact me for the slides.
- **Oct 2020**:
  - *Paper accepted at LoresMT 2020.* We built translation models for small, hand-aligned data for Bambara. Preprint [here](https://arxiv.org/abs/2011.05284).
  - *Paper accepted at COLING 2020.* This one is about building text classification corpora for Kinyarwanda and Kirundi, [as summarized by Andre](https://twitter.com/andre_niyongabo/status/1311719244703297536). Preprint [here](https://arxiv.org/abs/2010.12174).
- **Sep 2020**:
  - *Paper accepted at EMNLP 2020.* Summarizing my internship project at Google, this paper analyses inference strategies for mask-based semi-autoregressive translation. Preprint [here](https://arxiv.org/pdf/2010.02352.pdf).
  - *Paper accepted at EMNLP Findings 2020.* Follow-up on the AfricaNLP paper about the [Masakhane community](https://www.masakhane.io/) and participatory research for low-resource machine translation. Preprint [here](https://arxiv.org/pdf/2010.02353.pdf).
  - My thesis is officially published, you can download it [here](https://doi.org/10.11588/heidok.00028862).
- **Jul 2020**:
  - [Invited talk](https://europe.naverlabs.com/research/seminars/reinforcement-learning-with-human-feedback-for-neural-machine-translation/) at NAVER LABS Europe: "Reinforcement learning with human feedback for neural machine translation".
- **Apr 2020**:
  - *Paper accepted at EAMT 2020.* This paper concludes my PhD thesis and empirically measures the trade-off between (human) feedback strength and model improvement in machine translation. Preprint [here](https://arxiv.org/pdf/2004.11222.pdf).
- **Mar 2020**: 
  - Successfully defended my PhD thesis.
  - *Papers accepted at the AfricaNLP workshop at ICLR.* 
     1. The first paper describes the efforts of the Masakhane community to build machine translation models for as many African languages as possible, by growing and fostering a distributed community of African researchers, students, and computer scientists (and more). Preprint [here](https://arxiv.org/abs/2003.11529). Check out the [Masakhane GitHub repo for the benchmarks](https://github.com/masakhane-io) for details. 
     2. The second paper describes the tuning of Transformer model depth for low-resource machine translation. Preprint [here](https://arxiv.org/pdf/2004.04418).
- **Feb 2020**: I joined the *Google Translate* team in Montreal <3.
- **Jan 2020**: Handed in my *thesis*, finally. 
-->

## Publications
[Google scholar](https://scholar.google.com/citations?hl=en&user=j4cOSzAAAAAJ)

## Code
- [Joey NMT](https://github.com/joeynmt/joeynmt)

## Resources
- [HumanMT: Human feedback for MT from different interfaces](https://www.cl.uni-heidelberg.de/statnlpgroup/humanmt/)
- [Blog post on RL for NMT](https://www.cl.uni-heidelberg.de/statnlpgroup/blog/rl4nmt/)
- [Blog post on Joey NMT](https://www.cl.uni-heidelberg.de/statnlpgroup/blog/joey/)

## Contact
Email: \<lowercase first + last name\>.@cohere.com
