# Create VPS/RDP with google cloud

Cara membuat RDP menggunakan google cloud (mudah)

<h2>Langkah yang pertama</h2>
kalian harus membuat project baru dulu di google cloud, gini caranya :<br><br>
1. <strong>Masuk ke Console Google Cloud:</strong><br>
   Buka browser web dan pergi ke https://console.cloud.google.com. Jika Anda belum masuk, Anda akan diminta untuk masuk dengan akun Google Anda.

2. **Buat Proyek Baru:**
   - Klik pada menu navigasi di sudut kiri atas dan pilih "Proyek".
   - Klik tombol "Buat Proyek" di bagian atas layar.

3. **Isi Informasi Proyek:**
   - Pilih nama unik untuk proyek Anda.
   - Pastikan untuk memilih atau membuat organisasi untuk proyek Anda (organisasi ini berkaitan dengan tagihan dan manajemen akses).
   - Pilih lokasi tempat proyek Anda akan disimpan (lokasi ini berkaitan dengan infrastruktur fisik Google Cloud, seperti di mana sumber daya akan ditempatkan).

4. **Aktifkan Faktur dan Setelan Tambahan (Opsional):**
   - Jika Anda belum mengaktifkan faktur, Anda akan diminta untuk melakukannya. Masukkan informasi pembayaran Anda.
   - Pilih setelan tambahan sesuai kebutuhan proyek Anda.

5. **Klik "Buat":**
   - Setelah Anda mengisi semua informasi yang diperlukan, klik tombol "Buat" untuk membuat proyek.

6. **Pantau Proses Pembuatan:**
   - Tunggu sebentar sementara Google Cloud membuat proyek baru Anda. Proses ini biasanya berlangsung beberapa saat.

7. **Akses Proyek:**
   - Setelah proyek dibuat, Anda akan diarahkan kembali ke dashboard Console Google Cloud. Di sini, Anda dapat melihat proyek baru Anda dan mengakses berbagai layanan GCP.

Jika sudah membuat project baru saatnya kita ke

## Langkah yang ke-2
Kalian klik logo shell yang ada pada kanan atas yang di sebelah kirinya lonceng notifikasi
yang ini : ![image](https://github.com/vtxcommunity/rdp-with-google-cloud/assets/150561267/55d1ddee-140a-47d2-8859-0dcf3c907f7d).

Nanti akan terlihat sepeerti ini :
![image](https://github.com/vtxcommunity/rdp-with-google-cloud/assets/150561267/44d8479d-eed5-4dd4-aa8d-1c723d8e5cf3)

Habis itu kalian tekan logo ini :
![image](https://github.com/vtxcommunity/rdp-with-google-cloud/assets/150561267/480b8443-75f4-48b5-9384-67b25d48b217)
## Langkah yang ke-3
Jika sudah berada di dalam shellnya, silahkan tulis perintah ini :
**docker run -p 6070:80 dorowu/ubuntu-desktop-lxde-vnc**
![image](https://github.com/vtxcommunity/rdp-with-google-cloud/assets/150561267/0696bf79-c03c-463d-b2d2-8ac4c5beb4da)
setelah itu enter dan tunggu sampai prosesnya selesai.

Jika sudah selesai, kalian ganti portnya dulu. Cara gantinya klik logo web preview dan klik tulisan change port seperti ini :
![image](https://github.com/vtxcommunity/rdp-with-google-cloud/assets/150561267/c1275949-8a31-44fa-8a9b-ca219d5a2e64)

Ubah portnya menjadi **6070**<br>
![image](https://github.com/vtxcommunity/rdp-with-google-cloud/assets/150561267/76fadc35-8c6b-48da-b897-06a59923ab1b)

Udah deh jadi
![image](https://github.com/vtxcommunity/rdp-with-google-cloud/assets/150561267/1ee0de45-df2e-40ef-ba66-aab934a127e5)
gampang kan? kalau gak gampang ya siapa tau nanti jadi gampang hehe


<h5>© Copyright by VTX Community & MJ</h5>

