a. Alga Fiky 120140121

b. Alien.py

c. cara menjalankan kontainer
Buka terminal, lalu masuk ke direktori `~/Downloads` lalu buat image dengan menggunakan      perintah make-build seperti di bawah ini.

    make build

Lalu pastikan image sudah dibuild dengan mengecek menggunakan perintah seperti di bawah ini.

    docker images

Akan terlihat image dengan nama aircraft/pygame yang berarti image sudah dibuild.

Selanjutnya, jalankan perintah run seperti dibawah ini.

Untuk Linux:

    make run-linux

Untuk MacOS:

    make run-mac

Untuk Windows:

    make run-windows

Kemudian jalankan game melalu container yang sudah dibuat dengan menjalankan perintah seperti di bawah ini.

    python3 -m main.py
