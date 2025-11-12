# Csci166-RL-DQN-Final-Project
Baseline vs Variant RL agents on Atari Classic Donkey Kong using DQN

# DQN on ALE_DonkeyKong-v5

## Gameplay Videos

### Baseline Agent (DQN)

| Episode   | Avg Reward | Preview | Video  |
|-----------|------------|---------|--------|
| Randomish | ~200       | <img src="dk_thumbnail.png" width="120"/> | <video src="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/base_start-dk.mp4" controls width="320"></video> |
| MidPoint  | ~1200      | <img src="dk_thumbnail.png" width="120"/> | <video src="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/base_mid-dk.mp4" controls width="320"></video> |
| Endpoint  | ~1650      | <img src="dk_thumbnail.png" width="120"/> | <video src="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/base_end-dk.mp4" controls width="320"></video> |

### Variant Agent (Double + Dueling + PER)

| Episode        | Avg Reward            | Preview | Video  |
|----------------|-----------------------|---------|--------|
| Start/Midpoint | ~1400 (spikes to 2200) | <img src="dk_thumbnail.png" width="120"/> | <video src="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/variant_start-dk.mp4" controls width="320"></video> |
| End/Learned    | ~1300–1400 (volatile)  | <img src="dk_thumbnail.png" width="120"/> | <video src="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/variant_end-dk.mp4" controls width="320"></video> |
