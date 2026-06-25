---
title: 'Ziyang Zheng'
date: 2023-10-24
type: landing

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: me
    design:
      show_status: false
      spacing:
        padding: ['0', '0', '6rem', '0']
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: background.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: publication-cards
    content:
      title: Selected Publications
      items:
        - title: "Context Distillation as Latent Memory Management"
          venue: "Under review"
          authors: "**Ziyang Zheng**, Zeju Li, Xiangyu Wen, Jianyuan Zhong, Junhua Huang, Lei Chen, Mingxuan Yuan, and Qiang Xu."
          theme: memory
          image: papers/context-distillation.jpg
          url: https://arxiv.org/abs/2605.28889
        - title: "HMARS: Hierarchical Multi-Agent Long-Context Memory Management System"
          venue: "Under review"
          authors: "Zeju Li, **Ziyang Zheng**, et al."
          theme: agents
        - title: "CASCAD: Circuit-Aware SAT Solving via Learned Conditional Probabilities"
          venue: "Under review"
          authors: "Jiaying Zhu, **Ziyang Zheng**, Zhengyuan Shi, Yalun Cai, and Qiang Xu."
          theme: sat
          image: papers/cascad.jpg
          url: https://arxiv.org/abs/2508.04235
        - title: "TRACE: Learning to Compute on Circuit Graphs"
          venue: "DAC 2026"
          authors: "**Ziyang Zheng**, Jiaying Zhu, Jingyi Zhou, and Qiang Xu."
          theme: graph
          image: papers/trace.jpg
          url: https://arxiv.org/abs/2509.21886
        - title: "Making Slow Thinking Faster: Compressing LLM Chain-of-Thought via Step Entropy"
          venue: "ICLR 2026"
          authors: "Zeju Li, Jianyuan Zhong, **Ziyang Zheng**, Xiangyu Wen, Zhijian Xu, Yingying Cheng, Fan Zhang, and Qiang Xu."
          theme: cot
          image: papers/slow-thinking.jpg
          url: https://arxiv.org/abs/2508.03346
        - title: "Functional Matching of Logic Subgraphs: Beyond Structural Isomorphism"
          venue: "NeurIPS 2025"
          authors: "**Ziyang Zheng**, Kezhi Li, Zhengyuan Shi, and Qiang Xu."
          theme: matching
          image: papers/functional-matching.jpg
          url: https://arxiv.org/abs/2505.21988
        - title: "DeepGate4: Efficient and Effective Representation Learning for Circuit Design at Scale"
          venue: "ICLR 2025"
          authors: "**Ziyang Zheng**, Shan Huang, Jianyuan Zhong, Zhengyuan Shi, Guohao Dai, Ningyi Xu, and Qiang Xu."
          theme: circuit
          image: papers/deepgate4.jpg
          url: https://arxiv.org/abs/2502.01681
        - title: "DeepSeq2: Enhanced Sequential Circuit Learning with Disentangled Representations"
          venue: "ASP-DAC 2025, Best Paper Nomination"
          authors: "Sadaf Khan, Zhengyuan Shi, **Ziyang Zheng**, Min Li, and Qiang Xu."
          theme: sequence
          image: papers/deepseq2.jpg
          url: https://arxiv.org/abs/2411.00530
        - title: "Non-Cross Diffusion for Semantic Consistency"
          venue: "WACV 2025"
          authors: "**Ziyang Zheng**, Ruiyuan Gao, and Qiang Xu."
          theme: diffusion
          image: papers/non-cross-diffusion.jpg
          url: https://arxiv.org/abs/2312.00820
        - title: "DeepGate3: Towards Scalable Circuit Representation Learning"
          venue: "ICCAD 2024"
          authors: "Zhengyuan Shi, **Ziyang Zheng**, Sadaf Khan, Jianyuan Zhong, Min Li, and Qiang Xu."
          theme: gate
          image: papers/deepgate3.jpg
          url: https://arxiv.org/abs/2407.11095
        - title: "GL-Fusion: Global-Local Fusion Network for Multi-view Echocardiogram Video Segmentation"
          venue: "MICCAI 2023"
          authors: "**Ziyang Zheng**, Jiewen Yang, Xinpeng Ding, Xiaowei Xu, and Xiaomeng Li."
          theme: fusion
          image: papers/gl-fusion.jpg
          url: https://arxiv.org/abs/2309.11144
  - block: languages
    content:
      title: Languages
      username: me
---
