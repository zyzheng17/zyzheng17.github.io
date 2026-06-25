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
          authors: "**Zheng Z**, et al."
          theme: memory
          image: papers/context-distillation.jpg
          url: https://arxiv.org/abs/2605.28889
        - title: "HMARS: Hierarchical Multi-Agent Long-Context Memory Management System"
          venue: "Under review"
          authors: "Li Z, **Zheng Z**, et al."
          theme: agents
        - title: "CASCAD: Circuit-Aware SAT Solving via Learned Conditional Probabilities"
          venue: "Under review"
          authors: "Zhu J*, **Zheng Z***, et al."
          theme: sat
          image: papers/cascad.jpg
          url: https://arxiv.org/abs/2508.04235
        - title: "TRACE: Learning to Compute on Graphs"
          venue: "DAC 2026"
          authors: "**Zheng Z***, Zhu J*, Zhou J, et al."
          theme: graph
          image: papers/trace.jpg
          url: https://arxiv.org/abs/2509.21886
        - title: "Making Slow Thinking Faster: Compressing LLM Chain-of-Thought via Step Entropy"
          venue: "ICLR 2026"
          authors: "Li Z, Zhong J, **Zheng Z**, et al."
          theme: cot
          image: papers/slow-thinking.jpg
          url: https://arxiv.org/abs/2508.03346
        - title: "Functional Matching of Logic Subgraphs: Beyond Structural Isomorphism"
          venue: "NeurIPS 2025"
          authors: "**Zheng Z**, Li K, Shi Z, et al."
          theme: matching
          image: papers/functional-matching.jpg
          url: https://arxiv.org/abs/2505.21988
        - title: "DeepGate4: Efficient and Effective Representation Learning for Circuit Design at Scale"
          venue: "ICLR 2025"
          authors: "**Zheng Z**, Huang S, Zhong J, et al."
          theme: circuit
          image: papers/deepgate4.jpg
          url: https://arxiv.org/abs/2502.01681
        - title: "DeepSeq2: Enhanced Sequential Circuit Learning with Disentangled Representations"
          venue: "ASP-DAC 2025, Best Paper Nomination"
          authors: "Khan S, Shi Z, **Zheng Z**, et al."
          theme: sequence
          image: papers/deepseq2.jpg
          url: https://arxiv.org/abs/2411.00530
        - title: "Non-Cross Diffusion for Semantic Consistency"
          venue: "WACV 2025"
          authors: "**Zheng Z***, Gao R, Xu Q."
          theme: diffusion
          image: papers/non-cross-diffusion.jpg
          url: https://arxiv.org/abs/2312.00820
        - title: "DeepGate3: Towards Scalable Circuit Representation Learning"
          venue: "ICCAD 2024"
          authors: "Shi Z*, **Zheng Z***, Khan S, et al."
          theme: gate
          image: papers/deepgate3.jpg
          url: https://arxiv.org/abs/2407.11095
        - title: "GL-Fusion: Global-Local Fusion Network for Multi-view Echocardiogram Video Segmentation"
          venue: "MICCAI 2023"
          authors: "**Zheng Z***, Yang J*, Ding X, et al."
          theme: fusion
          image: papers/gl-fusion.jpg
          url: https://arxiv.org/abs/2309.11144
  - block: languages
    content:
      title: Languages
      username: me
---
