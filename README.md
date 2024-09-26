# Cultural LLM Research Resources
This is the list of tutorials, workshops, papers, and resources on computational linguistic approaches to cultural research. 
The list will be updated over the time. You are welcome to send a pull request for updating the list and be one of the contributors! 

📌 I plan to collect theses and books on Cultural LLM research and list them here. If you have one, don't hesitate to contact [**Me**](https://www.linkedin.com/in/faridlazuarda/) (Farid) or send a pull request! 

<!-- TODO -->
<!-- sort by year -->
<!-- add other resources (such as datasets, benchmarks, etc.) -->

## 🚀 Highlights
- If you are new on Cultural LLM research or looking for a new research direction, we have written a comprehensive survey paper on Cultural LLM: <b>Towards Measuring and Modeling "Culture" in LLMs: A Survey</b> <a href="https://arxiv.org/pdf/2403.15412.pdf">[Paper]</a>. Feel free to read and let us know if you have any suggestions! Thanks to Sagnik Mukherjee, Pradhyumna Lavania, Siddhant Singh, Ashutosh Dwivedi, Alham Fikri Aji, Jacki O'Neill, Ashutosh Modi, and Monojit Choudhury to make this possible 😊

## ⭐ Citation
If you find this paper and repo helpful for your research, please cite it below:

```bibtex

@misc{adilazuarda2024measuring,
      title={Towards Measuring and Modeling "Culture" in LLMs: A Survey}, 
      author={Muhammad Farid Adilazuarda and Sagnik Mukherjee and Pradhyumna Lavania and Siddhant Singh and Ashutosh Dwivedi and Alham Fikri Aji and Jacki O'Neill and Ashutosh Modi and Monojit Choudhury},
      year={2024},
      eprint={2403.15412},
      archivePrefix={arXiv},
      primaryClass={cs.CY}
}
```

