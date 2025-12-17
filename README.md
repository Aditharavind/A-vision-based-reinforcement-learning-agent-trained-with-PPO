# 🧠 Robot Brain: Vision-Based Decision Making with PPO

**Building in public / learning in public 🚧**

This project explores how an agent can learn to **perceive and act from raw visual input** using reinforcement learning.  
A CNN-based policy is trained with **Proximal Policy Optimization (PPO)** to navigate a dynamic environment directly from pixel observations—without any hand-coded rules.

Although the environment is simple, the architecture mirrors real robotic systems:
**perception → decision-making → action**.

---

## 🎥 Demo (Learned Behavior)

The video below shows the trained agent navigating the environment after learning purely through interaction.

> 🐔 The environment is single-agent: only one bird is controlled by the policy.  
> Other moving objects are part of the environment dynamics.

<p align="center">
  <img src="ppo.gif" width="400"/>
</p>

---

## 🧩 Architecture Overview

