# encryption BZEXE/BZIP2

<li>Install BZEXE/BZIP2</li>
<pre><code>sudo apt-get update</code></pre>
<pre><code>sudo apt install build-essential</code></pre>
<pre><code>sudo apt-get install -y jq</code></pre>

<li>Cara Pasang</li>
<pre><code>wget -q -O encshc "https://raw.githubusercontent.com/SatanTech/encryption/main/enc.sh" && chmod +x enc.sh</code></pre>
<li>Jalankan Perintah</li>
<pre><code>./enc.sh</code></pre>

Encryption menggunakan BZEXE/BZIP2 tanpa ribet harus encrypt satu persatu ini tools untuk encrypt sekaligus berapapun yang mau di encrypt

<li>Penting!</li>
Salin folder autoscript nya ke dalam folder root vps lalu ketik . enc.sh nama_folder
contoh : ./enc.sh sfvt
ini akan menencrypt seluruh file di dalam enc beserta sub folder nya
Contoh :

    ├── script.sh
    ├── folder1
    │   ├── subfolder1
    │   │   └── script1.sh
    │   └── subfolder2
    │       └── script2.sh
    └── folder2
        ├── subfolder3
        │   └── script3.sh
        └── subfolder4
            └── script4.sh
