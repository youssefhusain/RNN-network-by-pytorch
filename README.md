## Recurrent Neural Networks (RNNs)

- **RNNs** are *Recurrent Neural Networks*.
- They are **sequential**, not parallel.
- Commonly used in **text models**, since data is fed to them **step by step** (sequentially).
- They are **very slow** because **parallelism is not possible** in their structure.
- Suffer from the **vanishing gradient problem**, which causes them to **forget old or distant tokens** in the sequence.
- **Modern alternatives** like:
  - **LSTMs** (Long Short-Term Memory)
  - **Transformers**
  
  are preferred today because they:
  - Use the **attention mechanism**
  - Assign **attention scores** to each token, allowing the model to focus on relevant parts of the input sequence regardless of distance.
