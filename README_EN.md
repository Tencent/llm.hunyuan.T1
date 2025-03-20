# Reasoning Efficiency Redefined! Meet Tencent’s 'Hunyuan-T1'—The First Mamba-Powered Ultra-Large Model

<p align="center"><img src="https://github.com/user-attachments/assets/cb728f58-d29a-4b5a-8047-d97481c6607e" alt="" width="70%"/></p>
<p align="center">  😄 <a href="https://huggingface.co/tencent" target="_blank" rel="noopener noreferrer">huggingface</strong></a>&nbsp&nbsp | &nbsp&nbsp🐧 <a href="https://llm.hunyuan.tencent.com/#/blog/hy-t1/" target="_blank" rel="noopener noreferrer">blog</strong></a>&nbsp&nbsp | &nbsp&nbsp💬 <a href="https://huggingface.co/spaces/tencent/Hunyuan-T1" target="_blank" rel="noopener noreferrer">demo</strong></a>&nbsp&nbsp | &nbsp&nbsp🖥️ <a href="https://cloud.tencent.com/apply/p/i2zophus2x8" target="_blank" rel="noopener noreferrer">api</strong></a></ul>


Reinforcement learning in the post-training phase is increasingly attracting industry attention as it can bring new scaling paradigms. With the release of OpenAI's O-series models and DeepSeek R1, the crucial role that reinforcement learning plays in this process has been further verified.

In mid-February this year, the Hunyuan team launched the Hunyuan T1-Preview (Hunyuan-Thinker-1-Preview) reasoning model, based on the medium-scale Hunyuan foundation, on Tencent Yuanbao APP, bringing users an ultimate and fast deep-thinking experience.

Today, we are very pleased to announce that the deep-thinking model of the Hunyuan large model series has been successfully upgraded to the official version of Hunyuan-T1. This model is based on TurboS, the fast-thinking base, the world's first super-large-scale Hybrid-Transformer-Mamba MoE large model released by us at the beginning of March. Through large-scale post-training, its reasoning ability has been significantly expanded, and it has been further aligned with human preferences.

Compared with the previous T1-preview model, Hunyuan-T1 shows a significant improvement in overall performance. It is a powerful reasoning model that can be compared with DeepSeek R1 and has a significantly faster decoding speed.

Based on TurboS, T1 shows unique advantages in the direction of deep reasoning. TurboS's long-text capture ability helps T1 effectively solve problems such as context loss and long-distance information dependency often encountered in long-text reasoning. Secondly, its Mamba architecture is specifically optimized for processing long sequences. Through an efficient computing method, it can ensure the ability to capture long-text information while significantly reducing the consumption of computing resources, with a decoding speed 2 times faster under the same deployment conditions.

During the model training phase, 96.7% of our computing power was invested in reinforcement learning training, focusing on improving pure reasoning ability and optimizing alignment with human preferences.

We collected world-class science problems covering mathematics, logical reasoning, science, code, etc. These datasets cover everything from basic mathematical reasoning to complex scientific problem-solving. Combined with real feedback from ground-truth, we ensured that the model could demonstrate excellent capabilities when facing various reasoning tasks.

In terms of the training scheme, we adopted the curriculum learning approach to gradually increase the difficulty of the data and expand the model's context length step by step, enabling the model to improve its reasoning ability while learning to use tokens efficiently for reasoning.

Regarding the training strategy, we referred to classic reinforcement learning strategies such as data replay and periodic policy resetting, which significantly improved the long-term stability of model training by over 50%. During the alignment with human preferences phase, we adopted a unified reward system feedback scheme of self-rewarding (based on an early version of T1-preview to comprehensively evaluate and score the model's output) + reward mode, guiding the model to self-improve. The model shows richer content details and more efficient information in its responses.

In addition to achieving comparable or slightly better results than R1 on various public benchmarks such as MMLU-pro, CEval, AIME, ARC-C, Zebra Logic, and other Chinese and English knowledge and competition-level math and logical reasoning indicators, Hunyuan-T1 also performs on par with R1 in internal human evaluation datasets. It has a slight edge in cultural and creative instruction following, text summarization, and agent capabilities.

![企业微信截图_60d86f1b-68c5-494c-bf23-6ce63461d24b.png](/tencent/api/attachments/s3/url?attachmentid=28346863)
![企业微信截图_2a3ed8bc-6847-4e6c-9b4a-55c737165630.png](/tencent/api/attachments/s3/url?attachmentid=28348351)
