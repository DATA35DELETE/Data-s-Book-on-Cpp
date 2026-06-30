# Data's Book on C++
 
## C++
 
### Ön Söz
- Ben kimim?
- Bu Data's Book on C++ nedir?
- Bu dokümantasyon ne öğretecek?
 
---
 
### C++ : Giriş
- **Yazılım Nedir?**
  - **Donanım Nedir?**
  - **Low-Level ve High-Level**
  - **Yazılım Dilleri**
- **C++ Nedir?**
  - **Kısa Tarihçesi**
  - **C ile Farkı**: Neden C++'a geçilir? Ne ekler?
  - **Nasıl Kullanılır?**
  - **Kullanım Alanları**
  - **Prosedürel ve Nesne Yönelimli Programlama**: Nedir? Avantajları
- **C++'ı Kurma**
  - **G++ Kurulumu**: G++ Nedir? GCC ile Farkı? Nasıl Kurulur?
  - **IDE Seçimi**: VS Code
  - **İlk Proje**
- **İlk Kod**: cout ve cin
  - **iostream**: Tanım. `std::cout`, `std::cin`, `std::endl`. Örnek.
  - **C'den Farkı**: printf vs cout. scanf vs cin. Örnek.
  - **Parametreli Programlar Yazma**: argc ve argv. Tanım. Örnek.
- **Derleme Süreci**: Tanım. Neden Önemli?
  - **Ön İşleme (Preprocessor) (.i)**: Makro genişletme. Header birleştirme. Örnek.
  - **Derleme (.o)**: Object dosyası. Semboller. Örnek.
  - **Linking**: Object dosyalarını birleştirme. Static vs Dynamic. Link Hataları. Örnek.
  - **C++11 / C++14 / C++17 / C++20**: Standartlar. `-std=c++17` bayrağı. Örnek.
 
---
 
### C++ : Değişkenler
- **Değişkenler Nedir?**: Tanımı. Kullanım Senaryoları
- **Sayısal Değişkenler**
  - **short**: Tanım. unsigned short. Örnek.
  - **int**: Tanım. unsigned int. Örnek.
  - **long**: Tanım. long long. unsigned long. Örnek.
  - **float**: Tanım. Örnek.
  - **double**: Tanım. long double. Örnek.
- **İsimlendirme Kuralları**: Tablo Halinde
- **Char**: Tanım. Örnek.
- **bool**: Tanım. true/false. C ile Farkı. Örnek.
- **auto**: Tanım. Tip Çıkarımı. Örnek.
- **Depolama Sınıfları**: Tanım
  > Tablo Halinde
  - **static**
  - **extern**
  - **register**
- **Kullanıcıdan Değişken Alma**: `std::cin`. Örnek.
- **Değişkenlerin Türünü Değiştirme**: Tanım.
  - **int → float**: Örnek.
  - **float → int**: Örnek.
- **Sabitlik**: `const`. `constexpr`. `#define`. Farkları. Örnek.
- **typedef ve using**: Tanım. Farkları. Örnek.
 
---
 
### C++ : Operatörler
- **Operatörler Nedir?**: Tanımı. Kullanım Senaryoları
- **Atama Operatörü**: Tanım. Örnek.
- **Aritmetik Operatörler**
  - **+**: Tanım. Örnek.
  - **-**: Tanım. Örnek.
  - **\***: Tanım. Örnek.
  - **/**: Tanım. Örnek.
  - **%**: Tanım. Örnek.
  - **Bileşik Atama Operatörleri**: +=, -=, \*=, /=. Örnek.
- **Yorum Satırı**: // ve /* */. Tanım. Örnek.
- **Karşılaştırma Operatörleri**
  - **<, >, <=, >=, ==, !=**: Tanım. Örnek.
- **Mantıksal Operatörler**
  - **!**: Tanım. Örnek.
  - **&&**: Tanım. Örnek.
  - **||**: Tanım. Örnek.
- **Bitwise Operatörler**: &, |, ^, ~, <<, >>. Tanım. Örnek.
- **Ternary**: Tanım. Örnek. Avantajı.
- **sizeof Operatörü**: Tanım. Örnek.
- **Operatör Aşırı Yükleme (Operator Overloading)**: Tanım. Kullanım Senaryoları. Örnek.
- **Yazdırma Komutunda cout ile Veri Yazdırma**: Tanım. Örnek.
- **C++ Cast Operatörleri**: `static_cast`, `dynamic_cast`, `const_cast`, `reinterpret_cast`. Örnek.
 
---
 
### C++ : Karar Yapıları
- **Karar Yapısı Nedir?**: Tanım. Program Akışı. Örnek.
- **If-Else if-Else**: Tanım. Örnek.
- **Switch-Case-Default**: Tanım. Örnek.
 
---
 
### C++ : Döngü Yapıları
- **Döngü Nedir?**: Tanım. Örnek.
- **while**: Tanım. Örnek.
- **for**: Tanım. Örnek.
- **Range-Based for**: Tanım. C++11. Örnek.
- **break ve continue**: Tanım. Örnek.
 
---
 
### C++ : Diziler ve Stringler
- **Dizi Nedir?**: Tanım. Örnek. Avantajı.
- **Tek Boyutlu Diziler**: Tanım. Örnek.
  > Temel İşlemler
- **Çok Boyutlu Diziler**: Tanım. Örnek.
  > Temel İşlemler
- **std::array**: Tanım. C dizisi ile Farkı. Örnek.
- **String Yapısı**: Tanım. C-string vs `std::string`. Örnek.
  > string Metodları
- **std::string Fonksiyonları**: `length`, `substr`, `find`, `replace`, `append`, `compare`. Örnek.
- **std::string_view**: Tanım. Kullanım Senaryosu. Örnek. (C++17)
 
---
 
### C++ : Pointerlar ve Referanslar
- **Pointer Nedir?**: Tanım. Bellek Adresi. Örnek.
- **Pointer Tanımlama**: \* ve & operatörleri. Örnek.
- **Referans (&)**: Tanım. Pointer ile Farkı. Örnek.
- **Pointer Aritmetiği**: Tanım. Örnek.
  - **Char Dizisinde Pointer Aritmetiği**
- **Pointer ve Fonksiyonlar**: Call by Reference. Referans ile Karşılaştırma. Örnek.
- **Çift Pointer (Double Pointer)**: Tanım. Örnek.
- **NULL ve nullptr**: Tanım. C ile Farkı. Neden `nullptr`? Örnek.
- **Akıllı Pointerlar (Smart Pointers)**: Tanım. Neden Kullanılır?
  - **unique_ptr**: Tanım. Kullanım. Örnek.
  - **shared_ptr**: Tanım. Referans Sayımı. Örnek.
  - **weak_ptr**: Tanım. Döngüsel Referans Sorunu. Örnek.
- **Function Pointers**: Tanım. Kullanım Senaryoları.
  - **Tanımlama ve Kullanma**: Sözdizimi. Örnek.
  - **std::function**: Tanım. Function Pointer ile Farkı. Örnek.
  - **Callback Yapısı**: Tanım. Örnek.
  - **Function Pointer Dizisi**: Tanım. Örnek.
 
---
 
