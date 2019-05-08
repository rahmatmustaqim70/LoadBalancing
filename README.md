A.Jalankan perintah:
docker-compose up -d

B. Kemudian lihat proses dari 3 container backend dengan perintah:
docker ps

C. Akses langsung ke halaman web dengan port 8080

D. Lalu kita akan melakukan remote ke masing-masing container backend:
1. Buka terminal baru
2. Jalankan perintah: sudo docker exec -it <nama_container> bash
3. Install express js: npm install express
4. Jalankan aplikasi js: node index.js
5. Refresh halaman web pada port 8080, anda akan mendapatkan hasil output "i just received get request". Jadi setiap kali anda refresh halaman web, akan mendapatkan pesan tersebut.
6. Jalankan langkah D. 1-4 pada container berbeda, lalu lihat hasil output setelah anda refresh web.

