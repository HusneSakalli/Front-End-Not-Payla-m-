
# HTML Yapısı Ders Notu

## HTML Yapısı:
HTML, web sayfalarının yapısını oluşturmak için kullanılan bir dildir. HTML'de her öğe bir etikete (tag) sarılıdır ve bu etiketler genellikle `<etiket>` ve `</etiket>` formatında yazılır.

## Başlıklar:
HTML'deki başlıklar, `<h1>` ile `<h6>` etiketleri arasında tanımlanır ve bu etiketlerin numarası küçüldükçe başlıklar daha büyük ve önemli hale gelir.

### Kod Örneği:
```html
<h1>Book</h1>
<h2>Chapter 2</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>
<h2>Chapter 2</h2>
  <h3>Section 1</h3>
<h2>Diagram 1</h2>
<h2>Chapter 3</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>
```

Bu yapı bir kitap ya da belge tasarımında başlık hiyerarşisini temsil eder. `<h1>` ana başlığı, `<h2>`, `<h3>` gibi alt başlıkları ifade eder.

## Paragraflar:
HTML'de paragraflar, `<p>` etiketi ile tanımlanır. Bir paragraf metni her zaman bu etiketin içine yazılır.

### Kod Örneği:
```html
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>
```

Bu kod, iki paragrafı ifade eder. İlk paragraf tam bir cümleye sahipken, ikinci paragraf eksik bir cümledir.

## Düzeltmeler ve İyileştirmeler:
Bu HTML kodunda birkaç hata ve eksik gözükmektedir. Örneğin, yanlış yazılmış kelimeler ve tutarsız boşluklar mevcuttur. İşte düzeltilmiş hali:

### Düzeltilmiş Kod:
```html
<h1>Book</h1>
<h2>Chapter 2</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>
<h2>Chapter 2</h2>
  <h3>Section 1</h3>
<h2>Diagram 1</h2>
<h2>Chapter 3</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>
```

- 'parragrafy' kelimesi, 'paragraph' olarak düzeltilmiştir.
- Gereksiz boşluklar ve yanlış hiyerarşi düzeltildi.

## HTML Formatına Dair İpuçları:
- **Düzgün hiyerarşi**: Başlıkları doğru bir şekilde hiyerarşik olarak düzenlemek önemlidir. Örneğin, bir `<h3>` başlığı sadece bir `<h2>` başlığının altında olmalıdır.
- **Anlamlı içerik**: HTML etiketlerinin anlamlı bir şekilde kullanılması, sayfanın okunabilirliğini artırır.