### C++ : Hata Yönetimi
- **Hata Yönetimi Nedir?**
- **errno**: Tanım. Örnek.
- **perror ve strerror**: Tanım. Örnek.
- **Return Kodları ile Hata Yönetimi**: Tanım. Örnek.
- **assert**: Tanım. Örnek.
- **İstisna Yönetimi (Exception Handling)**: Tanım. C ile Farkı.
  - **try / catch / throw**: Sözdizimi. Örnek.
  - **std::exception**: Tanım. Türetme. Örnek.
  - **Özel Exception Sınıfı Yazma**: Tanım. Örnek.
  - **noexcept**: Tanım. Kullanım. Örnek.
 
---
 
### C++ : Fonksiyonlar
- **Fonksiyon Nedir?**: Tanım. main Fonksiyonu.
- **void'li Fonksiyonlar**: Tanım. Örnek.
- **Return'lü Fonksiyonlar**: Tanım. Örnek.
- **Parametreli Fonksiyonlar**: Tanım. Örnek.
- **Varsayılan Parametreler (Default Parameters)**: Tanım. Örnek.
- **Fonksiyon Aşırı Yükleme (Function Overloading)**: Tanım. Örnek.
- **Özyinelemeli Fonksiyonlar (Recursion)**: Tanım. Örnek.
- **Inline Fonksiyonlar**: Tanım. Makro ile Farkı. Örnek.
- **Lambda Fonksiyonlar**: Tanım. Sözdizimi. Capture List. Örnek. (C++11)
- **Fonksiyon Şablonları (Function Templates)**: Tanım. Örnek.
- **Fonksiyon Prototipleri**: Tanım. Neden Gerekli? Örnek.
 
---
 
### C++ : Nesne Yönelimli Programlama (OOP)
- **OOP Nedir?**: Tanım. Neden Kullanılır? C ile Karşılaştırma.
- **Sınıf (Class) ve Nesne (Object)**:
  - **Class Tanımlama**: Tanım. Sözdizimi. Örnek.
  - **Erişim Belirleyiciler**: `public`, `private`, `protected`. Tanım. Örnek.
  - **Üye Değişkenler ve Fonksiyonlar**: Tanım. Örnek.
- **Constructor ve Destructor**:
  - **Constructor**: Tanım. Türleri. Örnek.
  - **Destructor**: Tanım. Bellek Yönetimi. Örnek.
  - **Copy Constructor**: Tanım. Deep Copy vs Shallow Copy. Örnek.
  - **Move Constructor**: Tanım. C++11. Örnek.
- **this Pointer**: Tanım. Kullanım. Örnek.
- **Kapsülleme (Encapsulation)**: Tanım. Getter/Setter. Örnek.
- **Kalıtım (Inheritance)**:
  - **Tek Kalıtım**: Tanım. Sözdizimi. Örnek.
  - **Çok Kalıtım**: Tanım. Diamond Problem. Örnek.
  - **protected Kalıtım**: Tanım. Örnek.
- **Çok Biçimlilik (Polymorphism)**:
  - **Fonksiyon Overriding**: Tanım. Örnek.
  - **virtual Fonksiyonlar**: Tanım. vtable. Örnek.
  - **Saf Sanal Fonksiyon (Pure Virtual)**: `= 0`. Soyut Sınıf. Örnek.
  - **override ve final**: Tanım. C++11. Örnek.
- **Soyutlama (Abstraction)**: Tanım. Interface Benzeri Yapı. Örnek.
- **Arkadaş Fonksiyon (Friend Function)**: Tanım. Kullanım Senaryosu. Örnek.
- **static Üyeler**: Tanım. Sınıf Değişkeni. Örnek.
 
---
 
### C++ : Yapılar (Structs) ve Enum
- **Struct Nedir?**: Tanım. C ile Farkı. Class ile Farkı.
- **Struct Tanımlama ve Kullanma**: Tanım. Örnek.
- **Pointer ile Struct Kullanımı**: Tanım. -> operatörü. Örnek.
- **İç İçe Struct**: Tanım. Örnek.
- **Union**: Tanım. Struct ile Farkı. Örnek.
- **enum**: Tanım. Örnek.
- **enum class**: Tanım. enum ile Farkı. Tür Güvenliği. Örnek.
 
---
 
### C++ : Şablonlar (Templates)
- **Template Nedir?**: Tanım. Neden Kullanılır? Kullanım Senaryoları.
- **Fonksiyon Şablonları**: Tanım. Örnek.
- **Sınıf Şablonları**: Tanım. Örnek.
- **Template Özelleştirme (Specialization)**: Tanım. Örnek.
- **Variadic Templates**: Tanım. C++11. Örnek.
 
---
 
### C++ : STL (Standard Template Library)
- **STL Nedir?**: Tanım. Bileşenler. Kullanım Senaryoları.
- **Konteynerler (Containers)**:
  - **std::vector**: Tanım. Dinamik Dizi. Örnek.
    > Metodları
  - **std::list**: Tanım. Doubly Linked List. Örnek.
    > Metodları
  - **std::deque**: Tanım. Örnek.
  - **std::stack**: Tanım. LIFO. Örnek.
    > Metodları
  - **std::queue**: Tanım. FIFO. Örnek.
    > Metodları
  - **std::priority_queue**: Tanım. Heap. Örnek.
  - **std::set / std::multiset**: Tanım. Sıralı Küme. Örnek.
    > Metodları
  - **std::map / std::multimap**: Tanım. Anahtar-Değer. Örnek.
    > Metodları
  - **std::unordered_map**: Tanım. Hash Tablosu. map ile Farkı. Örnek.
  - **std::unordered_set**: Tanım. Örnek.
- **İteratörler (Iterators)**: Tanım. Türleri. Örnek.
- **Algoritmalar (Algorithms)**:
  - **std::sort**: Tanım. Örnek.
  - **std::find**: Tanım. Örnek.
  - **std::for_each**: Tanım. Örnek.
  - **std::transform**: Tanım. Örnek.
  - **std::count / std::count_if**: Tanım. Örnek.
  - **std::accumulate**: Tanım. Örnek.
- **std::pair ve std::tuple**: Tanım. Örnek.
- **std::optional**: Tanım. C++17. Örnek.
- **std::variant**: Tanım. C++17. Örnek.
 
---
 
### C++ : Bellek Yönetimi
- **Bellek Yönetimi Nedir?**: Stack vs Heap. Tanım. C ile Farkı.
- **Memory Layout**: Programın RAM'deki Yapısı. Görselleştirme.
  - **Text Segment**: Kod. Salt Okunur. Tanım.
  - **Data Segment**: Global ve Static Değişkenler. Initialized vs Uninitialized (BSS). Tanım.
  - **Stack**: Otomatik Ömürlü Değişkenler. LIFO. Stack Frame. Tanım.
  - **Heap**: Dinamik Bellek. new/delete. Tanım.
  - **Segment Hataları**: Segmentation Fault. Neden Olur? Örnek.
- **new ve delete**: Tanım. malloc/free ile Farkı. Örnek.
- **new[] ve delete[]**: Dizi Belleği. Örnek.
- **Akıllı Pointer ile Bellek Yönetimi**: RAII Prensibi. Tanım. Örnek.
- **Placement new**: Tanım. İleri Seviye Kullanım. Örnek.
- **Bellek Hataları**: Dangling Pointer. Buffer Overflow. Memory Leak. Örnek.
- **RAM'de İletişim (Shared Memory)**: Tanım. Kullanım Senaryoları.
  - **mmap**: Tanım. Örnek.
  - **POSIX Shared Memory**: shm_open. shm_unlink. Örnek.
  - **Windows Shared Memory**:
    - **File Mapping Nedir?**: CreateFileMapping. Tanım. Parametreler.
    - **Belleğe Bağlama**: MapViewOfFile. Tanım. Örnek.
    - **Bağlantıyı Kesme**: UnmapViewOfFile. CloseHandle. Örnek.
 
