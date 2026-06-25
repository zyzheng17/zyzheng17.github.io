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
        filename: banner.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: timeline-cards
    content:
      title: Education
      items:
        - role: Ph.D. Candidate, Computer Science and Engineering
          org: The Chinese University of Hong Kong
          date: "August 2023 -- Present"
          summary: |
            Advisor: Prof. Qiang Xu.
        - role: Bachelor, Mathematical Sciences
          org: Harbin Institute of Technology (Shenzhen)
          date: "July 2019 -- June 2023"
          summary: |
            Major in Data Science within the Mathematics discipline.

            - Rank: 2/64
            - China National Scholarship, 2021
  - block: timeline-cards
    content:
      title: Internships
      items:
        - role: Research Intern
          org: Noah's Ark Lab, Huawei, Hong Kong
          date: "December 2025 -- Present"
          summary: |
            Research on self-distillation and on-policy distillation for efficient model reasoning and deployment.
  - block: timeline-cards
    content:
      title: Research Experience
      items:
        - role: LLM Compression, Self-Distillation, and On-Policy Distillation
          org: CURE Lab, CUHK
          date: "2025 -- Present"
          summary: |
            I work on compressing LLM reasoning processes and managing long-context memory, including step-entropy-based chain-of-thought compression, latent memory management, hierarchical multi-agent memory systems, and on-policy distillation.
        - role: Computational Graphs, Optimization, and Neural Reasoning
          org: CURE Lab, CUHK
          date: "2024 -- Present"
          summary: |
            I work on scalable circuit representation learning, functional matching of logic subgraphs, SAT-oriented circuit learning, and learning to compute on circuit graphs.
        - role: Diffusion Models and Semantic Consistency
          org: CURE Lab, CUHK
          date: "2023 -- 2024"
          summary: |
            Research on non-cross diffusion and flow consistency for semantic consistency.
        - role: Multi-modal Video Segmentation and Transfer Learning
          org: Harbin Institute of Technology (Shenzhen)
          date: "2022 -- 2023"
          summary: |
            Research on global-local fusion and graph-driven transfer learning for echocardiogram video segmentation.
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
          authors: "Jiaying Zhu*, **Ziyang Zheng***, Zhengyuan Shi, Yalun Cai, and Qiang Xu."
          theme: sat
          image: papers/cascad.jpg
          url: https://arxiv.org/abs/2508.04235
        - title: "TRACE: Learning to Compute on Circuit Graphs"
          venue: "DAC 2026"
          authors: "**Ziyang Zheng***, Jiaying Zhu*, Jingyi Zhou, and Qiang Xu."
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
          authors: "**Ziyang Zheng***, Ruiyuan Gao, and Qiang Xu."
          theme: diffusion
          image: papers/non-cross-diffusion.jpg
          url: https://arxiv.org/abs/2312.00820
        - title: "DeepGate3: Towards Scalable Circuit Representation Learning"
          venue: "ICCAD 2024"
          authors: "Zhengyuan Shi*, **Ziyang Zheng***, Sadaf Khan, Jianyuan Zhong, Min Li, and Qiang Xu."
          theme: gate
          image: papers/deepgate3.jpg
          url: https://arxiv.org/abs/2407.11095
        - title: "Large Circuit Models: Opportunities and Challenges"
          venue: "Science China Information Sciences, 2024"
          authors: "Lei Chen, Yiqi Chen, Zhufei Chu, Wenji Fang, Tsung-Yi Ho, Ru Huang, Yu Huang, Sadaf Khan, Min Li, Xingquan Li, Yu Li, Yun Liang, Jinwei Liu, Yi Liu, Yibo Lin, Guojie Luo, Hongyang Pan, Zhengyuan Shi, Guangyu Sun, Dimitrios Tsaras, Runsheng Wang, Ziyi Wang, Xinming Wei, Zhiyao Xie, Qiang Xu, Chenhao Xue, Junchi Yan, Jun Yang, Bei Yu, Mingxuan Yuan, Evangeline F. Y. Young, Xuan Zeng, Haoyi Zhang, Zuodong Zhang, Yuxiang Zhao, Hui-Ling Zhen, **Ziyang Zheng**, Binwu Zhu, Keren Zhu, and Sunan Zou."
          theme: circuit
          image: papers/large-circuit-models.jpg
          url: https://arxiv.org/abs/2403.07257
        - title: "GL-Fusion: Global-Local Fusion Network for Multi-view Echocardiogram Video Segmentation"
          venue: "MICCAI 2023"
          authors: "**Ziyang Zheng***, Jiewen Yang*, Xinpeng Ding, Xiaowei Xu, and Xiaomeng Li."
          theme: fusion
          image: papers/gl-fusion.jpg
          url: https://arxiv.org/abs/2309.11144
---
