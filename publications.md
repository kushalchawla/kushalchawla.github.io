---
layout: page
title: Selected Publications
---

- **Be Selfish, But Wisely: Investigating the Impact of Agent Personality in Mixed-Motive Human-Agent Interactions**  
	**Kushal Chawla, Ian Wu, Yu Rong, Gale Lucas, Jonathan Gratch** <br/>
	<i>**EMNLP 2023**</i> <br/>
	**<a href="https://arxiv.org/pdf/2310.14404.pdf" target="_blank">Paper</a>** <br/>
	<p style="text-align: justify; text-justify: inter-word;">A natural way to design a negotiation dialogue system is via self-play RL: train an agent that learns to maximize its performance by interacting with a simulated user that has been designed to imitate human-human dialogue data. Although this procedure has been adopted in prior work, we find that it results in a fundamentally flawed system that fails to learn the value of compromise in a negotiation, which can often lead to no agreements (i.e., the partner walking away without a deal), ultimately hurting the model’s overall performance. We investigate this observation in the context of DealOrNoDeal task, a multi-issue negotiation over books, hats, and balls. Grounded in negotiation theory from Economics, we modify the training procedure in two novel ways to design agents with diverse personalities and analyze their performance with human partners. We find that although both techniques show promise, a selfish agent, which maximizes its own performance while also avoiding walkaways, performs superior to other variants by implicitly learning to generate value for both itself and the negotiation partner. We discuss the implications of our findings for what it means to be a successful negotiation dialogue system and how these systems should be designed in the future.</p>
	
	<img src="/static/img/selfish_emnlp23.png" alt='no image found' style='width:100%;height:auto'><br />

- **Social Influence Dialogue Systems: A Survey of Datasets and Models For Social Influence Tasks**  
	**Kushal Chawla, Weiyan Shi, Jingwen Zhang, Gale Lucas, Zhou Yu, Jonathan Gratch** <br/>
	<i>**EACL 2023**</i> <br/>
	**<a href="https://aclanthology.org/2023.eacl-main.53.pdf" target="_blank">Paper</a>** <br/>
	<p style="text-align: justify; text-justify: inter-word;">Dialogue systems capable of social influence such as persuasion, negotiation, and therapy, are essential for extending the use of technology to numerous realistic scenarios. However, existing research primarily focuses on either task-oriented or open-domain scenarios, a categorization that has been inadequate for capturing influence skills systematically. There exists no formal definition or category for dialogue systems with these skills and data-driven efforts in this direction are highly limited. In this work, we formally define and introduce the category of social influence dialogue systems that influence users' cognitive and emotional responses, leading to changes in thoughts, opinions, and behaviors through natural conversations. We present a survey of various tasks, datasets, and methods, compiling the progress across seven diverse domains. We discuss the commonalities and differences between the examined systems, identify limitations, and recommend future directions. This study serves as a comprehensive reference for social influence dialogue systems to inspire more dedicated research and discussion in this emerging area.</p>
	
	<img src="/static/img/survey_diag.png" alt='no image found' style='width:60%;height:auto'><br />

- **Opponent Modeling in Negotiation Dialogues by Related Data Adaptation**  
	**Kushal Chawla, Gale Lucas, Jonathan May, Jonathan Gratch** <br/>
	<i>**Findings of NAACL 2022**</i> <br/>
	**<a href="https://aclanthology.org/2022.findings-naacl.50.pdf" target="_blank">Paper</a>, <a href="https://github.com/kushalchawla/opponent-modeling" target="_blank">Code</a>** <br/>
	<p style="text-align: justify; text-justify: inter-word;">Opponent modeling is the task of inferring another party's mental state within the context of social interactions. In a multi-issue negotiation, it involves inferring the relative importance that the opponent assigns to each issue under discussion, which is crucial for finding high-value deals. A practical model for this task needs to infer these priorities of the opponent on the fly based on partial dialogues as input, without needing additional annotations for training. In this work, we propose a ranker for identifying these priorities from negotiation dialogues. The model takes in a partial dialogue as input and predicts the priority order of the opponent. We further devise ways to adapt related data sources for this task to provide more explicit supervision for incorporating the opponent's preferences and offers, as a proxy to relying on granular utterance-level annotations. We show the utility of our proposed approach through extensive experiments based on two dialogue datasets. We find that the proposed data adaptations lead to strong performance in zero-shot and few-shot scenarios. Moreover, they allow the model to perform better than baselines while accessing fewer utterances from the opponent. We release our code to support future work in this direction.</p>
	
	<img src="/static/img/opp_modeling.jpg" alt='no image found' style='width:100%;height:auto'><br />
	
- **Towards Emotion-Aware Agents For Negotiation Dialogues**  
	**Kushal Chawla, Rene Clever, Jaysa Ramirez, Gale Lucas, Jonathan Gratch** <br/>
	**_ACII 2021_** <br/>
	**<a href="https://arxiv.org/pdf/2107.13165.pdf" target="_blank">Paper</a>**<br/>
	<p style="text-align: justify; text-justify: inter-word;">Negotiation is a complex social interaction that encapsulates emotional encounters in human decision-making. Virtual agents that can negotiate with humans are useful in pedagogy and conversational AI. To advance the development of such agents, we explore the prediction of two important subjective goals in a negotiation - outcome satisfaction and partner perception. Specifically, we analyze the extent to which emotion attributes extracted from the negotiation help in the prediction, above and beyond the individual difference variables. We focus on a recent dataset in chat-based negotiations, grounded in a realistic camping scenario. We study three degrees of emotion dimensions - emoticons, lexical, and contextual by leveraging affective lexicons and a state-of-the-art deep learning architecture. Our insights will be helpful in designing adaptive negotiation agents that interact through realistic communication interfaces.</p>
	
- **CaSiNo: A Corpus of Campsite Negotiation Dialogues for Automatic Negotiation Systems**
	**Kushal Chawla, Jaysa Ramirez, Rene Clever, Gale Lucas, Jonathan May, Jonathan Gratch** <br/>
	**_NAACL 2021_** <br/>
	**<a href="https://www.aclweb.org/anthology/2021.naacl-main.254.pdf" target="_blank">Paper</a>, <a href="https://huggingface.co/datasets/casino" target="_blank">Dataset</a>** <br/>
	<p style="text-align: justify; text-justify: inter-word;">Automated systems that negotiate with humans have broad applications in pedagogy and conversational AI. To advance the development of practical negotiation systems, we present CaSiNo: a novel corpus of over a thousand negotiation dialogues in English. Participants take the role of campsite neighbors and negotiate for food, water, and firewood packages for their upcoming trip. Our design results in diverse and linguistically rich negotiations while maintaining a tractable, closed-domain environment. Inspired by the literature in human-human negotiations, we annotate persuasion strategies and perform correlation analysis to understand how the dialogue behaviors are associated with the negotiation performance. We further propose and evaluate a multi-task framework to recognize these strategies in a given utterance. We find that multi-task learning substantially improves the performance for all strategy labels, especially for the ones that are the most skewed. We release the dataset, annotations, and the code to propel future work in human-machine negotiations.</p>
	
	<img src="/static/img/casino.png" alt='no image found' style='width:100%;height:auto'><br />

Browse my <a href="https://scholar.google.co.in/citations?user=x4rFCskAAAAJ&hl=en" target="_blank">Google Scholar profile</a> or my <a href="https://kushalchawla.github.io/resume/" target="_blank">Resume</a> for a complete publication list.
<br />