---
 
### C++ : Dinamik Liste Yapımı
- **Dinamik Liste Nedir?**: Tanım. Array ile Farkı. Kullanım Senaryoları.
- **Linked List**: Tanım. Node Yapısı. Örnek.
  - **Tek Yönlü (Singly)**: Tanım. Örnek.
  - **Çift Yönlü (Doubly)**: Tanım. Örnek.
  - **Dairesel (Circular)**: Tanım. Örnek.
- **Stack (Yığın)**: Tanım. LIFO. Örnek.
  > Metodları
- **Queue (Kuyruk)**: Tanım. FIFO. Örnek.
  > Metodları
- **Generic Liste**: Template ile genel liste. Örnek.
- **STL ile Liste Yapıları**: std::list, std::stack, std::queue. Karşılaştırma.
 
---
 
### C++ : Dosya İşlemleri
- **Dosya İşlemleri Nedir?**
- **fstream Kütüphanesi**: Tanım. `ifstream`, `ofstream`, `fstream`. C ile Farkı.
- **Dosya Açma ve Kapama**: `open()`. `close()`. Modlar. Örnek.
  > Metodları
- **Dosya Yazma İşlemleri**: `<<` operatörü. `write()`. Örnek.
  > Metodları
- **Dosya Okuma İşlemleri**: `>>` operatörü. `getline()`. `read()`. Örnek.
  > Metodları
- **Dosya Konumlandırma**: `seekg`. `seekp`. `tellg`. `tellp`. Örnek.
- **İkili (Binary) Dosyalar**: Tanım. Örnek.
- **std::filesystem**: Tanım. C++17. Kullanım Senaryoları.
  - **Dosya Varlık Kontrolü**: `exists()`. Örnek.
  - **Dosya Kopyalama/Taşıma**: `copy()`. `rename()`. Örnek.
  - **Klasör Oluşturma/Silme**: `create_directory()`. `remove_all()`. Örnek.
  - **Klasör İçeriğini Listeleme**: `directory_iterator`. Örnek.
  - **Dosya Boyutu ve Bilgisi**: `file_size()`. `last_write_time()`. Örnek.
- **Native Dosya İşlemleri**: Tanım. fstream vs OS API. Kullanım Senaryoları.
  - **Linux — .so Dosyaları**:
    - **Shared Object Nedir?**: .so ve .a Farkı. Dinamik vs Statik.
    - **Derleme**: g++ -shared -fPIC. Örnek.
    - **Yükleme (Runtime)**: dlopen. Tanım. Parametreler. Örnek.
    - **Sembol Çözümleme**: dlsym. Tanım. Örnek.
    - **Hata Yönetimi**: dlerror. Örnek.
    - **Kapatma**: dlclose. Bellek Yönetimi. Örnek.
    - **LD_LIBRARY_PATH**: Tanım. Kullanım. Örnek.
    - **ldd Komutu**: Bağımlılık Analizi. Örnek.
  - **Windows — .dll Dosyaları**:
    - **DLL Nedir?**: .dll ve .lib Farkı. Implicit vs Explicit Linking.
    - **DLL Oluşturma**: `__declspec(dllexport)`. Örnek.
    - **Implicit Linking**: .lib ile Derleme. Tanım. Örnek.
    - **Explicit Linking (Runtime)**: LoadLibrary. Tanım. Parametreler. Örnek.
    - **Sembol Çözümleme**: GetProcAddress. Tanım. Örnek.
    - **Hata Yönetimi**: GetLastError. FreeLibrary. Örnek.
    - **DllMain**: Tanım. DLL_PROCESS_ATTACH / DETACH. Örnek.
    - **Dependency Walker / dumpbin**: Bağımlılık Analizi. Örnek.
- **JSON Dosyası**: JSON Nedir?
  - **JSON Mantığı**: Tanım. Yapısı.
  - **nlohmann/json Kütüphanesi**: Kurulum. Örnek.
  - **JSON Oluşturma**: Örnek.
  - **JSON Yazma**: Örnek.
  - **JSON Okuma**: Örnek.
- **XML Dosyası**: XML Nedir?
  - **XML Mantığı**: Tanım. Yapısı. JSON ile Farkı.
  - **pugixml Kütüphanesi**: Kurulum. Örnek.
  - **XML Okuma**: `load_file()`. `child()`. Örnek.
  - **Node Gezinme**: Örnek.
  - **Attribute Okuma**: `attribute()`. Örnek.
  - **XPath ile Sorgulama**: Tanım. `select_nodes()`. Örnek.
  - **XML Yazma**: `append_child()`. `save_file()`. Örnek.
- **Zlib ile Sıkıştırılmış Dosyalar**: Tanım. Kullanım Senaryoları.
  - **Zlib Nedir?**: Kurulum. Örnek.
  - **Dosya Sıkıştırma**: deflate. Örnek.
  - **Dosya Açma**: inflate. Örnek.
  - **gzip Formatı**: Tanım. Örnek.
 
---
 
### C++ : Önişlemci (Preprocessor)
- **Önişlemci Nedir?**: Tanım. Derleme Süreci.
- **#include**: Tanım. <> ve "" Farkı. Örnek.
- **#define**: Tanım. Makro. Örnek.
- **#ifdef / #ifndef / #endif**: Koşullu Derleme. Örnek.
- **Header Dosyaları (.h / .hpp)**: Tanım. Oluşturma. Kullanım. Örnek.
- **Makro Fonksiyonlar**: Tanım. Inline ile Farkı. Örnek.
- **Önceden Tanımlı Makrolar**: `__FILE__`, `__LINE__`, `__DATE__`, `__TIME__`, `__cplusplus`. Örnek.
 
---
 
### C++ : CMake ile Kapsamlı Proje
- **CMake Nedir?**: Tanım. Makefile ile Farkı. Kullanım Senaryoları.
- **CMake Kurulumu**: Tanım. Örnek.
- **CMakeLists.txt**: Tanım. Temel Yapı. C++ Standartı Belirleme. Örnek.
- **Çoklu Dosya Projesi**: Tanım. Örnek.
- **Kütüphane Oluşturma**: Static vs Shared. Örnek.
- **Dış Kütüphane Bağlama**: `find_package`. Örnek.
 
---
 
### C++ : Asenkron Programlama
- **Asenkron Nedir?**: Tanım. Senkron vs Asenkron. Kullanım Senaryoları.
- **Thread Nedir?**: Tanım. Process vs Thread. Örnek.
- **std::thread**:
  - **Thread Oluşturma**: `std::thread`. Örnek.
  - **Thread Bekleme**: `join()`. `detach()`. Örnek.
  - **Mutex**: Tanım. Race Condition. `std::mutex`. `std::lock_guard`. Örnek.
  - **Condition Variable**: `std::condition_variable`. Tanım. Örnek.
  - **std::atomic**: Tanım. Lock-Free Programlama. Örnek.
- **POSIX Threads (pthread)** *(Ek Bilgi)*:
  - **Thread Oluşturma**: `pthread_create`. Örnek.
  - **Thread Bekleme**: `pthread_join`. Örnek.
  - **Mutex**: `pthread_mutex`. Örnek.
