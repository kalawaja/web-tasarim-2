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

4. Kullanılacak Editör:
- VS Code

5. VS Code Eklentileri:
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

> 5. Responsive

- @media query   

|     min        |              max              |          device                      |
|----------------|-------------------------------|--------------------------------------|
| 320px          | 480px                         | Mobile devices                       |
| 481px          | 575px                         | iPads, Tablets, vertical             |
| 576px          | 768px                         | iPads, Tablets, landscape phones     |
| 769px          | 991px                         | Small screens, laptops               |
| 992px          | 1024px                        | Medium screens, desktops             |
| 1025px         | 1200px                        | Desktops, large screens              |
| 1201px         | and more                      | Extra large screens, TV              |

```css

@media (max-width: 1200px) {
    /* ... */
}

@media (max-width: 1024px) {
    /* ... */
}

@media (max-width: 991px) {
    /* ... */
}

@media (max-width: 768px) {
    /* ... */
}

@media (max-width: 575px) {
    /* ... */
}

@media (max-width: 480px) {
    /* ... */
}
```