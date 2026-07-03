1. Click "Add a README" button on your repo page
2. GitHub opens an editor — paste this:

# Whisper Hindi Fine-tuning (Practice Run)

Fine-tuning OpenAI Whisper for Hindi speech recognition.

## Model
- Base: `openai/whisper-small`
- Fine-tuned model: [whisper-small-hindi-finetuned](https://huggingface.co/YOUR_HF_USERNAME/whisper-small-hindi-finetuned)

## Dataset
- Google FLEURS Hindi (`hi_in`)
- 2120 training samples

## Results
| Epoch | Training Loss | Validation Loss | WER |
|-------|--------------|-----------------|-----|
| 1     | 0.994        | 0.286           | 32.06% |
| 2     | 0.498        | 0.281           | 29.98% |
| 3     | 0.318        | 0.288           | 30.03% |

## Stack
- Hugging Face Transformers
- Google Colab (T4 GPU)