- **Windows Threads** *(Ek Bilgi)*:
  - **Thread Oluşturma**: CreateThread. Örnek.
  - **Thread Bekleme**: WaitForSingleObject. Örnek.
- **std::async ve std::future**: Tanım. Asenkron Görev. Örnek. (C++11)
- **std::promise**: Tanım. future ile İlişkisi. Örnek.
 
---
 
### C++ : Güvenlik ve Şifreleme
- **Güvenlik Nedir?**: Tanım. Yaygın Açıklar.
- **Buffer Overflow Koruması**: Tanım. Örnek.
- **Input Validation**: Tanım. Örnek.
- **OpenSSL Kütüphanesi**: Kurulum. Tanım.
  - **Hashing**: MD5, SHA-256. Örnek.
  - **Simetrik Şifreleme**: AES. Örnek.
  - **Asimetrik Şifreleme**: RSA. Örnek.
- **Rastgele Sayı Üretme**: `std::random` ile `mt19937`. `<random>`. Örnek.
- **Bellek Temizleme**: `memset`. Örnek.
 
---
 
### C++ : Log Sistemi
- **Loglama Nedir?**: Tanım. Kullanım Senaryoları.
- **Log Seviyeleri**: DEBUG, INFO, TRACE, WARNING, ERROR, FATAL. Tanım.
- **Log Formatı**: Timestamp. Seviye. Mesaj. Örnek.
- **Konsola Loglama**: Tanım. Örnek.
- **Dosyaya Loglama**: Tanım. Örnek.
- **Basit Log Kütüphanesi Yazma**: Tanım. Örnek.
- **spdlog Kütüphanesi**: Kurulum. Tanım. Örnek.
 
---
 
### C++ : Veritabanı İşlemleri (SQLite)
- **Veritabanı Nedir?**: Tanım. Kullanım Senaryoları.
- **SQLite Nedir?**: Tanım. Kurulum.
- **sqlite3 Kütüphanesi**: Tanım. Kurulum. Örnek.
- **Bağlantı Kurma**: `sqlite3_open`. Database Dosyası. Örnek.
- **Veri Ekleme (INSERT)**: Tanım. Örnek.
  > Metodları
- **Veri Sorgulama (SELECT)**: Tanım. Örnek.
  > Metodları
- **Veri Güncelleme (UPDATE)**: Tanım. Örnek.
  > Metodları
- **Veri Silme (DELETE)**: Tanım. Örnek.
  > Metodları
- **Prepared Statements**: Tanım. SQL Injection Koruması. Örnek.
- **SQLiteCpp Sarmalayıcısı**: Tanım. C++ OOP Arayüzü. Örnek.
 
---
 
### C++ : HTTP İstekleri Yönetimi
- **HTTP Nedir?**: Tanım. Kullanım Senaryoları.
- **libcurl Kütüphanesi**: Tanım. Kurulum. Örnek.
- **GET İsteği**: Tanım. Örnek.
  > Seçenekler
- **POST İsteği**: Tanım. Örnek.
  > Seçenekler
- **Header Yönetimi**: Tanım. Örnek.
- **JSON ile HTTP**: İstek ve Yanıt. Örnek.
- **HTTPS ve SSL**: Tanım. Örnek.
- **Hata Yönetimi**: `curl_easy_strerror`. Örnek.
 
---
 
### C++ : Socket Programlama
- **Socket Nedir?**: Tanım. Kullanım Senaryoları.
- **TCP vs UDP**: Farkları. Tablo Halinde.
- **TCP Socket**:
  - **Server Oluşturma**: socket, bind, listen, accept. Örnek.
  - **Client Oluşturma**: socket, connect. Örnek.
  - **Veri Gönderme/Alma**: send, recv. Örnek.
- **UDP Socket**:
  - **Server ve Client**: sendto, recvfrom. Örnek.
- **Çok İstemcili Server**: thread ile. Örnek.
 
---
 
### C++ : Test Sistemi
- **Test Nedir?**: Tanım. Önemi. Kullanım Senaryoları.
- **Unit Test Nedir?**: Tanım. Örnek.
- **Google Test (gtest)**: Kurulum. Tanım. Örnek.
- **Catch2**: Kurulum. gtest ile Karşılaştırma. Örnek.
- **Test Yazma Prensipleri**: AAA (Arrange-Act-Assert). Örnek.
- **Mock Nesneler**: Tanım. Google Mock. Örnek.
 
---

### Sonsöz
- **Bu Dokümantasyonda Ne Öğrendik**
- **İlerki Projeler**
- **Diğer Data's Books Dökümantasyonları**
- **Özel Teşekkürler**

---

## Qt

### Qt : Giriş
- **Qt Nedir?**: Tanım. Kullanım Alanları. Neden Qt?
  - **Qt Widget vs Qt Quick**: Farkları. Hangisi Ne Zaman Kullanılır?
  - **Qt'nin Tarihçesi**: Kısa Özet.
  - **Lisanslama**: Açık Kaynak vs Ticari.
- **Qt Kurulumu**:
  - **Qt Online Installer**: Tanım. Kurulum Adımları.
  - **Qt Creator IDE**: Tanım. Arayüz Tanıtımı.
  - **Qt Versiyonları**: Qt5 vs Qt6. Farklar.
  - **CMake ile Qt Projesi**: `find_package(Qt6)`. `target_link_libraries`. Örnek.
- **İlk Qt Widget Projesi**:
  - **Proje Yapısı**: `.pro` dosyası. CMakeLists.txt. Örnek.
  - **QApplication**: Tanım. `exec()`. Örnek.
  - **İlk Pencere**: `QWidget`. `show()`. Örnek.
- **Meta-Object System**: Tanım. `QObject`. `Q_OBJECT` makrosu. Neden Gerekli?
- **moc (Meta-Object Compiler)**: Tanım. Derleme Sürecindeki Yeri. Örnek.

---

### Qt : Sinyal ve Slot Mekanizması
- **Sinyal ve Slot Nedir?**: Tanım. Observer Pattern ile Karşılaştırma. Kullanım Senaryoları.
- **Signal Tanımlama**: `signals:`. Sözdizimi. Örnek.
- **Slot Tanımlama**: `slots:`. `public slots`. `private slots`. Örnek.
- **connect() Fonksiyonu**: Tanım. Parametreler. Örnek.
  - **Eski Sözdizimi**: `SIGNAL()` ve `SLOT()` makroları. Örnek.
  - **Yeni Sözdizimi**: Fonksiyon Pointer ile. C++11. Örnek.
  - **Lambda ile connect()**: Tanım. Örnek.
- **emit**: Tanım. Sinyal Fırlatma. Örnek.
- **disconnect()**: Tanım. Kullanım Senaryoları. Örnek.
- **Sinyal-Slot Bağlantı Türleri**: `Qt::AutoConnection`, `Qt::DirectConnection`, `Qt::QueuedConnection`. Tanım. Tablo Halinde.
- **Özel Sinyaller Tanımlama**: Parametre Geçirme. Örnek.

---

### Qt : Temel Widget'lar
- **Widget Nedir?**: Tanım. QWidget Hiyerarşisi. Örnek.
- **QLabel**: Tanım. Metin ve Görsel Gösterme. Örnek.
  > Metodları
- **QPushButton**: Tanım. `clicked` sinyali. Örnek.
  > Metodları
