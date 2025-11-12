# Csci166-RL-DQN-Final-Project
Baseline vs Variant RL agents on Atari Classic Donkey Kong using DQN

# DQN on ALE_DonkeyKong-v5

## Gameplay Videos

## DQN Donkey Kong Agent Evaluation

### Baseline Agent (DQN)

| Episode   | Avg Reward | Preview | Video  |
|-----------|------------|---------|--------|
| Randomish | ~200       | <img src="dk_thumbnail.png" width="120"/> | [▶ Watch](videos/base_start-dk.mp4) |
| MidPoint  | ~1200      | <img src="dk_thumbnail.png" width="120"/> | [▶ Watch](videos/base_mid-dk.mp4)   |
| Endpoint  | ~1650      | <img src="dk_thumbnail.png" width="120"/> | [▶ Watch](videos/base_end-dk.mp4)   |

### Variant Agent (Double + Dueling + PER)

|     Episode    |       Avg Reward       | Preview | Video  |
|----------------|------------------------|---------|--------|
| Start/Midpoint | ~1400 (spikes to 2200) | <img src="dk_thumbnail.png" width="120"/> | [▶ Watch](videos/variant_start-dk.mp4)|
| End/Learned    | ~1300-1400 (volatile)  | <img src="dk_thumbnail.png" width="120"/> | [▶ Watch](videos/variant_end-dk.mp4)  |
