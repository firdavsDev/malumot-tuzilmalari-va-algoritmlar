# Ma'lumot tuzilmalari va algoritmlar 😎

Ma'lumot tuzilmalari va algoritmlarini O'zbek tilida o'rganishga bag'ishlangan ushbu repository - ga xush kelibsiz. Bu qo'llanma yordamida siz ma'lumot tuzilmalari va algoritmlarni batafsil o'rganishingiz mumkin. Qo'llanmada misollar Python va JavaScript dasturlash tillarida keltiriladi. 

Siz boshlang'ich darajadagi dasturchi bo'lasizmi yoki bilimingizni kengaytirmoqchi boʻlgan tajribali dasturchi, bu repository - da siz uchun yangilik topiladi. 

Agar repository yoqsa, yulduzcha bosib qo'llab quvvatlashni unutmang!

Mavzular bilan tanishing:

### Kirish
+ __[Nima bu ma'lumot tuzilmalari va algoritmlar?](https://github.com/devfarhod/malumot-tuzilmalari-va-algoritmlar/blob/main/kirish/nima_bu_malumot_tuzilmalari_va_algorithmlar.md)__
+ Dasturlashda ma'lumot tuzilmalari va algoritmlarining o'rni
+ Ma'lumot tuzilmalarining turlari
+ Algoritmlarning turlari
+ Vaqt va joy murakkabligi (Time and space complexity)
+ Ma'lumot tuzilmalari va algoritmlar qachon va qayerda ishlatiladi?
+ Nega ma'lumot tuzilmalari va algoritmlarni o'rganish kerak?

### Massivlar (Array) va bog'langan ro'yxatlar (Linked List)
+ Massivlar va ularning amallari
+ Bog'langan ro'yxatlar va ularning operatsiyalari
+ Ikki marta bog'langan ro'yxatlar (Doubly Linked List) va ularning operatsiyalari
+ Dinamik massivlar (Dynamic Array) va ularni amalda qo'llash

### Staklar (Stack) va navbatlar (Queue)
+ Stak va uning operatsiyalari
+ Navbat va uning operatsiyalari
+ Doiraviy navbat (Ciruclar Queue) va uni amalda qo'llash
+ Deque va uni amalda qo'llash

### Daraxtlar (Tree)
+ Ikkilik daraxtlar (Binary Tree) va ularning amallari
+ Ikkilik qidiruv daraxtlari (Binary Search Tree) va ularning amallari
+ AVL daraxtlari (AVL-Tree) va ularning amallari
+ B-daraxtlar (B-Tree) va ularning amallari

### Uyum (Heap)
+ Uyumlar  va ularning operatsiyalari
+ Binar uyumlar (Binary heap) va ularni amalda qo'llash
+ Fibonachchi uyumlari (Fibonacci heap) va ularni amalda qo'llash

### Xesh jadvallari (Hash Table)
+ Xesh-jadvallar va ularning amallari
+ To'qnashuvlarni hal qilish (Collision resolution) usullari
+ Yuk koeffitsienti (Load factor) va rehashing
+ Ochiq adreslash (Open addressing) va zanjir (Chaining)

### Saralash va qidirish
+ Saralash algoritmlari: qabariq saralash (Bubble sort), qoʻshish tartibi (Insertion sort), tanlash saralash (Selection sort), tez saralash (Quick sort), birlashtirish saralash (Merge sort), yigʻma tartiblash (Heap sort)
+ Qidiruv algoritmlari: chiziqli qidiruv (Linear search), Ikkilik qidiruv (Binary search)
+ Saralash va qidirish algoritmlarini solishtirish

### Grafiklar (Graph)
+ Grafiklar va ularning tasvirlari
+ Grafik o'tishlar: kenglik-birinchi qidiruv (Breadth-first search), chuqurlik-birinchi qidiruv (Depth-first search)
+ Minimal yoyilgan daraxtlar: Kruskal algoritmi, Prim algoritmi
+ Eng qisqa yo'l algoritmlari: Dijkstra algoritmi, Bellman-Ford algoritmi, A* algoritmi

### Dinamik dasturlash
+ Dinamik dasturlashga kirish
+ Eng uzun umumiy ketma-ketlik
+ 0-1 yukxalta muammosi
+ Matritsa zanjirini ko'paytirish
+ Rodni kesish

### Ochko'z (Greedy) algoritmlar
+ Ochko'z algoritmlarga kirish
+ Fraksiyonel yukxalta muammosi
+ Faoliyatni tanlash muammosi
+ Huffman kodlash

### Kengaytirilgan mavzular
+ Urinishlar va ularning operatsiyalari
+ Bloom filtrlari va ularni amalga oshirish
+ Naqshlarni moslashtirish (pattern matching) uchun KMP algoritmi
+ Naqshlarni moslashtirish uchun Rabin-Karp algoritmi


## Nima bu ma'lumot tuzilmalari va algoritmlar?

Ma'lumot tuzilmalari va algoritmlari mazali taom tayyorlash uchun retsept va ingredientlarga o'xshaydi. Retsept - bu algoritm bo'lib, u sizga taom tayyorlash uchun qanday amallarni bajarish kerakligini aytadi. Ingredientlar ma'lumotlar tuzilmalari bo'lib, ular ovqat tayyorlash uchun foydalanadigan turli komponentlardir. Yaxshi retsept va sifatli ingredientlardan mazali taom tayyorlangani kabi, to'g'ri ma'lumot tuzilmalari va algoritmlardan foydalanish dasturni yaxshi ishlashi va muammolarni samarali hal qilishga sababchi bo'ladi.

Ovqat pishirishda ovqat tayyorlash uchun foydalanishingiz mumkin bo'lgan juda ko'p turli xil retseptlar mavjud, shu bilan birga juda ko'p turli xil ingredientlar ham mavjud. Kompyuter dasturlarida ham xuddi shunday. Muammoni hal qilish uchun foydalanishingiz mumkin bo'lgan juda ko'p turli xil algoritmlar mavjud, shuningdek, ma'lumotlarni tartibga solish uchun foydalanishingiz mumkin bo'lgan juda ko'p turli xil ma'lumot tuzilmalari mavjud. Yaxshi oshpaz taom uchun to'g'ri retsept va ingredientlarni qanday tanlashni bilgani kabi, yaxshi dasturchi muammo uchun to'g'ri algoritm va ma'lumot tuzilishini qanday tanlashni bilishi kerak.

Turli xil retseptlar va ingredientlar turli xil ta'm va mazaga ega bo'lgani kabi, turli algoritmlar va ma'lumot tuzilmalari ham har xil kuchli va zaif tomonlarga ega. Yaxshi dasturchi, hal qilmoqchi bo'lgan muammo va mavjud resurslarga qarab qaysi algoritm va ma'lumot tuzilmasini tanlashni bilishi kerak.

Yaxshi tayyorlangan taom zavq keltirgani kabi, yaxshi tayyorlangan dasturdan foydalanish quvontiradi. Shuning uchun ma'lumot tuzilmalari va algoritmlari dastur ishlab chiqishda muhim rol o'ynaydi.