- **QLineEdit**: Tanım. Tek Satır Metin Girişi. Örnek.
  > Metodları
- **QTextEdit**: Tanım. Çok Satırlı Metin. Örnek.
  > Metodları
- **QCheckBox**: Tanım. `stateChanged` sinyali. Örnek.
  > Metodları
- **QRadioButton**: Tanım. `QButtonGroup` ile Gruplama. Örnek.
  > Metodları
- **QComboBox**: Tanım. Açılır Liste. Örnek.
  > Metodları
- **QSlider**: Tanım. `valueChanged` sinyali. Örnek.
  > Metodları
- **QSpinBox ve QDoubleSpinBox**: Tanım. Örnek.
  > Metodları
- **QProgressBar**: Tanım. Örnek.
  > Metodları
- **QListWidget**: Tanım. Örnek.
  > Metodları
- **QTableWidget**: Tanım. Örnek.
  > Metodları
- **QTreeWidget**: Tanım. Örnek.
  > Metodları

---

### Qt : Layout Yönetimi
- **Layout Nedir?**: Tanım. Neden Kullanılır? Manuel Konumlandırma ile Farkı.
- **QHBoxLayout**: Tanım. Yatay Dizilim. Örnek.
  > Metodları
- **QVBoxLayout**: Tanım. Dikey Dizilim. Örnek.
  > Metodları
- **QGridLayout**: Tanım. Izgara Düzeni. `rowSpan`. `columnSpan`. Örnek.
  > Metodları
- **QFormLayout**: Tanım. Form Düzeni. Etiket-Alan Çifti. Örnek.
  > Metodları
- **QStackedLayout**: Tanım. Katmanlı Düzen. Örnek.
- **Spacer (Boşluk)**: `QSpacerItem`. `addStretch()`. Örnek.
- **setSizePolicy**: Tanım. `QSizePolicy`. Expanding. Preferred. Örnek.
- **İç İçe Layout Kullanımı**: Tanım. Örnek.
- **Qt Designer ile Layout**: Tanım. `.ui` Dosyası. Örnek.

---

### Qt : Ana Pencere (QMainWindow)
- **QMainWindow Nedir?**: Tanım. Bileşenler. Örnek.
- **QMenuBar**: Tanım. Menü Oluşturma. `QMenu`. `QAction`. Örnek.
  > Metodları
- **QToolBar**: Tanım. Araç Çubuğu. İkon Ekleme. Örnek.
  > Metodları
- **QStatusBar**: Tanım. Durum Mesajı. Örnek.
  > Metodları
- **QDockWidget**: Tanım. Kayan Panel. Örnek.
  > Metodları
- **Central Widget**: Tanım. `setCentralWidget()`. Örnek.
- **QAction**: Tanım. Shortcut. `triggered` sinyali. Örnek.
- **Pencere Özellikleri**: `setWindowTitle`. `setWindowIcon`. `resize`. `setMinimumSize`. Örnek.

---

### Qt : Diyaloglar
- **QDialog Nedir?**: Tanım. Modal vs Modeless. Örnek.
- **QMessageBox**: Tanım. Bilgi. Uyarı. Hata. Soru. Örnek.
  > Metodları
- **QFileDialog**: Tanım. Dosya Açma. Kaydetme. Klasör Seçme. Örnek.
  > Metodları
- **QColorDialog**: Tanım. Renk Seçici. Örnek.
- **QFontDialog**: Tanım. Yazı Tipi Seçici. Örnek.
- **QInputDialog**: Tanım. Kullanıcıdan Değer Alma. Örnek.
- **Özel Diyalog Oluşturma**: `QDialog` Türetme. `accept()`. `reject()`. Örnek.

---

### Qt : Stil ve Tema
- **QSS (Qt Style Sheets)**: Tanım. CSS ile Benzerlik. Kullanım. Örnek.
  - **Widget Seçiciler**: Tanım. Örnek.
  - **Özellik Değiştirme**: `color`, `background-color`, `border`, `font`. Örnek.
  - **Pseudo-State**: `:hover`, `:pressed`, `:disabled`, `:checked`. Örnek.
  - **Harici QSS Dosyası Yükleme**: Tanım. Örnek.
- **QPalette**: Tanım. Renk Rolleri. Örnek.
- **QFont**: Tanım. Yazı Tipi Ayarları. Örnek.
- **Dark/Light Tema Yapımı**: Tanım. QSS ile Uygulama. Örnek.

---

### Qt : Model/View Mimarisi
- **Model/View Nedir?**: Tanım. MVC ile Karşılaştırma. Neden Kullanılır?
- **QAbstractItemModel**: Tanım. Temel Sınıf. Örnek.
- **QStandardItemModel**: Tanım. Kullanımı. Örnek.
  > Metodları
- **QListView**: Tanım. Model Bağlama. Örnek.
- **QTableView**: Tanım. Model Bağlama. Örnek.
- **QTreeView**: Tanım. Model Bağlama. Örnek.
- **QSortFilterProxyModel**: Tanım. Filtreleme ve Sıralama. Örnek.
- **Özel Model Yazma**: `QAbstractTableModel` Türetme. `rowCount`. `columnCount`. `data`. Örnek.
- **QItemDelegate**: Tanım. Özel Hücre Render. Örnek.

---

### Qt : Grafikler ve QPainter
- **QPainter Nedir?**: Tanım. Kullanım Senaryoları. Örnek.
- **paintEvent()**: Tanım. Override. Örnek.
- **Temel Çizim İşlemleri**:
  - **Çizgi**: `drawLine()`. Örnek.
  - **Dikdörtgen**: `drawRect()`. `drawRoundedRect()`. Örnek.
  - **Daire/Elips**: `drawEllipse()`. Örnek.
  - **Metin**: `drawText()`. Örnek.
  - **Görsel**: `drawImage()`. `drawPixmap()`. Örnek.
  - **Polygon**: `drawPolygon()`. Örnek.
- **QPen**: Tanım. Renk. Kalınlık. Stil. Örnek.
- **QBrush**: Tanım. Dolgu. Pattern. Örnek.
- **QColor**: Tanım. RGB. HSV. Alpha. Örnek.
- **QPixmap ve QImage**: Tanım. Farkları. Kullanım Senaryoları. Örnek.
- **QIcon**: Tanım. Kullanım. Örnek.
- **Animasyon**: `QPropertyAnimation`. `QAnimationGroup`. Örnek.

---

### Qt : Qt Designer ve .ui Dosyaları
- **Qt Designer Nedir?**: Tanım. Kullanım. Arayüz Tanıtımı.
- **.ui Dosyası**: Tanım. XML Yapısı. Örnek.
- **uic (UI Compiler)**: Tanım. `.ui` → `.h` Dönüşümü. Örnek.
- **CMake ile .ui Entegrasyonu**: `qt_wrap_ui()`. Örnek.
- **Designer'dan Kod Bağlama**: `setupUi()`. `ui->widgetAdi`. Örnek.
- **Promote Widget**: Tanım. Özel Widget'ı Designer'a Tanıtma. Örnek.

---

### Qt : Veri Yönetimi
- **QString**: Tanım. std::string ile Farkı. Örnek.
  > Metodları
- **QVariant**: Tanım. Dinamik Tip. Kullanım Senaryoları. Örnek.
- **QList ve QVector**: Tanım. std::vector ile Karşılaştırma. Örnek.
  > Metodları
