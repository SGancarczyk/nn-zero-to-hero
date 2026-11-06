# Neural Networks: Zero to Hero – my implementations

My code, notes and experiments from Andrej Karpathy's course
[Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html).

For each lecture I code along, then rewrite the key parts from memory
and run my own experiments (changing hyperparameters, architectures and datasets).

## Progress

| # | Lecture | Folder | Status | What I learned / result |
|---|---------|--------|--------|-------------------------|
| 1 | micrograd: backpropagation from scratch | `01-micrograd` | in progress | |
| 2 | makemore 1: bigram language model | `02-makemore-bigram` | – | |
| 3 | makemore 2: MLP | `03-makemore-mlp` | – | |
| 4 | makemore 3: activations, gradients, BatchNorm | `04-makemore-batchnorm` | – | |
| 5 | makemore 4: manual backprop | `05-makemore-backprop` | – | |
| 6 | makemore 5: WaveNet | `06-makemore-wavenet` | – | |
| 7 | GPT from scratch | `07-gpt` | – | |
| 8 | GPT tokenizer (BPE) | `08-tokenizer` | – | |
| 9 | Reproducing GPT-2 (124M) | `09-gpt2` | – | |

## Repository structure

```
01-micrograd/
  micrograd.ipynb          code written along with the lecture + my notes
  micrograd_from_memory.py my own rewrite of the engine, without the video
02-makemore-bigram/
  ...
data/
  names.txt                dataset used in the makemore lectures
```

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

The computation-graph visualisation in micrograd also needs the Graphviz program:

```bash
brew install graphviz
```

## Credits

Based on Andrej Karpathy's lectures. The code written along with the lectures
follows his implementations:
[micrograd](https://github.com/karpathy/micrograd),
[makemore](https://github.com/karpathy/makemore),
[nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero).
