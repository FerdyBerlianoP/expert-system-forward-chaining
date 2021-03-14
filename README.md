# expert-system-forward-chaining
This project is to learn how to make simple expert system with forward chaining methode use for python language

#analisa oleh saya ferdy berliano putra
pada program sispakMaint adalah kasus forward chaining kita mencari tahu penyakit yang kita alami melalui gejala yang di alami dan nantinya akan mendapatkan penyakit apa yg di alami berdasarkan aturan yang sudah ditentukan

gejalanya yaitu
1)Demam mendadak tinggi (38-40 C)
2)Demam tiba-tiba turun
3)Kebocoran pembuluh darah
4)Sakit kepala berat

sedangkan aturannya yaitu 
1) jika mengalami gejala 1,2,3 maka mengalami Demam Berdarah
2) jika mengalami gejala 1,2 maka mengalami Malaria
3) jika mengalami gejala 1,3 maka mengalami Chikungunya
4) jika mengalami gejala 2,4 maka mengalami Kaki Gajah
5) jika mengalami gejala 2 maka mengalami Demam Penyakit Kuning
6) jika mengalami gejala 1 maka mengalami Flu biasa

jadi ketika menjalankan programnya lalu kita memasukkan gejalanya 
jika mengalami gejala 1, 2, dan 3 maka kita mengalami penyakit demam berdarah
jika hanya mengalami gejala 1 dan 2 maka kita mengalami penyakit Malaria
jika hanya mengalami gejala 1 dan 3 maka kita mengalami penyakit Chikungunya
jika hanya mengalami gejala 2 dan 4 maka kita mengalami penyakit Kaki Gajah
jika hanya mengalami gejala 2 maka kita mengalami penyakit Demam Penyakit Kuning
jika hanya mengalami gejala 1 maka kita mengalami penyakit Flu biasa

#backward chaining
pada backward_chaining.py adalah kasus backward chaining dimana Basis pengetahuan adalah sekumpulan rumus terbatas dari tiga bentuk
saat kita menjalankan program tersebut masukkan # untuk melanjutkan ekseskusi