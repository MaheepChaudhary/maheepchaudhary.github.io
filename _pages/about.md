---
permalink: /
# title: <p>AI Safety Researcher <span>|</span> Mechanistic Interpretability <span>|</p>
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---




<div style="max-width: 850px; margin: 0 auto; line-height: 1.7; font-family: 'Poppins', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;">

<!-- Enhanced Opening Section
<div style="text-align: center; margin-bottom: 40px; padding: 30px; background: linear-gradient(135deg, rgba(52, 152, 219, 0.05) 0%, rgba(155, 89, 182, 0.05) 100%); border-radius: 20px;">
  <h1 style="font-size: 1.4em; color: #2c3e50; margin: 0 0 15px 0; font-weight: 600; font-family: 'Poppins', sans-serif;">Building Safe AI Through Mechanistic Understanding</h1>
  <div style="width: 60px; height: 3px; background: linear-gradient(90deg, #3498db, #9b59b6); margin: 0 auto 20px auto; border-radius: 2px;"></div>
</div> -->

<!-- Current Work Highlight -->
<!-- <div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 16px; padding: 25px; margin-bottom: 30px; color: white; box-shadow: 0 8px 32px rgba(0,0,0,0.1);">
  <h3 style="margin: 0 0 15px 0; color: white; font-size: 1.2em; font-weight: 600; font-family: 'Poppins', sans-serif;">🔬 Current Research</h3>
  <p style="margin: 0; font-size: 1.05em; line-height: 1.6; opacity: 0.95; font-family: 'Poppins', sans-serif;">Working with <a href="#" style="color: #74b9ff; text-decoration: none; font-weight: 600;">Fazl Barez</a> at <a href="#" style="color: #74b9ff; text-decoration: none; font-weight: 600;">University of Oxford</a> on whitebox monitoring of LLMs, and mentoring research projects at <a href="https://algoverseairesearch.org" style="color: #74b9ff; text-decoration: none; font-weight: 600;">Algoverse</a>.</p>
</div> -->

<p style="font-size: 2em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important; font-weight: bold; font-style: italic; text-align: center;">Surgically making neural networks safe!</p>

<!-- <p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;">I am Maheep, and I am working on "understanding" and "solving" misalignment via using <em style="font-family: 'Times New Roman', Times, serif !important;">mechanistic interpretability</em>. My research is oriented towards whitebox techniques, as models can be thinking evil but can give benign output after the last layer manipulates the latent state towards benign generation—acting as one of the main disadvantages for black-box safety learning \cite{?}.</p>
 -->

<!-- <strong style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;">About me:</strong> -->
<!-- <p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;"> -->
<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
  <strong style="font-family: 'Times New Roman', Times, serif !important;">About me:</strong>
  My research aims to solve one of AI safety's most challenging problems: models can harbor misaligned reasoning internally while producing benign outputs, rendering black-box evaluation fundamentally insufficient 
  (<a href="https://arxiv.org/abs/2409.06052" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Rosati et al., 2024</a>).
  This conviction drives my focus on white-box analysis, specifically using <em style="font-family: 'Times New Roman', Times, serif !important;">mechanistic interpretability</em> techniques to expose the internal computations that black-box methods cannot reach.
</p>

<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
  <strong style="font-family: 'Times New Roman', Times, serif !important;">My Foundation:</strong>
  My theoretical foundation lies in two survey works connecting causality to ML trustworthiness 
  (<a href="https://arxiv.org/abs/2409.15539" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Chaudhary et al., 2024</a>) 
  and mechanistic interpretability 
  (<a href="https://arxiv.org/abs/2503.17049" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Geiger et al., 2025</a>), 
  which frame my empirical investigations through the lens of causal intervention.
</p>

  <div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>


<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
  <strong style="font-family: 'Times New Roman', Times, serif !important;">My Findings:</strong>
  Building on this foundation, my diagnostic work has uncovered concerning patterns. In the past, using white-box analysis I was successful in finding:
</p>

