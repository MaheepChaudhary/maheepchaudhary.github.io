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

<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000;">
  <strong>About me:</strong>
  My research aims to solve one of AI safety's most challenging problems: models can harbor misaligned reasoning internally while producing benign outputs, rendering black-box evaluation fundamentally insufficient 
  (<a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/172be8b0b88fc2b4aee74237d43f8c04-Abstract-Conference.html" target="_blank" style="color: #0000EE; text-decoration: none;">Rosati et al., 2024</a>).
  This conviction drives my focus on white-box analysis, specifically using <em>mechanistic interpretability</em> techniques to expose the internal computations that black-box methods cannot reach.
</p>

<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000;">
  <strong>My Foundation:</strong>
  My theoretical foundation lies in two survey works connecting causality to ML trustworthiness 
  (<a href="https://arxiv.org/pdf/2307.16851" target="_blank" style="color: #0000EE; text-decoration: none;">Chaudhary et al., 2024</a>) 
  and mechanistic interpretability 
  (<a href="https://www.jmlr.org/papers/volume26/23-0058/23-0058.pdf" target="_blank" style="color: #0000EE; text-decoration: none;">Geiger et al., 2025</a>), 
  which frame my empirical investigations through the lens of causal intervention.
</p>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000;">
  <strong>My Findings:</strong>
  Building on this foundation, my diagnostic work has uncovered concerning patterns. In the past, using white-box analysis I was successful in finding:
</p>

<ul style="font-size: 0.9em; margin-bottom: 16px; line-height: 1.65; color: #000000; padding-left: 18px;">
  <li style="margin-bottom: 6px;">
    Models' ability to detect that they are being evaluated increases as they get bigger—suggesting that standard evaluation protocols may become fundamentally unreliable for AGI-level systems, hinting that there might be no way of evaluating AGI-level models before releasing 
    (<a href="https://arxiv.org/pdf/2509.13333" target="_blank" style="color: #0000EE; text-decoration: none;">Chaudhary et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px;">
    Models leave distinct signatures in attention patterns when generating harmful content—achieving around 95% accuracy in detecting harmful generation across models 
    (<a href="https://arxiv.org/pdf/2505.14300" target="_blank" style="color: #0000EE; text-decoration: none;">Chaudhary et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px;">
    Models shift information from left to right and all the way to the last token to store information, while taking support of punctuation and predicates to store information of all tokens, while having higher and lower complexity for different kinds of rules 
    (<a href="https://arxiv.org/pdf/2508.14067?" target="_blank" style="color: #0000EE; text-decoration: none;">Chauhan et al., 2025</a>).
  </li>
</ul>

<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000;">
  <strong>My Solutions:</strong>
  Crucially, my research extends beyond diagnosis to intervention. My research is not only focused on finding problems, but also on making models safer:
</p>

<ul style="font-size: 0.9em; margin-bottom: 16px; line-height: 1.65; color: #000000; padding-left: 18px; font-family: 'Georgia', 'Times New Roman', Times, serif;">
  <li style="margin-bottom: 6px;">
    I made Chain-of-Thought (CoT) more faithful 
    (<a href="https://arxiv.org/pdf/2509.13334?" target="_blank" style="color: #0000EE; text-decoration: none;">Swaroop et al., 2025</a>) 
    and improved its confidence calibration to make it more aligned 
    (<a href="https://arxiv.org/pdf/2511.06437" target="_blank" style="color: #0000EE; text-decoration: none;">More et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px;">
    I developed techniques to reduce privacy leakage in CoT 
    (<a href="https://arxiv.org/pdf/2511.07772" target="_blank" style="color: #0000EE; text-decoration: none;">Batra et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px;">
    I incorporated alignment constraints into pruning circuits to preserve the safety of the model 
    (<a href="https://arxiv.org/pdf/2511.07482" target="_blank" style="color: #0000EE; text-decoration: none;">Patel et al., 2025</a>).
  </li>
</ul>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000;">
  <strong>Future Steps:</strong>
  Looking forward, I am investigating jailbreaking through the lens of decision boundary uncertainty—recent work has shown that LLMs possess an "ethical boundary" in latent space separating safe from harmful representations, and that out-of-distribution inputs weaken this boundary, enabling jailbreaks (Huang et al., 2024). Building on my prior work detecting harmful generation via attention signatures, I aim to develop white-box interventions that identify high-uncertainty regions near safety decision boundaries and constrain the model's access to these vulnerable subspaces during inference. This shifts the paradigm from post-hoc output filtering to preventing models from entering representational states where safety boundaries become unreliable—addressing the core problem that misaligned reasoning can hide beneath benign outputs. Ultimately, this work seeks to make alignment verifiable at the computational level, not just the behavioral one.
</p>

<div style="height: 2px; background: linear-gradient(90deg, transparent, #2c3e50, transparent); margin: 20px 0;"></div>

<h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000;">🔬 Current Research</h3>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2505.14300" style="color: #000000; text-decoration: none; font-family: 'Georgia', 'Times New Roman', Times, serif !import;">SafetyNet: Detecting Harmful Outputs in LLMs by Modeling and Monitoring Deceptive Behaviors</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">Maheep Chaudhary, F. Barez</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">Under review</p>
</div>

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="https://arxiv.org/abs/2509.13333" style="color: #000000; text-decoration: none;">Evaluation Awareness Scales Predictably in Open-Weights Large Language Models</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">Maheep Chaudhary†, I. Su, N. Hooda, N. Shankar, J. Tan, K. Zhu, A. Panda, R. Lagasse, V. Sharma</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">NeurIPS 2025 Responsible FM Workshop</p>
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
    <a href="https://aclanthology.org/2024.emnlp-main.959/" style="color: #000000; text-decoration: none;">MemeCLIP: Leveraging CLIP Representations for Multimodal Meme Classification</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">S. B. Shah, S. Shiwakoti, Maheep Chaudhary, H. Wang</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">EMNLP 2024</p>
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

<div style="margin-bottom: 20px;">
  <h4 style="margin: 0 0 4px 0; font-size: 0.95em; font-weight: normal; color: #000000;">
    <a href="http://jmlr.org/papers/v26/23-0058.html" style="color: #000000; text-decoration: none;">Causal Abstraction: A Theoretical Foundation for Mechanistic Interpretability</a>
  </h4>
  <p style="margin: 0 0 2px 0; font-size: 0.8em; color: #666; font-style: italic;">A. Geiger, D. Ibeling, A. Zur, Maheep Chaudhary, S. Chauhan, J. Huang, A. Arora, Z. Wu, N. Goodman, C. Potts, T. Icard</p>
  <p style="margin: 0; font-size: 0.75em; color: #888; font-style: italic;">JMLR 2024</p>
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
