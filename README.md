# 🤖 Reinforcement Learning Practice

![Reinforcement Learning Banner](Demo/img/display.png)

<p align="center">
  <a href="#-table-of-contents"><img src="https://img.shields.io/badge/Table%20of%20Contents-📑-blue?style=for-the-badge"></a>
  <a href="#-repo-structure"><img src="https://img.shields.io/badge/Repo%20Structure-🏗️-green?style=for-the-badge"></a>
  <a href="#-certification-results"><img src="https://img.shields.io/badge/Certification-🏆-gold?style=for-the-badge"></a>
  <a href="#%EF%B8%8F-tech-stack"><img src="https://img.shields.io/badge/Tech%20Stack-⚙️-orange?style=for-the-badge"></a>
</p>

## 🌟 Overview

A comprehensive collection of **Reinforcement Learning implementations** from the **Deep RL Course**, featuring 12+ trained agents across diverse environments. This repository demonstrates mastery over various RL algorithms including **Deep Q-Networks (DQN)** , **Proximal Policy Optimization (PPO)** , **Advantage Actor-Critic (A2C)** , **REINFORCE**, and **Q-Learning** across platforms like **Unity ML-Agents**, **Gymnasium**, **Stable-Baselines3**, and **VizDoom**.

---

## 📋 Table of Contents

