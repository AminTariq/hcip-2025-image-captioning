<h1>HCIP 2025 Image Captioning Project</h1>

<p>
  This repository contains our <strong>HCIP 2024</strong> deep learning project for
  <strong>automatic image caption generation</strong> using the <strong>Flickr8k</strong> dataset.
</p>

<p>
  The project was developed within the context of the
  <strong>Huawei HCIP AI FCAI program</strong> and combines
  <strong>computer vision</strong> with <strong>natural language processing</strong>
  by extracting image features using <strong>InceptionV3</strong> and generating captions
  with an <strong>LSTM-based sequence model</strong>.
</p>

<h2>Project Overview</h2>

<p>
  The goal of this project is to generate a natural language description for an input image.
</p>

<h3>Workflow</h3>
<ol>
  <li>Download and load the Flickr8k dataset</li>
  <li>Read and preprocess image captions</li>
  <li>Clean text data and add sequence tokens</li>
  <li>Tokenize captions and prepare training sequences</li>
  <li>Extract image features using pretrained InceptionV3</li>
  <li>Train an LSTM-based caption generation model</li>
  <li>Generate captions for unseen images</li>
</ol>

<h2>Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>TensorFlow / Keras</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>PIL</li>
  <li>NLTK</li>
  <li>Kaggle API</li>
</ul>

<h2>Model Architecture</h2>

<p>This project uses a multimodal deep learning architecture:</p>

<ul>
  <li><strong>Image branch:</strong> InceptionV3 extracts visual features from images</li>
  <li><strong>Text branch:</strong> an Embedding layer and LSTM process partial captions</li>
  <li><strong>Fusion layer:</strong> image and text features are combined</li>
  <li><strong>Output layer:</strong> predicts the next word in the caption sequence</li>
</ul>

<h2>Dataset</h2>
<ul>
  <li><strong>Dataset:</strong> Flickr8k</li>
  <li><strong>Source:</strong> Kaggle</li>
  <li>Each image is associated with multiple human-written captions</li>
</ul>

<h2>File Structure</h2>

<pre>
hcip-2024-image-captioning/
├── HCIP_2024_Image_Captioning.ipynb
├── README.md
├── requirements.txt
└── .gitignore
</pre>

<h2>Notes</h2>
<ul>
  <li>The dataset itself is not uploaded to this repository</li>
  <li><code>kaggle.json</code> is required locally in order to download the dataset from Kaggle</li>
  <li>Trained model files and large datasets are excluded from GitHub</li>
</ul>

<h2>Academic Context</h2>
<p>
  This project was developed as part of <strong>HCIP 2024</strong> and was presented
  under the <strong>Huawei HCIP AI FCAI program</strong> context.
</p>

<h2>Authors</h2>
<ul>
  <li>Amin Tariq Amin Abbas</li>
  <li>Magdi Bakri Mohammed</li>
</ul>
