<h1>📊 BMLP Submission – Clustering & Classification Project</h1>

<hr>

<h2>👤 Identitas</h2>

<ul>
  <li><b>Nama:</b> Najla Putri Kaliandra Sabilillah</li>
  <li><b>Email:</b> najlakaliandra@gmail.com</li>
  <li><b>ID Dicoding:</b> najla_sabilillah</li>
</ul>

<hr>

<h2>📌 Deskripsi Proyek</h2>

<p>
Proyek ini merupakan implementasi <b>Machine Learning</b> yang mencakup dua pendekatan utama:
</p>

<ul>
  <li>📍 <b>Clustering</b> (Unsupervised Learning)</li>
  <li>🎯 <b>Classification</b> (Supervised Learning)</li>
</ul>

<p>
Proyek bertujuan untuk mengeksplorasi pola data menggunakan teknik clustering,
serta membangun dan membandingkan beberapa algoritma klasifikasi untuk menghasilkan model terbaik.
</p>

<hr>

<h2>📂 Dataset</h2>

<ul>
  <li><b>Nama Dataset:</b> bank_transactions</li>
  <li><b>Sumber:</b> 
    <a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vTbg5WVW6W3c8SPNUGc3A3AL-AG32TPEQGpdzARfNICMsLFI0LQj0jporhsLCeVhkN5AoRsTkn08AYl/pub?gid=2020477971&single=true&output=csv">
    bank_transactions (Google Sheets - CSV Export)
    </a>
  </li>
  <li>Dataset digunakan untuk proses clustering dan classification</li>
  <li>Melalui tahap preprocessing sebelum training</li>
  <li>Disimpan dalam format CSV</li>
</ul>

<pre>
data_clustering.csv
data_clustering_inverse.csv
</pre>

<hr>

<h2>📍 Clustering (Unsupervised Learning)</h2>

<p>
Tahapan clustering dilakukan untuk mengelompokkan data berdasarkan kemiripan fitur tanpa label target.
</p>

<h3>🔎 Tahapan</h3>

<ul>
  <li>Data preprocessing & scaling</li>
  <li>Dimensionality Reduction menggunakan <b>PCA</b></li>
  <li>Pembuatan model clustering</li>
  <li>Evaluasi hasil cluster</li>
</ul>

<h3>💾 Model yang Disimpan</h3>

<pre>
model_clustering.h5
PCA_model_clustering.h5
</pre>

<hr>

<h2>🎯 Classification (Supervised Learning)</h2>

<p>
Pada tahap classification, beberapa algoritma diuji untuk membandingkan performa model.
</p>

<h3>🧠 Algoritma yang Digunakan</h3>

<ul>
  <li>Logistic Regression</li>
  <li>Decision Tree</li>
  <li>Random Forest</li>
</ul>

<h3>⚙️ Proses</h3>

<ul>
  <li>Exploratory modeling</li>
  <li>Hyperparameter tuning</li>
  <li>Evaluasi performa model</li>
  <li>Pemilihan model terbaik</li>
</ul>

<h3>💾 Model yang Disimpan</h3>

<pre>
decision_tree_model.h5
explore_LogReg_classification.h5
explore_RandomForest_classification.h5
tuning_classification.h5
</pre>

<hr>

<h2>📈 Evaluation</h2>

<p>Model dievaluasi menggunakan metrik klasifikasi standar seperti:</p>

<ul>
  <li>Accuracy</li>
  <li>Precision</li>
  <li>Recall</li>
  <li>F1-Score</li>
</ul>

<p>
Proses tuning dilakukan untuk meningkatkan performa dan mengurangi overfitting.
</p>

<hr>

<h2>📁 Struktur Project</h2>

<pre>
├── data_clustering.csv
├── data_clustering_inverse.csv
├── model_clustering.h5
├── PCA_model_clustering.h5
├── decision_tree_model.h5
├── explore_LogReg_classification.h5
├── explore_RandomForest_classification.h5
├── tuning_classification.h5
├── [Clustering]_Submission_Akhir_....ipynb
└── [Klasifikasi]_Submission_Akhir_....ipynb
</pre>

<hr>

<h2>🛠 Tech Stack</h2>

<ul>
  <li>🐍 Python</li>
  <li>📊 Pandas</li>
  <li>📈 Matplotlib / Seaborn</li>
  <li>🧮 Scikit-learn</li>
  <li>📉 PCA (Dimensionality Reduction)</li>
</ul>

<hr>

<h2>🎯 Project Highlights</h2>

<ul>
  <li>✔ Implementasi Unsupervised & Supervised Learning</li>
  <li>✔ PCA untuk reduksi dimensi</li>
  <li>✔ Perbandingan beberapa algoritma klasifikasi</li>
  <li>✔ Hyperparameter tuning</li>
  <li>✔ Model disimpan untuk reuse</li>
</ul>
