# Final-Project-Algorith-Pseudocode
FLOWCHART

![Flowchart Sistem kasir (memasukan item dan auto calculate total harga)](https://user-images.githubusercontent.com/127107237/225240724-f289d7da-fb77-4fe4-a0a5-1fc276521906.png)


PSEUDECODE
FINAL PROJECT-Algorithm & Pseudocode - Assignment
FE4249027-Azhar Fauzan Nugroho

START
WHILE true DO
    SHOW "Masukkan Nama Barang"
    READ nama_barang
    SHOW "Masukkan Harga Barang"
    READ harga_barang
    SHOW "Masukkan Jumlah Barang"
    READ jumlah_barang
    total_harga = harga_barang * jumlah_barang
    SHOW "Total Harga: " + total_harga
    SHOW "Apakah ingin memasukkan barang lain? (y/n)"
    READ jawaban
    IF jawaban == "n" THEN
        EXIT WHILE
    ELSE IF jawaban == "y" THEN
        CONTINUE WHILE
    ELSE
        SHOW "Jawaban tidak valid. Silakan masukkan 'y' atau 'n'"
        CONTINUE WHILE
    END IF
END WHILE
SHOW "Terima kasih telah berbelanja di Toko ini"

