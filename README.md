## Text Sentiment Analysis using Caikit and Hugging Face
## IBMSkillsNetwork GPXX0PYAEN
---
### Author : Cognitive Class AI
### Mentee assignment from IBM Advance AI @ Infinite Learning Course completion of Text Sentiment Analysis using Caikit and Hugging Face from CognitiveClass.ai
---
### Mentee Info
### - Name : Santa Eliza
### - Program : IBM Advance AI @ Infinite Learning

### Tech Stack
### - Python
--- 
### Documentation
1. Install the requirements
```
Create file requirement.txt yang berisi :
    caikit[all]==0.9.2
    # Only needed for Hugging Face
    scipy
    torch
    transformers~=4.27.2
Kemudian, jalankan di terminal dengan: 

pip install -r requirements.txt
```
2. Create directory dengan nama : text_sentiment
```
Untuk menyimpan directory-directory yang dibutuhkan
```
3. Create  the data model specification
```
Create a data_model directory di text_sentiment. Kemudian create sebuah file classification.py
dan isi dengan code yang disediakan di cognitive. Selanjutnya create juga file init.py dan isi
dengan code yang disediakan cognitive.
```
4. Create the model wrapper
```
Create models directory untuk menyimpan model AI Hugging Face sehingga Caikit dapat memuat dan
menjalankannya. Selanjutnya create a config.yml file dan isi dengan code yang disediakan di cognituve.
Setelah itu, Create directory baru di text_sentiment : runtime_model dan buat didalamnya file hf_module.py
dan init.py. Isi kedua file dengan code yang telah disediakan di cognitive.
```

5. Start the runtime
```
Menyajikan model Hugging Face sehingga dapat dipanggil untuk analisis sentimen

Pertama, buat file start_runtime.py dan isi dengan code yang disediakan di cognitive.
Jalankan server di terminal dengan :

python start_runtime.py

Setelah dijalankan, akan menghasilkan output
```
6. Run the sentiment analysis in another terminal tab
```
Selanjutnya, mencoba model yang sudah dibuat dengan file client.py dan mengisikan code yang
sudah disesiakan di cognitive. Kemudian gunakan terminal baru untuk menjalankan kode file client :

python client.py

Output yang dihasilkan adalah klasifikasi sentiment (negatife/positive) dan score nya. Tentu, kita
bisa mengubah teks yang ingin dianalisis didalam code client sesuai keinginan dan menjalankannya
kembali untuk melihat analisis sentimennya.
```


