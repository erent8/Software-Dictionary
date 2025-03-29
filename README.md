# 📖 Yazılım Terimleri Sözlüğü

Bu repo yazılım dünyasında en sık kullanılan terimleri ve kısa açıklamalarını içermektedir. Yazılım geliştirme, sistem tasarımı, veri yapıları, algoritmalar, ağ, güvenlik, yapay zeka ve daha birçok alanda kullanılan terimler kategorilere ayrılmış şekilde sunulmuştur.

## 📑 İçindekiler
- [📌 Genel Yazılım Terimleri](#-genel-yazılım-terimleri)
- [🖥 Programlama Kavramları](#-programlama-kavramları)
- [🛠 Yazılım Geliştirme Süreçleri](#-yazılım-geliştirme-süreçleri)
- [🌐 Web Geliştirme](#-web-geliştirme)
- [📱 Mobil Geliştirme](#-mobil-geliştirme)
- [🏗 Sistem Mimarisi](#-sistem-mimarisi)
- [☁️ Bulut Bilişim](#️-bulut-bilişim)
- [🔄 DevOps ve SRE](#-devops-ve-sre)
- [🗄 Veritabanları](#-veritabanları)
- [🔐 Siber Güvenlik](#-siber-güvenlik)
- [🔍 Veri Bilimi](#-veri-bilimi)
- [🤖 Yapay Zeka ve Makine Öğrenmesi](#-yapay-zeka-ve-makine-öğrenmesi)
- [🌍 Blockchain ve Web3](#-blockchain-ve-web3)
- [🔧 Araçlar ve Teknolojiler](#-araçlar-ve-teknolojiler)
- [📊 Yazılım Metrikleri](#-yazılım-metrikleri)

## 📌 Genel Yazılım Terimleri

### Temel Kavramlar
- **API (Application Programming Interface):** Farklı yazılımlar arasında iletişim sağlayan arayüz
- **SDK (Software Development Kit):** Yazılım geliştirmek için gereken araçlar ve kütüphaneler paketi
- **IDE (Integrated Development Environment):** Kod yazmayı, derlemeyi ve hata ayıklamayı kolaylaştıran yazılım geliştirme ortamı
- **CLI (Command Line Interface):** Komut satırı arayüzü, terminal üzerinden komut girilerek yazılımların yönetilmesini sağlar
- **GUI (Graphical User Interface):** Kullanıcıların grafiksel arayüzler ile etkileşime geçmesini sağlayan sistem
- **REPL (Read-Eval-Print Loop):** Kod parçacıklarını anında çalıştırmaya yarayan etkileşimli ortam
- **Boilerplate:** Minimal değişikliklerle birçok yerde kullanılabilen hazır kod parçaları
- **CRUD:** Create (Oluşturma), Read (Okuma), Update (Güncelleme) ve Delete (Silme) işlemleri
- **Kernel:** İşletim sisteminin çekirdeği, donanım ile iletişimi sağlayan temel bileşen
- **Shell:** Kullanıcı ile işletim sistemi arasında arayüz sağlayan program

### Geliştirme Süreçleri
- **Debugging:** Koddaki hataları tespit etme ve düzeltme süreci
- **Refactoring:** Kodun işleyişini değiştirmeden, daha temiz ve anlaşılır hale getirilmesi  
- **Version Control:** Yazılım geliştirme sürecinde kod değişikliklerinin kaydedildiği ve yönetildiği sistem
- **Repository:** Kodların saklandığı, versiyonlarının takip edildiği depo
- **Build:** Kaynak kodun çalıştırılabilir hale getirilmesi işlemi
- **Deployment:** Bir yazılımın test ortamından canlı ortama taşınması süreci
- **Code Review:** Yazılan kodun diğer geliştiriciler tarafından incelenmesi süreci
- **Technical Debt:** Hızlı çözüm için kaliteyi kurban vererek oluşan teknik borç
- **Code Smell:** Kodda daha derin problemlere işaret edebilecek yüzeysel belirtiler
- **Hotfix:** Acil durumlarda canlı sistemdeki hatayı düzeltmek için yapılan hızlı değişiklik
- **Monkey Patch:** Çalışma zamanında kod davranışını geçici olarak değiştirme tekniği
- **Feature Toggle:** Özelliği kod tabanında tutarken açıp kapatılmasını sağlayan mekanizma
- **Code Freeze:** Belirli bir sürüm öncesi kod değişikliklerinin durdurulması
- **Breaking Change:** Mevcut API kullanımını bozan değişiklikler
- **Semantic Versioning:** Major.Minor.Patch formatıyla yazılım sürümlerini tanımlama standardı

### Yazılım Bileşenleri
- **Framework:** Belirli bir amaç için yazılmış, geliştiricilere hazır yapı sunan yazılım çatısı
- **Library:** Belirli işlevleri gerçekleştirmek için yazılmış, tekrar kullanılabilir kod koleksiyonu
- **Middleware:** İki sistem veya uygulama arasında köprü görevi gören yazılım katmanı
- **Runtime:** Bir programın çalıştırıldığı ortam
- **Compiler:** Kaynak kodu makine diline çeviren yazılım
- **Interpreter:** Kaynak kodu satır satır çalıştıran program
- **Transpiler:** Bir programlama dilindeki kodu başka bir dile çeviren araç
- **Static Typing:** Değişken türlerinin derleme zamanında kontrol edildiği dil özelliği
- **Dynamic Typing:** Değişken türlerinin çalışma zamanında kontrol edildiği dil özelliği
- **Bytecode:** Ara kod, kaynak kodla makine kodu arasındaki format
- **JIT (Just-in-Time) Compilation:** Kodun çalışma sırasında derlenmesi
- **AOT (Ahead-of-Time) Compilation:** Kodun çalıştırılmadan önce tamamen derlenmesi
- **Garbage Collection:** Kullanılmayan bellek alanlarını otomatik temizleyen sistem
- **Memory Leak:** Kullanılmayan bellek alanlarının serbest bırakılmadığı durum
- **Dependency Injection:** Bir nesneye bağımlılıklarının dışarıdan verilmesi tekniği
- **Module Bundling:** Çoklu JavaScript dosyalarını tek bir dosyada birleştirme işlemi

## 🖥 Programlama Kavramları

### Temel Yapılar
- **Variable:** Değişken, veri saklamak için kullanılan bellek bölümü
- **Function:** Belirli bir işlemi gerçekleştiren kod bloğu
- **Loop:** Belirli koşullar sağlanana kadar tekrar eden kod yapısı
- **Conditional Statements:** "if", "else" gibi koşullu ifadeler
- **Exception Handling:** Hata yönetimi mekanizması
- **Pointer:** Bellek adresini tutan değişken türü
- **Array:** Aynı türdeki verileri sıralı olarak tutan veri yapısı
- **String:** Karakter dizisi, metinsel değerleri saklayan veri türü
- **Boolean:** True (doğru) veya False (yanlış) değerlerini tutan veri türü
- **Integer:** Tam sayı değerlerini tutan veri türü
- **Float:** Ondalıklı sayıları tutan veri türü
- **Char:** Tek bir karakteri tutan veri türü
- **Scope:** Değişkenlerin erişilebilir olduğu kod bölgesi
- **Type Casting:** Bir veri türünü başka bir veri türüne dönüştürme işlemi
- **Ternary Operator:** Tek satırda if-else mantığı sağlayan operatör
- **Bitwise Operations:** Bit seviyesinde (0 ve 1) işlemler yapan operatörler

### Programlama Paradigmaları
- **Object-Oriented Programming (OOP):** Nesne tabanlı programlama paradigması
- **Functional Programming:** Fonksiyonlar üzerine kurulu programlama yaklaşımı
- **Procedural Programming:** Adım adım talimatlarla ilerleyen programlama yaklaşımı
- **Event-Driven Programming:** Olaylara tepki veren programlama yaklaşımı
- **Declarative Programming:** Ne yapılacağını belirten, nasılı gizleyen yaklaşım
- **Imperative Programming:** Nasıl yapılacağını adım adım belirten yaklaşım
- **Logic Programming:** Mantıksal kurallar ve kısıtlamalarla programlama yapma
- **Prototype-Based Programming:** Prototip kalıtımını kullanan nesne tabanlı yaklaşım
- **Aspect-Oriented Programming:** Çapraz kesen ilgileri (cross-cutting concerns) modülerleştiren yaklaşım
- **Meta Programming:** Kodun kendisini değiştiren veya üreten programlama tekniği

### OOP Kavramları
- **Class:** Nesnelerin şablonunu tanımlayan yapı
- **Object:** Bir sınıfın örneği, özellikleri ve davranışları olan varlık
- **Inheritance:** Bir sınıfın başka bir sınıfın özellik ve metodlarını miras alması
- **Encapsulation:** Verilerin ve metotların dış dünyadan gizlenmesi prensibi
- **Polymorphism:** Aynı arayüzü kullanan farklı nesnelerin farklı davranabilme yeteneği
- **Abstraction:** Karmaşık sistemleri basitleştirmek için gereksiz detayları gizleme
- **Interface:** Bir sınıfın uygulaması gereken metodları tanımlayan sözleşme
- **Constructor:** Bir nesne oluşturulduğunda çalışan özel metot
- **Destructor:** Bir nesne yok edildiğinde çalışan özel metot
- **Method Overloading:** Aynı isimli, farklı parametre listeli metotlar tanımlama
- **Method Overriding:** Üst sınıftaki bir metodu alt sınıfta yeniden tanımlama
- **Virtual Method:** Alt sınıflarda ezilmesi (override) beklenen metot
- **Mixin:** Sınıflara ek davranış eklemek için kullanılan özel sınıflar
- **Composition:** Bir nesneyi başka nesnelerden oluşturma prensibi

### Fonksiyonel Programlama
- **Pure Function:** Aynı girdiler için her zaman aynı çıktıyı üreten, yan etkisiz fonksiyon
- **Higher-Order Function:** Fonksiyonları parametre olarak alan veya döndüren fonksiyon
- **Lambda:** İsimsiz, anonim fonksiyon
- **Closure:** Kapsayan fonksiyonun değişkenlerine erişebilen fonksiyon
- **Currying:** Çok parametreli fonksiyonu, tek parametreli fonksiyonlar zincirine dönüştürme
- **Monad:** Fonksiyonel programlamada yan etkileri kapsülleyen yapı
- **Immutability:** Değişmezlik, nesnelerin oluşturulduktan sonra değiştirilememesi
- **Function Composition:** Fonksiyonları birleştirerek yeni fonksiyonlar oluşturma
- **First-Class Function:** Değişkenlere atanabilen, parametre olarak geçilebilen fonksiyonlar
- **Recursion Tail Optimization:** Özyinelemeli fonksiyonları optimize eden teknik

### Veri Yapıları
- **Data Structure:** Verileri organize etme ve saklama yöntemleri
- **Array:** Ardışık bellek bölgelerinde verileri tutan yapı
- **Linked List:** Her düğümün bir sonraki düğüme referans verdiği veri yapısı
- **Stack:** Son giren ilk çıkar (LIFO) prensibiyle çalışan veri yapısı
- **Queue:** İlk giren ilk çıkar (FIFO) prensibiyle çalışan veri yapısı
- **Tree:** Hiyerarşik yapıdaki verileri tutan veri yapısı
- **Binary Tree:** Her düğümün en fazla iki alt düğüme sahip olduğu ağaç yapısı
- **Binary Search Tree (BST):** Solda küçük, sağda büyük değerlerin olduğu ikili ağaç
- **Heap:** En büyük veya en küçük elemana hızlı erişim sağlayan ağaç yapısı
- **Hash Table:** Anahtar-değer çiftlerini tutan ve hızlı erişim sağlayan yapı
- **Graph:** Düğümler ve kenarlardan oluşan ilişkisel veri yapısı
- **Trie:** Karakter dizilerini verimli şekilde depolayan ağaç yapısı
- **Circular Buffer:** Sabit boyutlu, dairesel, üzerine yazılabilen tampon
- **B-Tree:** Çok yollu dengeli arama ağacı, veritabanlarında sık kullanılır
- **Red-Black Tree:** Kendini dengeleyen ikili arama ağacı
- **AVL Tree:** Daha katı dengeleme kriterlerine sahip, kendini dengeleyen ağaç

### Algoritmalar
- **Algorithm:** Belirli bir problemi çözmek için adım adım işlem dizisi
- **Recursion:** Bir fonksiyonun kendisini çağırarak çalışması
- **Sorting Algorithm:** Verileri belirli bir düzene göre sıralayan algoritma
- **Searching Algorithm:** Veri yapılarında eleman arayan algoritma
- **Greedy Algorithm:** Her adımda en iyi seçeneği seçen algoritma
- **Dynamic Programming:** Problemi alt problemlere bölerek çözen yaklaşım
- **Divide and Conquer:** Problemi küçük parçalara bölerek çözen yaklaşım
- **Breadth-First Search (BFS):** Grafta seviye seviye dolaşan arama algoritması
- **Depth-First Search (DFS):** Grafta derin yolları önce keşfeden arama algoritması
- **Dijkstra's Algorithm:** En kısa yolu bulan algoritma
- **A* Search Algorithm:** Hedefe yönelik en kısa yolu bulan algoritmalar
- **Backtracking:** Tüm olasılıkları deneyerek çözüm bulan yaklaşım
- **Binary Search:** Sıralı dizide ortadan bölerek arayan algoritma
- **Bubble Sort:** Komşu elemanları karşılaştırıp yer değiştiren basit sıralama algoritması
- **Quick Sort:** Böl ve yönet yaklaşımıyla çalışan hızlı sıralama algoritması
- **Merge Sort:** Bölme ve birleştirme prensibiyle çalışan sıralama algoritması

### Paralel İşleme ve Eşzamanlılık
- **Multithreading:** Aynı anda birden fazla işlem yürütmeyi sağlayan yöntem
- **Concurrency:** Aynı anda birden fazla işlemin çalışmasını sağlayan yapı
- **Parallelism:** Farklı çekirdeklerde aynı anda çalışan görevler
- **Thread:** İşletim sistemi tarafından programın çalıştırılabilir en küçük iş parçası
- **Process:** Çalışan bir programın işletim sistemi tarafındaki örneği
- **Race Condition:** Paylaşılan kaynağa eşzamanlı erişim sonucu oluşan hata
- **Deadlock:** İki veya daha fazla işlemin birbirlerinin kilitlediği kaynakları beklemesi
- **Mutex:** Paylaşılan kaynağa erişimi kilitleyerek senkronize eden mekanizma
- **Semaphore:** Sınırlı sayıda kaynağa eşzamanlı erişimi kontrol eden mekanizma
- **Critical Section:** Paylaşılan kaynağa erişen ve senkronizasyon gerektiren kod bölümü
- **Thread Pool:** Önceden oluşturulmuş ve yeniden kullanılabilen iş parçacığı havuzu
- **Atomic Operation:** Bölünemez işlem, yarıda kesintiye uğramayan işlem
- **Lock:** Kaynağı kilitleyerek tek bir işlemin erişimini sağlayan mekanizma
- **Starvation:** Bir işlemin sürekli olarak ihtiyaç duyduğu kaynağa erişememesi durumu
- **Actor Model:** Aktörler arasında mesaj geçişine dayalı eşzamanlılık modeli

## 🛠 Yazılım Geliştirme Süreçleri

### Metodolojiler
- **Agile:** Esnek ve iteratif yazılım geliştirme metodolojisi
- **Scrum:** Ekiplerin işlerini sprint adı verilen zaman dilimlerinde yönettiği Agile framework
- **Kanban:** Görsel panolarla iş akışını yönetmeye odaklanan metodoloji
- **Waterfall:** Adım adım ilerleyen geleneksel yazılım geliştirme modeli
- **Extreme Programming (XP):** Müşteri memnuniyeti ve kaliteli yazılım odaklı Agile metodoloji
- **Lean Software Development:** İsrafı azaltmaya ve değer yaratmaya odaklanan yaklaşım
- **SAFe (Scaled Agile Framework):** Büyük ölçekli organizasyonlar için Agile çerçeve
- **Feature-Driven Development (FDD):** Özellik bazlı geliştirme yaklaşımı
- **RAD (Rapid Application Development):** Hızlı uygulama geliştirme metodolojisi
- **Spiral Model:** Risk analizi ile geliştirme sürecini spiral biçimde ele alan model
- **V-Model:** Doğrulama ve geçerleme odaklı geliştirme modeli

### Yazılım Yaşam Döngüsü
- **SDLC (Software Development Life Cycle):** Yazılım geliştirme yaşam döngüsü
- **Requirement Analysis:** İhtiyaçların analiz edildiği yazılım geliştirme aşaması
- **Design:** Yazılımın tasarlandığı aşama
- **Implementation:** Kodlamanın yapıldığı aşama
- **Testing:** Yazılımın test edildiği aşama
- **Deployment:** Yazılımın canlı ortama alındığı aşama
- **Maintenance:** Yazılımın bakım ve güncellemelerinin yapıldığı aşama
- **End of Life (EOL):** Yazılımın destek süresinin sona erdiği aşama
- **Prototyping:** Hızlı prototipleme ile kullanıcı geribildirimi toplama süreci
- **MVP (Minimum Viable Product):** En az özellik seti ile piyasaya sürülen ilk ürün

### DevOps ve CI/CD
- **CI/CD:** Sürekli entegrasyon ve dağıtım prensipleri
- **DevOps:** Geliştirme ve operasyon ekipleri arasındaki işbirliğini artıran yaklaşım
- **Git Flow:** Git ile çalışma sürecini düzenleyen bir yöntem
- **Pull Request:** Kod değişikliklerini inceleme ve birleştirme talebi
- **Continuous Integration (CI):** Kod değişikliklerini otomatik olarak entegre etme süreci
- **Continuous Delivery (CD):** Yazılımın hızlı ve güvenli şekilde canlıya alınma süreci
- **Continuous Deployment:** Kod değişikliklerinin otomatik olarak canlıya alınma süreci
- **Infrastructure as Code (IaC):** Altyapının kod olarak tanımlanması ve yönetilmesi
- **Configuration Management:** Sistem yapılandırmalarının yönetimi
- **Containerization:** Uygulamaları izole konteynerler olarak paketleme ve çalıştırma
- **Orchestration:** Konteyner ve mikroservislerin yönetimi ve koordinasyonu
- **Blue-Green Deployment:** Sıfır kesinti için iki özdeş ortam arasında geçiş yapma tekniği
- **Canary Deployment:** Yeni sürümü küçük bir kullanıcı grubuna kademeli olarak sunma
- **Rollback:** Sorun durumunda önceki sürüme hızlıca geri dönme
- **Feature Branch:** Her özellik için ayrı bir dal kullanma stratejisi

### Test Süreçleri
- **Unit Test:** Küçük kod parçalarının bağımsız olarak test edilmesi
- **Integration Test:** Birden fazla bileşenin birlikte çalışmasının test edilmesi
- **Regression Test:** Daha önce çalışan özelliklerin hala çalıştığını doğrulamak için yapılan test
- **TDD (Test-Driven Development):** Önce test yazıp sonra kod geliştirme yöntemi
- **BDD (Behavior-Driven Development):** Kullanıcı senaryolarına dayalı yazılım geliştirme modeli
- **System Test:** Tüm sistemin bir bütün olarak test edilmesi
- **Acceptance Test:** Son kullanıcı gereksinimlerini karşıladığını doğrulayan test
- **End-to-End Test (E2E):** Uygulamanın baştan sona tüm akışının test edilmesi
- **Load Test:** Sistemin yük altındaki performansını ölçen test
- **Stress Test:** Sistemin sınırlarını zorlayan test
- **Smoke Test:** Temel işlevlerin çalıştığını hızlıca kontrol eden test
- **Sanity Test:** Belirli fonksiyonların detaylı çalışmasını kontrol eden dar kapsamlı test
- **Performance Test:** Yazılımın performansını ölçen test
- **Security Test:** Güvenlik açıklarını tespit etmeye yönelik test
- **Mutation Test:** Kodda yapay değişiklikler yaparak test kalitesini ölçen test
- **Mock:** Test sırasında gerçek nesnelerin yerine kullanılan simülasyon nesneleri
- **Stub:** Test sürecinde belirli davranışları taklit eden basit uygulama

### Proje Yönetimi
- **Sprint:** Scrum metodolojisinde belirli süredeki çalışma dönemi
- **User Story:** Kullanıcı bakış açısıyla yazılmış gereksinim tanımı
- **Backlog:** Yapılacak işlerin önceliklendirilmiş listesi
- **Sprint Planning:** Sprint içinde yapılacak işlerin planlandığı toplantı
- **Daily Standup:** Günlük durum toplantısı
- **Retrospective:** Sprint sonunda yapılan değerlendirme toplantısı
- **Burndown Chart:** Kalan işi gösteren grafik
- **Velocity:** Ekibin sprint başına tamamladığı iş miktarı
- **Epic:** Büyük, karmaşık bir kullanıcı hikayesi
- **Task:** İş listesindeki bir görev
- **Story Point:** Kullanıcı hikayesinin göreceli büyüklüğünü ifade eden birim
- **WIP (Work in Progress) Limit:** Aynı anda yapılan iş sayısını sınırlama
- **Definition of Done (DoD):** Bir görevin tamamlanmış sayılması için kriterleri
- **Definition of Ready (DoR):** Bir görevin başlanmaya hazır olma kriterleri
- **Milestone:** Proje sürecinde önemli dönüm noktası
- **Release Planning:** Ürün sürümlerinin planlanması

## 🌐 Web Geliştirme

### Temel Teknolojiler
- **HTTP / HTTPS:** Web istemcileri ve sunucuları arasında veri iletim protokolü
- **HTML:** Web sayfaları oluşturmak için kullanılan işaretleme dili
- **CSS:** Web sayfalarının görünümünü düzenleyen stil dili
- **JavaScript:** Web sayfalarına dinamik özellikler katan programlama dili
- **DOM (Document Object Model):** Web sayfalarını programlama dilleriyle manipüle etmeyi sağlayan API
- **WebSockets:** İstemci ve sunucu arasında kalıcı bağlantı kuran protokol
- **WebRTC:** Tarayıcılar arası gerçek zamanlı iletişim protokolü
- **WebAssembly (WASM):** Tarayıcıda yüksek performanslı çalışan binary format
- **PWA (Progressive Web App):** Mobil uygulama benzeri deneyim sunan web uygulamaları
- **SPA (Single Page Application):** Tek sayfa üzerinde çalışan web uygulamaları

### Frontend
- **Framework:** React, Angular, Vue gibi frontend uygulama çatıları
- **State Management:** Uygulama durumunun yönetilmesi (Redux, Vuex, Context API)
- **Virtual DOM:** Gerçek DOM'u verimli güncellemek için kullanılan sanal DOM yapısı
- **Responsive Design:** Farklı ekran boyutlarına uyum sağlayan tasarım yaklaşımı
- **CSS Preprocessor:** SASS, LESS gibi CSS kodunu genişleten önişlemciler
- **CSS Framework:** Bootstrap, Tailwind gibi hazır stil ve bileşen kütüphaneleri
- **Component-Based Design:** Bileşen tabanlı kullanıcı arayüzü geliştirme yaklaşımı
- **Lazy Loading:** Sayfanın ihtiyaç duyuldukça yüklenmesi tekniği
- **Code Splitting:** JavaScript kodunu küçük parçalara bölerek yükleme sürelerini iyileştirme
- **Bundling:** Modül ve bağımlılıkları tek bir dosyada birleştirme süreci

### Backend
- **REST API:** Kaynak tabanlı web servis mimarisi
- **GraphQL:** API'lerden veri çekmek için kullanılan esnek sorgu dili
- **gRPC:** Yüksek performanslı RPC (Uzak Prosedür Çağrısı) çerçevesi
- **API Gateway:** API'lere erişimi yöneten ve kontrol eden servis
- **Serverless:** Fiziksel sunucuları yönetmeden kod çalıştırma yaklaşımı
- **Microservices:** Uygulamaları küçük, bağımsız servislere bölen mimari yaklaşım
- **Backend Framework:** Django, Express, Laravel gibi backend çatıları
- **ORM (Object-Relational Mapping):** Veritabanı ve nesne modellerini bağlayan yazılım
- **MVC (Model-View-Controller):** Uygulama katmanlarını ayıran mimari desen
- **Route/Routing:** HTTP isteklerini uygun işleyici fonksiyonlara yönlendirme

### Web Güvenliği ve Standartlar
- **CORS:** Tarayıcıların farklı kaynaklardan veri almasına izin veren mekanizma
- **JWT:** JSON Web Token, kullanıcı kimlik doğrulama mekanizması
- **OAuth:** Yetkilendirme standardı, üçüncü parti erişim sağlama protokolü
- **HTTPS:** Şifrelenmiş HTTP protokolü
- **CSP (Content Security Policy):** XSS saldırılarına karşı koruma sağlayan güvenlik katmanı
- **OWASP:** Web uygulaması güvenlik açıklarını belirleyen topluluk
- **SSL/TLS:** Ağ iletişimini şifreleyen güvenlik protokolleri
- **Same-Origin Policy:** Tarayıcı güvenlik politikası
- **Cookie:** Web sitelerinin kullanıcı tarayıcısında sakladığı küçük veri parçası
- **Session:** Kullanıcının web sitesi ile etkileşiminin sunucu tarafında tutulması

### Web Veri Formatları
- **JSON:** Hafif ve insan tarafından okunabilir veri formatı
- **XML:** Yapılandırılmış veri için işaretleme dili
- **YAML:** Yapılandırma dosyaları için kullanılan insan tarafından okunabilir format
- **JSONP:** Farklı alan adlarından JSON veri almak için kullanılan yöntem
- **RSS/Atom:** Web içeriği besleme formatları
- **MIME Types:** İnternet üzerinde gönderilen içeriğin türünü belirten standart

## 📱 Mobil Geliştirme

### Genel Kavramlar
- **Native App:** Belirli bir mobil platform için o platformun teknolojisiyle geliştirilen uygulama
- **Hybrid App:** Web teknolojileri kullanarak geliştirilen mobil uygulama
- **Cross-Platform Development:** Farklı platformlar için tek kod tabanıyla geliştirme
- **App Store:** Mobil uygulamaların dağıtıldığı dijital mağaza
- **App Lifecycle:** Mobil uygulamanın çalışma sürecindeki farklı durumlar
- **Deep Link:** Mobil uygulamanın belirli sayfasına doğrudan erişim sağlayan URL
- **Push Notification:** Uygulamalar tarafından kullanıcıya gönderilen bildirimler
- **Offline-First:** İnternet bağlantısı olmadan da çalışabilen uygulama yaklaşımı
- **App Bundle:** Uygulamanın dağıtım için paketlenmiş hali
- **Permission:** Kullanıcıdan istenen izinler (kamera, konum vb.)

### iOS Geliştirme
- **Swift:** Apple'ın modern iOS ve macOS geliştirme dili
- **Objective-C:** iOS için daha eski nesne yönelimli programlama dili
- **Xcode:** Apple'ın resmi geliştirme ortamı
- **CocoaPods:** iOS için bağımlılık yöneticisi
- **UIKit:** iOS kullanıcı arayüzü geliştirme çerçevesi
- **SwiftUI:** Deklaratif UI oluşturma çerçevesi
- **Storyboard:** Görsel arayüz tasarım aracı
- **TestFlight:** iOS uygulamalarını test etme platformu
- **App Thinning:** Uygulama boyutunu optimize etme teknikleri
- **HealthKit:** Sağlık verilerine erişim sağlayan API

### Android Geliştirme
- **Kotlin:** Android geliştirme için modern programlama dili
- **Java:** Android için geleneksel programlama dili
- **Android Studio:** Resmi Android geliştirme ortamı
- **Gradle:** Android için inşa ve bağımlılık yönetim sistemi
- **APK:** Android uygulama paketi
- **AAB (Android App Bundle):** Uygulamanın Google Play Store'da dağıtım formatı
- **Activity:** Android uygulamalarındaki ekran bileşeni
- **Fragment:** Aktivite içindeki modüler UI bileşeni
- **Intent:** Bileşenler arası iletişim ve eylem mekanizması
- **Jetpack Compose:** Deklaratif UI geliştirme çerçevesi

### Cross-Platform Araçlar
- **React Native:** JavaScript kullanarak native mobil uygulamalar geliştirme çerçevesi
- **Flutter:** Dart dili ile hızlı UI geliştirme çerçevesi
- **Xamarin:** C# ile cross-platform uygulama geliştirme platformu
- **Ionic:** Web teknolojileri ile hibrit uygulama geliştirme çerçevesi
- **Capacitor:** Hybrid uygulamaları native özelliklerle güçlendiren köprü
- **Cordova:** Web teknolojileri ile mobil uygulama geliştirme platformu
- **NativeScript:** JavaScript/TypeScript ile native uygulamalar geliştirme platformu
- **Hot Reload:** Kodda yapılan değişiklikleri anında gösterme özelliği
- **Bridge:** Native kod ile JavaScript arasındaki iletişim katmanı
- **WebView:** Web içeriğini mobil uygulamada gösteren bileşen

## 🏗 Sistem Mimarisi

### Yazılım Mimarisi
- **Monolithic Architecture:** Tek bir birleşik birim içinde oluşturulan yazılım mimarisi
- **Microservices Architecture:** Bağımsız, küçük servislerden oluşan mimari yaklaşım
- **Serverless Architecture:** Sunucu yönetimi gerektirmeyen mimari
- **Event-Driven Architecture:** Olaylar üzerine kurulu mimari
- **SOA (Service-Oriented Architecture):** Servis odaklı mimari
- **Layered Architecture:** Katmanlı mimari (UI, iş mantığı, veri erişimi)
- **Hexagonal Architecture:** Bağlantı noktaları üzerine kurulu mimari (Port-Adapter)
- **Clean Architecture:** İç katmanların dış katmanlara bağımlı olmadığı mimari
- **CQRS:** Komut ve sorgu sorumluluk ayrımı deseni
- **Domain-Driven Design (DDD):** İş alanı odaklı yazılım geliştirme yaklaşımı

### Tasarım Desenleri
- **Design Pattern:** Yazılım geliştirmede tekrar eden problemlere çözüm şablonları
- **Singleton:** Bir sınıfın yalnızca bir örneğinin olmasını sağlayan tasarım deseni
- **Factory:** Nesne oluşturma işlemini soyutlayan tasarım deseni
- **Observer:** Bağımlı nesnelere otomatik bildirim gönderen tasarım deseni
- **Strategy:** Algoritmaları dinamik olarak değiştirmeyi sağlayan tasarım deseni
- **Decorator:** Nesnelere dinamik olarak davranış ekleyen tasarım deseni
- **Adapter:** Uyumsuz arayüzleri birlikte çalışabilir kılan tasarım deseni
- **Facade:** Karmaşık alt sistemleri basit bir arayüz arkasında gizleyen tasarım deseni
- **Command:** İsteği nesne olarak kapsülleyen tasarım deseni
- **Proxy:** Başka bir nesneye erişimi kontrol eden tasarım deseni

### Ölçeklendirme ve Performans
- **Scalability:** Artan yüke uyum sağlama yeteneği
- **Horizontal Scaling:** Sisteme daha fazla makine ekleyerek ölçekleme
- **Vertical Scaling:** Mevcut makinelerin kapasitesini artırarak ölçekleme
- **Load Balancing:** Trafiği birden çok sunucu arasında dağıtma
- **Caching:** Sık kullanılan verilerin hızlı erişim için önbellekte tutulması
- **CDN (Content Delivery Network):** İçeriği kullanıcılara yakın sunuculardan dağıtma
- **Auto-Scaling:** Sistem yüküne göre kaynakları otomatik ayarlama
- **Database Sharding:** Veritabanını parçalara bölerek ölçeklendirme
- **Throttling:** İstek sayısını sınırlayarak sistemi koruma
- **Latency:** Bir işlemin tamamlanması için geçen süre
- **Throughput:** Birim zamanda işlenen iş miktarı

## 🗄 Veritabanları

### İlişkisel Veritabanları
- **SQL:** İlişkisel veritabanlarını yönetmek için kullanılan sorgu dili
- **RDBMS:** İlişkisel veritabanı yönetim sistemi
- **Table:** Verilerin satır ve sütunlarda saklandığı temel yapı
- **Primary Key:** Bir tablodaki benzersiz tanımlayıcı
- **Foreign Key:** Başka bir tablonun birincil anahtarına referans veren alan
- **Index:** Sorgularda performansı artıran veri yapısı
- **Normalization:** Veri tekrarını azaltmak için verileri düzenleme süreci
- **Join:** Farklı tablolarda ilişkili verileri birleştirme
- **Transaction:** Atomik işlem, ya tamamen ya da hiç uygulanmayan işlemler grubu
- **View:** Sanal bir tablo, bir veya birden fazla tablonun özelleştirilmiş görünümü

### NoSQL Veritabanları
- **NoSQL:** Esnek veri saklama sağlayan, ilişkisel olmayan veritabanı türü
- **Document DB:** Belge odaklı NoSQL veritabanı (MongoDB, Couchbase)
- **Key-Value Store:** Anahtar-değer NoSQL veritabanı (Redis, DynamoDB)
- **Column-Family DB:** Sütun ailesi NoSQL veritabanı (Cassandra, HBase)
- **Graph DB:** Graf NoSQL veritabanı (Neo4j, ArangoDB)
- **Time Series DB:** Zaman serisi veritabanı (InfluxDB, Prometheus)
- **Wide-Column Store:** Geniş sütun veritabanı (Google Bigtable)
- **Schema-less:** Şemasız veri modeli
- **Eventual Consistency:** Nihai tutarlılık modeli
- **Partition Tolerance:** Bölünme toleransı

### Veritabanı Kavramları
- **ACID:** Veritabanı işlemlerinin güvenilirliğini sağlayan prensipler
- **BASE:** NoSQL veritabanları için ACID'in alternatifi, temel tutarlılık modeli
- **Sharding:** Büyük verileri küçük parçalara ayırarak veritabanı ölçekleme yöntemi
- **Replication:** Verilerin kopyalanarak farklı sunucularda tutulması
- **Master-Slave Replication:** Ana-bağımlı çoğaltma modeli
- **Connection Pooling:** Bağlantı havuzu, veritabanı bağlantılarını yeniden kullanma
- **Query Optimization:** Sorgu optimizasyonu
- **Stored Procedure:** Veritabanında saklanan ve çalıştırılabilen komut dizisi
- **Trigger:** Belirli olaylar gerçekleştiğinde otomatik çalışan kod
- **CAP Theorem:** Tutarlılık, Erişilebilirlik ve Bölünme Toleransı teoremi
- **ORM:** Nesne İlişkisel Eşleme, kod ile veritabanı arasında bağlantı kuran yazılım
- **Migration:** Veritabanı şemasındaki değişiklikleri yönetme süreci
- **Connection String:** Veritabanına bağlanmak için kullanılan format
- **Deadlock:** Kilitlenme, iki veya daha fazla işlem birbirlerinin kilitlerini beklemesi
- **N+1 Problem:** ORM'lerde yaygın görülen, çok fazla veritabanı sorgusu yapma problemi

### Veri Yönetimi
- **ETL (Extract, Transform, Load):** Verileri çıkarma, dönüştürme ve yükleme süreci
- **Data Warehouse:** Veri ambarı, analiz için optimize edilmiş veri deposu
- **Data Lake:** Veri gölü, ham veri depolama sistemi
- **Data Mart:** Belirli bir departman için özelleştirilmiş veri deposu
- **OLTP:** Çevrimiçi işlem işleme, günlük operasyonlar için veri işleme
- **OLAP:** Çevrimiçi analitik işleme, analiz için veri işleme
- **Data Mining:** Veri madenciliği, büyük verilerden anlamlı bilgiler çıkarma
- **Business Intelligence:** İş zekası, veri analizi ve raporlama
- **Star Schema:** Yıldız şeması, veri ambarı modelleme yöntemi
- **Snowflake Schema:** Kardanağacı şeması, veri ambarı modelleme yöntemi

## 🔐 Siber Güvenlik

### Temel Kavramlar
- **Hashing:** Verileri tek yönlü olarak şifreleyen işlem
- **Encryption:** Verileri güvenli hale getirmek için şifreleme yöntemi
- **XSS:** Web sayfalarına zararlı kod yerleştirme saldırısı
- **SQL Injection:** SQL sorgularına kötü amaçlı komutlar enjekte etme saldırısı
- **MFA:** Çok faktörlü kimlik doğrulama yöntemi
- **Vulnerability:** Güvenlik açığı, bir sistemin zayıf noktası
- **Exploit:** Güvenlik açığını kötüye kullanan yazılım veya teknik
- **Zero-Day Vulnerability:** Henüz kamuya açıklanmamış ve yamalar yayınlanmamış güvenlik açığı
- **Penetration Testing:** Sızma testi, güvenlik açıklarını bulmak için yapılan kontrollü saldırı
- **Threat Model:** Tehdit modeli, olası güvenlik tehditlerini tanımlama süreci

### Saldırı Türleri
- **DDoS (Distributed Denial of Service):** Dağıtık hizmet reddi saldırısı
- **Phishing:** Kimlik avı, kullanıcıları kandırarak bilgi elde etme
- **Man-in-the-Middle:** Ortadaki adam saldırısı, iletişimi gizlice dinleme
- **Brute Force:** Kaba kuvvet saldırısı, tüm olası kombinasyonları deneme
- **Ransomware:** Fidye yazılımı, verileri şifreleyip fidye isteme
- **Social Engineering:** Sosyal mühendislik, insan zafiyetlerini kullanan saldırı
- **Spoofing:** Kimlik taklidi, başka bir güvenilir kaynağı taklit etme
- **Rootkit:** Sistem üzerinde gizli erişim sağlayan zararlı yazılım
- **Keylogger:** Tuş vuruşlarını kaydeden zararlı yazılım
- **Buffer Overflow:** Tampon taşması, bellek sınırlarını aşan veri girişi

### Savunma Mekanizmaları
- **Firewall:** Güvenlik duvarı, ağ trafiğini kontrol eden sistem
- **IDS/IPS:** Saldırı tespit/önleme sistemleri
- **WAF (Web Application Firewall):** Web uygulama güvenlik duvarı
- **VPN (Virtual Private Network):** Sanal özel ağ, şifreli iletişim tüneli
- **Antivirus:** Virüs karşıtı yazılım
- **Patch Management:** Yama yönetimi, güvenlik güncellemelerini uygulama
- **Network Segmentation:** Ağ segmentasyonu, ağı izole bölümlere ayırma
- **Principle of Least Privilege:** En az ayrıcalık ilkesi
- **Defense in Depth:** Derinlemesine savunma, çok katmanlı güvenlik
- **Secure SDLC:** Güvenli yazılım geliştirme yaşam döngüsü

### Güvenlik Standartları ve Uyumluluk
- **GDPR:** Avrupa Birliği Genel Veri Koruma Tüzüğü
- **HIPAA:** Sağlık Sigortası Taşınabilirlik ve Sorumluluk Yasası
- **PCI DSS:** Ödeme Kartı Endüstrisi Veri Güvenliği Standardı
- **ISO 27001:** Bilgi güvenliği yönetim sistemi standardı
- **SOC 2:** Servis organizasyonları için güvenlik standardı
- **NIST Framework:** ABD Ulusal Standartlar ve Teknoloji Enstitüsü güvenlik çerçevesi
- **Privacy by Design:** Tasarımla gizlilik, ürün tasarımında gizliliğin gözetilmesi
- **Security by Default:** Varsayılan olarak güvenlik ilkesi
- **OWASP Top 10:** En yaygın web uygulama güvenlik riskleri listesi
- **Bug Bounty:** Güvenlik açıklarını bildirenlere ödül programı

### Kriptografi
- **Symmetric Encryption:** Simetrik şifreleme, aynı anahtar ile şifreleme ve çözme
- **Asymmetric Encryption:** Asimetrik şifreleme, farklı anahtarlarla şifreleme ve çözme
- **Public Key Infrastructure (PKI):** Açık anahtar altyapısı
- **Digital Signature:** Dijital imza, veri bütünlüğü ve kimlik doğrulama
- **Certificate Authority (CA):** Sertifika otoritesi, dijital sertifikaları doğrulayan güvenilir üçüncü taraf
- **TLS/SSL:** Transport Layer Security/Secure Sockets Layer, iletişim güvenlik protokolleri
- **AES (Advanced Encryption Standard):** Gelişmiş şifreleme standardı
- **RSA:** Asimetrik şifreleme algoritması
- **SHA (Secure Hash Algorithm):** Güvenli özet algoritması
- **Salt:** Şifre hashlerine eklenen rastgele değer, sözlük saldırılarını önlemek için

## 🔍 Veri Bilimi

### Temel Kavramlar
- **Data Science:** Veri bilimi, verilerden değer çıkarma disiplini
- **Big Data:** Büyük veri, geleneksel yöntemlerle işlenemeyen büyük ve karmaşık veri setleri
- **Data Mining:** Veri madenciliği, verilerden örüntüler ve bilgi çıkarma süreci
- **Descriptive Analytics:** Tanımlayıcı analitik, geçmiş verileri özetleme
- **Predictive Analytics:** Tahmine dayalı analitik, gelecek trendleri tahmin etme
- **Prescriptive Analytics:** Reçeteli analitik, en iyi eylemi önerme
- **Data Cleaning:** Veri temizleme, hatalı/eksik verileri düzeltme
- **Data Wrangling:** Veri düzenleme, ham veriyi kullanılabilir hale getirme
- **Feature Engineering:** Öznitelik mühendisliği, model performansını artırmak için özellikler oluşturma
- **Exploratory Data Analysis (EDA):** Keşifsel veri analizi, verileri görselleştirme ve anlama

### Veri Manipülasyonu ve Analizi
- **ETL (Extract, Transform, Load):** Veri çıkarma, dönüştürme ve yükleme süreci
- **Data Pipeline:** Veri işleme süreçleri dizisi
- **SQL:** Yapılandırılmış sorgu dili, veritabanı sorgulama
- **NoSQL:** İlişkisel olmayan veritabanları
- **Data Lake:** Ham veri depolama sistemi
- **Data Warehouse:** Analiz için optimize edilmiş veri deposu
- **OLAP (Online Analytical Processing):** Çevrimiçi analitik işleme
- **Data Mart:** Belirli bir bölüm veya işleve odaklanan veri ambarı alt kümesi
- **Business Intelligence (BI):** İş zekası, veri analizi ve raporlama
- **Real-time Analytics:** Gerçek zamanlı analitik, veri akışlarını anında analiz etme

### İstatistiksel Analiz
- **Statistical Inference:** İstatistiksel çıkarım, örnekten popülasyon hakkında sonuç çıkarma
- **Hypothesis Testing:** Hipotez testi, iddiaları verilerle doğrulama
- **Regression Analysis:** Regresyon analizi, değişkenler arasındaki ilişkileri inceleme
- **Correlation:** Korelasyon, değişkenler arasındaki ilişkinin gücü ve yönü
- **p-value:** Bir hipotezin geçerlilik olasılığını ölçen değer
- **Confidence Interval:** Güven aralığı, tahmin edilen değerin belirsizlik ölçüsü
- **A/B Testing:** İki veya daha fazla versiyonu karşılaştırma yöntemi
- **Statistical Significance:** İstatistiksel anlamlılık, sonucun şansa bağlı olmama olasılığı
- **T-test:** Ortalamalar arasındaki farkları test eden istatistiksel yöntem
- **ANOVA (Analysis of Variance):** Varyans analizi, gruplar arası farkları test eden yöntem

### Veri Görselleştirme
- **Data Visualization:** Veri görselleştirme, verileri görsel olarak temsil etme
- **Dashboard:** Gösterge paneli, önemli metrikleri gösterme
- **Histogram:** Sayısal verilerin dağılımını gösteren çubuk grafik
- **Scatter Plot:** Saçılım grafiği, iki değişken arasındaki ilişkiyi gösteren grafik
- **Heatmap:** Isı haritası, verinin yoğunluğunu renklerle gösteren görselleştirme
- **Box Plot:** Kutu grafiği, veri dağılımını ve aykırı değerleri gösteren grafik
- **Time Series Plot:** Zaman serisi grafiği, verilerin zaman içindeki değişimini gösteren grafik
- **Pie Chart:** Pasta grafiği, kategorik verilerin oranlarını gösteren dairesel grafik
- **Bar Chart:** Çubuk grafik, kategoriler arasında karşılaştırma yapan grafik
- **Interactive Visualization:** Etkileşimli görselleştirme, kullanıcı müdahalesine izin veren grafik

## 🤖 Yapay Zeka ve Makine Öğrenmesi

### Temel Kavramlar
- **Artificial Intelligence (AI):** Bilgisayar sistemlerinin insan benzeri zekaya sahip olmasını sağlayan alan
- **Machine Learning (ML):** Verilerden öğrenerek kararlar veren algoritmaların geliştirildiği alan
- **Deep Learning:** Sinir ağları kullanarak çok katmanlı öğrenme modelidir
- **Neural Network:** Beyin yapısından esinlenerek geliştirilen, çok katmanlı hesaplama modelleri
- **Algorithm:** Belirli bir görevi gerçekleştirmek için takip edilen adımlar
- **Training Data:** Modeli eğitmek için kullanılan veri seti
- **Test Data:** Modelin performansını değerlendirmek için kullanılan veri seti
- **Validation Data:** Model parametrelerini ayarlamak için kullanılan veri seti
- **Feature:** Öznitelik, modelin kullandığı girdi değişkeni
- **Label:** Etiket, modelin tahmin etmeye çalıştığı çıktı değişkeni

### Öğrenme Türleri
- **Supervised Learning:** Etiketlenmiş verilerle makine öğrenmesi modeli oluşturma
- **Unsupervised Learning:** Etiketlenmemiş verilerle desenleri ve ilişkileri öğrenme yöntemi
- **Reinforcement Learning:** Deneme-yanılma yoluyla en iyi kararları veren sistemleri geliştirme
- **Semi-Supervised Learning:** Az miktarda etiketli ve çok miktarda etiketsiz veri kullanma
- **Self-Supervised Learning:** Veri içinden etiketler oluşturarak öğrenme
- **Transfer Learning:** Bir problemde öğrenilen bilgiyi başka bir probleme aktarma
- **Online Learning:** Veri akışı sürerken eğitimi devam ettiren öğrenme
- **Batch Learning:** Tüm veriyi aynı anda kullanarak eğitim yapma
- **Active Learning:** Modelin etiketlenmesini isteyeceği verileri seçme yöntemi
- **Federated Learning:** Verileri merkezi bir sunucuya göndermeden dağıtık eğitim yapma

### Algoritma Türleri
- **Regression:** Sürekli değerler tahmin eden algoritma türü
- **Classification:** Kategorik değerler tahmin eden algoritma türü
- **Clustering:** Verileri benzerliklerine göre gruplayan algoritma türü
- **Decision Tree:** Karar ağacı, kararları dallanma şeklinde modelleyen algoritma
- **Random Forest:** Rastgele orman, birden çok karar ağacını birleştiren model
- **Support Vector Machine (SVM):** Destek vektör makinesi, veri noktalarını ayıran optimal hiper düzlem bulan algoritma
- **K-Nearest Neighbors (KNN):** K-en yakın komşu, benzer örneklere dayalı tahmin yapan algoritma
- **Naive Bayes:** Bayes teoremini kullanan olasılıksal sınıflandırma algoritması
- **K-Means:** K-ortalama, verileri K sayıda kümeye ayıran kümeleme algoritması
- **DBSCAN:** Yoğunluk tabanlı kümeleme algoritması

### Derin Öğrenme
- **Deep Neural Network (DNN):** Derin sinir ağı, çok katmanlı yapay sinir ağı
- **Convolutional Neural Network (CNN):** Evrişimli sinir ağı, görüntü işlemede kullanılır
- **Recurrent Neural Network (RNN):** Tekrarlayan sinir ağı, diziler üzerinde çalışır
- **Long Short-Term Memory (LSTM):** Uzun kısa süreli bellek, uzun bağımlılıkları öğrenebilen RNN türü
- **Generative Adversarial Network (GAN):** Üretici çekişmeli ağ, gerçekçi veri üreten model
- **Autoencoder:** Özdevinimli kodlayıcı, veri sıkıştırma ve özellik çıkarmada kullanılan model
- **Transformer:** İlgi mekanizmasını kullanan model, NLP'de sıkça kullanılır
- **BERT:** Çift yönlü kodlayıcı gösterimler, Google tarafından geliştirilen NLP modeli
- **GPT (Generative Pre-trained Transformer):** Üretken ön eğitimli dönüştürücü, metin üretmede kullanılır
- **ResNet:** Artık ağ, çok derin sinir ağlarını eğitmeyi kolaylaştıran mimari

### Model Performans Kavramları
- **Overfitting:** Modelin aşırı derecede eğitilerek yalnızca eğitim verisini iyi tahmin etmesi
- **Underfitting:** Modelin yetersiz öğrenmesi ve düşük performans göstermesi
- **Bias-Variance Tradeoff:** Modelin öğrenme kapasitesi ve genelleşme yeteneği arasındaki denge
- **Cross-Validation:** Çapraz doğrulama, modelin genelleme yeteneğini değerlendirme tekniği
- **Precision:** Kesinlik, doğru pozitif tahminlerin tüm pozitif tahminlere oranı
- **Recall:** Geri çağırma, doğru pozitif tahminlerin tüm gerçek pozitiflere oranı
- **F1 Score:** Kesinlik ve geri çağırmanın harmonik ortalaması
- **ROC Curve:** Alıcı işletim karakteristiği eğrisi, sınıflandırma performansını gösteren grafik
- **AUC (Area Under Curve):** Eğri altında kalan alan, sınıflandırma performans ölçüsü
- **Confusion Matrix:** Karışıklık matrisi, tahminlerin gerçek değerlerle karşılaştırılması

### Teknik Terimler
- **Feature Engineering:** Verilerden anlamlı öznitelikler çıkarma süreci
- **Gradient Descent:** Optimizasyon algoritması, model ağırlıklarını optimize eder
- **Hyperparameter Tuning:** Modelin performansını iyileştirmek için ayarlanması gereken değişkenler
- **Loss Function:** Modelin hata oranını hesaplayan fonksiyon
- **Backpropagation:** Yapay sinir ağlarında hata hesaplayıp model ağırlıklarını güncelleme yöntemi
- **GANs:** İki yapay sinir ağının birbirine karşı çalıştığı ve yeni veri üreten model
- **Dropout:** Eğitim sırasında bazı nöronları devre dışı bırakarak aşırı öğrenmeyi önleme tekniği
- **Batch Normalization:** Girdi değerlerini normalleştirerek eğitimi hızlandıran teknik
- **Learning Rate:** Öğrenme hızı, gradyan iniş adımlarının büyüklüğünü belirleyen parametre
- **Epoch:** Eğitim verilerinin tamamının bir kez işlenmesi
- **Batch Size:** Her iterasyonda işlenen örnek sayısı
- **One-Hot Encoding:** Kategorik değişkenleri ikili vektörlere dönüştürme
- **Regularization:** Düzenlileştirme, aşırı öğrenmeyi önleyen teknik
- **Ensemble Learning:** Birden fazla modeli birleştirerek daha iyi sonuç alma
- **Word Embedding:** Kelimeleri vektör uzayında temsil etme tekniği

---

Bu liste sürekli güncellenmektedir. Eğer eklenmesini istediğiniz terimler varsa lütfen katkıda bulunun! 🚀

## ☁️ Bulut Bilişim

### Temel Kavramlar
- **Cloud Computing:** İnternet üzerinden sunulan bilişim hizmetleri
- **IaaS (Infrastructure as a Service):** Sanal sunucu, depolama gibi altyapı hizmetleri
- **PaaS (Platform as a Service):** Uygulama geliştirme ve çalıştırma platformu
- **SaaS (Software as a Service):** Doğrudan kullanılabilen yazılım hizmetleri
- **FaaS (Function as a Service):** Sunucusuz işlev çalıştırma hizmeti
- **Public Cloud:** Genel erişime açık bulut hizmetleri
- **Private Cloud:** Özel kullanım için oluşturulan bulut ortamı
- **Hybrid Cloud:** Özel ve genel bulut karışımı
- **Multi-Cloud:** Birden fazla bulut sağlayıcısı kullanımı
- **Cloud Native:** Bulut ortamlar için özel tasarlanmış uygulamalar

### Bulut Servisleri
- **Virtual Machine (VM):** Sanal bilgisayar
- **Container:** Hafif, taşınabilir uygulama paketi
- **Kubernetes:** Konteyner orkestrasyonu platformu
- **Docker:** Konteyner oluşturma ve yönetme platformu
- **Object Storage:** Dosyaları belirli bir hiyerarşi olmadan depolama hizmeti
- **Blob Storage:** Binary Large Object depolama sistemi
- **CDN (Content Delivery Network):** İçerik dağıtım ağı
- **Load Balancer:** Yük dengeleyici
- **Autoscaling:** Otomatik ölçeklendirme
- **Serverless:** Sunucu yönetimi gerektirmeyen hizmetler

### Bulut Sağlayıcıları ve Teknolojiler
- **AWS (Amazon Web Services):** Amazon'un bulut platformu
- **Azure:** Microsoft'un bulut platformu
- **GCP (Google Cloud Platform):** Google'ın bulut platformu
- **Lambda:** AWS'nin sunucusuz işlev hizmeti
- **EC2:** AWS'nin sanal makine hizmeti
- **S3:** AWS'nin nesne depolama hizmeti
- **Azure Functions:** Microsoft'un sunucusuz işlev hizmeti
- **Cloud Functions:** Google'ın sunucusuz işlev hizmeti
- **Heroku:** Uygulama barındırma platformu
- **Firebase:** Google'ın mobil ve web uygulama geliştirme platformu

### Bulut Güvenliği
- **IAM (Identity and Access Management):** Kimlik ve erişim yönetimi
- **VPC (Virtual Private Cloud):** Sanal özel bulut
- **Security Group:** Güvenlik grubu, erişim kontrol listesi
- **Encryption at Rest:** Durağan veri şifreleme
- **Encryption in Transit:** İletim halindeki veri şifreleme
- **CASB (Cloud Access Security Broker):** Bulut erişim güvenlik aracısı
- **DDoS Protection:** Dağıtık hizmet engelleme koruması
- **Compliance:** Yasal ve düzenleyici uyumluluk
- **Shared Responsibility Model:** Paylaşılan sorumluluk modeli
- **Zero Trust Security:** Sıfır güven güvenlik modeli

## 🔄 DevOps ve SRE

### DevOps Kavramları
- **DevOps:** Geliştirme ve operasyon ekipleri arasındaki işbirliğini artıran yaklaşım
- **CI/CD Pipeline:** Sürekli entegrasyon ve dağıtım boru hattı
- **Infrastructure as Code (IaC):** Altyapının kod olarak tanımlanması ve yönetilmesi
- **Configuration Management:** Yapılandırma yönetimi
- **Containerization:** Konteynerleştirme
- **Automation:** Otomasyon
- **Deployment Strategy:** Dağıtım stratejisi
- **GitOps:** Git tabanlı operasyon yönetimi
- **Shift Left Testing:** Test süreçlerini geliştirme yaşam döngüsünün daha erken aşamalarına taşıma
- **Value Stream Mapping:** Değer akışı haritalama

### SRE (Site Reliability Engineering)
- **SRE:** Site güvenilirlik mühendisliği, operasyonel sorunları yazılım mühendisliği yaklaşımıyla çözme
- **SLI (Service Level Indicator):** Hizmet seviyesi göstergesi
- **SLO (Service Level Objective):** Hizmet seviyesi hedefi
- **SLA (Service Level Agreement):** Hizmet seviyesi anlaşması
- **Error Budget:** Hata bütçesi, güvenilirlik ölçütü
- **Toil:** Tekrarlayan, otomatikleştirilebilir operasyonel işler
- **Reliability:** Güvenilirlik, sistemin kesintisiz çalışması
- **Observability:** Gözlemlenebilirlik, sistemin iç durumunu anlama
- **Chaos Engineering:** Üretim ortamında kasıtlı hatalar oluşturarak dayanıklılığı test etme
- **Post-Mortem:** Olay sonrası inceleme raporu

### Altyapı ve Yapılandırma Yönetimi
- **Terraform:** Altyapı olarak kod aracı
- **Ansible:** Yapılandırma yönetimi ve otomasyon aracı
- **Puppet:** Yapılandırma yönetimi aracı
- **Chef:** Altyapı otomasyon aracı
- **Salt:** Yapılandırma yönetimi ve uzaktan yürütme aracı
- **CloudFormation:** AWS'nin altyapı olarak kod hizmeti
- **ARM Templates:** Azure Resource Manager şablonları
- **Packer:** Makine imajı oluşturma aracı
- **Vagrant:** Geliştirme ortamlarını oluşturma ve yönetme aracı
- **Helm:** Kubernetes paket yöneticisi

### İzleme ve Günlük Tutma
- **Monitoring:** Sistem performansını ve sağlığını izleme
- **Logging:** Günlük kayıtları tutma
- **Tracing:** İşlem izleme, dağıtık sistemlerde istek takibi
- **Metrics:** Ölçümler, sistem performansını sayısal olarak izleme
- **Alerting:** Uyarı sistemi
- **Dashboards:** Gösterge panelleri
- **APM (Application Performance Monitoring):** Uygulama performans izleme
- **ELK Stack:** Elasticsearch, Logstash, Kibana
- **Prometheus:** Metrik toplama ve uyarı sistemi
- **Grafana:** Metrik görselleştirme aracı

### Konteynerleştirme ve Orkestrasyon
- **Docker:** Konteyner oluşturma ve çalıştırma platformu
- **Docker Compose:** Çoklu konteyner uygulamaları tanımlama ve çalıştırma aracı
- **Kubernetes:** Konteyner orkestrasyon platformu
- **Pod:** Kubernetes'te bir veya daha fazla konteyner içeren birim
- **Node:** Kubernetes kümesindeki işçi makine
- **Namespace:** Kubernetes kaynaklarını gruplama ve izole etme mekanizması
- **Service:** Kubernetes'te pod gruplarını açığa çıkaran soyutlama
- **Ingress:** Kubernetes kümesine dış erişim kuralları
- **ConfigMap:** Yapılandırma bilgilerini depolama
- **Secret:** Hassas bilgileri depolama

## 🌍 Blockchain ve Web3

### Temel Kavramlar
- **Blockchain:** Değiştirilemez, dağıtık kayıt defteri teknolojisi
- **Distributed Ledger:** Dağıtık kayıt defteri, birden çok düğümde saklanan eşzamanlı kayıtlar
- **Cryptocurrency:** Kripto para, şifreleme kullanan dijital para birimi
- **Bitcoin:** İlk ve en bilinen kripto para birimi
- **Ethereum:** Akıllı sözleşmeleri destekleyen blockchain platformu
- **Smart Contract:** Akıllı sözleşme, blockchain üzerinde otomatik çalışan kod
- **Consensus Mechanism:** Uzlaşma mekanizması, ağdaki anlaşmayı sağlayan süreç
- **Mining:** Madencilik, yeni blokların oluşturulma süreci
- **Hash Function:** Özet fonksiyonu, veriden sabit boyutlu özet oluşturan algoritma
- **Public Key Cryptography:** Açık anahtar kriptografisi, blockchain güvenliğinin temeli

### Blockchain Mekanizmaları
- **Proof of Work (PoW):** İş kanıtı, hesaplama gücüne dayalı uzlaşma mekanizması
- **Proof of Stake (PoS):** Hisse kanıtı, sahip olunan token miktarına dayalı uzlaşma mekanizması
- **Delegated Proof of Stake (DPoS):** Delegeli hisse kanıtı, temsilcilere dayalı uzlaşma mekanizması
- **Practical Byzantine Fault Tolerance (PBFT):** Bizans hata toleransı protokolü
- **Merkle Tree:** Merkle ağacı, blockchain veri yapısında kullanılan özet ağacı
- **Block:** Blok, işlemleri içeren blockchain yapı taşı
- **Transaction:** İşlem, blockchain ağında kaydedilen veri birimi
- **Gas:** Ethereum ağında işlem maliyetini belirleyen birim
- **Nonce:** Madencilikte çözülmesi gereken kriptografik bulmaca değeri
- **Hard Fork:** Sert çatal, blockchain protokolünde geriye dönük uyumlu olmayan değişiklik

### Web3 Kavramları
- **Web3:** İnternet'in merkeziyetsiz, blockchain tabanlı yeni nesli
- **Decentralized Application (dApp):** Merkeziyetsiz uygulama, blockchain üzerinde çalışan uygulama
- **DeFi (Decentralized Finance):** Merkeziyetsiz finans, geleneksel finans işlemlerini blockchain üzerinde gerçekleştirme
- **NFT (Non-Fungible Token):** Değiştirilemez token, benzersiz dijital varlıklar
- **DAO (Decentralized Autonomous Organization):** Merkeziyetsiz otonom organizasyon
- **Wallet:** Cüzdan, kripto varlıkları saklamak için kullanılan yazılım
- **Token Standard:** Token standardı, belirli özelliklere sahip token sınıfları (ERC-20, ERC-721)
- **Metaverse:** Metaevren, dijital sosyal etkileşim ortamı
- **Interoperability:** Farklı blockchain ağları arasında bilgi ve değer aktarımı
- **Layer 2 Solutions:** Ana blockchain üzerinde ölçeklenebilirliği artıran çözümler

### Akıllı Sözleşmeler ve Geliştirme
- **Solidity:** Ethereum akıllı sözleşmeleri için programlama dili
- **Web3.js/ethers.js:** Ethereum ile etkileşim için JavaScript kütüphaneleri
- **Truffle/Hardhat:** Ethereum geliştirme çerçeveleri
- **Ganache:** Yerel Ethereum geliştirme için test ağı
- **Gas Optimization:** Akıllı sözleşme işlem maliyetlerini azaltma teknikleri
- **Oracles:** Blockchain dışındaki verileri akıllı sözleşmelere aktaran servisler
- **IPFS (InterPlanetary File System):** Merkeziyetsiz dosya depolama sistemi
- **ENS (Ethereum Name Service):** Ethereum adresleri için alan adı sistemi
- **Tokenomics:** Token ekonomisi, kripto para birimlerinin ekonomik modeli
- **zkSNARKs/zkSTARKs:** Sıfır bilgi kanıtı teknolojileri, gizlilik korumalı işlemler

## 🔧 Araçlar ve Teknolojiler

### Programlama Dilleri
- **JavaScript:** Web geliştirme için yaygın olarak kullanılan dil
- **Python:** Genel amaçlı, okunabilir programlama dili, veri bilimi ve yapay zekada yaygın
- **Java:** Nesne yönelimli, platform bağımsız programlama dili
- **C++:** Yüksek performanslı sistem programlama dili
- **C#:** Microsoft tarafından geliştirilen nesne yönelimli dil
- **Go:** Google tarafından geliştirilen basit, hızlı ve verimli dil
- **Rust:** Güvenlik ve performans odaklı sistem programlama dili
- **TypeScript:** JavaScript'in tür güvenliği eklenmiş üst kümesi
- **PHP:** Web geliştirme için tasarlanmış betik dili
- **Swift:** Apple ekosistemi için modern programlama dili

### Frontend Teknolojileri
- **React:** Facebook tarafından geliştirilen JavaScript kütüphanesi
- **Angular:** Google tarafından geliştirilen frontend çerçevesi
- **Vue.js:** Kullanımı kolay, progresif JavaScript çerçevesi
- **Next.js:** React tabanlı, sunucu tarafı rendering destekli çerçeve
- **Webpack:** Modern JavaScript uygulamaları için modül paketleyici
- **Babel:** JavaScript kod dönüştürücü, modern kodu eski tarayıcılarda çalıştırma
- **ESLint:** JavaScript kod kalitesini kontrol eden araç
- **SASS/SCSS:** CSS ön işlemci, daha güçlü stil yazımı
- **Tailwind CSS:** Utility-first CSS çerçevesi
- **SPA (Single Page Application):** Tek sayfa uygulamaları

### Backend Teknolojileri
- **Node.js:** JavaScript çalıştırmak için sunucu taraflı platform
- **Express.js:** Node.js için web uygulama çerçevesi
- **Django:** Python tabanlı yüksek seviyeli web çerçevesi
- **Flask:** Python için hafif web çerçevesi
- **Ruby on Rails:** Ruby dili için web uygulama çerçevesi
- **Spring Boot:** Java tabanlı uygulama geliştirme çerçevesi
- **Laravel:** PHP için web uygulama çerçevesi
- **ASP.NET Core:** Microsoft'un çapraz platform web çerçevesi
- **FastAPI:** Modern, hızlı Python web çerçevesi
- **GraphQL:** API sorgu dili ve çalışma zamanı

### Veritabanı Teknolojileri
- **MySQL:** Açık kaynaklı ilişkisel veritabanı yönetim sistemi
- **PostgreSQL:** Gelişmiş özelliklere sahip açık kaynaklı ilişkisel veritabanı
- **MongoDB:** Doküman tabanlı NoSQL veritabanı
- **Redis:** Bellek içi anahtar-değer veri yapısı deposu
- **Elasticsearch:** Dağıtık, RESTful arama ve analitik motoru
- **Cassandra:** Yüksek ölçeklenebilir NoSQL veritabanı
- **SQLite:** Sunucu gerektirmeyen, hafif ilişkisel veritabanı
- **Neo4j:** Graf veritabanı yönetim sistemi
- **MariaDB:** MySQL'in açık kaynaklı çatalı
- **DynamoDB:** Amazon'un tam yönetilen NoSQL veritabanı hizmeti

### Geliştirme Araçları
- **Git:** Dağıtık versiyon kontrol sistemi
- **GitHub/GitLab/Bitbucket:** Git tabanlı kod barındırma platformları
- **Docker:** Uygulamaları konteynerlerde paketleme platformu
- **Kubernetes:** Konteyner orkestrasyon platformu
- **Jenkins:** Sürekli entegrasyon ve dağıtım (CI/CD) aracı
- **Jira:** Proje ve sorun takip yazılımı
- **Postman:** API geliştirme ve test aracı
- **Visual Studio Code:** Yaygın kullanılan kod editörü
- **IntelliJ IDEA:** Java geliştirme için IDE
- **PyCharm:** Python geliştirme için IDE

### Test Araçları
- **Jest:** JavaScript test çerçevesi
- **Mocha:** JavaScript test çerçevesi
- **Selenium:** Web uygulamaları için test otomasyon aracı
- **JUnit:** Java için birim test çerçevesi
- **PyTest:** Python için test çerçevesi
- **Cypress:** Modern web test otomasyon çerçevesi
- **Cucumber:** Davranış odaklı geliştirme (BDD) aracı
- **TestNG:** Java için test otomasyon çerçevesi
- **Mockito:** Java için mock test çerçevesi
- **Jasmine:** JavaScript için davranış odaklı test çerçevesi

## 📊 Yazılım Metrikleri

### Kod Kalitesi
- **Cyclomatic Complexity:** Yazılımdaki karar yollarının karmaşıklığı
- **Code Coverage:** Test edilen kod yüzdesini ölçen metrik
- **Technical Debt:** Gelecekte ek çalışma gerektiren eksik geliştirmeler
- **Maintainability Index:** Kodun bakım yapılabilirliğini ölçen metrik
- **Code Smell:** Potansiyel derin problemlere işaret eden yüzeysel kod belirtileri
- **Lines of Code (LOC):** Kod satır sayısı
- **Code Churn:** Belirli bir sürede değişen kod miktarı
- **Code Duplication:** Tekrarlanan kod miktarı
- **Function Points:** Yazılım işlevselliğini ölçen metrik
- **Comment Ratio:** Kod içindeki yorum oranı

### Performans Metrikleri
- **Response Time:** Sistemin istek yanıt süresi
- **Throughput:** Birim zamanda işlenen istek sayısı
- **Latency:** İşlem gecikmesi
- **Apdex Score:** Kullanıcı memnuniyeti ölçümü
- **Error Rate:** Hata oranı, başarısız işlem yüzdesi
- **CPU Usage:** İşlemci kullanım oranı
- **Memory Usage:** Bellek kullanım oranı
- **Disk I/O:** Disk giriş/çıkış işlemleri
- **Network Bandwidth:** Ağ bant genişliği kullanımı
- **Server Load:** Sunucu yük ölçümleri

### Proje Metrikleri
- **Velocity:** Ekibin birim zamanda tamamladığı iş miktarı
- **Burndown Chart:** Kalan işin zamana göre gösterimi
- **Lead Time:** İşin başlatılmasından tamamlanmasına kadar geçen süre
- **Cycle Time:** İşe başlandıktan sonra tamamlanmasına kadar geçen süre
- **Sprint Burndown:** Sprint içinde kalan işin günlük takibi
- **Defect Density:** Kod satırı başına düşen hata sayısı
- **Mean Time Between Failures (MTBF):** Arızalar arasındaki ortalama süre
- **Mean Time to Recovery (MTTR):** Arızadan sonra sistemi düzeltme süresi
- **Customer Satisfaction Score:** Müşteri memnuniyet ölçümü
- **ROI (Return on Investment):** Yatırım getirisi, proje maliyetinin kazanca oranı

### DevOps Metrikleri
- **Deployment Frequency:** Üretime yapılan dağıtım sıklığı
- **Change Lead Time:** Kod değişikliğinin üretime alınma süresi
- **Change Failure Rate:** Başarısız değişiklik oranı
- **Mean Time to Restore (MTTR):** Servis kesintisini düzeltme süresi
- **Deployment Time:** Dağıtım süresi
- **Automated Tests Pass Rate:** Otomatik testlerin başarı oranı
- **Infrastructure as Code Coverage:** Kod olarak tanımlanan altyapı yüzdesi
- **Incident Rate:** Olay sıklığı
- **Time to Detect:** Sorunun tespit edilme süresi
- **Release Stabilization Time:** Sürüm kararlı hale gelme süresi

---

Bu liste sürekli güncellenmektedir. Eğer eklenmesini istediğiniz terimler varsa lütfen katkıda bulunun! 🚀