| | |
|---|---|
| [🎯 Project Highlights](#-project-highlights) | [🏗️ Repository Structure](#️-repo-structure) |
| [📚 Project Explanations & Demos](#-project-explanations--demos) | [🏆 Certification Results](#-certification-results) |
| [⚙️ Tech Stack](#️-tech-stack) | [🚀 Getting Started](#-getting-started) |
| [📊 Performance Metrics](#-performance-metrics) | [🤝 Contributing](#-contributing) |
| [📄 License](#-license) | |

---

## 🎯 Project Highlights

- **✅ 10/12 Units Passed** in Deep RL Course (80%+ completion)
- **🧠 6+ RL Algorithms**: PPO, DQN, A2C, REINFORCE, Q-Learning
- **🎮 12+ Environments**: Unity ML-Agents, Gymnasium, Atari, VizDoom, PandaGym
- **🏆 Course Certification**: Deep RL Course Certificate
- **🎥 Interactive Demos**: Video replays embedded in project explanations

---

## 🏗️ Repo Structure

```
📁 Reinforcement-Learning-Practice/
│
├── 📁 # 1️⃣ HUGGY UNITY ML (Bonus Unit)
├── 1_HuggyUnityML/
│   └── bonus_unit1.ipynb     → Training Huggy the Dog with PPO
│
├── 📁 # 2️⃣ LUNAR LANDER (Unit 1)
├── 2_LunarLanderBaseline3/
│   └── unit1.ipynb           → PPO with Stable-Baselines3
│
├── 📁 # 3️⃣ TABULAR RL (Unit 2)
├── 3_Taxi&FrozenLakeGymnasium/
│   └── unit2.ipynb           → Q-Learning from scratch
│
├── 📁 # 4️⃣ ATARI SPACE INVADERS (Unit 3)
├── 4_AtariSpaceInvadersBaseline3/
│   └── unit3.ipynb           → DQN for Space Invaders
│
├── 📁 # 5️⃣ POLICY GRADIENTS (Unit 4)
├── 5_Cartpole&PixelcopterPytorch/
│   └── unit4.ipynb           → REINFORCE from scratch
│
├── 📁 # 6️⃣ UNITY ADVANCED (Unit 5)
├── 6_Pyramid&SnowballTargetUnityML/
│   └── unit5.ipynb           → Pyramids & Snowball with PPO
│
├── 📁 # 7️⃣ ROBOTICS RL (Unit 6)
├── 7_AdvantageAutoCriticPandaGym/
│   └── unit6.ipynb           → A2C for Panda Robots
│
├── 📁 # 8️⃣ VIZDOOM AGENT (Unit 8 Part II)
├── 8_DoomAgentVizdoom/
│   └──unit8_part2.ipynb     → Health Gathering in VizDoom
│
├── 📁 # 🎥 DEMO VIDEOS
├── Demo/
│   └── 📁 vid/
│       ├── replay1.mp4          → Huggy Unity Training
│       ├── replay2.mp4          → Lunar Lander Landing
│       ├── replay3.1.mp4        → Taxi-v3 Optimal Path
│       ├── replay3.2.mp4        → FrozenLake Navigation
│       ├── replay4.mp4          → Space Invaders Gameplay
│       ├── replay5.1.mp4        → Cartpole Balance
│       ├── replay5.2.mp4        → PixelCopter Flight
│       ├── replay6.1.mp4        → Pyramids Completion
│       ├── replay6.2.mp4        → Snowball Target Hit
│       ├── replay7.1.mp4        → Panda Pick & Place
│       ├── replay7.2.mp4        → Panda Reach Dense
│       └── replay8.mp4          → VizDoom Health Gathering
│   └── 📁 img/
│       └── display.png          → RL Workflow Display
│
└── README.md                     → You are here!
```

---

## 📚 Applied RL Projects 

### 🐶 Huggy Unity ML
**Hugging Face Repo**: [KraTUZen/ppo-Huggy](https://huggingface.co/KraTUZen/ppo-Huggy)

Training the adorable dog "Huggy" to fetch sticks in Unity ML-Agents environment using PPO. This project introduces Unity ML-Agents toolkit and demonstrates 3D environment training.

<div align="center">
  <video src="Demo/vid/replay1.mp4" width="600" controls>
    Your browser does not support the video tag.
  </video>
  <p><em>🦴 Huggy learning to fetch sticks (Best Score: 3.827)</em></p>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| PPO | Unity ML-Agents | ML-Agents-Huggy | 3.0 | **3.827** |

---

### 🛰 Lunar Lander
**Hugging Face Repo**: [KraTUZen/ppo-LunarLander-v2](https://huggingface.co/KraTUZen/ppo-LunarLander-v2)

Mastering the Lunar Lander environment using Proximal Policy Optimization (PPO) with Stable-Baselines3. The agent learns to land safely between the flags with precision control.

<div align="center">
  <video src="Demo/vid/replay2.mp4" width="600" controls>
    Your browser does not support the video tag.
  </video>
  <p><em>🌑 lunar landing (Score: 245.02 / 200 required)</em></p>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| PPO | Stable-Baselines3 | LunarLander-v2 | 200 | **245.02** |

---

### 🕹 Taxi & FrozenLake
**Hugging Face Repos**: [KraTUZen/q-Taxi-v3](https://huggingface.co/KraTUZen/q-Taxi-v3), [KraTUZen/q-FrozenLake-v1-no-slippery](https://huggingface.co/KraTUZen/q-FrozenLake-v1-no-slippery)

Classic tabular Q-Learning implementations from scratch. Taxi-v3 involves passenger pickup/dropoff, while FrozenLake demonstrates navigation in grid worlds.

<div align="center">
  <table>
    <tr>
      <td align="center">
        <video src="Demo/vid/replay3.1.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>🚕 Taxi-v3 (Score: 4.85)</em></p>
      </td>
      <td align="center">
        <video src="Demo/vid/replay3.2.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>❄️ FrozenLake (Score: 1.0)</em></p>
      </td>
    </tr>
  </table>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| Q-Learning | Gymnasium | Taxi-v3 | 4.0 | **4.85** |
| Q-Learning | Gymnasium | FrozenLake-v1 | 0.5 | **1.0** |

---

### 👾 Atari Space Invaders
**Hugging Face Repo**: [KraTUZen/dqn-SpaceInvadersNoFrameskip-v4](https://huggingface.co/KraTUZen/dqn-SpaceInvadersNoFrameskip-v4)

Deep Q-Network (DQN) for the classic Atari game Space Invaders. Features CNN-based feature extraction from raw pixels, experience replay, and target networks.

<div align="center">
  <video src="Demo/vid/replay4.mp4" width="600" controls>
    Your browser does not support the video tag.
  </video>
  <p><em>☄ Space Invaders Gameplay (Score: 451.47 / 200 required)</em></p>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| DQN | Stable-Baselines3 | SpaceInvadersNoFrameskip-v4 | 200 | **451.47** |

---

### 🔀 CartPole & PixelCopter
**Hugging Face Repos**: [KraTUZen/Reinforce-CartPole-v1](https://huggingface.co/KraTUZen/Reinforce-CartPole-v1), [KraTUZen/Reinforce-PixelCopter](https://huggingface.co/KraTUZen/Reinforce-PixelCopter)

REINFORCE algorithm implementations from scratch using PyTorch. CartPole demonstrates policy gradients simply, while PixelCopter handles vision-based continuous control.

<div align="center">
  <table>
    <tr>
      <td align="center">
        <video src="Demo/vid/replay5.1.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>⚖️ CartPole (Score: 500)</em></p>
      </td>
      <td align="center">
        <video src="Demo/vid/replay5.2.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>🚁 PixelCopter (Score: 12.03)</em></p>
      </td>
    </tr>
  </table>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| REINFORCE | PyTorch | CartPole-v1 | 350 | **500** |
| REINFORCE | PyTorch | PixelCopter-PLE-v0 | 5 | **12.03** |

---

### 🍀 Pyramids & Snowball Target
**Hugging Face Repos**: [KraTUZen/ppo-PyramidsTraining](https://huggingface.co/KraTUZen/ppo-PyramidsTraining), [KraTUZen/ppo-SnowballTarget](https://huggingface.co/KraTUZen/ppo-SnowballTarget)

Advanced Unity ML-Agents environments solved with PPO. Pyramids requires building structures, while Snowball Target involves hitting moving targets.

<div align="center">
  <table>
    <tr>
      <td align="center">
        <video src="Demo/vid/replay6.1.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>🔺 Pyramids (Score: 1.38)</em></p>
      </td>
      <td align="center">
        <video src="Demo/vid/replay6.2.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>🎯 Snowball Target (Score: 3.27)</em></p>
      </td>
    </tr>
  </table>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| PPO | Unity ML-Agents | Pyramids | -100 | **1.38** |
| PPO | Unity ML-Agents | SnowballTarget | -100 | **3.27** |

---

### 🐼 Panda Robotics
**Hugging Face Repos**: [KraTUZen/a2c-PandaReachDense-v3](https://huggingface.co/KraTUZen/a2c-PandaReachDense-v3), [KraTUZen/a2c-PandaPickAndPlace-v3](https://huggingface.co/KraTUZen/a2c-PandaPickAndPlace-v3)

Robotics manipulation with Franka Emika Panda robot arm using A2C. Tasks include reaching targets and pick-and-place operations.

<div align="center">
  <table>
    <tr>
      <td align="center">
        <video src="Demo/vid/replay7.2.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>🦾 Panda Reach (Score: -2.5)</em></p>
      </td>
      <td align="center">
        <video src="Demo/vid/replay7.1.mp4" width="280" controls>
          Your browser does not support the video tag.
        </video>
        <p><em>🎍 Panda Pick & Place (Score: -2.5)</em></p>
      </td>
    </tr>
  </table>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| A2C | PandaGym | PandaReachDense-v3 | -3.5 | **-2.5** |
| A2C | PandaGym | PandaPickAndPlace-v3 | -3.5 | **-2.5** |

---

### 👨‍🚀 Doom Agent Vizdoom
**Hugging Face Repo**: [KraTUZen/rl_vizdoom_health_gathering_supreme](https://huggingface.co/KraTUZen/rl_vizdoom_health_gathering_supreme)

First-person shooter agent trained in VizDoom to gather health packs while avoiding damage. Demonstrates RL in partially observable 3D environments.

<div align="center">
  <video src="Demo/vid/replay8.mp4" width="600" controls>
    Your browser does not support the video tag.
  </video>
  <p><em>🔫 VizDoom Health Gathering (Score: 5.34 / 5 required)</em></p>
</div>

| **Algorithm** | **Framework** | **Environment** | **Min Required** | **Best Result** |
|---|---|---|---|---|
| PPO | VizDoom | doom_health_gathering_supreme | 5 | **5.34** |

---

## 🏆 Certification Results

### Deep RL Course Progress (80%+ Completion)

| Status | Unit | Environment | Min Required | Best Result | Best Model ID |
|:------:|:----:|-------------|:------------:|:-----------:|---------------|
| ✅ | **Bonus Unit 1** | ML-Agents-Huggy | 3.0 | **3.827** | [`ppo-Huggy`](https://huggingface.co/KraTUZen/ppo-Huggy) |
| ✅ | **Unit 1** | LunarLander-v2 | 200 | **245.02** | [`ppo-LunarLander-v2`](https://huggingface.co/KraTUZen/ppo-LunarLander-v2) |
| ✅ | **Unit 2** | Taxi-v3 | 4.0 | **4.85** | [`q-Taxi-v3`](https://huggingface.co/KraTUZen/q-Taxi-v3) |
| ✅ | **Unit 2** | FrozenLake-v1 | 0.5 | **1.0** | [`q-FrozenLake-v1-no-slippery`](https://huggingface.co/KraTUZen/q-FrozenLake-v1-no-slippery) |
| ✅ | **Unit 3** | SpaceInvadersNoFrameskip-v4 | 200 | **451.47** | [`dqn-SpaceInvadersNoFrameskip-v4`](https://huggingface.co/KraTUZen/dqn-SpaceInvadersNoFrameskip-v4) |
| ✅ | **Unit 4** | CartPole-v1 | 350 | **500** | [`Reinforce-CartPole-v1`](https://huggingface.co/KraTUZen/Reinforce-CartPole-v1) |
| ✅ | **Unit 4** | PixelCopter-PLE-v0 | 5 | **12.03** | [`Reinforce-PixelCopter`](https://huggingface.co/KraTUZen/Reinforce-PixelCopter) |
| ✅ | **Unit 5** | ML-Agents-SnowballTarget | -100 | **3.27** | [`ppo-SnowballTarget`](https://huggingface.co/KraTUZen/ppo-SnowballTarget) |
| ✅ | **Unit 5** | ML-Agents-Pyramids | -100 | **1.38** | [`ppo-PyramidsTraining`](https://huggingface.co/KraTUZen/ppo-PyramidsTraining) |
| ✅ | **Unit 6** | PandaReachDense-v3 | -3.5 | **-2.5** | [`a2c-PandaReachDense-v3`](https://huggingface.co/KraTUZen/a2c-PandaReachDense-v3) |
| ✅ | **Unit 6** | PandaPickAndPlace-v3 | -3.5 | **-2.5** | [`a2c-PandaPickAndPlace-v3`](https://huggingface.co/KraTUZen/a2c-PandaPickAndPlace-v3) |
| ❌ | **Unit 7** | ML-Agents-SoccerTwos | -100 | -1000 | *Skipped (Corrupted)* |
| ❌ | **Unit 8 PI** | LunarLander-v2 | -500 | -1000 | *Skipped (Similar to Unit 1)* |
| ✅ | **Unit 8 PII** | doom_health_gathering_supreme | 5 | **5.34** | [`rl_vizdoom_health_gathering_supreme`](https://huggingface.co/KraTUZen/rl_vizdoom_health_gathering_supreme) |

<div align="center">
  <a href="https://cdn-uploads.huggingface.co/production/uploads/noauth/Fs26ce0uSjtQB4JREjFo1.webp">
    <img src="https://img.shields.io/badge/🎓%20View%20Certificate-Deep%20RL%20Course-4285F4?style=for-the-badge&logo=deeplearning.ai&logoColor=white" alt="Certificate">
  </a>
  <br>
  <sub>✅ Achieved 80%+ completion requirement (10/12 units passed)</sub>
</div>

---

## ⚙️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-009688?style=for-the-badge&logo=python&logoColor=white)

| **Category** | **Technologies** |
|---|---|
| **RL Libraries** | Stable-Baselines3, HuggingFace Hub 🤗 |
| **Deep Learning** | PyTorch, TensorBoard |
| **Environments** | Gymnasium, Unity ML-Agents, VizDoom, PandaGym, PyBullet, Atari-Py |
| **Algorithms** | PPO, DQN, A2C, REINFORCE, Q-Learning |

---

## 🚀 Getting Started

### Option 1: Conda (Recommended)

```bash
# Create environment
conda env create -f environment.yml

# Activate
conda activate rl-practice

# Verify installation
python -c "import gymnasium; print('✅ Gymnasium OK')"
```

### Option 2: Pip

```bash
# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate
# Activate (Linux/Mac)
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Running Notebooks

```bash
# Navigate to project folder
cd "1_HuggyUnityML"

# Launch Jupyter
jupyter notebook bonus_unit1.ipynb
```

---

## 📊 Performance Metrics

| **Environment** | **Algorithm** | **Min Required** | **Best Score** | **Improvement** |
|---|---|---|---|---|
| Huggy | PPO | 3.0 | **3.827** | +27.6% |
| LunarLander-v2 | PPO | 200 | **245.02** | +22.5% |
| Taxi-v3 | Q-Learning | 4.0 | **4.85** | +21.3% |
| FrozenLake-v1 | Q-Learning | 0.5 | **1.0** | +100% |
| SpaceInvaders | DQN | 200 | **451.47** | +125.7% |
| CartPole-v1 | REINFORCE | 350 | **500** | +42.9% |
| PixelCopter | REINFORCE | 5 | **12.03** | +140.6% |
| SnowballTarget | PPO | -100 | **3.27** | +103.3%* |
| Pyramids | PPO | -100 | **1.38** | +101.4%* |
| PandaReach | A2C | -3.5 | **-2.5** | +28.6% |
| PandaPickAndPlace | A2C | -3.5 | **-2.5** | +28.6% |
| VizDoom | PPO | 5 | **5.34** | +6.8% |

*\*Relative improvement from negative baseline*

---

## 🤝 Contributing

Contributions are welcome! Whether it's new algorithms, environments, or improvements:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/NewAlgorithm`)
3. 💾 Commit changes (`git commit -m 'Add NewAlgorithm'`)
4. 📤 Push to branch (`git push origin feature/NewAlgorithm`)
5. 🔃 Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  
### ⭐ Star this repo if you find it helpful!

*"The future of AI lies in agents that learn from interaction."*

[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-KraTUZen-FFD21E?style=for-the-badge)](https://huggingface.co/KraTUZen)

</div>
```