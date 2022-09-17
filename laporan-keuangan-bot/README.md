# laporan-keuangan-bot
Laporan keuangan, pencatatan pengeluaran dengan Bot Telegram yang terintegrasi dengan Google Spreadsheet

<img src="https://user-images.githubusercontent.com/101353193/181287924-5cb3b590-d841-4a52-a4a0-f412072ce246.jpg" width="45%"> <img src="https://user-images.githubusercontent.com/101353193/181287939-faaeaf1d-7064-40f4-93cf-e3318a93a957.jpg" width="45%">

# Mulai

## Buat Bot telegram
1. Buka telegram search @BotFather
2. Create New Bot /newbot
3. Masukkan nama kemudian username.
4. Setelah berhasil maka akan mendapatkan Bot Token.

## Buat Spreadsheet dengan kolom:
1. ID
2. Tanggal
3. Kategori
4. Item
5. Harga
6. ID Pelapor
7. Nama Pelapor

## Buat App Script 
1. Buka index.gs
2. Sesuaikan Token, Spreadsheet URL, Nama sheet, dan Pengguna bot (Chat ID*)
3. Deploy sebagai Web app, dan simpan urlnya

## Set webhook Bot Telegram
1. Buka di browser https://api.telegram.org/bot[token]/setwebhook?url=[url hasil deploy]

## *Note:
Untuk mendapatkan Chat ID, buka telegram, search @getYourID_bot atau https://t.me/getyourid_bot
