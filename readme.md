TASK_1:

  "Variable":
      - Hər hansı bir əməliyyatı həyata keçirə bilmək üçün onu yaddaşa yazmaq lazımdı. Yaddaşa yazdığımız əməliyyatı ramnan çağırıb istifadə eləmək üçün dəyişkəndən istifadə edilir: For exam. a = 5 yazdığımız zaman ramda bir yer ayırır və ora 5 yazılır. Ramda yazılan hər nöqtəni bir qutu kimi fikirləşəcək olsaq, qutunun içinə informasiya atırıq və daha sonra qutunu çağıra bilmək üçün ona ad veririk.

  "Programming paradigms":
      - Proqramlaşdırma paradiqması programlaşdırmada gedəcəyimiz bir yol, bir üsuldur. Qarşımıza çıxan problemlərin həllərinin necə formule şəklinə salınıb yazılması stilidir.
      Loru dildə desək 2 əsas üsul var: Inperative və Declerative.
      - İnperative, yəni məcburi programlaşdırma. Hər programlaşdırma dilində olan standart anlayışlar desək səhf olmaz. Yəni
      əlavə heç bir işimizi asandlaşdıracaq bir şeydən istifadə etmədən düz kod yazmaq.
      - Declerative programlaşdırma isə hərfi mənası ilə gedəsi olsaq məntiqli programlaşdırma deyə bilərik. Misal olaraq işdiyəcəyimiz hər hansı bir böyük proyektdə kodlarımızın əkstəsirləri olmadan, daha az kod yazaraq istifadə edəcəyimiz paradiqmadır.

  "Object-Oriented paradigms":
      - Obyekt yönümlü paradiqma işlədiyimiz layihədə hər şeyi bir siniflər və obyektlər olaraq görür. Fərqli-fərqli siniflər yaradaraq içində ayrı-ayrı obyektlər düzəldərək bunlardan istifadə imkanı yaradır bizə. Həm bizi çox kod yazmaqdan canımızı qurtarır həmdə ki, işimizi bir növ azaldır və asantlaşdırır.

  "How web sites work?":
      - Yeni bir website qurduğumuz zaman ilk olaraq sayt yığılır, daha sonra yeni domain alınır, internetə çıxışı olan bir server yaradılır, daha sonra yığdığımız saytın fayllarını serverimizə yerləşdirərək database kimi istifadə edilir. İstifadəçi saytda daxil olanda (for exp: www.az) , ilk olaraq internet üzərindən domain yoxlanılır. Saytın varlığı bilinəndən sonra browserimiz bizi saytın adresinə yönləndirir.

  "Difference Client Side and Server Side of a web site":
      - Client-side: sadə dildə desək yazdığımız kodlarımız bir başa istifadəçinin browserində run olur.
      - Server-side: burda isə yazdığımız kodlarımız istfiadə etdiyimiz bütün fayllar serverimizdə run olur və istifadəçinin browserində görünür. Bu zaman istifadəçinin browserində source koda baxmaq istəsək orda yalnız html və css kodlarını görəcik.
      Digər yazdığımız funksiyalarımız serverdə run olur və istifadəçinin ekranına yalnız nəticəni ötürür. Belə olan halda təhlükəsizliyə, yazdığımız kodlarımızın və istifadə etdiyimiz faylların gizliliyi qorunur. Client-side və Server-side arasında əsas fərqlər bunlardır.

  "What is version Controlling?":
      - Version Controlling: normalda hər kəs programlaşdırmaya başladığı zaman bütün yazdığı kodları local disk'də saxlayırlar.
      Komputerdə çıxan hər hansı bir problemdə və ya hard diskin istifadəyə yararsız hala düşdüyü zaman istifadə etdiyimiz bütün fayllar və yazdığımız bütün kodlar boşa getmiş olur. Sırf buna görə əlbətdəki version Controllingdən istifadə edilmir. Bu problemin qarşısını almaq üçün hər istifadə etdiyimiz hər hansı fayları öz cloudumuzda saxlaya bilərik. Ama version Controlling'in bizə "bəxş etdiyi" bir çox imkan var. Bunlardan bir neçəsini sadalayaq. Misal üçün böyük bir proyekt yazdığımızı düşünək. Bu proyektin üzərində 1-2 aydı işləyirik. Local diskimizdə və ya hər hansı bir cloudumuzda fayllarımızı saxlayırıqsa proyektimizin yalnız son saxlanılmış (save) olunmuş halını görürük. Ama version Controlling bizə ayrı-ayrı tarixlərdə hər dəyişiklik etdiyimiz vaxta qaytararaq proyektimizin əvvəlki versiyalarını göstərmək imkanı verir. Bir növ əlimizdə "Time Machine" varmış kimi istədiyimiz vaxta qayıdaraq səhflərimizi görə, vaxt keçdikcə proyektdə olan development'i görə bilirik. Əlavə olaraq paralel sürətdə bir komanda şəklində proyektdə işləyiriksə, bir faylın üzərində bir neçə şəxs eyni zamanda işləyə bilir və sonda onların yazdıqlarını avtomatik birləşdirmək imkanımız olur. Mextəlif zamanlarda etdiyimiz səhflərimizə qayıdaraq baxa, harda necə düzəlişlər edərək yeni qeydlərimizi apara bilərik.

    "Most used Version Controlling Tools":
      - İnternetdə axtarış etdiyimiz zaman əsas bu 5 tool'u görürük: CVS, SVN, GIT, Mercurial, Bazaar.
      Bunlardan ən məşhuru və bizimdə istifadə etdiyimit GIT (GITHUB)'dır.

TASK_2:

    "What is HTML and differences between HTML5 and  older versions?":
    "What are new features of HTML 5?":
      - HTML: programlaşdırma dilindən daha çox işarət dilidir (Hyper Text Markup Language). Web site qurmaq üçün istifadə olunur və əsas funksiyası website'in dizaynını qurmaqdı. Vaxt keçdikcə HTML inkişaf etdirilərək HTML5-ə qədər gəldi. HTML5-də onnan əvvəlki versiyalarda olan bəzi problemlər aradan qalxdı. Yeni tag'lar əlavə olundu. CSS ilə olan bəzi uyğunlaşma problemləri aradan qalxdı. Dizayn olaraq isə əsas istifadə etdiyi javascript və css-dir. Yeni tag'lar <article>, <aside>, <details>, <figcaption>, <figure>, <footer>, <header>, <main>, <mark>, <nav>, <section>, <summary>, <time> və s. gəlmişdir. Bunları istifadə etdikcə daha yaxşı öyrənəcəyik :).

      