<ul style="font-size: 0.9em; margin-bottom: 16px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important; padding-left: 18px;">
  <li style="margin-bottom: 6px; font-family: 'Times New Roman', Times, serif !important;">
    Models' ability to detect that they are being evaluated increases as they get bigger—suggesting that standard evaluation protocols may become fundamentally unreliable for AGI-level systems, hinting that there might be no way of evaluating AGI-level models before releasing 
    (<a href="https://arxiv.org/abs/2507.15327" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Chaudhary et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px; font-family: 'Times New Roman', Times, serif !important;">
    Models leave distinct signatures in attention patterns when generating harmful content—achieving around 95% accuracy in detecting harmful generation across models 
    (<a href="https://arxiv.org/abs/2507.15327" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Chaudhary et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px; font-family: 'Times New Roman', Times, serif !important;">
    Models shift information from left to right and all the way to the last token to store information, while taking support of punctuation and predicates to store information of all tokens, while having higher and lower complexity for different kinds of rules 
    (<a href="https://arxiv.org/abs/2504.05110" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Chauhan et al., 2025</a>).
  </li>
</ul>

<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
  <strong style="font-family: 'Times New Roman', Times, serif !important;">My Solutions:</strong>
  Crucially, my research extends beyond diagnosis to intervention. My research is not only focused on finding problems, but also on making models safer:
</p>

<ul style="font-size: 0.9em; margin-bottom: 16px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important; padding-left: 18px;">
  <li style="margin-bottom: 6px; font-family: 'Times New Roman', Times, serif !important;">
    I made Chain-of-Thought (CoT) more faithful 
    (<a href="https://arxiv.org/abs/2505.06069" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Swaroop et al., 2025</a>) 
    and improved its confidence calibration to make it more aligned 
    (<a href="https://arxiv.org/abs/2505.06082" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">More et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px; font-family: 'Times New Roman', Times, serif !important;">
    I developed techniques to reduce privacy leakage in CoT 
    (<a href="https://arxiv.org/abs/2505.06062" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Batra et al., 2025</a>).
  </li>
  <li style="margin-bottom: 6px; font-family: 'Times New Roman', Times, serif !important;">
    I incorporated alignment constraints into pruning circuits to preserve the safety of the model 
    (<a href="https://arxiv.org/abs/2505.06079" target="_blank" style="color: #0000EE; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Patel et al., 2025</a>).
  </li>
</ul>

  <div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>


<p style="font-size: 0.9em; margin-bottom: 22px; line-height: 1.65; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
  <strong style="font-family: 'Times New Roman', Times, serif !important;">Future Steps:</strong>
Looking forward, I am investigating jailbreaking through the lens of decision boundary uncertainty—recent work has shown that LLMs possess an "ethical boundary" in latent space separating safe from harmful representations, and that out-of-distribution inputs weaken this boundary, enabling jailbreaks (Huang et al., 2024). Building on my prior work detecting harmful generation via attention signatures, I aim to develop white-box interventions that identify high-uncertainty regions near safety decision boundaries and constrain the model's access to these vulnerable subspaces during inference. This shifts the paradigm from post-hoc output filtering to preventing models from entering representational states where safety boundaries become unreliable—addressing the core problem that misaligned reasoning can hide beneath benign outputs. Ultimately, this work seeks to make alignment verifiable at the computational level, not just the behavioral one.</p>


<div style="height: 2px; background: linear-gradient(90deg, transparent, #2c3e50, transparent); margin: 20px 0 20px 0;"></div>


<!-- font-family: 'Times New Roman', Times, serif !important;">I am Maheep, and I am working on "understanding" and "solving" misalignment via using <em style="font-family: 'Times New Roman', Times, serif !important;">mechanistic interpretability</em>. My research is oriented towards whitebox techniques, as models can be thinking evil but can give benign output after the last layer manipulates the latent state towards benign generation—acting as one of the main disadvantages for black-box safety learning \cite{?}.</p> -->

<!-- <p style="font-size: 1.05em; margin-bottom: 22px; line-height: 1.65; color: #34495e; font-family: 'Poppins', sans-serif;">Previously, I have collaborated with <a href="https://atticusg.github.io" style="color: #3498db; text-decoration: none; font-weight: 500;">Atticus Geiger</a> and <a href="https://nandischoots.com" style="color: #3498db; text-decoration: none; font-weight: 500;">Nandi Schoots</a>, <a href="https://www.ox.ac.uk" style="color: #3498db; text-decoration: none; font-weight: 500;">University of Oxford</a> on mechanistic (causal) interpretability; and <a href="https://haohanwang.github.io" style="color: #3498db; text-decoration: none; font-weight: 500;">Haohan Wang</a> at <a href="https://illinois.edu" style="color: #3498db; text-decoration: none; font-weight: 500;">UIUC</a> on trustworthy machine learning, and completed my <strong style="color: #000000ff;">master's at NTU Singapore</strong>. Before diving deep into AI safety research, I won the Smart India Hackathon with 200K+ participants and led international teams solving real-world AI problems.</p> -->

<!-- <p style="font-size: 1.05em; margin-bottom: 22px; line-height: 1.65; color: #34495e; font-family: 'Poppins', sans-serif; text-align: center;">In my life's causal DAG, my mentors are parent nodes of each success 🙏🏻.</p>  -->

<!-- Enhanced Contact Section -->
<!-- <div style="text-align: center; margin: 40px 0; padding: 25px; background: rgba(52, 152, 219, 0.05); border-radius: 16px; border: 2px solid rgba(52, 152, 219, 0.1);">
  <p style="margin: 0 0 15px 0; font-size: 1.1em; color: #2c3e50; font-weight: 500; font-family: 'Poppins', sans-serif;">💬 Let's Collaborate</p>
  <a href="mailto:maheepchaudhary.research@gmail.com" style="display: inline-block; background: linear-gradient(135deg, #3498db, #2980b9); color: white; padding: 12px 30px; border-radius: 25px; text-decoration: none; font-weight: 600; font-size: 1.05em; transition: transform 0.3s ease, box-shadow 0.3s ease; box-shadow: 0 4px 15px rgba(52, 152, 219, 0.3); font-family: 'Poppins', sans-serif;">✉️ Get in Touch</a>
  <p style="margin: 15px 0 0 0; font-size: 0.9em; color: #7f8c8d; font-family: 'Poppins', sans-serif;">Open to collaborations in: <strong>model eval awareness, mechanistic interpretability, AI safety</strong></p>
</div> -->

<!-- <h2 style="font-size: 1.8em; font-weight: 700; margin: 60px 0 20px 0; color: #2c3e50; letter-spacing: -0.5px; font-family: 'Poppins', sans-serif; text-align: center;">🔬 Research</h2> -->

<!-- <p style="font-size: 1.05em; margin-bottom: 45px; line-height: 1.65; color: #555; font-family: 'Poppins', sans-serif; text-align: center;">I research AI safety and interpretability to ensure advanced AI systems are aligned with human values. This involves mechanistic interpretability, deception detection, and causal methods for understanding neural networks.</p> -->

<!-- Featured Paper (SafetyNet) -->
<!-- <div style="margin: 40px 0; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 20px; overflow: hidden; box-shadow: 0 12px 40px rgba(0,0,0,0.15); transition: all 0.3s ease; position: relative;">
  <div style="position: absolute; top: 15px; right: 15px; background: rgba(255,255,255,0.2); padding: 8px 15px; border-radius: 20px; color: white; font-size: 0.85em; font-weight: 600; font-family: 'Poppins', sans-serif;">⭐ FEATURED</div>
  <div style="display: flex; align-items: center; padding: 30px; gap: 30px; background: rgba(255,255,255,0.95); backdrop-filter: blur(10px);">
    <img src="/images/safetynet.png" alt="SafetyNet Research" style="width: 140px; height: 140px; border-radius: 16px; flex-shrink: 0; object-fit: cover; box-shadow: 0 6px 20px rgba(0,0,0,0.15);">
    <div style="flex: 1;">
      <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 8px;">
        <span style="background: #9b59b6; color: white; padding: 4px 12px; border-radius: 15px; font-size: 0.8em; font-weight: 600; font-family: 'Poppins', sans-serif;">Obfuscation</span>
        <span style="background: #f39c12; color: white; padding: 4px 12px; border-radius: 15px; font-size: 0.8em; font-weight: 600; font-family: 'Poppins', sans-serif;">Causal Interpretability</span>
        <img src="/images/oxford_logo.jpeg" alt="University of Oxford" style="width: 36px; height: 36px; border-radius: 50%; background: white; padding: 3px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
      </div>
      <h3 style="margin: 0 0 12px 0; font-size: 1.35em; font-weight: 700; line-height: 1.3; color: #2c3e50; font-family: 'Poppins', sans-serif;"><a href="https://arxiv.org/pdf/2505.14300" style="color: #2c3e50; text-decoration: none;">SafetyNet: Detecting Harmful Outputs in LLMs by Modeling and Monitoring Deceptive Behaviors</a></h3>
      <p style="margin: 0 0 10px 0; font-size: 1em; color: #7f8c8d; font-weight: 500; font-family: 'Poppins', sans-serif;">Maheep Chaudhary, Fazl Barez</p>
      <p style="margin: 0 0 12px 0; font-size: 0.9em; color: #e74c3c; background: rgba(231, 76, 60, 0.1); display: inline-block; padding: 4px 12px; border-radius: 15px; font-weight: 600; font-family: 'Poppins', sans-serif;">📝 Under review at NeurIPS 2025</p>
      <p style="margin: 0; font-size: 0.95em; color: #5d6d7e; line-height: 1.5; font-family: 'Poppins', sans-serif;">Demonstrated: obfuscation occurs through information shifts from non-linear to linear representation spaces; proves white-box monitoring systems can be made more effective by enabling them to monitor multiple representation spaces.</p>
    </div>
  </div>
</div> -->

<div style="margin: 30px 0;">
  
  <!-- SafetyNet -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/safetynet.png" alt="SafetyNet" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="https://arxiv.org/pdf/2505.14300" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">SafetyNet: Detecting Harmful Outputs in LLMs by Modeling and Monitoring Deceptive Behaviors</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">Maheep Chaudhary, F. Barez</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">Under review</p>
    </div>
  </div>

  <!-- Evaluation Awareness -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/evaluation_sae.png" alt="Evaluation Awareness" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Evaluation Awareness Scales Predictably in Open-Weights Large Language Models</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">Maheep Chaudhary†, I. Su, N. Hooda, N. Shankar, J. Tan, K. Zhu, A. Panda, R. Lagasse, V. Sharma</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">NeurIPS 2025 Responsible FM Workshop</p>
    </div>
  </div>

  <!-- SALT -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/salt.png" alt="SALT" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">SALT: Steering Activations towards Leakage-free Thinking in Chain of Thought</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">S. Batra, P. Tillman, S. Gaggar, S. Kesineni, S. Dev, K. Zhu, A. Panda, Maheep Chaudhary†</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">NeurIPS 2025 Responsible FM Workshop</p>
    </div>
  </div>

  <!-- Alignment-Constrained Pruning -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/pruning.png" alt="Dynamic Pruning" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Alignment-Constrained Dynamic Pruning for LLMs: Identifying and Preserving Alignment-Critical Circuits</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">D. Patel, G. Gervacio, D. Raimi, K. Zhu, R. Lagasse, G. Grand, A. Panda, Maheep Chaudhary†</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">NeurIPS 2025 Responsible FM Workshop</p>
    </div>
  </div>

  <!-- Chain-of-Thought Confidence -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/confidence.png" alt="CoT Confidence" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Optimizing Chain-of-Thought Confidence via Topological and Dirichlet Risk Analysis</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">A. More, A. Zhang, N. Bonilla, A. Vivekan, K. Zhu, P. Sharafoleslami, Maheep Chaudhary†</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">NeurIPS 2025 Responsible FM Workshop</p>
    </div>
  </div>

  <!-- FRIT -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/frit.png" alt="FRIT" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">FRIT: Using Causal Importance to Improve Chain-of-Thought Faithfulness</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">A. Swaroop, A. Nallani, S. Uboweja, A. Uzdenova, M. Nguyen, K. Zhu, S. Dev, A. Panda, V. Sharma, Maheep Chaudhary†</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">NeurIPS 2025 FoRLM Workshop</p>
    </div>
  </div>

  <!-- Amortized Latent Steering -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/latent_steering.png" alt="Latent Steering" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Amortized Latent Steering: Low-Cost Alternative to Test-Time Optimization</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">N. Egbuna, S. Gaur, S. Dev, A. Panda, Maheep Chaudhary†</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">NeurIPS 2025 Efficient Reasoning Workshop</p>
    </div>
  </div>

  <!-- Hydra -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/hydra.png" alt="Hydra" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Hydra: A Modular Architecture for Efficient Long-Context Reasoning</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">S. Chaudhary, D. Patel, Maheep Chaudhary, B. Browning</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">NeurIPS 2025 Efficient Reasoning Workshop</p>
    </div>
  </div>

  <!-- Divider -->
  <div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

  <h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000; font-family: 'Times New Roman', Times, serif !important;">📑 Literature Surveys & Theory</h3>

  <!-- Causal Abstraction JMLR -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/causal_abstraction.png" alt="Causal Abstraction" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="http://jmlr.org/papers/v26/23-0058.html" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Causal Abstraction: A Theoretical Foundation for Mechanistic Interpretability</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">A. Geiger, D. Ibeling, A. Zur, Maheep Chaudhary, S. Chauhan, J. Huang, A. Arora, Z. Wu, N. Goodman, C. Potts, T. Icard</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">JMLR 2024</p>
    </div>
  </div>

  <!-- Causality Survey -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/causality.png" alt="Causality" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="https://arxiv.org/abs/2307.16851" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Towards Trustworthy and Aligned Machine Learning: A Data-centric Survey with Causality Perspectives</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">Maheep Chaudhary*, H. Liu*, H. Wang</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">arXiv preprint</p>
    </div>
  </div>

  <!-- SAE -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/evaluation_sae.png" alt="Sparse Autoencoders" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="https://arxiv.org/abs/2409.04478" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Evaluating Open-Source Sparse Autoencoders on Disentangling Factual Knowledge in GPT-2 Small</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">Maheep Chaudhary, A. Geiger</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">arXiv preprint</p>
    </div>
  </div>

  <!-- PALADIN -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/paladin.png" alt="PALADIN" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">PALADIN: Self-Correcting Language Model Agents to Cure Tool-Failure Cases</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">S. V. Vuddanti, A. Shah, S. K. Chittiprolu, T. Song, S. Dev, K. Zhu, Maheep Chaudhary†</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">arXiv preprint</p>
    </div>
  </div>

  <!-- Divider -->
  <div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

  <h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000; font-family: 'Times New Roman', Times, serif !important;">📚 Additional Publications</h3>

  <!-- Modularity -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/modularity.png" alt="Modularity" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="https://arxiv.org/abs/2502.02470" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Modular Training of Neural Networks aids Interpretability</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">S. Golechha, Maheep Chaudhary, J. Velja, A. Abate, N. Schoots</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">arXiv preprint</p>
    </div>
  </div>

  <!-- Punctuation -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/punctuations.png" alt="Punctuation" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="https://arxiv.org/abs/2508.14067" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">Punctuation and Predicates in Language Models</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">S. Chauhan, Maheep Chaudhary, K. Choy, S. Nellessen, N. Schoots</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">arXiv preprint</p>
    </div>
  </div>

  <!-- MemeCLIP -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/memeclip.png" alt="MemeCLIP" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="https://aclanthology.org/2024.emnlp-main.959/" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">MemeCLIP: Leveraging CLIP Representations for Multimodal Meme Classification</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">S. B. Shah, S. Shiwakoti, Maheep Chaudhary, H. Wang</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">EMNLP 2024</p>
    </div>
  </div>

  <!-- Recommendation System -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/recommendation.png" alt="Recommendation System" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">An Intelligent Recommendation cum Reminder System</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">R. Saxena, Maheep Chaudhary, C.K. Maurya, S. Prasad</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">ACM IKDD CODS & COMAD 2022</p>
    </div>
  </div>

  <!-- CQFaRAD -->
  <div style="display: flex; gap: 20px; margin-bottom: 25px; align-items: flex-start;">
    <img src="/images/cqfarad.png" alt="CQFaRAD" style="width: 100px; height: 100px; border-radius: 8px; flex-shrink: 0; object-fit: cover;">
    <div style="flex: 1;">
      <h4 style="margin: 0 0 6px 0; font-size: 0.9em; font-weight: normal; color: #000000; font-family: 'Times New Roman', Times, serif !important;">
        <a href="#" style="color: #000000; text-decoration: none; font-family: 'Times New Roman', Times, serif !important;">CQFaRAD: Collaborative Query-Answering Framework for a Research Article Dataspace</a>
      </h4>
      <p style="margin: 0 0 4px 0; font-size: 0.75em; color: #666; font-style: italic; font-family: 'Times New Roman', Times, serif !important;">M. Singh, S. Pandey, R. Saxena, Maheep Chaudhary, N. Lal</p>
      <p style="margin: 0; font-size: 0.7em; color: #888; font-style: italic; font-family: 'Times New
<div style="height: 2px; background: linear-gradient(90deg, transparent, #ecf0f1, transparent); margin: 30px 0;"></div>

<h3 style="font-size: 1.2em; font-weight: normal; margin: 30px 0 20px 0; color: #000000; font-family: 'Times New Roman', Times, serif !important;">Background & Recognition</h3>

<p style="font-size: 0.9em; line-height: 1.65; margin-bottom: 15px; color: #34495e; font-family: 'Times New Roman', Times, serif !important;">
Winner of Smart India Hackathon (200K+ participants) and ASEAN-India Hackathon leader across 10+ countries. Mentored 40+ students, selected for UNESCO-India-Africa Program (20+ countries), and reviewer for ICML 2025 and NeurIPS 2024 workshops.
</p>



<!-- <div style="background: linear-gradient(135deg, #74b9ff 0%, #0984e3 100%); border-radius: 20px; padding: 35px; margin: 50px 0; color: white; box-shadow: 0 10px 40px rgba(0,0,0,0.15);">
  <h3 style="margin: 0 0 20px 0; color: white; font-size: 1.4em; font-weight: 700; text-align: center; font-family: 'Poppins', sans-serif;">💡 My Research Philosophy</h3>
  <p style="margin: 0; font-size: 1.15em; line-height: 1.7; opacity: 0.95; text-align: center; font-family: 'Poppins', sans-serif;">I believe powerful AI systems must be interpretable and aligned with human values. My work focuses on understanding the internal mechanisms of neural networks and developing practical methods to detect when they behave in unintended ways. From theoretical foundations to deployed safety systems, I work across the full spectrum of AI alignment research.</p>
</div> -->


<!-- <div style="text-align: center; margin-top: 50px; padding: 30px; background: rgba(52, 152, 219, 0.05); border-radius: 16px;">
  <p style="font-size: 1em; line-height: 1.6; color: #7f8c8d; margin-bottom: 20px; font-family: 'Poppins', sans-serif;">Want to learn more about my research approach and methodology?</p>
  <a href="https://drive.google.com/file/d/1Al37c66ZkPu9T0WxXt1ZcBdLtxxZ6Aha/view?usp=sharing" style="display: inline-block; background: linear-gradient(135deg, #3498db, #2980b9); color: white; padding: 12px 25px; border-radius: 25px; text-decoration: none; font-weight: 600; font-size: 1em; transition: transform 0.3s ease; box-shadow: 0 4px 15px rgba(52, 152, 219, 0.3); font-family: 'Poppins', sans-serif;">📄 Read My Research Statement</a>
</div> -->

</div>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

/* Enhanced styling for better visual appeal */
a[style*="background: linear-gradient"]:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(52, 152, 219, 0.4) !important;
}

div[style*="transition: all 0.3s ease"]:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 40px rgba(0,0,0,0.15) !important;
}

h3 a:hover, h4 a:hover {
  color: #3498db !important;
}

/* Responsive design improvements */
@media (max-width: 768px) {
  div[style*="display: flex"] {
    flex-direction: column !important;
  }
  
  div[style*="grid-template-columns"] {
    grid-template-columns: 1fr !important;
  }
  
  div[style*="width: 130px"], div[style*="width: 140px"], div[style*="width: 80px"] {
    width: 100% !important;
    max-width: 200px !important;
    height: auto !important;
    margin: 0 auto 20px auto !important;
  }
}
</style>



