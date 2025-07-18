# Intensity Heatmap

Aplikasi berbasis Flask yang menggunakan model YOLOv12n untuk mendeteksi objek dalam video dan memvisualisasikan intensitas aktivitas dalam bentuk heatmap.

## 🚀 Fitur

- Upload video melalui antarmuka web
- Deteksi objek menggunakan YOLOv12n
- Pembuatan heatmap berdasarkan intensitas posisi objek
- Tampilkan hasil video dengan overlay heatmap

## 🖼️ Screenshot

### 1. Form Upload Video

![Form Upload Video](screenshots/upload-form.png)
![Form Upload Video](screenshots/upload-form1.png)

### 2. Proses Deteksi dan Heatmap

![Proses Heatmap](screenshots/heatmap-process.png)
![Proses Heatmap](screenshots/heatmap-process1.png)

### 3. Output Video dengan Overlay Heatmap

![Output Heatmap](screenshots/output-video.png)

## 🖥️ Teknologi

- Python 3.11
- Flask
- YOLOv12n (PyTorch)
- OpenCV
- Matplotlib & NumPy
- HTML, CSS, JavaScript

## 📁 Struktur Direktori

intensity_heatmap/
├── flaskapp.py
├── object_detection.py
├── yolov12n.pt
├── requirements.txt
├── output.mp4
├── uploads/
├── static/
├── templates/
├── screenshots/
└── Resources/Videos/

## ⚙️ Cara Menjalankan

```bash
git clone https://github.com/Asep-Jelpa-Nasution/intensity_heatmap.git
cd intensity_heatmap
source Scripts/activate        # Windows: Scripts\activate.bat
pip install -r requirements.txt
python flaskapp.py
```
