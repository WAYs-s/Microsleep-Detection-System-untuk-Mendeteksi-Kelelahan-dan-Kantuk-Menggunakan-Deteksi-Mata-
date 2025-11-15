# 🧠 Real-Time Face Detection and Drowsiness Monitoring Using Mediapipe & OpenCV

Proyek ini merupakan implementasi **deteksi wajah dan kelelahan pengguna (drowsiness detection)** secara real-time menggunakan **Mediapipe** dan **OpenCV**.  
Sistem ini mampu mengenali keberadaan wajah pengguna, melacak pergerakan mata, serta menganalisis tingkat kantuk berdasarkan posisi landmark wajah.

---
## 🤝 Support By :
Dosen Pengampu : Akhmad Hendriawan ST., MT. (NIP.197501272002121003)  
Mata kuliah : Pengolahan Citra  
Program Studi : D4 Teknik Elektronika  
Politeknik Elektronika Negeri Surabaya  

---

## 👥 Daftar Anggota Kelompok 6

| No | Nama Lengkap        | NRP           |
|----|----------------------|----------------|
| 1  | Al Farruq Rodhiyatul A.          | 2122600021     |
| 2  | Yunanta Adi Wijaya    | 2122600035     |
| 3  | Dewangga Pratama Ikko P.    | 2122600052     |
| 4  |Dewa Gede Angkasa A. |2122600059 |

---

## 🚀 Fitur Utama
- Deteksi wajah secara real-time menggunakan kamera.  
- Pelacakan *facial landmarks* (mata, hidung, mulut, dan kontur wajah).  
- Analisis ekspresi atau kondisi mata untuk indikasi kelelahan.  
- Tampilan visual interaktif dengan koordinat landmark di layar.  
- Dapat dikembangkan menjadi sistem peringatan otomatis (alarm).

---

## 🧩 Teknologi yang Digunakan
- **Python 3.12**  
- **OpenCV** untuk pengolahan citra dan akses kamera.  
- **Mediapipe FaceMesh** untuk deteksi dan pelacakan titik wajah.  
- (Opsional) **NumPy** untuk analisis rasio mata (EAR).  

---

## ⚙️ Cara Menjalankan Program
1. Pastikan Python telah terinstal.  
2. Instal dependensi berikut dengan mengetik pada Terminal (CMD):
   ```bash
   pip install opencv-python mediapipe pygame
3. Setelah terinstal Setelah semua dependensi terinstal, jalankan program utama dengan perintah:
   ```bash
   python microsleep.py
4. Program Siap dioperasikan

---
## 🧭 Alur Kerja Sistem
![Alt text](https://github.com/WAYs-s/Microsleep-Detection-System-untuk-Mendeteksi-Kelelahan-dan-Kantuk-Menggunakan-Deteksi-Mata-/blob/bf6e8e9971c3a1363763172793faa47b40efceff/Alur%20Kerja%20Microsleep.jpg)

---
## 🧭 Flowchart Sistem
![Alt text](https://github.com/WAYs-s/Microsleep-Detection-System-untuk-Mendeteksi-Kelelahan-dan-Kantuk-Menggunakan-Deteksi-Mata-/blob/bf6e8e9971c3a1363763172793faa47b40efceff/FLOWCHART%20MEDIPIPE%20CAMERA.png)

---
## 🧭 Diagram UML
Diagram UML penggambaran Interaksi antara User dengan Aplikasi dalam case normal
<img src= "https://github.com/WAYs-s/Microsleep-Detection-System-untuk-Mendeteksi-Kelelahan-dan-Kantuk-Menggunakan-Deteksi-Mata-/blob/e88adc46c650ad2732db9c7d64e6abe6d8be6919/Interaksi_MicroSleep.png" alt="Alt text" width="500" height="1000">

---
## 🖊️ Kesimpulan
- Sistem berbasis MediaPipe Face Mesh berhasil mendeteksi tanda microsleep secara real-time melalui perhitungan Eye Aspect Ratio (EAR).
- Nilai ambang batas 0.25 terbukti efektif untuk membedakan kondisi mata terbuka dan tertutup.
- Fitur alarm suara dan notifikasi visual memberikan peringatan dini yang membantu pengguna untuk segera mengambil waktu istirahat singkat (microbreak).
- Aplikasi menyediakan dua mode utama, yaitu User Mode untuk penggunaan umum dan Developer Mode untuk pengaturan parameter yang lebih detail.

---
##  📸 Dokumentasi 

Berikut video percobaan program  yang digunakan dalam mendeteksi ngantuk.
Link video: https://youtu.be/ZdpbrX9DYDI




