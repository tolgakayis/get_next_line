# get_next_line
In this 42 Istanbul project, I learned the concept of static variables. The function here, gets me one line at a time from the file that is given, whenever it's called. Also, it is completely memory-leak free. The get_next_line() function is given a file descriptor which is read by the helper functions and added to the static variable. It works with any count of BUFFER_SIZE. It can also read from standart input. If you want to read from multiple file descriptors you should use the bonus part files. It uses an array of strings for the static variable and it keeps the read lines separately.

Bu 42 İstanbul projesinde statik değişken kavramını öğrendim. Buradaki fonksiyon, ne zaman çağrılsa, verilen dosyadan bana her seferinde bir satır getiriyor. Ayrıca, tamamen memory-leak bulunmaz. get_next_line() fonksiyonuna, yardımcı fonksiyonlar tarafından okunan ve statik değişkene eklenen bir dosya tanıtıcı verilir. Herhangi bir BUFFER_SIZE sayısıyla çalışır. Standart girişten de okuyabilir. Birden fazla dosya tanıtıcıdan okumak istiyorsanız, bonus dosyalarını kullanmalısınız. Statik değişken için bir dizi listesi kullanır ve okunan satırları ayrı tutar.