## <span id="head-content"> *Content* </span>
* [1. 🏫 Workshops](#head1)
* [2. 🌳 Culture Taxonomy](#head2)
  * [Taxonomy Based on the Definition of Culture](#head-t2a)
    * [A. Semantic Proxies](#head-t2ai)
    * [B. Demographic Proxies](#head-t2aii)
    * [C. Linguistic-Culture Interaction](#head-t2aiii)
  * [Taxonomy Based on the Methods Used](#head-t2b)
    * [A. Black-Box Approaches](#head-t2bi)
    * [B. White-Box Approaches](#head-t2bii)
* [3. 📚 Books](#head3)


## <span id="head1"> 🏫 Workshops </span>
This is the list of the Cultural LLM workshop series:
-  First Workshop on Cross-Cultural Considerations in NLP (C3NLP), EACL 2023 <a href="https://aclanthology.org/2023.c3nlp-1.0/">[Website]</a>
- Second Workshop on Cross-Cultural Considerations in NLP, ACL 2024 <a href="https://sites.google.com/view/c3nlp">[Website]</a>
- Cultures in AI/AI in Culture, NeurIPS 2022 <a href="https://ai-cultures.github.io/">[Website]</a>


### <span id="head2"> 🌳 Culture Taxonomy in LLM Studies </span>
As defined in Adilazuarda, et al. (2024), we structure this curated list into three distinct taxonomies under the "Culture" umbrella. Note that the taxonomies are based on existing work, is not exhaustive and should not be taken as a roadmap.

Furthermore, “Linguistic culture interaction” and the the proxies defined here are not mutually exclusive. They are different categorizations of how the community approaches studies of culture. For example, Common Ground ( i.e. what information is shared between people amongst a certain culture ) can be studied through the lens of regionality (a demographic proxy) or across religions (another demographic proxy).


### <span id="head-t2a"> 1. Taxonomy Based on the Definition of Culture </span>
<p align="center" width="100%">
<img src="/assets/definition.jpeg" alt="Culture Taxonomy Based on the Definition of Culture" style="height: 500px; width:auto;"/>
</p>

#### <span id="head-t2ai"><u>A. Semantic Proxies</u></span>

#### Emotions and Values
- <b>Hershcovich, et al. (2022)</b> <i>Challenges and Strategies in Cross-Cultural NLP</i>. ACL <a href="https://aclanthology.org/2022.acl-long.482.pdf">[Paper]</a>
- <b>Kovac, et al. (2023)</b> <i>Large Language Models as Superpositions of Cultural Perspectives</i>. ArXiv <a href="https://aclanthology.org/2023.findings-emnlp.892.pdf">[Paper]</a>
- <b>Koto, et al. (2023)</b> <i>Large language models only pass primary school exams in Indonesia: A comprehensive test on IndoMMLU</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.760.pdf">[Paper]</a>
- <b>Wibowo, et al. (2023)</b> <i>COPAL-ID: Indonesian Language Reasoning with Local Culture and Nuances</i>. ArXiv <a href="https://arxiv.org/pdf/2311.01012.pdf">[Paper]</a>
- <b>Cao, et al. (2023)</b> <i>Assessing Cross-Cultural Alignment between ChatGPT and Human Societies: An Empirical Study</i>. Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP)<a href="https://aclanthology.org/2023.c3nlp-1.7.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Wan, et al. (2023)</b> <i>Are personalized stochastic parrots more dangerous? evaluating persona biases in dialogue systems</i>. EMNLP <a href="https://aclanthology.org/2023.findings-emnlp.648.pdf">[Paper]</a>
- <b>Tanmay, et al. (2023)</b> <i>Probing the Moral Development of Large Language Models through Defining Issues Test</i>. ArXiv <a href="https://arxiv.org/pdf/2309.13356.pdf">[Paper]</a>
- <b>Zhang, et al. (2023)</b> <i>The Skipped Beat: A Study of Sociopragmatic Understanding in LLMs for 64 Languages</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.160.pdf">[Paper]</a>
- <b>Tanmay, et al. (2023)</b> <i>The Skipped Beat: A Study of Sociopragmatic Understanding in LLMs for 64 Languages</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.160.pdf">[Paper]</a>
- <b>Shaikh, et al. (2023)</b> <i>Modeling Cross-Cultural Pragmatic Inference with Codenames Duet</i>. ACL Findings <a href="https://aclanthology.org/2023.emnlp-main.160.pdf">[Paper]</a>
- <b>Jiang, et al. (2022)</b> <i>Can Machines Learn Morality? The Delphi Experiment</i>. ArXiv <a href="https://arxiv.org/pdf/2110.07574.pdf">[Paper]</a>
- <b>Talat, et al. (2022)</b> <i>A Word on Machine Ethics: A Response to Jiang et al (2021)</i>. ArXiv <a href="https://arxiv.org/pdf/2111.04158.pdf">[Paper]</a>
- <b>Huang and Yang (2023)</b> <i>Culturally Aware Natural Language Inference</i>. EMNLP Findings <a href="https://aclanthology.org/2023.findings-emnlp.509.pdf">[Paper]</a>
- <b>Naous, et al (2023)</b> <i>Having Beer after Prayer? Measuring Cultural Bias in Large Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2305.14456.pdf">[Paper]</a>
- <b>Wu, et al (2023)</b> <i>Cross-Cultural Analysis of Human Values, Morals, and Biases in Folk Tales</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.311.pdf">[Paper]</a>
- <b>Fung, et al (2023)</b> <i>NORMSAGE: Multi-Lingual Multi-Cultural Norm Discovery from Conversations On-the-Fly</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.941.pdf">[Paper]</a>
- <b>Mukherjee, et al (2023)</b> <i>Global Voices, Local Biases: Socio-Cultural Prejudices across Languages</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.981.pdf">[Paper]</a>
- <b>Santy, et al (2023)</b> <i>NLPositionality: Characterizing Design Biases of Datasets and Models</i>. ACL Main <a href="https://aclanthology.org/2023.acl-long.505v2.pdf">[Paper]</a>

#### Food and Drink
- <b>Palta and Rudinger (2023)</b> <i>FORK: A Bite-Sized Test Set for Probing Culinary Cultural Biases in Commonsense Reasoning Models</i>. ACL Findings <a href="https://aclanthology.org/2023.findings-acl.631.pdf">[Paper]</a>
- <b>Cao, et al (2024)</b> <i>Cultural Adaptation of Recipes</i>. TACL <a href="https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00634/119279/Cultural-Adaptation-of-Recipes">[Paper]</a>


#### Social and Political Relations
- <b>Wang, et al (2024)</b> <i>SeaEval for Multilingual Foundation Models: From Cross-Lingual Alignment to Cultural Reasoning</i>. ArXiv <a href="https://arxiv.org/pdf/2309.04766.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Durmus, et al. (2023)</b> <i>Towards Measuring the Representation of Subjective Global Opinions in Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2306.16388.pdf">[Paper]</a>
- <b>Shaikh, et al. (2023)</b> <i>Modeling Cross-Cultural Pragmatic Inference with Codenames Duet</i>. ACL Findings <a href="https://aclanthology.org/2023.findings-acl.410.pdf">[Paper]</a>
- <b>Bauer, et al. (2023)</b> <i>Social Commonsense for Explanation and Cultural Bias Discovery</i>. EACL Main <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>
- <b>Feng, et al. (2023)</b> <i>From Pretraining Data to Language Models to Downstream Tasks: Tracking the Trails of Political Biases Leading to Unfair NLP Models</i>. ACL <a href="https://aclanthology.org/2023.acl-long.656.pdf">[Paper]</a>


#### Basic Actions and Technology
- <b>Durmus, et al. (2023)</b> <i>Towards Measuring the Representation of Subjective Global Opinions in Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2306.16388.pdf">[Paper]</a>
- <b>Bauer, et al. (2023)</b> <i>Social Commonsense for Explanation and Cultural Bias Discovery</i>. EACL Main <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>

#### Names
- <b>Wu, et al (2023)</b> <i>Cross-Cultural Analysis of Human Values, Morals, and Biases in Folk Tales</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.311.pdf">[Paper]</a>
- <b>Quan, et al (2020)</b> <i>RiSAWOZ: A Large-Scale Multi-Domain Wizard-of-Oz Dataset with Rich Semantic Annotations for Task-Oriented Dialogue Modeling</i>. EMNLP Main <a href="https://aclanthology.org/2020.emnlp-main.67.pdf">[Paper]</a>


#### <span id="head-t2aii"><u>B. Demographic Proxies</u></span>
#### Ethnicity
- <b>Koto, et al. (2023)</b> <i>Large language models only pass primary school exams in Indonesia: A comprehensive test on IndoMMLU</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.760.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Wan, et al. (2023)</b> <i>Are personalized stochastic parrots more dangerous? evaluating persona biases in dialogue systems</i>. EMNLP <a href="https://aclanthology.org/2023.findings-emnlp.648.pdf">[Paper]</a>
- <b>Durmus, et al. (2023)</b> <i>Towards Measuring the Representation of Subjective Global Opinions in Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2306.16388.pdf">[Paper]</a>
- <b>Shaikh, et al. (2023)</b> <i>Modeling Cross-Cultural Pragmatic Inference with Codenames Duet</i>. ACL Findings <a href="https://aclanthology.org/2023.findings-acl.410.pdf">[Paper]</a>
- <b>Bauer, et al. (2023)</b> <i>Social Commonsense for Explanation and Cultural Bias Discovery</i>. EACL Main <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>
- <b>Feng, et al. (2023)</b> <i>From Pretraining Data to Language Models to Downstream Tasks: Tracking the Trails of Political Biases Leading to Unfair NLP Models</i>. ACL <a href="https://aclanthology.org/2023.acl-long.656.pdf">[Paper]</a>


#### Education
- <b>Koto, et al. (2023)</b> <i>Large language models only pass primary school exams in Indonesia: A comprehensive test on IndoMMLU</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.760.pdf">[Paper]</a>
- <b>Quan, et al (2020)</b> <i>RiSAWOZ: A Large-Scale Multi-Domain Wizard-of-Oz Dataset with Rich Semantic Annotations for Task-Oriented Dialogue Modeling</i>. EMNLP Main <a href="https://aclanthology.org/2020.emnlp-main.67.pdf">[Paper]</a>
- <b>Shaikh, et al. (2023)</b> <i>Modeling Cross-Cultural Pragmatic Inference with Codenames Duet</i>. ACL Findings <a href="https://aclanthology.org/2023.findings-acl.410.pdf">[Paper]</a>
- <b>Bauer, et al. (2023)</b> <i>Social Commonsense for Explanation and Cultural Bias Discovery</i>. EACL Main <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>
- <b>Wu, et al (2023)</b> <i>Cross-Cultural Analysis of Human Values, Morals, and Biases in Folk Tales</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.311.pdf">[Paper]</a>
- <b>Santy, et al (2023)</b> <i>NLPositionality: Characterizing Design Biases of Datasets and Models</i>. ACL Main <a href="https://aclanthology.org/2023.acl-long.505v2.pdf">[Paper]</a>


#### Religion
- <b>Koto, et al. (2023)</b> <i>Large language models only pass primary school exams in Indonesia: A comprehensive test on IndoMMLU</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.760.pdf">[Paper]</a>
- <b>Durmus, et al. (2023)</b> <i>Towards Measuring the Representation of Subjective Global Opinions in Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2306.16388.pdf">[Paper]</a>
- <b>Bauer, et al. (2023)</b> <i>Social Commonsense for Explanation and Cultural Bias Discovery</i>. EACL Main <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>
- <b>Das, et al. (2023)</b> <i>Toward Cultural Bias Evaluation Datasets: The Case of Bengali Gender, Religious, and National Identity </i>. Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP) <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>


#### Race
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Durmus, et al. (2023)</b> <i>Towards Measuring the Representation of Subjective Global Opinions in Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2306.16388.pdf">[Paper]</a>


#### Gender
- <b>Cao, et al. (2023)</b> <i>Assessing cross-cultural alignment between ChatGPT and human societies: An empirical study</i>. ACL <a href="https://aclanthology.org/2023.c3nlp-1.7.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Wan, et al. (2023)</b> <i>Are personalized stochastic parrots more dangerous? evaluating persona biases in dialogue systems</i>. EMNLP <a href="https://aclanthology.org/2023.findings-emnlp.648.pdf">[Paper]</a>
- <b>An, et al. (2023)</b> <i>SODAPOP: Open-Ended Discovery of Social Biases in Social Commonsense Reasoning Models</i>. EMNLP <a href="https://aclanthology.org/2023.eacl-main.116.pdf">[Paper]</a>
- <b>Wu, et al (2023)</b> <i>Cross-Cultural Analysis of Human Values, Morals, and Biases in Folk Tales</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.311.pdf">[Paper]</a>



#### Language
- <b>Hershcovich, et al. (2022)</b> <i>Challenges and Strategies in Cross-Cultural NLP</i>. ACL <a href="https://aclanthology.org/2022.acl-long.482.pdf">[Paper]</a>
- <b>Koto, et al. (2023)</b> <i>Large language models only pass primary school exams in Indonesia: A comprehensive test on IndoMMLU</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.760.pdf">[Paper]</a>
- <b>Kovac, et al. (2023)</b> <i>Large Language Models as Superpositions of Cultural Perspectives</i>. ArXiv <a href="https://aclanthology.org/2023.findings-emnlp.892.pdf">[Paper]</a>
- <b>Wibowo, et al. (2023)</b> <i>COPAL-ID: Indonesian Language Reasoning with Local Culture and Nuances</i>. ArXiv <a href="https://arxiv.org/pdf/2311.01012.pdf">[Paper]</a>
- <b>Cao, et al. (2023)</b> <i>Assessing cross-cultural alignment between ChatGPT and human societies: An empirical study</i>. ACL <a href="https://aclanthology.org/2023.c3nlp-1.7.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Tanmay, et al. (2023)</b> <i>Probing the Moral Development of Large Language Models through Defining Issues Test</i>. ArXiv <a href="https://arxiv.org/pdf/2309.13356.pdf">[Paper]</a>
- <b>Huang and Yang (2023)</b> <i>Culturally Aware Natural Language Inference</i>. EMNLP Findings <a href="https://aclanthology.org/2023.findings-emnlp.509.pdf">[Paper]</a>
- <b>Zhang, et al. (2023)</b> <i>The Skipped Beat: A Study of Sociopragmatic Understanding in LLMs for 64 Languages</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.160.pdf">[Paper]</a>
- <b>Kabra, et al. (2023)</b> <i>Multi-lingual and Multi-cultural Figurative Language Understanding</i>. ACL Findings <a href="https://aclanthology.org/2023.findings-acl.525.pdf">[Paper]</a>
- <b>Naous, et al (2023)</b> <i>Having Beer after Prayer? Measuring Cultural Bias in Large Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2305.14456.pdf">[Paper]</a>
- <b>Shaikh, et al. (2023)</b> <i>Modeling Cross-Cultural Pragmatic Inference with Codenames Duet</i>. ACL Findings <a href="https://aclanthology.org/2023.emnlp-main.160.pdf">[Paper]</a>
- <b>Zhou, et al. (2023)</b> <i>Cultural Compass: Predicting Transfer Learning Success in Offensive Language Detection with Cultural Features </i>. EMNLP Findings <a href="https://aclanthology.org/2023.findings-emnlp.845.pdf">[Paper]</a>
- <b>Zhou, et al. (2023)</b> <i>Cultural Compass: Predicting Transfer Learning Success in Offensive Language Detection with Cultural Features </i>. EMNLP Findings <a href="https://aclanthology.org/2023.findings-emnlp.845.pdf">[Paper]</a>
- <b>Mukherjee, et al (2023)</b> <i>Global Voices, Local Biases: Socio-Cultural Prejudices across Languages</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.981.pdf">[Paper]</a>
- <b>CH-Wang, et al (2023)</b> <i>Sociocultural Norm Similarities and Differences via Situational Alignment and Explainable Textual Entailment</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.215.pdf">[Paper]</a>
- <b>Dev, et al (2023)</b> <i>Building Socio-culturally Inclusive Stereotype Resources with Community Engagement</i>. ArXiv <a href="https://arxiv.org/pdf/2307.10514.pdf">[Paper]</a>
- <b>Dev, et al (2023)</b> <i>Building Socio-culturally Inclusive Stereotype Resources with Community Engagement</i>. ArXiv <a href="https://arxiv.org/pdf/2307.10514.pdf">[Paper]</a>
- <b>Khanuja, et al (2023)</b> <i>Evaluating the Diversity, Equity, and Inclusion of NLP Technology: A Case Study for Indian Languages</i>. ArXiv <a href="https://aclanthology.org/2023.findings-eacl.131.pdf">[Paper]</a>
- <b>Santy, et al (2023)</b> <i>NLPositionality: Characterizing Design Biases of Datasets and Models</i>. ACL Main <a href="https://aclanthology.org/2023.acl-long.505v2.pdf">[Paper]</a>
- <b>Das, et al. (2023)</b> <i>Toward Cultural Bias Evaluation Datasets: The Case of Bengali Gender, Religious, and National Identity </i>. Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP) <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>



#### Region
- <b>Seth, et al. (2024)</b> <i>DOSA: A Dataset of Social Artifacts from Different Indian Geographical Subcultures</i>. LREC-COLING <a href="https://aclanthology.org/2024.lrec-main.474/">[Paper]</a>
- <b>Hershcovich, et al. (2022)</b> <i>Challenges and Strategies in Cross-Cultural NLP</i>. ACL <a href="https://aclanthology.org/2022.acl-long.482.pdf">[Paper]</a>
- <b>Koto, et al. (2023)</b> <i>Large language models only pass primary school exams in Indonesia: A comprehensive test on IndoMMLU</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.760.pdf">[Paper]</a>
- <b>Wibowo, et al. (2023)</b> <i>COPAL-ID: Indonesian Language Reasoning with Local Culture and Nuances</i>. ArXiv <a href="https://arxiv.org/pdf/2311.01012.pdf">[Paper]</a>
- <b>Wang, et al (2024)</b> <i>SeaEval for Multilingual Foundation Models: From Cross-Lingual Alignment to Cultural Reasoning</i>. ArXiv <a href="https://arxiv.org/pdf/2309.04766.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Wan, et al. (2023)</b> <i>Are personalized stochastic parrots more dangerous? evaluating persona biases in dialogue systems</i>. EMNLP <a href="https://aclanthology.org/2023.findings-emnlp.648.pdf">[Paper]</a>
- <b>An, et al. (2023)</b> <i>SODAPOP: Open-Ended Discovery of Social Biases in Social Commonsense Reasoning Models</i>. EMNLP <a href="https://aclanthology.org/2023.eacl-main.116.pdf">[Paper]</a>
- <b>Zhang, et al. (2023)</b> <i>The Skipped Beat: A Study of Sociopragmatic Understanding in LLMs for 64 Languages</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.160.pdf">[Paper]</a>
- <b>Durmus, et al. (2023)</b> <i>Towards Measuring the Representation of Subjective Global Opinions in Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2306.16388.pdf">[Paper]</a>
- <b>Jha, et al. (2023)</b> <i>. SeeGULL: A stereotype benchmark with broad geo-cultural coverage leveraging generative models</i>. ACL <a href="https://aclanthology.org/2023.acl-long.548.pdf">[Paper]</a>
- <b>Ramezani and Xu (2023)</b> <i>. Knowledge of cultural moral norms in large language models</i>. ACL <a href="https://aclanthology.org/2023.acl-long.26.pdf">[Paper]</a>
- <b>Kabra, et al. (2023)</b> <i>Multi-lingual and Multi-cultural Figurative Language Understanding</i>. ACL Findings <a href="https://aclanthology.org/2023.findings-acl.525.pdf">[Paper]</a>
- <b>Zhou, et al. (2023)</b> <i>Cultural Compass: Predicting Transfer Learning Success in Offensive Language Detection with Cultural Features </i>. EMNLP Findings <a href="https://aclanthology.org/2023.findings-emnlp.845.pdf">[Paper]</a>
- <b>Mukherjee, et al (2023)</b> <i>Global Voices, Local Biases: Socio-Cultural Prejudices across Languages</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.981.pdf">[Paper]</a>
- <b>CH-Wang, et al (2023)</b> <i>Sociocultural Norm Similarities and Differences via Situational Alignment and Explainable Textual Entailment</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.215.pdf">[Paper]</a>
- <b>Dev, et al (2023)</b> <i>Building Socio-culturally Inclusive Stereotype Resources with Community Engagement</i>. ArXiv <a href="https://arxiv.org/pdf/2307.10514.pdf">[Paper]</a>
- <b>Khanuja, et al (2023)</b> <i>Evaluating the Diversity, Equity, and Inclusion of NLP Technology: A Case Study for Indian Languages</i>. ArXiv <a href="https://aclanthology.org/2023.findings-eacl.131.pdf">[Paper]</a>
- <b>Santy, et al (2023)</b> <i>NLPositionality: Characterizing Design Biases of Datasets and Models</i>. ACL Main <a href="https://aclanthology.org/2023.acl-long.505v2.pdf">[Paper]</a>
- <b>Cao, et al. (2023)</b> <i>Assessing cross-cultural alignment between ChatGPT and human societies: An empirical study</i>. ACL <a href="https://aclanthology.org/2023.c3nlp-1.7.pdf">[Paper]</a>
- <b>Dwivedi, et al. (2023)</b> <i>EtiCor: Corpus for Analyzing LLMs for Etiquettes</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.428.pdf">[Paper]</a>




#### <span id="head-t2aiii"><u>C. Linguistic-Culture Interaction </u></span>
An approach to categorize the study of culture in language technology, as proposed by Hershcovich et al. (2022), defines the interactions between language and culture through three key dimensions:

<p align="center" width="100%">
<img src="/assets/lci_axes.png" alt="Culture Taxonomy Based on the Definition of Culture" style="height: 300px; width:auto;"/>
</p>

1. **Aboutness:** Focuses on culturally relevant topics, showing how interests and interpretations vary across cultures. This impacts sentiment analysis and domain relevance in NLP, highlighting how cultural contexts shape communication content.

2. **Common Ground:** Refers to shared knowledge and assumptions within a culture, affecting language conceptualization and semantic categories (like kinship and spatial relations). It includes the understanding of traditions, social norms, and expected behaviors.

3. **Objectives and Values:** Concerns the goals and ethical principles guiding behavior and communication. This dimension underscores the need for NLP technologies to align with cultural ethics and values, addressing fairness and bias minimization.
#### Aboutness
No studies has been found for this taxon.

#### Common Ground
- <b>Koto, et al. (2023)</b> <i>Large language models only pass primary school exams in Indonesia: A comprehensive test on IndoMMLU</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.760.pdf">[Paper]</a>
- <b>Wibowo, et al. (2023)</b> <i>COPAL-ID: Indonesian Language Reasoning with Local Culture and Nuances</i>. ArXiv <a href="https://arxiv.org/pdf/2311.01012.pdf">[Paper]</a>
- <b>Wang, et al (2024)</b> <i>SeaEval for Multilingual Foundation Models: From Cross-Lingual Alignment to Cultural Reasoning</i>. ArXiv <a href="https://arxiv.org/pdf/2309.04766.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Quan, et al (2020)</b> <i>RiSAWOZ: A Large-Scale Multi-Domain Wizard-of-Oz Dataset with Rich Semantic Annotations for Task-Oriented Dialogue Modeling</i>. EMNLP Main <a href="https://aclanthology.org/2020.emnlp-main.67.pdf">[Paper]</a>
- <b>Zhang, et al. (2023)</b> <i>The Skipped Beat: A Study of Sociopragmatic Understanding in LLMs for 64 Languages</i>. EMNLP <a href="https://aclanthology.org/2023.emnlp-main.160.pdf">[Paper]</a>
- <b>Bauer, et al. (2023)</b> <i>Social Commonsense for Explanation and Cultural Bias Discovery</i>. EACL Main <a href="https://aclanthology.org/2023.eacl-main.271.pdf">[Paper]</a>
- <b>Naous, et al (2023)</b> <i>Having Beer after Prayer? Measuring Cultural Bias in Large Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2305.14456.pdf">[Paper]</a>
- <b>Wu, et al (2023)</b> <i>Cross-Cultural Analysis of Human Values, Morals, and Biases in Folk Tales</i>. EMNLP Main <a href="https://aclanthology.org/2023.emnlp-main.311.pdf">[Paper]</a>
- <b>Nguyen, et al (2023)</b> <i>Extracting Cultural Commonsense Knowledge at Scale</i>. ACM Web Conference <a href="https://dl.acm.org/doi/pdf/10.1145/3543507.3583535">[Paper]</a>
- <b>Huang and Yang (2023)</b> <i>Culturally Aware Natural Language Inference</i>. EMNLP Findings <a href="https://aclanthology.org/2023.findings-emnlp.509.pdf">[Paper]</a>


#### Objectives and Values
- <b>Kovac, et al. (2023)</b> <i>Large Language Models as Superpositions of Cultural Perspectives</i>. ArXiv <a href="https://aclanthology.org/2023.findings-emnlp.892.pdf">[Paper]</a>
- <b>Cao, et al. (2023)</b> <i>Assessing cross-cultural alignment between ChatGPT and human societies: An empirical study</i>. ACL <a href="https://aclanthology.org/2023.c3nlp-1.7.pdf">[Paper]</a>
- <b>Johnson, et al. (2022)</b> <i>The Ghost in the Machine has an American accent: value conflict in GPT-3</i>. ArXiv <a href="https://arxiv.org/pdf/2203.07785.pdf">[Paper]</a>
- <b>Dev, et al (2023)</b> <i>Building Socio-culturally Inclusive Stereotype Resources with Community Engagement</i>. ArXiv <a href="https://arxiv.org/pdf/2307.10514.pdf">[Paper]</a>
- <b>Gupta, et al (2024)</b> <i>Self-Assessment Tests are Unreliable Measures of LLM Personality</i>. ArXiv <a href="https://arxiv.org/pdf/2307.10514.pdf">[Paper]</a>
- <b>Wan, et al. (2023)</b> <i>Are personalized stochastic parrots more dangerous? evaluating persona biases in dialogue systems</i>. EMNLP <a href="https://aclanthology.org/2023.findings-emnlp.648.pdf">[Paper]</a>
- <b>Tanmay, et al. (2023)</b> <i>Probing the Moral Development of Large Language Models through Defining Issues Test</i>. ArXiv <a href="https://arxiv.org/pdf/2309.13356.pdf">[Paper]</a>
- <b>An, et al. (2023)</b> <i>SODAPOP: Open-Ended Discovery of Social Biases in Social Commonsense Reasoning Models</i>. EMNLP <a href="https://aclanthology.org/2023.eacl-main.116.pdf">[Paper]</a>
- <b>Sorensen, et al. (2023)</b> <i>Value Kaleidoscope: Engaging AI with Pluralistic Human Values, Rights, and Duties</i>. ArXiv <a href="https://arxiv.org/pdf/2309.00779.pdf">[Paper]</a>
- <b>Durmus, et al. (2023)</b> <i>Towards Measuring the Representation of Subjective Global Opinions in Language Models</i>. ArXiv <a href="https://arxiv.org/pdf/2306.16388.pdf">[Paper]</a>



### <span id="head-t2b">2. Taxonomy Based on the Methods Used </span>
<p align="center" width="100%">
    <img src="/assets/methods.jpeg" alt="Culture Taxonomy Based on the Methods Used" style="height: 230px; width:auto;"/>
</p>

#### <span id="head-t2bi"> <u> A. Black-box Approaches </u> </span>

#### Generative Probing
- <b>Nadeem, et al. (2021)</b> <i>StereoSet: Measuring stereotypical bias in pretrained language models</i>. ACL <a href="https://aclanthology.org/2021.acl-long.416.pdf">[Paper]</a>
- <b>Nangia, et al. (2020)</b> <i>CrowS-pairs: A challenge dataset for measuring social biases in masked language models</i>. EMNLP <a href="https://aclanthology.org/2020.emnlp-main.154.pdf">[Paper]</a>
- <b>Wan, et al. (2023)</b> <i>Are personalized stochastic parrots more dangerous? evaluating persona biases in dialogue systems</i>. EMNLP <a href="https://aclanthology.org/2023.findings-emnlp.648.pdf">[Paper]</a>
- <b>Jha, et al. (2023)</b> <i>. SeeGULL: A stereotype benchmark with broad geo-cultural coverage leveraging generative models</i>. ACL <a href="https://aclanthology.org/2023.acl-long.548.pdf">[Paper]</a>


#### Discriminative Probing 
- <b>Cao, et al. (2023)</b> <i>Assessing cross-cultural alignment between ChatGPT and human societies: An empirical study</i>. ACL <a href="https://aclanthology.org/2023.c3nlp-1.7.pdf">[Paper]</a>
- <b>Tanmay, et al. (2023)</b> <i>Probing the Moral Development of Large Language Models through Defining Issues Test</i>. ArXiv <a href="https://arxiv.org/pdf/2309.13356.pdf">[Paper]</a>
- <b>Rao, et al. (2023)</b> <i>Ethical reasoning over moral alignment: A case and framework for in-context ethical policies in LLMs</i>. EMNLP <a href="https://aclanthology.org/2023.findings-emnlp.892.pdf">[Paper]</a>
- <b>Kovac, et al. (2023)</b> <i>Large Language Models as Superpositions of Cultural Perspectives</i>. ArXiv <a href="https://aclanthology.org/2023.findings-emnlp.892.pdf">[Paper]</a>


#### <span id="head-t2bii"> <u> B. White-box Approaches </u> </span>
#### Mechanistic Interpretability
- <b>Wichers, et al. (2024)</b> <i>Gradient-Based Language Model Red Teaming</i>. ArXiv <a href="https://arxiv.org/pdf/2401.16656.pdf">[Paper]</a>






---

## <span id="head3"> 📚 Books </span>
- Inglehart, R & C. Welzel. 2005. Modernization, Cultural Change and Democracy: The Human Development Sequence. New York: Cambridge University Press
- David Edmonds (2016). Philosophers Take on the World. Oxford University Press UK.