- **QMap ve QHash**: Tanım. std::map ile Karşılaştırma. Örnek.
  > Metodları
- **QSet**: Tanım. Örnek.
- **QByteArray**: Tanım. Binary Veri. Örnek.
- **QJsonDocument**: Tanım. JSON Okuma/Yazma. Örnek.
  > Metodları
- **QSettings**: Tanım. Uygulama Ayarlarını Saklama. Örnek.
  > Metodları

---

### Qt : Dosya ve I/O İşlemleri
- **QFile**: Tanım. Dosya Açma/Kapama. Modlar. Örnek.
  > Metodları
- **QTextStream**: Tanım. Metin Okuma/Yazma. Örnek.
  > Metodları
- **QDataStream**: Tanım. Binary Okuma/Yazma. Örnek.
  > Metodları
- **QDir**: Tanım. Klasör İşlemleri. Örnek.
  > Metodları
- **QFileInfo**: Tanım. Dosya Bilgisi. Örnek.
  > Metodları
- **QFileSystemWatcher**: Tanım. Dosya Değişikliği İzleme. Örnek.
- **Kaynak Sistemi (Qt Resource System)**: `qrc` Dosyası. `:/` Prefix. CMake Entegrasyonu. Örnek.

---

### Qt : Ağ (Network) İşlemleri
- **Qt Network Modülü**: Tanım. Kurulum. `find_package(Qt6 COMPONENTS Network)`.
- **QNetworkAccessManager**: Tanım. HTTP İstekleri. Örnek.
- **GET İsteği**: `get()`. `QNetworkReply`. Örnek.
- **POST İsteği**: `post()`. Örnek.
- **QNetworkRequest**: Tanım. Header Yönetimi. Örnek.
- **QNetworkReply**: Tanım. `finished` sinyali. Hata Yönetimi. Örnek.
- **SSL/HTTPS**: Tanım. `QSslConfiguration`. Örnek.
- **QTcpServer ve QTcpSocket**: Tanım. TCP Sunucu/İstemci. Örnek.
- **QUdpSocket**: Tanım. UDP İletişim. Örnek.
- **QWebSocket**: Tanım. WebSocket İletişimi. Örnek.

---

### Qt : Multithreading
- **Qt'de Thread Yönetimi**: Tanım. `std::thread` ile Farkı.
- **QThread**: Tanım. `run()`. Örnek.
  - **Worker-Thread Paterni**: Tanım. Sinyal-Slot ile İletişim. Örnek.
  - **moveToThread()**: Tanım. Kullanım. Örnek.
- **QMutex**: Tanım. `lock()`. `unlock()`. Örnek.
- **QMutexLocker**: Tanım. RAII. Örnek.
- **QReadWriteLock**: Tanım. Okuma/Yazma Kilidi. Örnek.
- **QSemaphore**: Tanım. Örnek.
- **QWaitCondition**: Tanım. Örnek.
- **QtConcurrent**: Tanım. `run()`. `map()`. `filter()`. Örnek.
- **QFuture ve QFutureWatcher**: Tanım. Asenkron Sonuç Takibi. Örnek.

---

### Qt : Veritabanı İşlemleri (Qt SQL)
- **Qt SQL Modülü**: Tanım. Kurulum. `find_package(Qt6 COMPONENTS Sql)`.
- **Desteklenen Veritabanları**: SQLite. PostgreSQL. MySQL. ODBC. Tablo Halinde.
- **QSqlDatabase**: Tanım. Bağlantı Kurma. Örnek.
- **QSqlQuery**: Tanım. SQL Çalıştırma. Örnek.
  > Metodları
- **Veri Ekleme (INSERT)**: Tanım. Örnek.
- **Veri Sorgulama (SELECT)**: Tanım. `next()`. Örnek.
- **Veri Güncelleme (UPDATE)**: Tanım. Örnek.
- **Veri Silme (DELETE)**: Tanım. Örnek.
- **Prepared Statements**: Tanım. SQL Injection Koruması. `bindValue()`. Örnek.
- **QSqlTableModel**: Tanım. View ile Entegrasyon. Örnek.
- **QSqlRelationalTableModel**: Tanım. İlişkisel Tablo. Örnek.
- **Transaction Yönetimi**: `transaction()`. `commit()`. `rollback()`. Örnek.

---

### Qt : CMake ile Kapsamlı Qt Projesi
- **Qt CMake Yapısı**: Tanım. `qt_add_executable`. Örnek.
- **Modülleri Dahil Etme**: `find_package`. Modül Listesi. Örnek.
- **Kaynak Dosyaları**: `qt_add_resources()`. Örnek.
- **UI Dosyaları**: `qt_wrap_ui()`. Örnek.
- **Çoklu Platform Desteği**: Windows. Linux. macOS. Örnek.
- **Dağıtım (Deployment)**: `windeployqt`. `macdeployqt`. `linuxdeployqt`. Örnek.
- **Statik Derleme**: Tanım. Kullanım Senaryoları. Örnek.

---

### Qt : Test Sistemi
- **Qt Test Modülü**: Tanım. Kurulum. `find_package(Qt6 COMPONENTS Test)`.
- **QTest**: Tanım. Temel Kullanım. Örnek.
- **Test Sınıfı Yazma**: `QObject` Türetme. `private slots`. Örnek.
- **QCOMPARE ve QVERIFY**: Tanım. Örnek.
- **QBENCHMARK**: Tanım. Performans Testi. Örnek.
- **GUI Test**: `QTest::mouseClick`. `QTest::keyClick`. Örnek.
- **Sinyal Testi**: `QSignalSpy`. Tanım. Örnek.

---

## Unreal Engine

### Unreal Engine : Giriş
- **Unreal Engine Nedir?**: Tanım. Kullanım Alanları. Neden UE?
  - **Kısa Tarihçesi**: UE1'den UE5'e. Önemli Dönüm Noktaları.
  - **Unity ile Karşılaştırma**: Tablo Halinde.
  - **Lisanslama**: Ücretsiz Kullanım. Royalty Modeli.
- **UE5 Kurulumu**:
  - **Epic Games Launcher**: Tanım. Kurulum Adımları.
  - **Engine Versiyonu Seçimi**: Tanım. LTS Kavramı.
  - **Visual Studio Entegrasyonu**: Hangi Bileşenler Kurulmalı? Örnek.
  - **Proje Oluşturma**: Template Seçimi. C++ vs Blueprint. Örnek.
- **Editor Arayüzü**:
  - **Viewport**: Tanım. Kamera Kontrolü. Örnek.
  - **Content Browser**: Tanım. Asset Yönetimi. Örnek.
  - **Outliner**: Tanım. Sahne Hiyerarşisi. Örnek.
  - **Details Panel**: Tanım. Özellik Düzenleme. Örnek.
  - **Toolbar ve Play Modu**: Tanım. PIE (Play In Editor). Örnek.
- **UE Proje Yapısı**:
  - **Klasör Yapısı**: `Source/`. `Content/`. `Config/`. `Binaries/`. Tanım.
  - **.uproject Dosyası**: Tanım. İçeriği. Örnek.
  - **Build.cs Dosyası**: Tanım. Modül Tanımı. Örnek.
  - **Target.cs Dosyası**: Tanım. Derleme Hedefi. Örnek.

---

