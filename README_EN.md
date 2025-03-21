# Reasoning Efficiency Redefined! Meet Tencent’s 'Hunyuan-T1'—The First Mamba-Powered Ultra-Large Model

<p align="center"><img src="https://github.com/user-attachments/assets/cb728f58-d29a-4b5a-8047-d97481c6607e" alt="" width="70%"/></p>
<p align="center"> 😄 <a href="https://llm.hunyuan.tencent.com/#/Blog/hy-t1/" target="_blank" rel="noopener noreferrer">blog</strong></a>&nbsp&nbsp | &nbsp&nbsp 🔗  <a href="https://cloud.tencent.com/product/hunyuan" target="_blank" rel="noopener noreferrer">api</strong></a>&nbsp&nbsp | &nbsp&nbsp 📝  <a href="https://cloud.tencent.com/apply/p/jevgtnvuh3" target="_blank" rel="noopener noreferrer">Contact</strong></a> 


Reinforcement learning has pioneered a new Scaling paradigm in the post-training phase of large language models, a breakthrough that is increasingly attracting attention from the industry. With the successive release of OpenAI's O-series models and DeepSeek R1, the excellent performance demonstrated by the models fully proves the crucial role of reinforcement learning in the optimization process

In mid-February this year, the Hunyuan team launched the Hunyuan T1-Preview (Hunyuan-Thinker-1-Preview) reasoning model based on the medium-scale Hunyuan base on the Tencent Yuanbao APP, bringing users an ultimate and rapid in-depth thinking experience.

Today, we are very pleased to announce that the in-depth thinking model of the Hunyuan large model series has been successfully upgraded to the Hunyuan-T1 official version. This model is based on the TurboS fast-thinking base, the world's first ultra-large-scale Hybrid-Transformer-Mamba MoE large model released by us at the beginning of March. Through large-scale post-training, its reasoning ability has been significantly expanded and further aligned with human preferences.

Compared with the previous T1-preview model, Hunyuan-T1 has shown a significant overall performance improvement and is a leading cutting-edge strong reasoning large model in the industry.
Based on TurboS, T1 shows unique advantages in the direction of in-depth reasoning. TurboS's long-text capture ability helps Turbo-S effectively solve the problems of context loss and long-distance information dependence often encountered in long-text reasoning. Secondly, its Mamba architecture specifically optimizes the processing ability of long sequences. Through an efficient computing method, it can ensure the ability to capture long-text information while significantly reducing the consumption of computing resources. Under the same deployment conditions, the decoding speed is 2 times faster.

In the post-training phase of the model, we invested 96.7% of our computing power in reinforcement learning training, focusing on improving pure reasoning ability and optimizing alignment with human preferences.
We collected world science and reasoning problems, covering mathematics/logic reasoning/science/code, etc. These data sets cover everything from basic mathematical reasoning to complex scientific problem solving. Combined with ground-truth real feedback, we ensure that the model can demonstrate excellent capabilities when facing various reasoning tasks.

In terms of training plans, we adopted a curriculum learning approach to gradually increase data difficulty while expanding the model's context length in a step-by-step manner, enabling the model to improve its reasoning ability while learning to use tokens efficiently for reasoning.

Regarding the training strategy, we referred to classic reinforcement learning strategies such as data replay and periodic policy resetting, which significantly improved the long-term stability of model training by over 50%. During the alignment with human preferences phase, we adopted a unified reward system feedback scheme of self-rewarding (based on an early version of T1-preview to comprehensively evaluate and score the model's output) + reward mode, guiding the model to self-improve. The model shows richer content details and more efficient information in its responses.

In addition to achieving comparable or slightly better results than R1 on various public benchmarks such as MMLU-pro, CEval, AIME, ARC-C, Zebra Logic, and other Chinese and English knowledge and competition-level math and logical reasoning indicators, Hunyuan-T1 also performs on par with R1 in internal human evaluation datasets. It has a slight edge in cultural and creative instruction following, text summarization, and agent capabilities.


<p align="center"><img src="https://github.com/user-attachments/assets/f04fef05-6de8-49aa-ac14-df9a755145a9" alt="" width="80%"/></p>
<p align="center"><img src="https://github.com/user-attachments/assets/1c5d1fd8-0ee7-4f96-a1ff-aa4eaea45653" alt="" width="80%"/></p>


<p align="center"><span style="color: #999999; font-size: 9px;">Note: The evaluation metrics of other models in the table are from official evaluation results. For the parts not included in the official evaluation results, they are from the results of the Hunyuan internal evaluation platform.

</span>




<link rel="stylesheet" href="/llm.hunyuan.T1/assets/css/custom-theme.css">


