<h2>A. INSTALASI WINDOWS SERVER 2022</h2>

1. Download ISO windows server 2022

   https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022

2. Buka Virtual Box lalu buatlah machine baru dan jalankan


3. Memilih bahasa, waktu, keyboard input yang diinginkan lalu -> NEXT

   <img width="514" alt="1" src="https://user-images.githubusercontent.com/93085602/143668525-e5ef3e78-4393-4ea8-ad82-38630e447c84.PNG">

4. Install now

   <img width="516" alt="2" src="https://user-images.githubusercontent.com/93085602/143668541-01ea23e1-4e29-4473-9daf-f368d02db41c.PNG">

5. Pilihlah <b>"windows server 2022 standard Evaluation"</b> lalu -> NEXT

   <img width="514" alt="4" src="https://user-images.githubusercontent.com/93085602/143668546-9f3a98c7-b9d0-4058-9056-e484c304fcb5.PNG">

6. Centang checkbox <b>"I agree" lalu</b> -> NEXT

   <img width="512" alt="5" src="https://user-images.githubusercontent.com/93085602/143668551-59c2f600-59ea-4817-bc06-02ff061a76a3.PNG">

7. Memilih tipe instalasi, pilihlan <b>"Custom: install"</b>

   <img width="514" alt="6" src="https://user-images.githubusercontent.com/93085602/143668558-d47fa4cd-178e-481f-bea7-e8c46cc8aadf.PNG">

8. Menentukan drive yang akan digunakan lalu -> NEXT
   
   <img width="513" alt="7" src="https://user-images.githubusercontent.com/93085602/143668564-52efa107-c1de-48f5-b91d-f005a884f194.PNG">

9. Tunggu hingga instalasi selesai lalu -> <b>restart now</b>

   <img width="511" alt="8" src="https://user-images.githubusercontent.com/93085602/143668566-6ebd916e-77c2-4a5a-b4a9-08e45b859122.PNG">
   <img width="514" alt="9" src="https://user-images.githubusercontent.com/93085602/143668573-da51cc50-e8b9-442c-9087-0bd4f55d151c.PNG">

10. <b>Windows getting ready</b>

    <img width="516" alt="11" src="https://user-images.githubusercontent.com/93085602/143668571-8a9f6dcd-6c5b-44d7-b93a-979544d3ebd2.PNG">

11. Masukkan password yang mencakup <b>(capslock & symbol & angka)</b> lalu -> <b>finish</b>

    <img width="514" alt="12" src="https://user-images.githubusercontent.com/93085602/143668579-de8721b9-6e53-429f-a3ea-967300e25542.PNG">

12. Pilih menu <b>input -> keyboard -> Insert Ctrl+Alt+Del</b>

    <img width="515" alt="Screenshot (155)" src="https://user-images.githubusercontent.com/93085602/143668594-1e49aaef-c87e-4db3-9b67-8fc8c90e955c.png">

13. Masukkan kata sandi yang sudah dibuat sebelumnya

    <img width="514" alt="22" src="https://user-images.githubusercontent.com/93085602/143668602-6c2b92e4-5d20-4b91-8c3d-a7833dc28c13.PNG">

14. Buka file explorer -> CD Drive(D)VirtualBox Guest Additions-> install aplikasi <b>"VBoxWindowsAdditions"</b>

    <img width="516" alt="15" src="https://user-images.githubusercontent.com/93085602/143668615-4d2586b4-6d2c-4ba0-a600-0e46a82a5108.PNG">

15. Pilih file location -> NEXT

    <img width="515" alt="17" src="https://user-images.githubusercontent.com/93085602/143668924-325ad73e-96f8-44af-badc-0898d2f0d481.PNG">

16. Install 

    <img width="516" alt="18" src="https://user-images.githubusercontent.com/93085602/143668633-95fa49d9-14f0-498e-ace7-e6243eedfe4f.PNG">

