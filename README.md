# Code Style Enforcer
- Aligned a code-generation model to PEP8 using RLHF with PPO; modeled code as MDP actions with rewards from a DistilBERT flake8 classifier
- Fine-tuned CodeParrot-small (110M) on 200+ compliant Python snippets, then applied 2-shot PPO with KL penalty to improve style fidelity

[![Onboarding Project Presentation](https://img.youtube.com/vi/vK_5pbcdh9s/0.jpg)](https://youtu.be/vK_5pbcdh9s)
