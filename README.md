# 🤖 Tokenizer Comparator: BERT vs GPT-2 vs XLNet

This project is an interactive tool to **compare how different transformer models tokenize text** using their respective algorithms:

- **BERT** uses **WordPiece**
- **GPT-2** uses **Byte Pair Encoding (BPE)**
- **XLNet** uses **SentencePiece**

The tool allows users to input custom text and instantly visualize how each model splits it into tokens. 
It’s project also use **Gradio** for a simple and user-friendly web interface.

## 🧠 Purpose

Tokenization plays a key role in NLP model behavior and performance. This project helps:

- Understand how popular tokenization strategies differ
- Visualize token alignment across models
- Provide an educational and demo-ready interface for showcasing NLP knowledge

## 🚀 Features

- 📝 **Custom text input**: Type or paste your own sentence
- 📊 **Token comparison table**: See how BERT, GPT-2, and XLNet tokenize the same sentence
- 🌐 **Interactive UI**: Powered by [Gradio](https://www.gradio.app/)
- 📦 Based on Hugging Face Transformers

## 📌 Technologies Used

- Python
- Hugging Face Transformers
- Gradio
- Matplotlib
- Google Colab (optional)

## 📈 Example

Input sentence:
> "Two roads diverged in a yellow wood, and sorry I could not travel both."

| BERT (WordPiece) | GPT-2 (BPE) | XLNet (SentencePiece) |
|------------------|-------------|------------------------|
| two              | Two         | Two                   |
| roads            | roads       | roads                 |
| diverged         | diverged    | diverged              |
| in               | in          | in                    |
| a                | a           | a                     |
| yellow           | yellow      | yellow                |
| wood             | wood        | wood                  |
| ,                | ,           | ,                     |
| and              | and         | and                   |
| sorry            | sorry       | sorry                 |
| i                | I           | I                     |
| could            | could       | could                 |
| not              | not         | not                   |
| travel           | travel      | travel                |
| both             | both        | both                  |
| .                | .           | .                     |

