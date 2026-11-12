# Research papers

> 71 landmark papers on deep learning, transformers, LLMs, RAG, agents, vision and safety. Every link goes to the paper on arXiv, and titles, authors and years are taken from arXiv itself.

[← Back to the README](README.md)

## If you only read 10

1. [Attention Is All You Need](https://arxiv.org/abs/1706.03762): Vaswani et al., 2017
2. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805): Devlin et al., 2018
3. [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165): Brown et al., 2020
4. [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155): Ouyang et al., 2022
5. [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685): Hu et al., 2021
6. [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401): Lewis et al., 2020
7. [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903): Wei et al., 2022
8. [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629): Yao et al., 2022
9. [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290): Rafailov et al., 2023
10. [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135): Dao et al., 2022

## Foundations of deep learning

- **[Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781)**: Mikolov et al., 2013. Word embeddings that started modern NLP.
- **[Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215)**: Sutskever et al., 2014. Sequence-to-sequence learning with neural networks.
- **[Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)**: Bahdanau et al., 2014. Introduced attention for machine translation.
- **[Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980)**: Kingma et al., 2014. The default optimiser for deep learning.
- **[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167)**: Ioffe et al., 2015. Normalising activations to train deeper networks faster.
- **[Layer Normalization](https://arxiv.org/abs/1607.06450)**: Ba et al., 2016. Layer normalisation, used inside every transformer.
- **[Decoupled Weight Decay Regularization](https://arxiv.org/abs/1711.05101)**: Loshchilov et al., 2017. AdamW: how weight decay should actually be done.
- **[Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)**: He et al., 2015. Residual connections that made very deep networks trainable.
- **[Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)**: Hinton et al., 2015. Knowledge distillation: teach a small model from a big one.
- **[U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)**: Ronneberger et al., 2015. The U-Net, still the backbone of many image models.

## Transformers and large language models

- **[Attention Is All You Need](https://arxiv.org/abs/1706.03762)**: Vaswani et al., 2017. The transformer. Start here.
- **[BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)**: Devlin et al., 2018. Bidirectional pre-training that reshaped NLP.
- **[Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)**: Raffel et al., 2019. T5: every NLP task as text-to-text.
- **[Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)**: Brown et al., 2020. GPT-3 and in-context few-shot learning.
- **[Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361)**: Kaplan et al., 2020. Scaling laws for neural language models.
- **[Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556)**: Hoffmann et al., 2022. Chinchilla: how to balance model size and training data.
- **[RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864)**: Su et al., 2021. Rotary position embeddings (RoPE).
- **[Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity](https://arxiv.org/abs/2101.03961)**: Fedus et al., 2021. Switch Transformers: mixture-of-experts at scale.
- **[LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971)**: Touvron et al., 2023. LLaMA: strong open foundation models.
- **[Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/abs/2307.09288)**: Touvron et al., 2023. Llama 2: open models with a detailed training recipe.
- **[Mistral 7B](https://arxiv.org/abs/2310.06825)**: Jiang et al., 2023. Mistral 7B: efficient small models.
- **[Mixtral of Experts](https://arxiv.org/abs/2401.04088)**: Jiang et al., 2024. Mixtral: a sparse mixture-of-experts model.
- **[Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752)**: Gu et al., 2023. Mamba: state-space models as a transformer alternative.
- **[GPT-4 Technical Report](https://arxiv.org/abs/2303.08774)**: OpenAI et al., 2023. The GPT-4 technical report.
- **[DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948)**: DeepSeek-AI et al., 2025. DeepSeek-R1: reasoning learned through reinforcement learning.
- **[A Survey of Large Language Models](https://arxiv.org/abs/2303.18223)**: Zhao et al., 2023. A broad survey of the LLM landscape.

## Alignment and post-training

- **[Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)**: Schulman et al., 2017. PPO, the workhorse of RLHF.
- **[Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155)**: Ouyang et al., 2022. InstructGPT: aligning models with human feedback.
- **[Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)**: Bai et al., 2022. Constitutional AI: training with written principles.
- **[Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290)**: Rafailov et al., 2023. DPO: preference tuning without a reward model.

## Fine-tuning and efficiency

- **[LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)**: Hu et al., 2021. LoRA: low-rank adapters for cheap fine-tuning.
- **[QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314)**: Dettmers et al., 2023. QLoRA: fine-tune big models on a single GPU.
- **[GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers](https://arxiv.org/abs/2210.17323)**: Frantar et al., 2022. GPTQ: post-training quantisation for LLMs.
- **[AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration](https://arxiv.org/abs/2306.00978)**: Lin et al., 2023. AWQ: activation-aware weight quantisation.
- **[FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135)**: Dao et al., 2022. FlashAttention: fast, memory-efficient exact attention.

## Inference and serving

- **[Efficient Memory Management for Large Language Model Serving with PagedAttention](https://arxiv.org/abs/2309.06180)**: Kwon et al., 2023. PagedAttention and vLLM: efficient KV-cache serving.
- **[Fast Inference from Transformers via Speculative Decoding](https://arxiv.org/abs/2211.17192)**: Leviathan et al., 2022. Speculative decoding for faster generation.

## Retrieval and RAG

- **[Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401)**: Lewis et al., 2020. The original RAG paper.
- **[Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/abs/2004.04906)**: Karpukhin et al., 2020. Dense passage retrieval.
- **[ColBERT: Efficient and Effective Passage Search via Contextualized Late Interaction over BERT](https://arxiv.org/abs/2004.12832)**: Khattab et al., 2020. ColBERT: late-interaction retrieval.
- **[Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://arxiv.org/abs/1908.10084)**: Reimers et al., 2019. Sentence-BERT: sentence embeddings.
- **[Precise Zero-Shot Dense Retrieval without Relevance Labels](https://arxiv.org/abs/2212.10496)**: Gao et al., 2022. HyDE: retrieve with a hypothetical answer.
- **[Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection](https://arxiv.org/abs/2310.11511)**: Asai et al., 2023. Self-RAG: retrieve, generate and critique.
- **[From Local to Global: A Graph RAG Approach to Query-Focused Summarization](https://arxiv.org/abs/2404.16130)**: Edge et al., 2024. GraphRAG: retrieval over knowledge graphs.
- **[Lost in the Middle: How Language Models Use Long Contexts](https://arxiv.org/abs/2307.03172)**: Liu et al., 2023. Why long contexts are not used evenly.

## Reasoning and prompting

- **[Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)**: Wei et al., 2022. Chain-of-thought prompting.
- **[Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171)**: Wang et al., 2022. Self-consistency: sample many reasoning paths.
- **[Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)**: Yao et al., 2023. Tree of Thoughts: deliberate search over reasoning.

## Agents and tool use

- **[ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)**: Yao et al., 2022. ReAct: interleave reasoning and actions.
- **[Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)**: Schick et al., 2023. Toolformer: models that teach themselves to use tools.
- **[Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)**: Park et al., 2023. Generative agents: simulated believable behaviour.
- **[Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291)**: Wang et al., 2023. Voyager: a lifelong-learning agent.
- **[SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)**: Jimenez et al., 2023. SWE-bench: can models resolve real GitHub issues?

## Vision, speech and multimodal

- **[You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)**: Redmon et al., 2015. YOLO: real-time object detection.
- **[Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://arxiv.org/abs/1506.01497)**: Ren et al., 2015. Faster R-CNN: region proposal networks.
- **[An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)**: Dosovitskiy et al., 2020. Vision Transformer (ViT).
- **[Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030)**: Liu et al., 2021. Swin Transformer: hierarchical vision transformers.
- **[Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)**: Radford et al., 2021. CLIP: learning images from natural language.
- **[Segment Anything](https://arxiv.org/abs/2304.02643)**: Kirillov et al., 2023. Segment Anything.
- **[Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)**: Radford et al., 2022. Whisper: robust speech recognition at scale.

## Generative models

- **[Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)**: Goodfellow et al., 2014. Generative adversarial networks.
- **[Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)**: Kingma et al., 2013. Variational autoencoders.
- **[Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)**: Ho et al., 2020. Denoising diffusion probabilistic models.
- **[High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)**: Rombach et al., 2021. Latent diffusion, the basis of Stable Diffusion.

## Reinforcement learning

- **[Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)**: Mnih et al., 2013. Deep Q-networks playing Atari.

## Evaluation and safety

- **[Measuring Massive Multitask Language Understanding](https://arxiv.org/abs/2009.03300)**: Hendrycks et al., 2020. MMLU: broad multitask language understanding.
- **[Holistic Evaluation of Language Models](https://arxiv.org/abs/2211.09110)**: Liang et al., 2022. HELM: holistic evaluation of language models.
- **[Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena](https://arxiv.org/abs/2306.05685)**: Zheng et al., 2023. LLM-as-a-judge and MT-Bench.
- **[Concrete Problems in AI Safety](https://arxiv.org/abs/1606.06565)**: Amodei et al., 2016. Concrete problems in AI safety.
- **[Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)**: Zou et al., 2023. Universal adversarial attacks on aligned models.
- **[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)**: Greshake et al., 2023. Indirect prompt injection in LLM-integrated apps.
