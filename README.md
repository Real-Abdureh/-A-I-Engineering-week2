

## Attention Mechanism

The attention mechanism is the core of a transformer model. For every token, the model determines which other tokens in the sequence are most relevant for understanding its meaning.

It calculates attention scores between tokens to decide how much focus one token should place on another.

### Example

In the sentence:

```text
"The bank near the river was flooded."
```

the word **"bank"** learns to pay more attention to **"river"** than to finance-related words, helping the model understand that it refers to a riverbank rather than a financial institution.

Attention enables transformers to capture:

* Contextual meaning
* Relationships between words
* Long-range dependencies in text

---

## Transformer Blocks

Transformer blocks combine:

* Multi-head attention
* Feed-forward neural networks
* Normalization layers

These blocks are stacked repeatedly to refine token representations layer by layer.

### What happens across layers?

* Early layers often learn syntax and grammar
* Middle layers capture sentence structure
* Deeper layers understand semantics and long-range relationships

After passing through many transformer blocks, the model develops rich contextual representations that can be used for tasks such as:

* Predicting the next token
* Text generation
* Translation
* Summarization
* Classification

---

## Summary

Together, these components form the foundation of modern Large Language Models (LLMs):

| Component          | Role                                |
| ------------------ | ----------------------------------- |
| Tokens             | Convert text into processable units |
| Attention          | Determines relevant context         |
| Transformer Blocks | Learn complex language patterns     |

This architecture is what allows LLMs to understand and generate human-like text effectively.

```
```
