# bai-app
Sistem Aplikasi BAI

*Applikasi -> JAVA
  Saat Hosting App Pastikan
  -konfigurasi ulang file PHP di folder FILES sesuai hosting
  -ubah url di file java sesuai hosting baru (fragment,model dll)
  -periksa kembali database terutama gambar pastikan sesuai hosting
  -pastikan hosting ada SSL
  
*Web Admin ->NodeJS(BE)-bootstrap(ui)
  PERHATIAN!!
  -NodeJS tidak bisa dihosting silahkan upload di VPS
  -menjalankan NodeJS
    npm i 
    sequelize db:drop
    sequelize db:create
    sequelize db:migrate
    nodemon
  
*Developer
  -App cuma support hosting dengan SSL silahkan dikembangkan (android volly http)
  -web_admin cuma support VPS
  -FrontEnd app bisa dikembangkan lagi
