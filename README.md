Ini merupakan repository jupyter notebook untuk mendeteksi gambar tangan gunting, kertas dan batu.<br/>
Data gambar yang digunakan untuk membuat model berjumlah 2188 gambar.<br/>
Teknik yang digunakan untuk membuat model adalah dengan menggunakan <i>sequential model<i>, yaitu MLP (Multi Layer Perceptron).<br/>
<i>Activation function<i> yang digunakan pada model ini adalah <i>relu (rectified linear unit)<i> dan softmax.<br/>
Model ini memiliki beberapa layer dengana masing-masing menggunakan <i>MaxPolling2D layer<i>, <i>Conv2D layer<i>, <i>Flatten layer<i>, dan <i>Dense layer<i>. Model berhasil mendapatkat Akurasi sebesar 98 %.<br/>
<br/>
Model bisa dikatakan bagus dengan setidaknya mempunyai waktu training < 30 menit dan akurasi diatas 95 %.
<br/>
<br/>

sumber Dataset : https://dicodingacademy.blob.core.windows.net/picodiploma/ml_pemula_academy/rockpaperscissors.zip<br/><br/>

Dataset dibagi menjadi 2 dengan validation image berjumlah 40%.<br/>
Training Image : 1314 gambar.<br/>
Validation Image : 874 gambar.<br/>
<br/>
Disediakan juga sample gambar untuk tes model berjumlah 13 gambar.
<br/>
Model menggunakan 35 epoch dengan masing-masing 30 step.
<br/>
<br/>
Requirement Library Python yang harus diinstall :<br/>
`pip install tensorflow`<br/>
`pip install matplotlib`<br/>
`pip install numpy`<br/>
`pip install keras`<br/>
<br/>
Berikut contoh ketika model dites untuk mendeteksi sample gambar :<br/><br/>
![Tes Image Recognition](doc_img/tes_image.png)
<br/>
<br/>
Berikut grafik <i>Accuracy<i> dan <i>Loss<i> dari model yang telah dibuat : <br/><br/>
![Diagram Akurasi](doc_img/diagram_akurasi.png)
![Diagram Loss](doc_img/diagram_loss.png)
