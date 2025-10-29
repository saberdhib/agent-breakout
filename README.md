# agent-breakout
PPO reinforcement learning agent trained to play Atari Breakout using Gymnasium and PyTorch. Includes CNN-based Actor-Critic model, preprocessing pipeline, PPO training loop with GAE, reward visualization, and Hugging Face integration for model saving and deployment.


#  PPO Breakout Agent

A reinforcement learning project implementing a PPO (Proximal Policy Optimization) agent trained to play **Atari Breakout** using **Gymnasium** and **PyTorch**.

---

##  Overview
- **Model:** CNN-based Actor-Critic  
- **Algorithm:** PPO with GAE (Generalized Advantage Estimation)  
- **Preprocessing:** Grayscale, normalization, frame stacking  
- **Training Visualization:** Reward curves and moving averages  
- **Deployment:** Integrated with Hugging Face for model hosting and Space visualization  

---

##  Run Locally

```bash
pip install -r requirements.txt
python simulate_breakout.py
