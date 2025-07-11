

---

# 📦 Text Compression Comparison Tool

A comprehensive Streamlit-based application that compares traditional and machine learning-based text compression algorithms, including **Huffman Coding**, **Shannon-Fano Coding**, and **Autoencoder-based ML Compression**.

---

## 🚀 Features

* 🔤 **Huffman Coding** – Frequency-based lossless text compression using variable-length codes.
* 📊 **Shannon-Fano Coding** – Entropy-based tree construction for balanced compression.
* 🤖 **ML-Based Compression** – Autoencoder neural networks for pattern-based lossy compression with reconstruction.
* 🖥️ **Interactive Streamlit Interface** – Intuitive UI for uploading and testing text in real time.
* 📈 **Compression Analytics** – Visual comparison of compression ratio, speed, entropy, and accuracy.
* ⚡ **Real-Time Feedback** – Compression results and graphs are generated instantly as input is provided.

---

## 🛠️ Tech Stack

| Technology       | Purpose                    |
| ---------------- | -------------------------- |
| Python 3.x       | Core programming language  |
| Streamlit        | Web-based user interface   |
| TensorFlow/Keras | Autoencoder implementation |
| NumPy            | Numerical computations     |
| Matplotlib       | Data visualizations        |
| Collections      | Frequency analysis         |

---

## 🧩 Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd os
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the application:**

   ```bash
   streamlit run main.py
   ```

---

## 🌐 Usage Guide

1. Visit `http://localhost:8501` in your browser.
2. Input or paste text into the provided field.
3. Instantly receive:

   * Compressed outputs via Huffman, Shannon-Fano, and Autoencoder.
   * Compression ratio and entropy details.
   * Graphs comparing algorithm efficiency.

---

## 🔍 Compression Techniques

### 1. 📌 Huffman Coding

* **Type**: Lossless
* **Description**: Constructs a binary tree with character frequencies to assign short codes to frequent symbols.
* **Best Use**: Non-uniform character distributions.

### 2. 🧩 Shannon-Fano Coding

* **Type**: Lossless
* **Description**: Divides symbols into probability-based groups and assigns binary codes.
* **Best Use**: Texts with relatively balanced symbol frequencies.

### 3. 🤖 ML-Based Autoencoder

* **Type**: Lossy with reconstruction
* **Description**: Uses deep learning to reduce dimensionality and learn efficient latent representations.
* **Best Use**: Complex pattern recognition in longer or structured text.

---

## 📊 Analytics & Metrics

* 📉 **Compression Ratio**: Compressed size vs original size.
* ⏱️ **Time Efficiency**: Encoding/decoding speed across methods.
* 🔣 **Entropy Analysis**: Measures information content post-compression.
* 📊 **Visualizations**: Real-time bar charts and comparison graphs.

---

## 📁 Project Structure

```
os/
├── main.py              # Streamlit app script
├── README.md            # Documentation
├── .gitignore           # Ignored files and folders
└── requirements.txt     # Required Python packages
```

---

## ⚙️ Performance Insights

| Aspect              | Huffman / Shannon-Fano | ML-Based (Autoencoder)     |
| ------------------- | ---------------------- | -------------------------- |
| Speed               | Fast                   | Slower (training involved) |
| Memory Usage        | Low                    | High                       |
| Adaptability        | Static frequency-based | Learns deep patterns       |
| Compression Quality | High (lossless)        | Medium to High (lossy)     |

---

## 🧪 Roadmap & Enhancements

* [ ] Add support for LZW and Arithmetic coding
* [ ] Enable file upload for large text inputs
* [ ] Batch text compression
* [ ] Use advanced models (VAE, Transformers)
* [ ] Include benchmark suite for timing/performance
* [ ] Export functionality for results and logs

---

## 🤝 Contributing

We welcome contributions!

1. Fork this repo
2. Create your branch: `git checkout -b feature/new-algo`
3. Commit your changes: `git commit -m 'Add new compression method'`
4. Push the branch: `git push origin feature/new-algo`
5. Open a Pull Request

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📦 Dependencies

All necessary libraries are listed in `requirements.txt`. Install with:

```bash
pip install -r requirements.txt
```

---

## 🙋 Support

Have questions or feedback?
📨 [Open an issue](https://github.com/your-repo/issues) or contribute to improve the project!

---

Would you like me to generate a `requirements.txt` template or help deploy this to the cloud (e.g., Streamlit Community Cloud or Hugging Face Spaces)?
