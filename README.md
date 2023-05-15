# lexicon-labeling-lstm
Laporan Penelitian "Performance of Lexical Resource and Manual Labeling on Long Short-Term Memory Model for Text Classification"

Awalan : Laporan penlitian ini telah terbit di JITEKI (Jurnal Ilmiah Teknik Elektro Komputer dan Informatika (JITEKI) - Vol. 9, No. 1, March 2023, pp. 74-84

Abstrak (Translate) : 
Pemberian label data adalah aspek penting dalam analisis sentimen yang melibatkan pemberian label pada data teks untuk mencerminkan sentimen yang diungkapkan. Metode tradisional dalam memberi label data melibatkan annotasi manual oleh manusia, yang bisa memakan waktu dan biaya jika menghadapi volume data teks yang besar. Automasi dari proses pemberian label data dapat dicapai melalui penggunaan sumber daya leksikon, yang terdiri dari kamus atau basis data kata dan frasa yang sudah diberi label sentimen. Kontribusi dari penelitian ini adalah evaluasi kinerja sumber daya leksikon dalam pemberian label pada dokumen. Evaluasi bertujuan untuk memberikan wawasan mengenai akurasi penggunaan sumber daya leksikon dan memberikan informasi bagi penelitian selanjutnya. Dalam penelitian ini, dataset yang tersedia secara publik digunakan dan diberi label negatif, netral, dan positif. Untuk menghasilkan label baru, sumber daya leksikon seperti VADER, AFINN, SentiWordNet, dan Liu & Hu digunakan. Kemudian, sebuah model LSTM dilatih menggunakan label-label yang baru dihasilkan. Kinerja model yang dilatih dievaluasi dengan mengujinya pada data yang sudah diberi label manual. Penelitian ini menemukan bahwa pemberian label manual menghasilkan akurasi tertinggi sebesar 0,79, 0,80, dan 0,80 untuk tahap pelatihan, validasi, dan pengujian secara berturut-turut. Hal ini kemungkinan disebabkan oleh penciptaan label data uji secara manual, yang memungkinkan model untuk belajar dan menangkap pola-pola yang seimbang. Model yang menggunakan sumber daya leksikon (VADER dan AFINN) memiliki akurasi lebih rendah sebesar 0,54 dan 0,56. SentiWordNet memiliki akurasi terendah di antara semua model dengan nilai 0,49, dan model Liu & Hu memiliki skor pengujian terendah sebesar 0,26. Penelitian kami menunjukkan bahwa sumber daya leksikon saja tidak cukup untuk pemberian label data sentimen karena mereka bergantung pada kamus yang telah ditentukan sebelumnya dan mungkin tidak sepenuhnya mampu menangkap konteks kata dalam sebuah kalimat. Oleh karena itu, pemberian label manual diperlukan sebagai pelengkap metode berbasis leksikon untuk mencapai hasil yang lebih baik.
