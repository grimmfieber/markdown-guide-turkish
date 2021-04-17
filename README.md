
# Markdown nedir?

 > **Markdown** veya githubda bilinen kısaltmasıyla `.md`, kendine ait syntaxı olan bir metin editörüdür.

### Nerede ve Nasıl kullanırım?
Bu yazıyı github profilimden okuduğunuzu ve yazının `.md` olarak yazıldığını düşünürseniz, githubda proje açıklamalarında standartlaşmış hale geldiğinden yoğun bir kullanıma sahiptir. Projenizi yüklediğinizde **README.md** olarak beliren `.md` uzantılı dosyaya yazdığınız Markdown komutları projenizin açıklamasında aktif olacaktır.

### Daha iyi bir Markdown aracı? 
Markdown'ı yazarken kullandığımız syntaxın çıktısını görerek çalışmamız, bizim için daha kolay ve verimli olacaktır. Bunun için Dillinger gibi siteler işinizi görecektir tabi ki masaüstü için Markup editörleri olduğunu da hatırlatırım.

**İlk denemenizin nasıl göründüğünü görerek yazmak isterseniz..**
>[Dillinger](https://www.dillinger.io)
*Dillingerda sol tarafa yazıp sağ tarafta değişimi gözlemleyebilirsiniz.*

### Neden Markdown?
> Basit bir yazı için bile HTML kullanmaktansa, markdown kullanarak yazdıklarınızı HTML'e veya PDF'e dönüştürebilirsiniz.
__Taşınılabilir oluşundan tutun, günümüz firmalarının çoğunun destekliyor oluşu da markdown kullanmanın faydalı olabileceğini gösterir.__

### Syntaxı zor mu?
> Elbette office yazılımlarındaki word gibi editörlere alışık olan bünyeler için ilk başta karışık gelebilir, **fakat HTML'den kat kat anlaşılabilir** bir syntaxa sahip ve her çevreden insanın kullanabileceği düzeyde **basit bir syntaxa sahip olduğu için standardizasyona daha açık** denebilir. 
## Ne kadar mı basit?
> **Bu yazıyı ilk defa dokümentasyona bakarak yazıyorum.** 
>> __*Orijinal dokümentasyondaki bilgileri Türkçeleştirerek özetlemek istedim.*__

![görsel bozuk](https://resources.jetbrains.com/help/img/idea/2020.3/markdown-basics.png)

---
### Başlıklar
# Başlık 1
`# Başlık 1` yazarak Başlık 1 boyutunda başlıklar yazabilirsiniz.
>`<h2>Başlık 1</h1>` ~HTML kodu~
## Başlık 2
`## Başlık 2` yazarak Başlık 2 boyutunda başlıklar yazabilirsiniz.
>`<h2>Başlık 2</h2>` ~HTML kodu~
### Başlık 3
`### Başlık 3` yazarak "Başlık 3" boyutunda başlıklar yazabilirsiniz.
>`<h3>Başlık 3</h3>` ~HTML kodu~
#### Başlık 4
`#### Başlık 4` yazarak Başlık 3 boyutunda başlıklar yazabilirsiniz.
>`<h4>Başlık 4</h4>` ~HTML kodu~
##### Başlık 5
`##### Başlık 5` yazarak Başlık 3 boyutunda başlıklar yazabilirsiniz.
>`<h5>Başlık 5</h5>` ~HTML kodu~
###### Başlık 6
`###### Başlık 6`yazarak Başlık 3 boyutunda başlıklar yazabilirsiniz.
>`<h6>Başlık 6</h6>` ~HTML kodu~

---
### Paragraf

> Editörünüze hiçbir şey eklemeden sadece yazarak paragrafları yazabilirsiniz, HTML'in aksine `<p>` etiketine gerek yoktur.


---
### Bold ve İtalik yazım
>**Kalın yazmak için**
>
>>`**Kalın yazmak için**` formatını kullanın "**" yazıyı kalınlaştırır.

>*İtalik yazmak için*
>
>>`*İtalik yazmak için*` formatını kullanın "*" yazıyı italikleştir.
---


### Blockquotelar

**blockquote yazmak için: `>` sembolünü kullanın.**

>Bu bir blockquote yazım örneğidir.

Bu bir blockquote yazım örneği değildir.

--- 

### Nested (gömülü) Blockquotelar
> Blockquote oluşturmak için `>` karakterini kullanmamız gerekiyor
> Sonraki satıra başlarken de başına `>` ekliyoruz 
>> Nested yapmak istediğimiz blockquote için istenilen satıra `>>` ile başlıyoruz.

> `>` normal blockquote
>`>` normal blockquote
>> `>>` nested blockquote

---


### Sıralı Liste
1. ilk sıra
2. ikinci sıra
3. üçüncü sıra
4. dördüncü sıra

##### Nasıl?
> Çok basit bir şekilde metine liste sırasıyla başlayın.
 >> örneğin 
>`1. ilk sıra`
> `2. ikinci sıra` 

...

---

### Sırasız liste
- ilk sıra
- ikinci sıra
- üçüncü sıra

##### Nasıl
>Basit bir şekilde sıraya alacağınız kelimenin başına `-` karakterini ekleyin.

---

### Kod eklemek

> bunun için "``" karakterini kullanıyoruz.
Bu karaktere Türkçe klavyede `alt gr`+`,` iki kere basarak ulaşabilirsiniz.
Bu kod bloğu içinde kalan kısımlar `bu şekilde gözükecektir.`

---

### Yatay çizgiler
> **Maddeler arası, aynen bu metinde çektiğim gibi çizgiler çekmek için `---` karakterini tuşlayın.**

---

### Tıklanabilir Link eklemek

**`[kullanıcı tıklarken görünecek kelime](https://www.yönlendirmesiİstenenSiteninAlanAdı.com)`**

_**[profilim](https://www.github.com/grimmfieber)**_

> yukardaki tıklanır linki oluşturan dizin `[profilim](https://www.github.com/grimmfieber)`


---

### Metine görsel ekleme
 
 Bunun için ekleyeceğimiz görselin adresini kopyalamalı ve "(adres)" olacak şekilde parantez içine yapıştırmalıyız.
 
 > `![link patlaksa ekranda yazacak uyarı](gösterilmesini istediğiniz görselin urlsi)`
 
 > **örnek olarak :** ![görsel bozuk](image.jpg)
 
 > **örnek olarak :** ![linki aldığımda çalışıyordu](https://kirkstrobeck.github.io/whatismarkdown.com/img/markdown.png)
 
---

### Tablolar
| Syntax      | Açıklama | Test Text     |
| :---        |    :----:   |          ---: |
| Başlık      | Başlık     | içerik  |
| Paragraf   | Metin        | ve fazlası      |

#### syntax

`| Syntax      | Açıklama | Test Text     |
| :---        |    :----:   |          ---: |
| Başlık      | Başlık     | içerik  |
| Paragraf   | Metin        | ve fazlası      |`

---







# Orijinal Kaynak ve daha fazlası için
> **[markdownguide.org](https://www.markdownguide.org/basic-syntax)**
