Fungsi Tiap System Call:

1. read
   Fungsi: Membaca isi file atau direktori.
   Contoh di output: read(3, "\177ELF\2\1\1\0..."...)
   Mode: Kernel mode → karena membaca file dari sistem (disk atau cache).
   
2. write
   Fungsi: Menulis data ke terminal.
   Contoh di output: write(1, "adduser.conf\t..."...)
   Mode: Kernel mode → menulis ke stdout (biasanya terminal), yang juga dikelola oleh kernel.
 