17. Centang checkbox dan pilih install

    <img width="515" alt="20" src="https://user-images.githubusercontent.com/93085602/143668643-cbfafb68-68df-4832-9bc1-5f9f2db9efea.PNG">

18. Jika PC tidak digunakan disaat itu, pilihlah <b>"reboot now" -> finish</b>

    <img width="514" alt="21" src="https://user-images.githubusercontent.com/93085602/143668647-ccfd78e2-1937-4a52-ac59-a5f9eae38f86.PNG">

19. Pilih menu <b>input -> keyboard -> Ctrl+Alt+Del</b> lalu masukkan password

    <img width="515" alt="Screenshot (155)" src="https://user-images.githubusercontent.com/93085602/143668650-3b9ac982-74f3-4c04-88e1-cf40e3d9afa8.png">

20. Tampilan berhasil install windows server 2022

    <img width="515" alt="23" src="https://user-images.githubusercontent.com/93085602/143668653-53b423e9-199c-42d8-914d-f218c926faac.PNG">



<h2>B. INSTALASI ACTIVE DIRECTORY DOMAIN SERVICE</h2>



1. Buka <b>Command Prompt</b> lalu cek ipconfig

<img width="505" alt="1b" src="https://user-images.githubusercontent.com/93085602/143680662-cc04c088-d0b9-49fe-a383-3e0e26b0813c.PNG">

2. Search <b>"Server Manager" </b>

<img width="512" alt="server" src="https://user-images.githubusercontent.com/93085602/143680731-d9ce6018-eba7-40a9-a7d0-82ee2c0ea651.PNG">

3. Buka Server Manager

<img width="514" alt="2b" src="https://user-images.githubusercontent.com/93085602/143680755-dfc028c7-47f4-4ec3-a3c4-080c9c549e83.PNG">

4. Pilih menu <b>"Manage" -> "Add Roles and Features"</b>

<img width="514" alt="1d" src="https://user-images.githubusercontent.com/93085602/143680816-5dda13b7-170d-4d4f-9313-799cb126d7d5.PNG">

5. Lalu NEXT 

<img width="516" alt="3b" src="https://user-images.githubusercontent.com/93085602/143680800-01496984-7212-4468-8bc3-fdd9c773db49.PNG">

6. Selanjutnya kita akan menggunakan aturan default dari sistem <b>"Role-based or feature-based installation"</b> lalu NEXT

<img width="512" alt="4b" src="https://user-images.githubusercontent.com/93085602/143680857-6b5a6115-904a-47f6-8653-b7233de29fb2.PNG">

7. Klik <b>"select a server from the server pool"</b> lalu akan ada tampilan default penyimpanan yang akan digunakan lalu -> NEXT

<img width="514" alt="5b" src="https://user-images.githubusercontent.com/93085602/143681026-c9fc1210-28ce-4683-8c86-d8963f1d6763.PNG">

8. Pada Server Roles, pilihlah checkbox <b>"Active Directory Domain Services"</b>

<img width="513" alt="6b" src="https://user-images.githubusercontent.com/93085602/143681117-14012582-cc01-49f3-ad04-2ec061ed9a80.PNG">

9. Akan muncul notif penjelasan dari <b>"Active Directory Domain Services"</b>. Centang <b>"Include management tools"</b> lalu -> <b>"Add Feature"</b> lalu -> NEXT

<img width="515" alt="7b" src="https://user-images.githubusercontent.com/93085602/143681125-51e995c1-c4fc-460a-bcdb-a787063fc935.PNG">

10. Klik checkbox <b>"Group Policy Management"</b> lalu -> NEXT

<img width="514" alt="9b" src="https://user-images.githubusercontent.com/93085602/143681172-cc57a2c4-03a8-4dab-bd29-1a4934dcf8fb.PNG">

11. Akan ada tampilan penjelasan dari <b>"Active Directory Domain Services"</b> lalu -> NEXT

<img width="512" alt="10b" src="https://user-images.githubusercontent.com/93085602/143681206-e67fc221-fa6e-42f5-b8ac-64cf7575cccf.PNG">