### Unreal Engine : UE C++ Temelleri
- **UE C++ Nedir?**: Tanım. Standart C++ ile Farkı. UE Makroları.
- **UCLASS Makrosu**: Tanım. Blueprint'e Açma. Örnek.
- **UPROPERTY Makrosu**: Tanım. Bellek Yönetimi. Editor'a Açma. Örnek.
  - **Specifier'lar**: `EditAnywhere`, `BlueprintReadWrite`, `VisibleAnywhere`, `Category`. Tablo Halinde.
- **UFUNCTION Makrosu**: Tanım. Blueprint'e Açma. Örnek.
  - **Specifier'lar**: `BlueprintCallable`, `BlueprintPure`, `CallInEditor`. Tablo Halinde.
- **USTRUCT Makrosu**: Tanım. Örnek.
- **UENUM Makrosu**: Tanım. Örnek.
- **Unreal Build Tool (UBT)**: Tanım. Derleme Süreci. Hot Reload. Örnek.
- **Unreal Header Tool (UHT)**: Tanım. Kod Üretimi. `generated.h`. Örnek.
- **UE Temel Tipleri**: `int32`, `float`, `FString`, `FName`, `FText`, `bool`. Tablo Halinde.
- **FString, FName, FText**: Tanım. Farkları. Dönüşümler. Örnek.
- **TArray, TMap, TSet**: Tanım. STL ile Karşılaştırma. Örnek.
  > Metodları

---

### Unreal Engine : Actor ve Component Sistemi
- **Actor Nedir?**: Tanım. Sahneye Ekleme. Yaşam Döngüsü. Örnek.
  - **BeginPlay()**: Tanım. Örnek.
  - **Tick()**: Tanım. `DeltaTime`. Örnek.
  - **EndPlay()**: Tanım. Örnek.
- **Component Nedir?**: Tanım. Actor ile İlişkisi. Kullanım Senaryoları.
  - **USceneComponent**: Tanım. Transform. Root Component. Örnek.
  - **UStaticMeshComponent**: Tanım. 3D Mesh Ekleme. Örnek.
  - **USkeletalMeshComponent**: Tanım. Animasyonlu Mesh. Örnek.
  - **UCameraComponent**: Tanım. Kamera Ekleme. Örnek.
  - **UAudioComponent**: Tanım. Ses Ekleme. Örnek.
  - **UPointLightComponent**: Tanım. Işık Ekleme. Örnek.
- **Component Oluşturma**: `CreateDefaultSubobject()`. `SetupAttachment()`. Örnek.
- **Actor Spawn ve Destroy**: `SpawnActor()`. `Destroy()`. Örnek.
- **Actor Bulma**: `FindActor`. `GetAllActorsOfClass`. Örnek.
- **Özel Actor Sınıfı Yazma**: Adım Adım. Örnek.

---

### Unreal Engine : Pawn, Character ve Controller
- **Pawn Nedir?**: Tanım. Actor ile Farkı. Kontrol Edilebilir Nesne. Örnek.
- **Character Nedir?**: Tanım. Pawn ile Farkı. Hazır Hareket Sistemi. Örnek.
  - **UCharacterMovementComponent**: Tanım. Hız. Yerçekimi. Zıplama. Örnek.
  - **UCapsuleComponent**: Tanım. Çarpışma Kapsülü. Örnek.
- **PlayerController**: Tanım. Input Yönetimi. Pawn ile İlişkisi. Örnek.
- **AIController**: Tanım. AI Yönetimi. Örnek.
- **GameMode ve GameState**: Tanım. Oyun Kuralları. Örnek.
- **PlayerState**: Tanım. Oyuncu Verisi. Örnek.
- **Possession**: `Possess()`. `UnPossess()`. Tanım. Örnek.

---

### Unreal Engine : Input Yönetimi
- **Input Sistemi**: Tanım. Legacy vs Enhanced Input. Karşılaştırma.
- **Enhanced Input (UE5)**:
  - **Input Action**: Tanım. Asset Oluşturma. Örnek.
  - **Input Mapping Context**: Tanım. Tuş Ataması. Örnek.
  - **BindAction()**: Tanım. ETriggerEvent. Örnek.
  - **AddMappingContext()**: Tanım. Örnek.
- **Legacy Input** *(Ek Bilgi)*:
  - **Axis Mapping**: Tanım. Örnek.
  - **Action Mapping**: Tanım. Örnek.
  - **BindAxis() ve BindAction()**: Tanım. Örnek.
- **Mouse Input**: `GetMousePosition`. `SetShowMouseCursor`. Örnek.
- **Gamepad Desteği**: Tanım. Örnek.

---

### Unreal Engine : Collision ve Physics
- **Collision Nedir?**: Tanım. Kullanım Senaryoları.
- **Collision Channel ve Response**: Tanım. `ECC_WorldStatic`, `ECC_Pawn`. Tablo Halinde.
- **Collision Preset**: Tanım. `BlockAll`, `OverlapAll`. Örnek.
- **OnComponentHit**: Tanım. Çarpışma Olayı. Örnek.
- **OnComponentBeginOverlap**: Tanım. Geçiş Olayı. Örnek.
- **Line Trace (Raycast)**:
  - **LineTraceSingleByChannel**: Tanım. Parametreler. Örnek.
  - **LineTraceMultiByChannel**: Tanım. Örnek.
  - **FHitResult**: Tanım. İçeriği. Örnek.
- **Sphere ve Box Trace**: Tanım. Örnek.
- **Physics Simulation**: `SetSimulatePhysics()`. Kütle. Sürtünme. Örnek.
- **Impulse ve Force**: `AddImpulse()`. `AddForce()`. Örnek.
- **PhysicsConstraint**: Tanım. Eklem Simülasyonu. Örnek.

---

### Unreal Engine : Animasyon
- **Animasyon Sistemi**: Tanım. Genel Bakış.
- **Animation Blueprint (ABP)**: Tanım. Event Graph. AnimGraph. Örnek.
- **AnimInstance**: Tanım. C++ ile Bağlantı. Örnek.
- **State Machine**: Tanım. State ve Transition. Örnek.
- **Blend Space**: Tanım. 1D ve 2D. Hareket Geçişleri. Örnek.
- **Montage**: Tanım. Kullanım Senaryoları. `PlayAnimMontage()`. Örnek.
- **Skeleton ve Skeletal Mesh**: Tanım. İlişkisi. Örnek.
- **IK (Inverse Kinematics)**: Tanım. Control Rig ile Kullanım. Örnek.
- **Root Motion**: Tanım. Etkinleştirme. Örnek.
- **Notify**: Tanım. Animasyon Olayı. C++ ile Bağlama. Örnek.

---

### Unreal Engine : Yapay Zeka (AI)
- **UE AI Sistemi**: Tanım. Genel Bakış. Kullanım Senaryoları.
- **NavMesh (Navigation Mesh)**: Tanım. `RecastNavMesh`. Oluşturma. Örnek.
- **AIController ile Hareket**: `MoveToLocation()`. `MoveToActor()`. Örnek.
- **Behavior Tree**: Tanım. Yapısı. Kullanım.
  - **Task**: Tanım. `ExecuteTask()`. Örnek.
  - **Decorator**: Tanım. Koşul Kontrolü. Örnek.
  - **Service**: Tanım. Periyodik Güncelleme. Örnek.
- **Blackboard**: Tanım. AI Veri Deposu. Key Tipleri. Örnek.
- **EQS (Environment Query System)**: Tanım. Çevresel Sorgulama. Örnek.
- **Perception System**: Tanım. `UAISenseConfig_Sight`. `UAISenseConfig_Hearing`. Örnek.

