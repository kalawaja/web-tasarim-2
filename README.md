# Zemin İstanbul İSMEK - Web Tasarım Geliştirme 2 (HTML5 ve CSS3 ile Mobil Uyumlu-Responsive Kodlama)

> ### Programın Amacı
Bu eğitim programıyla, HTML5 ve CSS3 kodlarını kullanılarak mobil uyumlu web tasarımı yapabilecek kişiler yetiştirmeyi hedeflenmektedir.<br>

> ### İstihdam Alanları
Bu eğitimi başarı ile bitirenler; web ortamında etkileşimli programlar hazırlayan şirket, ajans ve bu hizmetlere ihtiyaç duyan firma, kurum ve kuruluşlarda web tasarımcı olarak istihdam edilebilirler.

---

> ### Kurs Boyunca Kullanılacak Araçlar
 
1. Programlar :
- VS Code

2. Google Chrome Eklentisi :
- **css peeper** → (Fonts, colors, assets)

3. Siteler :
- [Bootstrap](https://getbootstrap.com/)
- [W3Schools](https://www.w3schools.com/)
- [Mehmet Selçuk Batal - HTML ve CSS ile A'dan Z'ye Web Tasarımı](https://www.youtube.com/playlist?list=PLQlzUjV4jUuRgSyZ0bWkmRuyi_WV3L8Ra)

3. Kullanılacak Editör:
- VS Code

4. VS Code Eklentileri:
- **Live Preview**

> ### Giriş için Önemli Notlar

> 1. meta                              


|     link       |              style            |          script                      |
|----------------|-------------------------------|--------------------------------------|
| rel            | `body {}`                     | `alert()`                            |
| href           | `h1 {}`                       | `function myFunction()`              |
| ...            | `p {}`                        | ...                                  |

|     charset    |              name             |          content                     |
|----------------|-------------------------------|--------------------------------------|
| `utf-8`        | viewport                      |`width=device-width, initial-scale=1` |
|  ...           | author                        |`İsmek Teknoloji - ...`               |
|  ...           | copyright                     |`Zemin İstanbul - a@b.net`            |
|  ...           | description                   |`İBB Teknoloji Transfer Ofisi ...`    |
|  ...           | keywords                      |`zemin, istanbul, ...`                |
|  ...           | robots                        |`noindex, nofollow`                   |

> 2. video, audio

+ `<!doctype html>` -> HTML5 için

> 3. Responsive

+ `<meta name="viewport" content="width=device-width, initial-scale=1.0">` -> Mobil Uyumlu

> 4. Önemli Diğer Notlar
- Semantik etiketleri biçimlendirirken "#id" kullan,
- Semantik etiketler dışındaki diğer tüm etikerleri biçimlendirirken ".class" kullan. <br><br>

- 1.5em
- 1.5rem <br><br>

- 300px
- 35% (İçinde bulunduğu kapsayıcının ...) <br><br>

- 35vw (Tarayıcıda gözüken tüm alanın ...)
- 100vh <br><br>

- calc() 
> ```css
> header {
> width: calc(100vw-20px);
> }
> ```
