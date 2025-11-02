This project explores modern post-training techniques for aligning and improving large language models beyond pretraining.
It implements three complementary approaches:

Supervised Fine-Tuning (SFT): adapting a base model into an instruction-following assistant using curated input–output pairs.

Direct Preference Optimization (DPO): aligning model behavior with human preferences through “chosen vs. rejected” responses, without an explicit reward model.

Online Reinforcement Learning (PPO / GRPO): optimizing verifiable objectives such as reasoning accuracy or helpfulness using online feedback loops.

The repository includes code for data curation, reward shaping, evaluation pipelines, and prompt-based benchmarking to measure behavioral alignment and performance gains.