---

### Unreal Engine : Materyaller ve Shaderlar
- **Material Sistemi**: Tanım. Material Editor. Genel Bakış.
- **Material Expression Nodes**: Tanım. Temel Node'lar. Örnek.
- **Material Instance**: Tanım. Dynamic Material Instance. Örnek.
- **Texture**: Tanım. Import. UV Mapping. Örnek.
- **PBR (Physically Based Rendering)**: Tanım. Base Color. Metallic. Roughness. Normal. Örnek.
- **Material Parameter Collection**: Tanım. Global Parametre. Örnek.
- **C++ ile Material Değiştirme**: `SetMaterial()`. `CreateDynamicMaterialInstance()`. Örnek.
- **Post Process Material**: Tanım. Ekran Efektleri. Örnek.

---

### Unreal Engine : UI (UMG - Unreal Motion Graphics)
- **UMG Nedir?**: Tanım. Widget Blueprint. Kullanım Senaryoları.
- **Widget Blueprint Oluşturma**: Tanım. Designer ve Graph. Örnek.
- **Temel UI Widget'ları**: `Text`, `Button`, `Image`, `ProgressBar`, `ScrollBox`. Örnek.
  > Her Widget'ın Temel Metodları
- **Anchor ve Alignment**: Tanım. Responsive UI. Örnek.
- **UUserWidget**: Tanım. C++ ile Widget Yazma. Örnek.
- **UPROPERTY ile Widget Bağlama**: `BindWidget`. Tanım. Örnek.
- **Widget Oluşturma ve Gösterme**: `CreateWidget()`. `AddToViewport()`. Örnek.
- **Widget'ı Kaldırma**: `RemoveFromParent()`. Örnek.
- **Data Binding**: Tanım. `Bind` Fonksiyonları. Örnek.
- **HUD Sınıfı**: Tanım. `AHUD`. `DrawHUD()`. Örnek.
- **Animasyon**: UMG Animasyonu. C++ ile Tetikleme. Örnek.

---

### Unreal Engine : Ses (Audio)
- **UE Audio Sistemi**: Tanım. Genel Bakış.
- **Sound Wave**: Tanım. Import. Örnek.
- **Sound Cue**: Tanım. Node Tabanlı Ses Tasarımı. Örnek.
- **Sound Attenuation**: Tanım. Mesafeye Göre Ses. Örnek.
- **UAudioComponent**: Tanım. Örnek.
- **PlaySound2D ve PlaySoundAtLocation**: Tanım. Farkları. Örnek.
- **MetaSound** *(UE5)*: Tanım. Prosedürel Ses. Örnek.
- **C++ ile Ses Kontrolü**: `UGameplayStatics::PlaySound2D`. Örnek.

---

### Unreal Engine : Seviye ve Dünya Yönetimi
- **Level Nedir?**: Tanım. Persistent Level. Sub-Level. Örnek.
- **World Composition**: Tanım. Büyük Dünyalar. Örnek.
- **Level Streaming**: Tanım. `LoadStreamLevel`. `UnloadStreamLevel`. Örnek.
- **World Settings**: Tanım. GameMode Override. Yerçekimi. Örnek.
- **Actor'ü Levelden Yükleme**: `SpawnActor`. Blueprint Referansı. Örnek.
- **Persistent ve Geçici Veriler**: Tanım. Kullanım Senaryoları.
- **Level Geçişi**: `OpenLevel()`. `UGameplayStatics::OpenLevel`. Örnek.

---

### Unreal Engine : Veri Yönetimi ve Save Sistemi
- **SaveGame Nedir?**: Tanım. Kullanım Senaryoları.
- **USaveGame**: Tanım. Türetme. UPROPERTY ile Veri Saklama. Örnek.
- **SaveGameToSlot()**: Tanım. Örnek.
- **LoadGameFromSlot()**: Tanım. Örnek.
- **DoesSaveGameExist()**: Tanım. Örnek.
- **DataTable**: Tanım. CSV/JSON'dan Veri Yükleme. C++ ile Erişim. Örnek.
- **Data Asset**: Tanım. `UPrimaryDataAsset`. Örnek.
- **Config Dosyaları**: `GConfig`. `.ini` Dosyası Okuma/Yazma. Örnek.

---

### Unreal Engine : Çoğaltma ve Ağ (Replication & Networking)
- **UE Ağ Mimarisi**: Tanım. Server-Client Modeli. Genel Bakış.
- **Replication Nedir?**: Tanım. `bReplicates`. Örnek.
- **UPROPERTY Replication**: `Replicated`. `ReplicatedUsing`. Örnek.
- **GetLifetimeReplicatedProps()**: Tanım. `DOREPLIFETIME`. Örnek.
- **RPC (Remote Procedure Call)**:
  - **Server RPC**: `UFUNCTION(Server, Reliable)`. Örnek.
  - **Client RPC**: `UFUNCTION(Client, Reliable)`. Örnek.
  - **Multicast RPC**: `UFUNCTION(NetMulticast, Unreliable)`. Örnek.
- **HasAuthority()**: Tanım. Server/Client Kontrolü. Örnek.
- **OnRep Fonksiyonları**: Tanım. Değişken Değişince Tetikleme. Örnek.
- **GameState ve PlayerState Replication**: Tanım. Örnek.
- **Listen Server vs Dedicated Server**: Farkları. Tablo Halinde.

---

### Unreal Engine : Performans ve Optimizasyon
- **Profiling Araçları**: Tanım. `stat fps`. `stat unit`. Örnek.
- **Unreal Insights**: Tanım. Kullanım. Örnek.
- **GPU Profiler**: Tanım. Örnek.
- **LOD (Level of Detail)**: Tanım. Static Mesh LOD. Skeletal Mesh LOD. Örnek.
- **Culling**: Tanım. Frustum Culling. Occlusion Culling. Distance Culling. Örnek.
- **Tick Optimizasyonu**: `PrimaryActorTick.bCanEverTick`. `SetActorTickInterval`. Örnek.
- **Object Pooling**: Tanım. Kullanım Senaryoları. Örnek.
- **Instanced Static Mesh**: Tanım. `UInstancedStaticMeshComponent`. Örnek.
- **Nanite** *(UE5)*: Tanım. Virtualized Geometry. Kullanım. Örnek.
- **Lumen** *(UE5)*: Tanım. Global Illumination. Performans Ayarları. Örnek.
- **Memory Profiler**: Tanım. Bellek Sızıntısı Tespiti. Örnek.

---

### Unreal Engine : Paketleme ve Dağıtım
- **Build Konfigürasyonları**: Development. Shipping. Debug. Tablo Halinde.
- **Platform Seçimi**: Windows. Linux. Android. iOS. Konsol. Örnek.
- **Packaging Settings**: Tanım. Project Settings. Örnek.
- **Cook İşlemi**: Tanım. Asset Dönüştürme. Örnek.
- **Windows'a Paketleme**: Adım Adım. Örnek.
- **Android'e Paketleme**: SDK Kurulumu. APK/AAB. Örnek.
- **Otomasyon**: `RunUAT.bat`. Build Pipeline. Örnek.

---

### Sonsöz
- **Bu Dokümantasyonda Ne Öğrendik**
- **İlerki Projeler**
- **Diğer Data's Books Dökümantasyonları**
- **Özel Teşekkürler**

---