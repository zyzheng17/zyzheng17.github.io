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
        - title: "Context Distillation with Latent Memory Management"
          venue: "Under review"
          authors: "Ziyang Zheng and collaborators."
          theme: memory
          status: Under review
        - title: "HMARS: Hierarchical Multi-Agent Long-Context Memory Management System"
          venue: "Under review"
          authors: "Zhe Li, Ziyang Zheng, and collaborators."
          theme: agents
          status: Under review
        - title: "CASCAD: Circuit-Aware SAT Solving via Learned Conditional Probabilities"
          venue: "Under review"
          authors: "Jiaqi Zhu*, Ziyang Zheng*, and collaborators."
          theme: sat
          status: Under review
        - title: "TRACE: Learning to Compute on Graphs"
          venue: "DAC 2026"
          authors: "Ziyang Zheng*, Jiaqi Zhu*, Jiaming Zhou, and collaborators."
          theme: graph
        - title: "Making Slow Thinking Faster: Compressing LLM Chain-of-Thought via Step Entropy"
          venue: "ICLR 2026"
          authors: "Zhe Li, Jianyuan Zhong, Ziyang Zheng, and collaborators."
          theme: cot
        - title: "Functional Matching of Logic Subgraphs: Beyond Structural Isomorphism"
          venue: "NeurIPS 2025"
          authors: "Ziyang Zheng, Kezhi Li, Zhengyuan Shi, and Qiang Xu."
          theme: matching
        - title: "DeepGate4: Efficient and Effective Representation Learning for Circuit Design at Scale"
          venue: "ICLR 2025"
          authors: "Ziyang Zheng, Shan Huang, Jianyuan Zhong, Zhengyuan Shi, Guohao Dai, Ningyi Xu, and Qiang Xu."
          theme: circuit
        - title: "DeepSeq2: Enhanced Sequential Circuit Learning with Disentangled Representations"
          venue: "ASP-DAC 2025, Best Paper Nomination"
          authors: "Saad Khan, Zhengyuan Shi, Ziyang Zheng, and collaborators."
          theme: sequence
        - title: "Non-Cross Diffusion for Semantic Consistency"
          venue: "WACV 2025"
          authors: "Ziyang Zheng, Ruiyuan Gao, and Qiang Xu."
          theme: diffusion
        - title: "DeepGate3: Towards Scalable Circuit Representation Learning"
          venue: "ICCAD 2024"
          authors: "Zhengyuan Shi*, Ziyang Zheng*, Saad Khan, Jianyuan Zhong, Min Li, and Qiang Xu."
          theme: gate
        - title: "GL-Fusion: Global-Local Fusion Network for Multi-view Echocardiogram Video Segmentation"
          venue: "MICCAI 2023"
          authors: "Ziyang Zheng*, Jiewen Yang*, Xinpeng Ding, and collaborators."
          theme: fusion
  - block: languages
    content:
      title: Languages
      username: me
---
