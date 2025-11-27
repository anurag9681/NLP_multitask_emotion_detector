<h1 align="center">🎭 Multimodal Emotion Detection using LSTM</h1>
<h3 align="center">Text Cleaning • Preprocessing • Deep Learning (LSTM) • Multimodal Architecture</h3>

<p align="center">
This repository contains an end-to-end multimodal emotion detection system leveraging 
<strong>LSTM-based deep learning</strong>, <strong>text cleaning</strong>, and advanced <strong>preprocessing</strong>.
The model is designed to classify human emotions from textual data with high accuracy.
</p>

<hr>

<h2>🚀 Key Features</h2>

<ul>
  <li><strong>🧹 Text Cleaning Pipeline</strong>
    <ul>
      <li>Lowercasing, stopword removal, punctuation stripping</li>
      <li>Lemmatization & tokenization</li>
      <li>Handling emojis, slang, repeated characters</li>
    </ul>
  </li>

  <li><strong>🧠 LSTM-based Deep Learning</strong>
    <ul>
      <li>Bidirectional LSTM architecture</li>
      <li>Word embeddings (Word2Vec)</li>
      <li>Multiclass emotion classification</li>
    </ul>
  </li>

  
  <li><strong>📊 Dataset Handling</strong>
    <ul>
      <li>Dataset stored in <code>data/</code> folder</li>
      <li>Supports CSV/JSON raw emotion data</li>
    </ul>
  </li>

  <li><strong>💡 Easy-to-understand modular code</strong></li>
</ul>

<hr>

<h2>📂 Repository Structure</h2>

<pre>
├── data/                       # Raw dataset files
│   ├── Emotions.csv
│   ├── Hate Speech.csv
│   └── Viol.csv
│
├── code/                       # All code files
│   ├── multi-tak-ml-model.ipynv        # Text cleaning & preprocessing functions and LSTM model
│
└── README.md
</pre>

<hr>

<h2>🛠️ Installation</h2>

<pre>
git clone https://github.com/anurag9681/NLP_multitask_emotion_detector.git
</pre>

<hr>

<h2>🔧 Preprocessing & Text Cleaning</h2>

<p>This project includes a custom preprocessing pipeline:</p>

<ul>
  <li>Tokenization</li>
  <li>Lemmatization</li>
  <li>Special character handling</li>
  <li>Contraction expansion (don't → do not)</li>
  <li>Emoji & emoticon normalization</li>
  <li>Removing noise: URLs, mentions, hashtags</li>
</ul>


<p>
The model uses:
</p>

<ul>
  <li>Embedding layer (pretrained or random init)</li>
  <li>LSTM</li>
  <li>Dense + Softmax for final emotion prediction</li>
</ul>

<hr>



<hr>

<h2>🤝 Contributing</h2>
<p>
Contributions are welcome! Feel free to open issues, add new models, 
improve preprocessing, or extend multimodal support (e.g., audio + video).
</p>

<hr>

<h2>🛡️ Disclaimer</h2>
<p>
This project is meant for research and educational purposes only. 
It should not be used for medical, psychological, or clinical decision-making.
</p>

<hr>

<h2 align="center">⭐ If you find this project useful, please star the repository!</h2>
