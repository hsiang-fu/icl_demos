# In-Context Learning Demos

Hands-on Google Colab tutorials for exploring how large language models adapt from instructions and examples without updating their weights.

## Quick start

1. Choose a notebook from the table below and open it in Google Colab.
2. In Colab, open **Secrets** and add `GEMINI_API_KEY`, or enter the key when prompted.
3. Run the notebook from top to bottom. Read the note above each API call before continuing.
4. Start with a beginner notebook if this is your first time using in-context learning.

> These notebooks call the Gemini API. Usage may incur charges depending on your Google account and API plan. Reinforcement-learning notebooks can also take longer and may require a Colab runtime with additional system support.

## Suggested learning path

1. **Pattern completion** — see the core ICL mechanism on compact symbolic tasks.
2. **Time-series prediction** — move from symbolic grids to numerical sequences.
3. **Linear regression** — use contextual feedback for iterative optimization.
4. **Classification tutorials** — apply demonstrations to visual decisions.
5. **PID tuning and numerical optimization** — use LLMs as optimizers.
6. **ProPS, ProPS+, and SAS-Prompt** — explore advanced policy search and robot self-improvement.

## Notebook index

| Category | Notebook | Level | Runtime | Colab |
|---|---|---:|---:|---|
| Sequence and pattern learning | [Pattern Completion with the ARC Corpus](In_Context_Learning_Demo_PatternCompletion.ipynb) | Beginner | 15–20 minutes | [Open in Colab](https://colab.research.google.com/drive/1buA3TM0VWCR_8x3KT0ZzQnt0uEt3poIa?usp=sharing) |
| Sequence and pattern learning | [Time-Series Prediction](In_Context_Learning_Demo_TimeSeriesPrediction.ipynb) | Beginner | 15–20 minutes | [Open in Colab](https://colab.research.google.com/drive/1GSsmx1Ms5-RnfafRm6qGohgaVgyrSi0W?usp=sharing) |
| Sequence and pattern learning | [Translation of Fictional Movie Languages](In_Context_Learning_Demo_LanguageTranslation.ipynb) | Intermediate | 20–30 minutes | [Open in Colab](https://colab.research.google.com/drive/1YZzoJ5VnTLUdf9G0Yz2hgo0XL5IcAEDm?usp=sharing) |
| Prediction and regression | [Language-Conditioned Glucose Forecasting](In_Context_Learning_Demo_LanguageConditionedTimeSeriesPrediction.ipynb) | Intermediate | 25–35 minutes | [Open in Colab](https://colab.research.google.com/drive/1H9d4L6nRtwdMAzK74TMEHPhXP1jiWOwB?usp=sharing) |
| Prediction and regression | [Linear Regression Optimization](In_Context_Learning_Demo_LinearRegression.ipynb) | Beginner | 15–20 minutes | [Open in Colab](https://colab.research.google.com/drive/15i2-DoPTyb_LOV5EmRkna3efJCpbkN5o?usp=sharing) |
| Reinforcement learning and optimization | [Numerical Optimization with LLMs](In_Context_Learning_Demo_NumericalOptimization.ipynb) | Intermediate | 25–35 minutes | [Open in Colab](https://colab.research.google.com/drive/1wycQA14rN1Hb5JFN8gXiimqYzdE7sOnO?usp=sharing) |
| Classification | [Binary Classification of Hazelnut Quality](In_Context_Learning_Demo_BinaryClassification.ipynb) | Intermediate | 25–35 minutes | [Open in Colab](https://colab.research.google.com/drive/188FsxIqfm_zZ809XpHWt1dpV0eWcCR2L?usp=sharing) |
| Classification | [Image Classification of Weld Defects](In_Context_Learning_Demo_ImageClassification.ipynb) | Intermediate | 25–35 minutes | [Open in Colab](https://colab.research.google.com/drive/1z-_mY-IYXp1E1P8TlnKk1wSeEk5Ly6pL?usp=sharing) |
| Reinforcement learning and optimization | [PID Controller Tuning](In_Context_Learning_Demo_PIDTuning.ipynb) | Intermediate | 30–45 minutes | [Open in Colab](https://colab.research.google.com/drive/1-i77JAvwwk8y8V0UahxwJhpEOShaMzIN?usp=sharing) |
| Reinforcement learning and optimization | [Prompted Policy Search (ProPS)](In_Context_Learning_Demo_PromptedPolicySearch%28ProPS%29.ipynb) | Advanced | 30–45 minutes | [Open in Colab](https://colab.research.google.com/drive/1jM3X1va2hkoewPUAtGxAAEeYndSoB9ey?usp=sharing) |
| Reinforcement learning and optimization | [Prompted Policy Search with Environment Semantics (ProPS+)](In_Context_Learning_Demo_PromptedPolicySearch%2B%28ProPS%2B%29.ipynb) | Advanced | 45–60 minutes | [Open in Colab](https://colab.research.google.com/drive/1QPdc9foXzIj-NlY0z5hBqKwfxIF5tQOp?usp=sharing) |
| Reinforcement learning and optimization | [SAS-Prompt for Robot Self-Improvement](In_Context_Learning_Demo_SASPromptReimplementation.ipynb) | Advanced | 30–45 minutes | [Open in Colab](https://colab.research.google.com/drive/187PwBsrodSKbdU-7j5L5AVfw832tXOZ8?usp=sharing) |

## Common requirements

- A Google account and a Gemini API key
- Google Colab or a compatible Python/Jupyter environment
- Internet access for API calls and data downloads
- Patience for the advanced simulation notebooks, which run longer than the introductory demos

The notebooks use secure key entry and do not store your API key in the file. Outputs are intentionally cleared in the repository so each tutorial opens in a clean state.

## Troubleshooting

- **Missing API key:** Add `GEMINI_API_KEY` to Colab Secrets, then rerun the connection cell.
- **Model not selected:** Run the model-selection cell and confirm a model before starting the demo.
- **Missing data:** Rerun the data-download cell from a fresh runtime.
- **MuJoCo or rendering error:** Use a compatible Colab runtime and rerun the installation cell before importing Gymnasium.
- **Unexpected variables or stale state:** Select **Runtime → Restart session**, then run the notebook from the beginning.

## License

See [LICENSE](LICENSE).