12. Pilih INSTALL

<img width="515" alt="11b" src="https://user-images.githubusercontent.com/93085602/143681221-98b07f03-4c76-44ce-ad20-3277733c4838.PNG">

13. Selesai Instalasi, kita dapat mengabaikan pesan yang ditampilkan

<img width="513" alt="14b" src="https://user-images.githubusercontent.com/93085602/143681264-deb73121-664e-4e23-9775-f3940ff04ae4.PNG">

14. Jika <b>"Active Directory Domain Services"</b> sudah terinstall maka akan tampil seperti berikut

<img width="513" alt="15b" src="https://user-images.githubusercontent.com/93085602/143681304-58fc464a-fd72-407f-97e3-8f93401a7a3b.PNG">



<h2>C. INSTALASI DNS SERVER</h2>


1. Buka Server Manager

<img width="513" alt="15b" src="https://user-images.githubusercontent.com/93085602/143681555-74c0ec40-0dd3-4e10-b8d9-f7dd5c7ff430.PNG">

2. Pilih menu <b>"manage" -> "Add Roles and Features"</b> lalu NEXT

<img width="516" alt="2c" src="https://user-images.githubusercontent.com/93085602/143681592-cfdc9a26-31e6-419c-b3a2-7cfb85a38fbf.PNG">

3. Selanjutnya kita akan menggunakan aturan default dari sistem <b>"Role-based or feature-based installation"</b> lalu NEXT

<img width="512" alt="4b" src="https://user-images.githubusercontent.com/93085602/143680857-6b5a6115-904a-47f6-8653-b7233de29fb2.PNG">

4. Klik <b>"select a server from the server pool"</b> lalu akan ada tampilan default penyimpanan yang akan digunakan lalu -> NEXT

<img width="514" alt="5b" src="https://user-images.githubusercontent.com/93085602/143681026-c9fc1210-28ce-4683-8c86-d8963f1d6763.PNG">

5. Pilih checkbox <b>"DNS Server"</b>

<img width="513" alt="5c" src="https://user-images.githubusercontent.com/93085602/143681658-781c85e1-9a9e-41b9-8e30-fb5dd7af7f7e.PNG">

6. Akan muncul tampilan fungsi dari DNS Server lalu centang "Include" selanjutnya <b>"Add Feature"</b>

<img width="514" alt="6c" src="https://user-images.githubusercontent.com/93085602/143681684-cf3edf9e-9ed0-44be-be4b-9909686d76f1.PNG">

7. Akan muncul notifikasi apakah kita tetap lanjut menginstall DNS Server. Pilih <b>"Continue"</b> lalu NEXT

<img width="513" alt="7c" src="https://user-images.githubusercontent.com/93085602/143681722-e844f4cb-539e-4765-a12e-a3fcce1dcf9e.PNG">

8. Lalu NEXT

<img width="512" alt="9c" src="https://user-images.githubusercontent.com/93085602/143681734-70d9d260-0c9f-40f6-b913-c14b93c79168.PNG">

9. NEXT

<img width="511" alt="10c" src="https://user-images.githubusercontent.com/93085602/143681739-0af040c5-2349-4e7e-bac6-40823ae4851d.PNG">

10. INSTALL

<img width="513" alt="11c" src="https://user-images.githubusercontent.com/93085602/143681747-43175ed4-0016-4fd9-ab63-a61c3b8e1836.PNG">

11. Instalasi selesai

<img width="512" alt="13c" src="https://user-images.githubusercontent.com/93085602/143681758-a030eb29-2b5d-4e2d-8731-f3d5c69b9e3b.PNG">

12. Setelah instal DNS Server, pada server manager akan muncul berikut

<img width="514" alt="13e" src="https://user-images.githubusercontent.com/93085602/143681792-062cb1f4-1d96-4f2a-bd8f-500a11c25939.PNG">



<h2>D. INSTALASI NET FRAMEWORK 3.5</h2>






