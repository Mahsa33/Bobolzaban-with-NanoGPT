# Bobolzaban-with-NanoGPT

BolbolZaban/gpt2-persian* is a GPT-2 language model trained on Persian poetry from the BolbolZaban dataset. Its hyperparameters closely resemble those of the standard GPT-2-medium model. To adapt the NanoGPT code for this task, the Tiktoken tokenizer was replaced with the BulbulZaban tokenizer. Due to GPU constraints, the batch size and sequence length were reduced to 4 and 512, respectively.

NanoGPT : https://github.com/karpathy/build-nanogpt

BolbolZaban : https://github.com/khashei/bolbolzaban-gpt2-persian
