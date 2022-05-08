---
layout: page
title: Selected Publications
---

- Title: **Opponent Modeling in Negotiation Dialogues by Related Data Adaptation**  
	Authors: Kushal Chawla, Gale Lucas, Jonathan May, Jonathan Gratch <br/>
	Publication Venue: Findings of NAACL 2022 <br/>
	Useful Links: <a href="https://arxiv.org/pdf/2205.00344.pdf" target="_blank">Paper</a>, <a href="https://github.com/kushalchawla/opponent-modeling" target="_blank">Code</a> <br/>
	Abstract: Opponent modeling is the task of inferring another party's mental state within the context of social interactions. In a multi-issue negotiation, it involves inferring the relative importance that the opponent assigns to each issue under discussion, which is crucial for finding high-value deals. A practical model for this task needs to infer these priorities of the opponent on the fly based on partial dialogues as input, without needing additional annotations for training. In this work, we propose a ranker for identifying these priorities from negotiation dialogues. The model takes in a partial dialogue as input and predicts the priority order of the opponent. We further devise ways to adapt related data sources for this task to provide more explicit supervision for incorporating the opponent's preferences and offers, as a proxy to relying on granular utterance-level annotations. We show the utility of our proposed approach through extensive experiments based on two dialogue datasets. We find that the proposed data adaptations lead to strong performance in zero-shot and few-shot scenarios. Moreover, they allow the model to perform better than baselines while accessing fewer utterances from the opponent. We release our code to support future work in this direction.
	
	<img src="/static/img/opp_modeling.jpg" alt='no image found' style='width:100%;height:auto'><br />
	
- Title: **Towards Emotion-Aware Agents For Negotiation Dialogues**  
	Authors: Kushal Chawla, Rene Clever, Jaysa Ramirez, Gale Lucas, Jonathan Gratch <br/>
	Publication Venue: ACII 2021 <br/>
	Useful Links: <a href="https://arxiv.org/pdf/2107.13165.pdf" target="_blank">Paper</a><br/>
	Abstract: Negotiation is a complex social interaction that encapsulates emotional encounters in human decision-making. Virtual agents that can negotiate with humans are useful in pedagogy and conversational AI. To advance the development of such agents, we explore the prediction of two important subjective goals in a negotiation - outcome satisfaction and partner perception. Specifically, we analyze the extent to which emotion attributes extracted from the negotiation help in the prediction, above and beyond the individual difference variables. We focus on a recent dataset in chat-based negotiations, grounded in a realistic camping scenario. We study three degrees of emotion dimensions - emoticons, lexical, and contextual by leveraging affective lexicons and a state-of-the-art deep learning architecture. Our insights will be helpful in designing adaptive negotiation agents that interact through realistic communication interfaces.
	
	<br />
	
- Title: **CaSiNo: A Corpus of Campsite Negotiation Dialogues for Automatic Negotiation Systems**  
	Authors: Kushal Chawla, Jaysa Ramirez, Rene Clever, Gale Lucas, Jonathan May, Jonathan Gratch <br/>
	Publication Venue: NAACL 2021 <br/>
	Useful Links: <a href="https://www.aclweb.org/anthology/2021.naacl-main.254.pdf" target="_blank">Paper</a>, <a href="https://huggingface.co/datasets/casino" target="_blank">Dataset</a> <br/>
	Abstract: Automated systems that negotiate with humans have broad applications in pedagogy and conversational AI. To advance the development of practical negotiation systems, we present CaSiNo: a novel corpus of over a thousand negotiation dialogues in English. Participants take the role of campsite neighbors and negotiate for food, water, and firewood packages for their upcoming trip. Our design results in diverse and linguistically rich negotiations while maintaining a tractable, closed-domain environment. Inspired by the literature in human-human negotiations, we annotate persuasion strategies and perform correlation analysis to understand how the dialogue behaviors are associated with the negotiation performance. We further propose and evaluate a multi-task framework to recognize these strategies in a given utterance. We find that multi-task learning substantially improves the performance for all strategy labels, especially for the ones that are the most skewed. We release the dataset, annotations, and the code to propel future work in human-machine negotiations.
	
	<img src="/static/img/casino.png" alt='no image found' style='width:100%;height:auto'><br />

Browse my <a href="https://scholar.google.co.in/citations?user=x4rFCskAAAAJ&hl=en" target="_blank">Google Scholar profile</a> or my <a href="https://kushalchawla.github.io/resume/" target="_blank">Resume</a> for a complete publication list.
<br />
