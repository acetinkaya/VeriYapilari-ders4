## Python - Veri Yapıları ve Algoritmalar  
# Ders 4. Programlama Dilinde Veri Türleri ve Operatörler

![alternatif metin](https://github.com/acetinkaya/yapayzeka/blob/main/Programlama-8.png)

Bu ders içerisinde;

4.1. Veri Türleri   
4.1.1. Integer (int) Veri Türü   
4.1.2. Float (float) Veri Türü   
4.1.3. String (str) Veri Türü    
4.1.4. Boolean (bool) Veri Türü   
4.2. Operatör Nedir?    
4.2.1. Aritmetik Operatörler     
4.2.2. Karşılaştırma Operatörleri    
4.2.3. Mantıksal Operatörler    
4.2.4. Atama, Arttırma ve Azaltma Operatörleri  
4.2.5. Bit Düzeyinde Operatörler  
4.3. Operatör İşlem Önceliği    
4.4. ASCII Tablosu  
4.5. Uygulamalı Örnekler ve Alıştırmalar  

---

4.1. Veri Türleri  
4.1.1. Integer (int) Veri Türü -> Tam sayıları temsil eder. Matematiksel işlemler ve sayısal veriler için kullanılır.  
4.1.2. Float (float) Veri Türü -> Ondalıklı (kesirli) sayıları ifade eder.  
4.1.3. String (str) Veri Türü  -> Metin verilerini saklar. Harfler, kelimeler, cümleler veya özel karakterler içerebilir.  
4.1.4. Boolean (bool) Veri Türü  -> Koşulları kontrol etmek için kullanılır. Sadece iki değer alabilir: "True" (Doğru - 1) veya "False" (Yanlış - 0).  

---

4.2. Operatör Nedir?  

Operatörler, programlama dillerinde veri üzerinde işlem yapmak için kullanılan sembollerdir. Python'da operatörler, değişkenler ve değerler üzerinde işlemler gerçekleştirmek için kullanılmaktadır.

4.2.1. Aritmetik Operatörler  

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Operator_tablosu-1.png)

---
  
4.2.2. Karşılaştırma Operatörleri  

İlgili işlemdeki değerleri karşılaştırarak boolean "True" veya "False" sonuç elde edilmektedir.

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Operator_tablosu-2.png)

---

4.2.3. Mantıksal Operatörler  

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Programlama-4.png)

---

4.2.4. Atama, Arttırma ve Azaltma Operatörleri  

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Programlama-2.png)

---

4.2.5. Bit Düzeyinde Operatörler

Bit düzeyinde (bitwise) operatörler, sayıların ikili (binary) temsilleri üzerinde işlem yapmak için kullanılır. Bu operatörler, sayıları bit seviyesinde işler ve genellikle düşük seviyeli programlama veya performans gerektiren uygulamalarda tercih edilmektedir.

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Operator_tablosu-3.png)

---

4.3. Operatör İşlem Önceliği 

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Operator_tablosu-4.png)

---

4.4. ASCII Tablosu 

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Asci.png)

---
  
4.5. Uygulamalı Örnekler ve Alıştırmalar

# Örnek - 1:

    Ders_no = 4   # Integer (int) Veri Türü
    pi_sayisi = 3.14159  # Float (float) Veri Türü
    Dersin_ismi = "Python - Veri Yapıları ve Algoritmalar" # String (str) Veri Türü
    durum1 = True
    durum2 = False

    print(Ders_no)
    print(pi_sayisi)
    print(Dersin_ismi)
    print(durum1)
    print(durum2)
    
# Örnek - 2:

    a = 7
    b = 3
    print(a + b)  

# Örnek - 3:

    a = 7
    b = 3
    print("Toplama:", a * b)
    print("Üs alma:", a ** b)
    print("Mod:", a % b)

# Örnek - 4:

    a = 7 
    b = 3
    print("a == b:", a == b)
    print("a < b:", a < b)

# Örnek - 5:

    a = True 
    b = False
    print("a and b:", a and b)
    print("a or b:", a or b)
    print("not a:", not a)
    
# Örnek - 6:

    x = 7
    x += 3  # x = x + 3
    print(x) 
    
# Örnek - 7:

    a = 7
    b = 3
    print("a & b:", a & b)
    print("a << b:", a << b)

# Örnek - 8:

    print(7 & 3)  # 3
    print(7 | 3)  # 7
    print(7 ^ 3)  # 4
    print(~3)     # -4
    print(7 << 3) # 56
    print(7 >> 3) # 0
    
# Örnek - 9:

![alternatif metin](https://github.com/acetinkaya/VeriYapilari-ders4/blob/main/Programlama-3.png)
