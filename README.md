# Code Style Enforcer
- Implemented RLHF and designed an MDP where code generation acted as actions, with reward derived from a custom-trained DistilBERT-based classifier predicting flake8 compliance
- Fine-tuned a CodeParrot-small GPT-2 model (110M) on 200+ Python snippets
- Conducted 2-shot PPO with gradient updates and KL clipping to improve style in generated code
