# Inery ilə verilənlər bazasının idarə edilməsi: mərkəziyyətsizlik içdən çölə doğru 
![image](https://user-images.githubusercontent.com/65338121/209341886-7f876100-f316-4db2-9e52-e45b19dc71c0.png)

TL;DR
 
Keçmişdə köhnə verilənlər bazası idarəetmə həlləri mərkəzləşdirilmiş sistemlər kimi ehtiyacları ödəmək üçün çox təsirli olmamışdır.
Tamamilə mərkəzləşdirilməmiş verilənlər bazası idarəetmə həlli bütövlük, təhlükəsizlik, dəyişməzlik, şəffaflıq və s. təmin edir.
Inery, Inery Blockchain və IneryDB vasitəsilə mərkəzsizləşdirmə və suveren mərkəzləşdirilməmiş verilənlər bazası idarəetməsi arasındakı boşluğu doldurur.
Biz tez-tez blockchain-i gücü mərkəzləşdirməyin və etibarsız sistemlər yaratmağın bir yolu kimi düşünürük. Ancaq bugünkü blokçeyn əsaslı həllər həqiqətən mərkəzləşdirilməmişdirmi?
Verilənlər bazaları yarandığı gündən informasiya idarəçiliyi ekosisteminin mühüm hissəsi olmuşdur. Verilənləri saxlamağımız, idarə etməyimiz və onlarla qarşılıqlı əlaqəmiz bu müddət ərzində kəskin şəkildə dəyişdi, lakin verilənlər bazalarının mərkəzi əhəmiyyəti sabit qaldı.
Ətrafımızdakı dünya getdikcə rəqəmsallaşdıqca məlumatların həcmi, müxtəlifliyi və sürəti eksponensial sürətlə artır. Eyni zamanda, bizə təqdim olunan məlumatlara etibar etmək qabiliyyətimiz azalır. Saxta xəbərlər və botlar əsrində istifadə etdiyimiz məlumatların bütövlüyünü yoxlaya bilmək həmişəkindən daha vacibdir.
Blockchain bura daxil olur.
Verilənlər bazasını qeyri-mərkəzləşdirərək və kriptoqrafik üsullardan istifadə etməklə, blokçeyn həlləri məlumatların dəqiq olmasını və etibarlı olmasını təmin etmək üçün bir yol təqdim edir.

### Metaaverslərin işini korlamaq
Əgər siz kriptovalyuta istifadəçisisinizsə və ya hətta bu məkanda həvəsli pərakəndə investorsunuzsa, o zaman metaverse ilə gündə bir neçə dəfə qarşılıqlı əlaqədə olma şansınız var. Təəssüf ki, istifadəçilərin əksəriyyəti bu metaverse dünyalarının necə qurulduğuna göz yumur.
Bugünkü web 3.0 ekosistemi məlumatların AWS kimi bulud xidməti təminatçılarında yerləşdiyi çox mərkəzləşdirilmiş infrastruktura əsaslanır. Bu o deməkdir ki, biz mərkəzləşdirilmiş web 2.0 infrastrukturu üzərində mərkəzləşdirilməmiş veb 3.0-ın əsasını qoyuruq.
Burada sual yaranır: "Niyə məhsulun ruhu hələ də mərkəzləşdirilmişdirsə, mərkəzləşdirilməmiş protokollardan istifadə edin?"
Bu, ilk baxışda problem kimi görünməsə də, bir sıra potensial zəifliklər yaradır.
Məsələn, bu mərkəzləşdirilmiş provayderlərin bir çoxunun onurğa sütunu olan Amazon, keçmişdə bir sıra fasilələrlə üzləşib. AWS Maniacs-a görə, Amazon Veb Xidmətləri təkcə 2021-ci ildə 3 fasilə ilə üzləşib. Bu, məlumatlarımızı bir uğursuzluq nöqtəsinə etibar etdiyimiz üçün daha bir zəiflik səviyyəsi yaradır.
Blockchain protokolunda bu mərkəzləşdirmə elementinin təsirləri Solana vəziyyətində açıq şəkildə görünə bilər. "Ethereum qatili" adlandırılan Solana 2022-ci ilin ilk yarısında təxminən 12 fasilə ilə üzləşdi - bu, perspektivli layihələrdə mərkəzləşmənin zəifliyinə sübutdur.
Beləliklə, tamamilə mərkəzləşdirilməmiş verilənlər bazası idarəetmə həlli tələb olunur.
Məsələn, BigchainDB mərkəzləşdirilməmiş DB həllidir, lakin mərkəzləşdirilmiş NoSQL verilənlər bazası proqramı MongoDB ilə təchiz edilmişdir.
Inery fərqlidir. Biz sıfırdan yuxarı tamamilə mərkəzləşdirilməmiş verilənlər bazası idarəçiliyi üçün xüsusi olaraq blokçeyn həllini qururuq.
Nə üçün verilənlər bazası idarəetməsi üçün Blockchain Həllini axtarırsınız?
Metadata verilənlər haqqında məlumatdır. Verilənlər bazasında saxlanılan məlumatları təsvir etmək, müəyyən etmək, tapmaq və ya başqa üsullarla əldə etmək, istifadə etmək və ya şərh etmək üçün istifadə olunur.
Inery, mərkəzləşdirilməmiş verilənlər bazasında saxlanılan məlumatları izləmək üçün metadata idarəetməsindən istifadə edir. Buraya məlumatın özü haqqında data (məsələn, onun formatı, ölçüsü və növü), eləcə də onun digər məlumatlarla (məsələn, valideyn-övlad münasibətləri və xarici açar məhdudiyyətləri) necə əlaqəli olduğu haqqında məlumatlar daxildir.
CRUD (Yarat, Oxu, Yenilə, Sil) funksiyaları istənilən verilənlər bazası idarəetmə həlli üçün vacibdir. Inery-nin mərkəzləşdirilməmiş verilənlər bazası idarəetmə həlli bu vacib funksiyaları təmin edir, eyni zamanda mərkəzləşdirilməmiş verilənlər bazasında saxlanılan məlumatların düzgünlüyünə və bütövlüyünə zəmanət verir.
Aşağıda tamamilə mərkəzləşdirilməmiş DB həllinə keçmək üçün bir neçə vacib səbəb var.
### Mərkəzsizləşdirmə
Blockchain-in əsas üstünlüyü onun mərkəzləşdirilməmiş olmasıdır. Bu o deməkdir ki, heç bir uğursuzluq nöqtəsi və məlumatlara müdaxilə edə biləcək heç bir mərkəzi orqan yoxdur.
### Dəyişməzlik
Məlumat blokçeynində qeydə alındıqdan sonra onu dəyişdirmək və ya silmək mümkün deyil. Bu, onu yoxlanıla bilən və etibarlı olması lazım olan məlumatların saxlanması üçün ideal platforma halına gətirir.
### Şəffaflıq
Blockchain-də qeydə alınan bütün məlumatlar şəbəkədəki hər kəsə görünür. Bu, məlumatları izləmək və yoxlamağı asanlaşdırır.
### Məlumatların bütövlüyü
Ənənəvi verilənlər bazaları ilə bağlı ən böyük problemlərdən biri məlumatların bütövlüyüdür. Verilənlər bazasındakı məlumatlara müdaxilə edilib-edilmədiyini bilmək çox vaxt çətindir. Blockchain ilə məlumatların bütövlüyü təmin edilə bilər, çünki məlumatlara edilən bütün dəyişikliklər blokçeyndə qeyd olunur və asanlıqla yoxlanıla bilər.
### Məlumat Təhlükəsizliyi
Ənənəvi verilənlər bazaları ilə bağlı digər problem məlumatların təhlükəsizliyidir. Mərkəzləşdirilmiş verilənlər bazaları ilə, hakerlər tərəfindən istismar edilə bilən bir uğursuzluq nöqtəsi var. Blockchain ilə məlumatlar kompüterlər şəbəkəsi arasında paylanır və şifrələnir, bu da onu daha təhlükəsiz edir.
### Suverenlik və Ölçeklenebilirlik imkanları
Inery-nin 1-ci səviyyə blokcheyn həlli verilənlər bazası idarəçiliyi üçün optimallaşdırılmaq və müəssisələrə maneəsiz miqyasını böyütməyə və ya azaltmağa imkan vermək üçün hazırlanmışdır.
Self Delegated Proof of Stake (SDPoS) konsensus modelini tətbiq etməklə, Inery blockchain, Proof of Work blokçeynləri ilə müqayisədə 5000 TPS-dən çox yüksək ötürmə qabiliyyəti, Sybil müqaviməti və daha yüksək enerji səmərəliliyi təklif edir.
Inery blockchain üzərində qurulmuş IneryDB, DPoS və asinxron Bizans Hata Dözümlülüyünü (BFT) aktivləşdirməklə effektiv verilənlər bazası idarəçiliyini gücləndirən bir Xidmət kimi mərkəzləşdirilməmiş Məlumat Bazasıdır (DBaaS).

Inery-nin məqsədi, beləliklə, IneryDB ilə də elədir ki, qovşaqlar bir çox ölkədə məhdudiyyətsiz yerləşə bilər və olmalıdır. Bir node uğursuz ola bilər, lakin digərləri işləməyə davam edəcək. Bundan əlavə, məlumatların minimum təkrarlanması və daxili ehtiyatlar ilə məlumat itkisi ilə bağlı heç bir narahatlıq yaratmağa ehtiyac yoxdur.
### Sarma
Bütövlükdə, mərkəzləşdirilməmiş verilənlər bazası idarəçiliyi veb 3.0 dünyasında həmişə uzun müddətdir narahatlıq doğurur və Inery bu problemin həllini təklif edir.
DB idarəetməsi üçün vahid blokçeyn həlli ilə Inery məlumatların miqyası, təhlükəsizlik və suverenlik problemlərinin öhdəsindən gəlməyə çalışır.
Inery, verilənlər bazası idarəçiliyi və IneryDB üçün xüsusi olaraq hazırlanmış lay-1 blokçeyn həllimizlə bu pozulmanın ön sıralarındadır.
### Inery haqqında
Inery, məlumat üçün yeni bir paradiqmanı təmin etmək məqsədi ilə mərkəzləşdirilməmiş verilənlər bazası idarəçiliyinin həllini təklif edən ilk səviyyə-1 blokcheynidir. Inery məlumatların zəncirvari əlaqəsini, daha yüksək sürəti və daha yaxşı təhlükəsizliyi təmin etmək üçün nəzərdə tutulmuşdur. O, xüsusi olaraq blokçeyn funksiyaları və paylanmış verilənlər bazası idarəetmə xüsusiyyətləri ilə inteqrasiya olunmuş verilənlər bazası idarəçiliyinə müraciət edir.
Inery verilənlər bazası idarəetmə həlli (IneryDB) şəxsi məlumatlara nəzarətin istifadəçilərin və müəssisələrin əlində qaldığı verilənlər bazası idarəçiliyi üçün təhlükəsiz, ucuz və dəyişməz üsula imkan verir. O, digər sistemlər, proqramlar və lay-1 şəbəkələri ilə problemsiz əlaqə yaratmaqla dəyər yaratmağa imkan vermək üçün web3 gələcəyi üçün əsas yaradır.
