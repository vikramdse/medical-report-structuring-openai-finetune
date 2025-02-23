# Medical Report Structuring with OpenAI Fine-Tune

This project focuses on structuring medical reports using OpenAI's fine-tuned model (gpt-4o-mini-2024-07-18). It transforms unstructured medical data into well-organized JSON formats, enabling easier analysis and integration with healthcare systems. By leveraging the fine-tuned model, it enhances accuracy in structuring compared to the base model.

---

## Features

- Converts unstructured medical text into structured JSON objects.
- Fine-tuned on specific medical report data for high accuracy.
- Supports a variety of medical domains such as diagnosis, treatment plans, and symptoms.
- Utilizes OpenAI's advanced language models for natural language understanding.
- OpenAI Fine-tuned model: gpt-4o-mini-2024-07-18

---

---

## Fune-tuned Results

- Training loss: 0.0249
- Validation loss: 0.0900
- Full validation loss: 0.0262
- Average Similarity (finetuned model): > 98%
- Average Similarity (Base Model): ~ 87%

---

---

## Fune-tuning Benefits

- High Accuracy Outputs: Produces more accurate and reliable results.
- Efficiency: Reduces token usage. In contrast, base proprietary models require few-shot prompting to enhance accuracy, leading to higher token consumption.
- Lower Cost: Due to reduced token usage, fine-tuning is more cost-effective compared to using the base model.
- Scalability: Easily adapts to large-scale implementations and can be tailored to specific medical domains or report types.

---

## License

MIT License

Copyright (c) 2025 Vikram Salunkhe
[vikramsalunkhe.com](https://www.vikramsalunkhe.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Acknowledgements

- **OpenAI** for providing state-of-the-art language models.
- **Hugging Face Dataset**: [WoutDeRijck/medical_reports](https://huggingface.co/datasets/WoutDeRijck/medical_reports)
