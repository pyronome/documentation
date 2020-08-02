---
id: basvuru-kalip-sablonu-kaynak-kod-yardimcilari
title: Kalıp Şablonu Kaynak Kod Yardımcıları
sidebar_label: Şablon Kaynak Kod Yardımcıları
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

## Değişkenler

### Küresel Değişkenler

| Global Variables | Description |
| --- | --- |
| `{{$__globals__/PYRONOME_SHORT_VERSION}}` |  |
| `{{$__globals__/PYRONOME_VERSION}}` |  |
| `{{$__globals__/PYRONOME_LONG_VERSION}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_NAME}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_CAPTION}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_VERSION}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_DATETIME}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_DATETIME_FORMATTED}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_DATE}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_TIME}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_YEAR}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_MONTH}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_DAY}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_HOUR}}` |  |
| `{{$__globals__/PYRONOME_CURRENT_MINUTE}}` |  |
| `{{$__globals__/PYRONOME_PATTERN_NAME}}` |  |
| `{{$__globals__/PYRONOME_PATTERN_CAPTION}}` |  |
| `{{$__globals__/PYRONOME_PATTERN_VERSION}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_USER_NAME}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_USER_EMAIL}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_USER_FULL_NAME}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_CREATION_DATETIME}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_CREATION_DATETIME_FORMATTED}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_CREATION_DATE}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_CREATION_TIME}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATETIME}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATETIME_FORMATTED}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATE}}` |  |
| `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_TIME}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_2BYTES_LOWERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_4BYTES_LOWERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_8BYTES_LOWERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_16BYTES_LOWERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_32BYTES_LOWERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_2BYTES_UPPERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_4BYTES_UPPERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_8BYTES_UPPERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_16BYTES_UPPERCASE}}` |  |
| `{{$__globals__/PYRONOME_RANDOM_STRING_32BYTES_UPPERCASE}}` |  |

### Model Değişkenleri

```
- project
    - model_list
        - model
            - name
            - property_list
                - property
                    - name 
```

### Kalıp Değişkenleri

[Platform Kalıplar Değişkenler Sayfası](/latest/tr/docs/platform-kaliplar/#değişkenler-sayfası) bölümünde detayları belirtilen, kalıplar arası bilgi transferi için kullanılan değişken değerlerinin kaynak koda aktarılması gerekli olabilir. Bu değişkenleri `{{$__variables__/` ön takısı ile kaynak koda aktarabilirsiniz.

**Örneğin;**

- `MAX_CPU_COUNT` şeklinde tanımlanan değişken değeri, şablon kaynak koduna `{{$__variables__/MAX_CPU_COUNT}}` ifadesi ile aktarılabilir.
- `PUBLIC_API_KEY` şeklinde tanımlanan değişken değeri, şablon kaynak koduna `{{$__variables__/PUBLIC_API_KEY}}` ifadesi ile aktarılabilir.

## Denetim Yapıları

| Denetim Yapısı | Açıklama |
| --- | --- |
| `{{@if...}}` | "EĞER" denetiminin yapılmasını sağlayan denetim yapısıdır. `...` ile belirtilen bölüme mantıksal sınama ifadesi yazılmalıdır. Mantıksal sınama ifadelerini `(` ve `)` simgeleri ile gruplayabilir; `&&` ve `\|\|` mantıksal sınama operatörleri ile birbirine bağlayabilirsiniz. |
| `{{@else}}` | "DEĞİLSE" denetiminin yapılmasını sağlayan denetim yapısıdır. |
| `{{@elseif...}}` | "DEĞİLSE EĞER" denetiminin yapılmasını sağlayan denetim yapısıdır. `...` ile belirtilen bölüme mantıksal sınama ifadesi yazılmalıdır. Mantıksal sınama ifadelerini `(` ve `)` simgeleri ile gruplayabilir; `&&` ve `\|\|` mantıksal sınama operatörleri ile birbirine bağlayabilirsiniz. |
| `{{@endif}}` | "EĞER" ile başlayan denetim cümlesinin bittiğini belirten denetim yapısıdır. |

**Örnek 1:** `{{$__value__}}` ifadesinin değerinin "5" olduğu bir durum için aşağıdaki şablon kaynak kodu:

```
{{@if {{$__value__}} < "5"}}
DEĞER 5'TEN KÜÇÜK
{{@elseif {{$__value__}} == "5"}}
DEĞER 5'E EŞİT
{{@else}}
DEĞER 5'TEN BÜYÜK
{{@endif}}
```

kaynak kod üreteçleri tarafından aşağıdaki koda dönüştürülecektir:

```
DEĞER 5'E EŞİT
```

**Örnek 2:** `{{$type/__value__}}` ifadesinin değerinin "String" olduğu bir durum için aşağıdaki şablon kaynak kodu:

```
{{@if {{$type/__value__}} == "String"}}
$defaultValue = '';
{{@else}}
$defaultValue = 0;
{{@endif}}
```

kaynak kod üreteçleri tarafından aşağıdaki koda dönüştürülecektir:

```
$defaultValue = "";
```

**Örnek 3:** `{{$type/__value__}}` ifadesinin değerinin "String" olduğu ve `{{$__index__}}` ifadesinin değerinin "0" olduğu bir durum için aşağıdaki şablon kaynak kodu: 

```
{{@if ({{$type/__value__}} == "String") && ({{$__index__}} == "0")}}
$values = [];
$values[0] = '';
{{@elseif {{$type/__value__}} == "String"}}
$values[{{$__index__}}] = '';
{{@endif}}
```

kaynak kod üreteçleri tarafından aşağıdaki koda dönüştürülecektir:

```
$values = [];
$values[0] = '';
```

Yukarıdaki ifade aşağıdaki biçimde içe içe birleştirilmiş olarak da yazılabilir:

```
{{@if {{$type/__value__}} == "String"}}
{{@if {{$__index__}} == "0"}}
$values = [];
{{@endif}}
$values[{{$__index__}}] = '';
{{@endif}}
```

## Kaçış Simgesi

Pyronome kalıp şablonları için özel bir anlama sahip olan `{{` ve `}}` ifadeleri, birçok başka yazılım dili, anaçatı ve kütüphane için de özel bir anlama sahip olabilir. Bu nedenle bazı durumlarda Pyronome kaynak kod üreteçlerinin `{{` ve `}}` ifadelerini görmezden gelmesini isteyebilirsiniz. Bu gibi durumlarda `{{!` ifadesi kullanılabilir. `{{!` ifadesi kaynak kod üretim aşamasında, `{{` ifadesine dönüştürülür.

**Örneğin;**

- `{{!name}}` ifadesi, `{{name}}` ifadesine dönüştürülür.
- `{{!$URL}}` ifadesi, `{{$URL}}` ifadesine dönüştürülür.
- `{{!@if}}` ifadesi, `{{@if}}` ifadesine dönüştürülür.
