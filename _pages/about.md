---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div style="max-width: 850px; margin: 0 auto; line-height: 1.7; font-family: 'Georgia', 'Times New Roman', Times, serif;">

<p style="font-size: 1.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-weight: bold; text-align: center;"><em>Surgically making neural networks safe!</em></p>




<h3 style="font-size: 1.1em; font-weight: bold; margin-bottom: 12px; margin-top: 0; color: #000000;">
  About Me
</h3>
<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000;">
  My research addresses one of AI safety's hardest problems: models can think one thing internally while saying another—meaning we can't verify true alignment just by checking outputs
  (<a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/172be8b0b88fc2b4aee74237d43f8c04-Abstract-Conference.html" target="_blank" style="color: #3d7a7a; text-decoration: none;">Rosati et al., 2024</a>).
  This drives my focus on <strong>white-box analysis</strong>: using mechanistic interpretability to see what's actually happening inside models.
</p>

<h3 style="font-size: 1.1em; font-weight: bold; margin-bottom: 12px; margin-top: 24px; color: #000000;">
  Foundation
</h3>
<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000;">
  My work builds on two survey papers: one connecting causal reasoning to ML trustworthiness 
  (<a href="https://arxiv.org/pdf/2307.16851" target="_blank" style="color: #3d7a7a; text-decoration: none;">Chaudhary et al., 2024</a>), 
  and another on mechanistic interpretability 
  (<a href="https://www.jmlr.org/papers/volume26/23-0058/23-0058.pdf" target="_blank" style="color: #3d7a7a; text-decoration: none;">Geiger et al., 2025</a>). 
  Together, these give me a <strong>causal-mechanistic framework</strong> for investigating how models work from the inside out.
</p>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<h3 style="font-size: 1.1em; font-weight: bold; margin-bottom: 12px; margin-top: 0; color: #000000;">
  Key Findings
</h3>

<ul style="font-size: 0.9em; margin-bottom: 16px; line-height: 1.65; color: #000000; padding-left: 18px;">
  <li style="margin-bottom: 6px;">
    <strong>Models can detect when they're being evaluated—and this ability increases with scale</strong>
    (<a href="https://arxiv.org/pdf/2509.13333" target="_blank" style="color: #3d7a7a; text-decoration: none;">Chaudhary et al., 2025</a>). 
    If models behave differently during testing versus deployment, we can't trust safety evaluations.
  </li>
  <li style="margin-bottom: 6px;">
    Models leave distinct attention signatures when generating harmful content—enabling <strong>~95% detection accuracy</strong>
    (<a href="https://arxiv.org/pdf/2505.14300" target="_blank" style="color: #3d7a7a; text-decoration: none;">Chaudhary et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px;">
    Models can reach harmful outputs through <strong>multiple pathways</strong> (SafetyNet, 
    <a href="https://arxiv.org/pdf/2505.14300" target="_blank" style="color: #3d7a7a; text-decoration: none;">Chaudhary et al., 2025</a>). 
    Blocking one route may just cause rerouting.
  </li>
  <li style="margin-bottom: 6px;">
    Models shift information toward final tokens, using punctuation as intermediate storage
    (<a href="https://arxiv.org/pdf/2508.14067?" target="_blank" style="color: #3d7a7a; text-decoration: none;">Chauhan et al., 2025</a>).
  </li>
</ul>

<h3 style="font-size: 1.1em; font-weight: bold; margin-bottom: 12px; margin-top: 24px; color: #000000;">
  Solutions
</h3>

<ul style="font-size: 0.9em; margin-bottom: 16px; line-height: 1.65; color: #000000; padding-left: 18px;">
  <li style="margin-bottom: 6px;">
    Made Chain-of-Thought more faithful 
    (<a href="https://arxiv.org/pdf/2509.13334?" target="_blank" style="color: #3d7a7a; text-decoration: none;">Swaroop et al., 2025</a>) 
    and better calibrated 
    (<a href="https://arxiv.org/pdf/2511.06437" target="_blank" style="color: #3d7a7a; text-decoration: none;">More et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px;">
    Reduced privacy leakage in CoT reasoning 
    (<a href="https://arxiv.org/pdf/2511.07772" target="_blank" style="color: #3d7a7a; text-decoration: none;">Batra et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px;">
    Incorporated alignment constraints into circuit pruning 
    (<a href="https://arxiv.org/pdf/2511.07482" target="_blank" style="color: #3d7a7a; text-decoration: none;">Patel et al., 2025</a>).
  </li>
</ul>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<h3 style="font-size: 1.1em; font-weight: bold; margin-bottom: 12px; margin-top: 0; color: #000000;">
  Current Focus: Model Organisms of Hyperawareness
</h3>

<p style="font-size: 0.95em; margin-bottom: 16px; line-height: 1.65; color: #000000;">
  Can we trust safety evaluations if models know they're being tested? My research shows this awareness is already measurable and scales with capability — creating risk of models that fake alignment during evaluation.
</p>

<p style="font-size: 0.9em; color: #000000;">
  <a href="https://www.lesswrong.com/posts/srEijciwxfWEisYqX/awareness-jailbreaking-revealing-true-alignment-in" style="color: #3d7a7a; text-decoration: none;">Read the full research agenda</a>
</p>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #2c3e50, transparent); margin: 20px 0;"></div>

<h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000;">🔬 Current Research</h3>

<div style="margin-bottom: 30px; display: flex; gap: 20px; align-items: flex-start;">
<img src="images/safetynet.png" 
     style="width: 100px; height: 100px; border: 1px solid #eee; border-radius: 4px; object-fit: contain;">  <div>
    <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
      <a href="https://arxiv.org/abs/2505.14300" style="color: #000000; text-decoration: none; font-family: 'Georgia', 'Times New Roman', Times, serif;">SafetyNet: Detecting Harmful Outputs in LLMs by Modeling and Monitoring Deceptive Behaviors</a>
    </h4>
    <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">Maheep Chaudhary, F. Barez</p>
    <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">Under review</p>
  </div>
</div>

<div style="margin-bottom: 30px; display: flex; gap: 20px; align-items: flex-start;">
  <img src="images/evaluation_awareness.png" alt="Evaluation Awareness Scaling" style="width: 100px; height: 100px; border: 1px solid #eee; border-radius: 4px; object-fit: contain;">
  <div>
    <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
      <a href="https://arxiv.org/abs/2509.13333" style="color: #000000; text-decoration: none;">Evaluation Awareness Scales Predictably in Open-Weights Large Language Models</a>
    </h4>
    <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">Maheep Chaudhary†, I. Su, N. Hooda, N. Shankar, J. Tan, K. Zhu, A. Panda, R. Lagasse, V. Sharma</p>
    <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 Responsible FM Workshop</p>
  </div>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2511.07772" style="color: #000000; text-decoration: none;">SALT: Steering Activations towards Leakage-free Thinking in Chain of Thought</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">S. Batra, P. Tillman, S. Gaggar, S. Kesineni, S. Dev, K. Zhu, A. Panda, Maheep Chaudhary†</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 Responsible FM Workshop</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2511.07482" style="color: #000000; text-decoration: none;">Alignment-Constrained Dynamic Pruning for LLMs: Identifying and Preserving Alignment-Critical Circuits</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">D. Patel, G. Gervacio, D. Raimi, K. Zhu, R. Lagasse, G. Grand, A. Panda, Maheep Chaudhary†</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 Responsible FM Workshop</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2511.06437" style="color: #000000; text-decoration: none;">Optimizing Chain-of-Thought Confidence via Topological and Dirichlet Risk Analysis</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">A. More, A. Zhang, N. Bonilla, A. Vivekan, K. Zhu, P. Sharafoleslami, Maheep Chaudhary†</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 Responsible FM Workshop</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2509.13334" style="color: #000000; text-decoration: none;">FRIT: Using Causal Importance to Improve Chain-of-Thought Faithfulness</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">A. Swaroop, A. Nallani, S. Uboweja, A. Uzdenova, M. Nguyen, K. Zhu, S. Dev, A. Panda, V. Sharma, Maheep Chaudhary†</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 FoRLM Workshop</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2509.18116" style="color: #000000; text-decoration: none;">Amortized Latent Steering: Low-Cost Alternative to Test-Time Optimization</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">N. Egbuna, S. Gaur, S. Dev, A. Panda, Maheep Chaudhary†</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 Efficient Reasoning Workshop</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2509.25238" style="color: #000000; text-decoration: none;">PALADIN: Self-Correcting Language Model Agents to Cure Tool-Failure Cases</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">S. V. Vuddanti, A. Shah, S. K. Chittiprolu, T. Song, S. Dev, K. Zhu, Maheep Chaudhary†</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">arXiv preprint</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2508.15099" style="color: #000000; text-decoration: none;">Hydra: A Modular Architecture for Efficient Long-Context Reasoning</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">S. Chaudhary, D. Patel, Maheep Chaudhary, B. Browning</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 Efficient Reasoning Workshop</p>
</div>


<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2409.04478" style="color: #000000; text-decoration: none;">Evaluating Open-Source Sparse Autoencoders on Disentangling Factual Knowledge in GPT-2 Small</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">Maheep Chaudhary, A. Geiger</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">arXiv preprint</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2508.14067" style="color: #000000; text-decoration: none;">Punctuation and Predicates in Language Models</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">S. Chauhan, Maheep Chaudhary, K. Choy, S. Nellessen, N. Schoots</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">arXiv preprint</p>
</div>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000;">📑 Literature Surveys & Theory</h3>

<div style="margin-bottom: 30px; display: flex; gap: 20px; align-items: flex-start;">
  <img src="images/causal_abstraction.png" alt="Causal Abstraction" style="width: 100px; height: 100px; border: 1px solid #eee; border-radius: 4px; object-fit: contain;">
  <div>
    <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
      <a href="http://jmlr.org/papers/v26/23-0058.html" style="color: #000000; text-decoration: none;">Causal Abstraction: A Theoretical Foundation for Mechanistic Interpretability</a>
    </h4>
    <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">A. Geiger, D. Ibeling, A. Zur, Maheep Chaudhary, S. Chauhan, J. Huang, A. Arora, Z. Wu, N. Goodman, C. Potts, T. Icard</p>
    <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">JMLR 2024</p>
  </div>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2307.16851" style="color: #000000; text-decoration: none;">Towards Trustworthy and Aligned Machine Learning: A Data-centric Survey with Causality Perspectives</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">Maheep Chaudhary*, H. Liu*, H. Wang</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">arXiv preprint</p>
</div>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000;">📚 Additional Publications</h3>


<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://aclanthology.org/2024.emnlp-main.959/" style="color: #000000; text-decoration: none;">MemeCLIP: Leveraging CLIP Representations for Multimodal Meme Classification</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">S. B. Shah, S. Shiwakoti, Maheep Chaudhary, H. Wang</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">EMNLP 2024</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2502.02470" style="color: #000000; text-decoration: none;">Modular Training of Neural Networks aids Interpretability</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">S. Golechha, Maheep Chaudhary, J. Velja, A. Abate, N. Schoots</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">arXiv preprint</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="#" style="color: #000000; text-decoration: none;">An Intelligent Recommendation cum Reminder System</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">R. Saxena, Maheep Chaudhary, C.K. Maurya, S. Prasad</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">ACM IKDD CODS & COMAD 2022</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="#" style="color: #000000; text-decoration: none;">CQFaRAD: Collaborative Query-Answering Framework for a Research Article Dataspace</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">M. Singh, S. Pandey, R. Saxena, Maheep Chaudhary, N. Lal</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">ACM COMPUTE 2021</p>
</div>
<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000;">Background & Recognition</h3>

<p style="font-size: 0.9em; line-height: 1.65; margin-bottom: 15px; color: #34495e;">
Winner of Smart India Hackathon (200K+ participants) and ASEAN-India Hackathon leader across 10+ countries. Mentored 40+ students, selected for UNESCO-India-Africa Program (20+ countries), and reviewer for ICML 2025 and NeurIPS 2024 workshops.
</p>

</div>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

/* Apply Georgia font to all elements */
* {
  font-family: 'Georgia', 'Times New Roman', Times, serif !important;
}

h4 a:hover {
  color: #3498db !important;
}

@media (max-width: 768px) {
  div[style*="max-width: 850px"] {
    padding: 0 15px;
  }
}
</style>
