# 📡 Network Traffic Analysis

## 📝 Deskripsi
Project ini adalah simulasi analisis trafik jaringan menggunakan **Jupyter Notebook**, dibuat sebagai **portofolio**.  
Tujuannya: mendeteksi pola trafik normal dan anomali menggunakan **machine learning**, sekaligus memvisualisasikan hasil secara interaktif.

Meskipun sederhana, project ini menunjukkan kemampuan dalam:  
- Mengolah data trafik jaringan (Source IP, Destination IP, Protocol, dsb.)  
- Melakukan **encoding** data untuk model ML  
- Mengidentifikasi **anomali** pada jaringan  
- Visualisasi interaktif menggunakan Python (Matplotlib/Seaborn)

---

## ⚙️ Fitur
- 📊 **Analisis Trafik**: Notebook menampilkan trafik normal vs anomali  
- 🤖 **Deteksi Anomali**: Menggunakan algoritma **Isolation Forest**  
- 📈 **Visualisasi**: Plot distribusi trafik berdasarkan protokol dan anomali  
- 🗂 **Data Preprocessing**: Encode IP, protokol, dan fitur numerik lainnya agar siap untuk ML  

---

## 🛠 Teknologi
- Python 3.x  
- Jupyter Notebook  
- Pandas & NumPy  
- Scikit-learn (Isolation Forest)  
- Matplotlib & Seaborn (Visualisasi)  
- Tabulate (Tabel data rapi di console)  

---

## 🚀 Cara Jalankan
 
```bash
1. Clone repository: 
git clone https://github.com/username/network-traffic-analysis.git
cd network-traffic-analysis
2. Install dependencies:
pip install -r requirements.txt
3. Buka Jupyter Notebook:
jupyter notebook
