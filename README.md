# Code Style Enforcer
- Aligned a code-generation model to PEP8 using RLHF with PPO; modeled code as MDP actions with rewards from a DistilBERT flake8 classifier
- Fine-tuned CodeParrot-small (110M) on 200+ compliant Python snippets, then applied 2-shot PPO with KL penalty to improve style fidelity

[![Onboarding Project Presentation](https://img.youtube.com/vi/vK_5pbcdh9s/0.jpg)](https://youtu.be/vK_5pbcdh9s)

## Sources
- [Reinforcement Learning from Human Feedback explained with math derivations and the PyTorch code. ](https://www.youtube.com/watch?v=qGyFrqc34yc)
- [TRL - Transformer Reinforcement Learning](https://huggingface.co/docs/trl/index) 
- [PPO Trainer](https://huggingface.co/docs/trl/main/en/ppo_trainer) 
- [The N+ Implementation Details of RLHF with PPO: A Case Study on TL;DR Summarization](https://arxiv.org/abs/2403.17031)
- [Reinforcement Learning with Human Feedback (RLHF) in 4 minutes](https://www.youtube.com/watch?v=vJ4SsfmeQlk)
- [An introduction to Policy Gradient methods - Deep Reinforcement Learning](https://www.youtube.com/watch?v=5P7I-xPq8u8)

Model: [codeparrot/codeparrot-small · Hugging Face](https://huggingface.co/codeparrot/codeparrot-small) \
Dataset: [codeparrot/codeparrot-clean · Hugging Face](https://huggingface.co/datasets/codeparrot/codeparrot-clean) \
flake8 docs: [Flake8](https://flake8.pycqa.org/en/latest/)
