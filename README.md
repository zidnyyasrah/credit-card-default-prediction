# credit card default prediction

Pada kesempatan kali ini saya akan membuat model classification untuk memprediksi status default pada kartu kredit, dataset yang digunakan adalah credit_card_default dari bigquery public data. Dataset berisi informasi tentang usia, gender, tingkat pendidikan dan juga informasi mengenai kartu kredit seperti limit, billing, jumlah pembayaran dan status default dari bulan april sampai september 2005.


Berdasarkan hasil evaluasi, saya menemukan bahwa model tersebut mendapatkan skor precision yang cukup tinggi untuk not defaultnya, artinya kemampuan model dalam mengklasifikasikan dengan benar orang yang tidak akan melakukan default. Namun, saya juga melihat bahwa model tersebut memiliki recall yang rendah untuk yang defaultnya, artinya model cenderung melewatkan beberapa kasus default yang sebenarnya.

Hasil ini mengindikasikan bahwa model memiliki kemampuan dalam mengidentifikasi orang yang tidak berisiko default, tapi perlu ditingkatkan dalam mengenali dengan lebih akurat kasus-kasus default. Meskipun model memiliki tingkat akurasi yang baik secara keseluruhan, saya rasa kinerja model dalam mengklasifikasikan kasus default masih belum praktikal untuk digunakan dikehidupan nyata.
