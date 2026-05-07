# Dərs 1 — CSS-ə giriş, CSS qoşulma növləri, CSS sintaksisi

## Dərsin müddəti:

⏰ Təxminən 1 saat 30 dəqiqə — 2 saat

---

# Dərsin planı

| Mövzu               | Vaxt      |
| ------------------- | --------- |
| CSS nədir           | 10 dəq    |
| CSS niyə lazımdır   | 5 dəq     |
| CSS qoşulma növləri | 30 dəq    |
| CSS sintaksisi      | 20 dəq    |
| Class və ID         | 20 dəq    |
| Praktika            | 20-30 dəq |

---

# 1. CSS nədir?

CSS — saytın görünüşünü dəyişmək üçün istifadə olunur.

HTML saytı qurur.

CSS isə saytı gözəlləşdirir.

Məsələn:

* rəng verir;
* ölçü dəyişir;
* fon əlavə edir;
* düymələri gözəlləşdirir.

---

# HTML vs CSS

## HTML

```html id="yxk6ch"
<h1>Salam</h1>
```

Sadə yazıdır.

---

## CSS ilə

```html id="q9v8yr"
<h1 style="color:red;">Salam</h1>
```

Artıq yazı qırmızı oldu.

---

# Müəllim üçün izah

Şagirdlərə belə deyə bilərsiniz:

> HTML evin karkasıdır.
> CSS isə evin dizaynıdır.

---

# 2. CSS qoşulma növləri

CSS sayta 3 cür qoşulur.

---

# 1) Inline CSS

CSS birbaşa tagın içində yazılır.

```html id="cr4r8q"
<p style="color:red;">Salam</p>
```

---

# İzah

| Hissə | Mənası                  |
| ----- | ----------------------- |
| style | CSS yazmağa imkan verir |
| color | Yazının rəngi           |
| red   | Qırmızı                 |

---

# Şagirdlərə sual verin

❓ color: blue; nə edər?

---

# Praktika

Şagirdlər yazsın:

```html id="2w4go0"
<h1 style="color:blue;">Başlıq</h1>
```

Sonra:

* green
* yellow
* black

rənglərini yoxlasınlar.

---

# 2) Internal CSS

CSS ayrıca `<style>` tagında yazılır.

```html id="tq2k42"
<!DOCTYPE html>
<html>
<head>

<style>

h1{
    color:red;
}

</style>

</head>
<body>

<h1>Salam</h1>

</body>
</html>
```

---

# İzah

| Kod   | İzah            |
| ----- | --------------- |
| style | CSS yeri        |
| h1    | h1 tagını seçir |
| color | rəng            |
| red   | qırmızı         |

---

# Praktika

Tapşırıq:

1. h1 qırmızı olsun
2. p mavi olsun

---

# 3) External CSS

Ən düzgün üsuldur.

---

# HTML

```html id="63epgc"
<link rel="stylesheet" href="style.css">
```

---

# CSS faylı

```css id="w8vb2z"
h1{
    color:green;
}
```

---

# Müəllim üçün qeyd

Burada mütləq izah edin:

* CSS ayrıca faylda olur
* Böyük layihələrdə belə edilir

---

# 3. CSS Sintaksisi

---

# Nümunə

```css id="fxz1yo"
h1{
    color:red;
}
```

---

# İzah

| Hissə | Adı      |
| ----- | -------- |
| h1    | Selector |
| color | Property |
| red   | Value    |

---

# Vacib qaydalar

## CSS-də:

* `{}` mütləqdir
* `:` mütləqdir
* `;` mütləqdir

---

# Səhv nümunə

```css id="hllc7h"
h1{
    color red
}
```

---

# Düzgün

```css id="o4t1e2"
h1{
    color:red;
}
```

---

# 4. CSS Selectors

---

# Tag selector

```css id="0rm7pc"
p{
    color:blue;
}
```

Bütün p tagları dəyişəcək.

---

# Class

## HTML

```html id="4j8y8k"
<p class="text">Salam</p>
```

## CSS

```css id="sm9s8o"
.text{
    color:red;
}
```

---

# İzah

`.` class üçündür.

---

# ID

## HTML

```html id="jlwm4x"
<p id="title">Salam</p>
```

## CSS

```css id="m6x72d"
#title{
    color:green;
}
```

---

# İzah

`#` id üçündür.

---

# Class vs ID

| Class                         | ID                 |
| ----------------------------- | ------------------ |
| çox elementdə istifadə olunur | yalnız 1 elementdə |
| . ilə yazılır                 | # ilə yazılır      |

---

# Böyük Praktika

Şagirdlər bunu yazsın:

```html id="06lmha"
<!DOCTYPE html>
<html>
<head>

<style>

h1{
    color:red;
}

.text{
    color:blue;
}

#title{
    color:green;
}

</style>

</head>
<body>

<h1 id="title">Başlıq</h1>

<p class="text">Salam</p>

<p class="text">CSS öyrənirik</p>

</body>
</html>
```

---

# Dərsin sonunda veriləcək tapşırıq

## Task 1

3 fərqli başlıq yaradın:

* biri qırmızı
* biri yaşıl
* biri mavi

---

## Task 2

2 paragraph yaradın:

* biri class ilə
* biri id ilə

---

## Task 3

Saytın fonunu dəyişin.

---

# Ev tapşırığı

## “Mənim haqqımda” saytı

Şagird yaratmalıdır:

* başlıq
* haqqında məlumat
* sevdiyi oyun
* sevdiyi film

Və:

* rəng verməlidir
* CSS istifadə etməlidir
* class istifadə etməlidir
* id istifadə etməlidir

---

# Dərs 2 — CSS Colors və CSS Backgrounds

## Dərsin müddəti:

⏰ 1 saat 30 dəqiqə — 2 saat

---

# Dərsin planı

| Mövzu       | Vaxt   |
| ----------- | ------ |
| CSS Colors  | 35 dəq |
| HEX Colors  | 20 dəq |
| RGB         | 15 dəq |
| Backgrounds | 30 dəq |
| Praktika    | 20 dəq |

---

# 1. CSS Colors

CSS-də rəng vermək üçün:

```css id="p26dzn"
color:red;
```

---

# Ən çox istifadə olunan rənglər

```css id="ij3m6j"
color:red;
color:blue;
color:green;
color:black;
color:white;
color:yellow;
```

---

# Praktika

Şagirdlər:

* h1
* p
* button

rənglərini dəyişsinlər.

---

# 2. HEX Colors

---

# Nümunə

```css id="wdfvij"
color:#ff0000;
```

---

# İzah

HEX `#` ilə başlayır.

---

# Populyar HEX rənglər

| Rəng    | Kod     |
| ------- | ------- |
| Qırmızı | #ff0000 |
| Yaşıl   | #00ff00 |
| Mavi    | #0000ff |
| Ağ      | #ffffff |
| Qara    | #000000 |

---

# Praktika

Şagirdlər:

* fonu qara etsin
* yazını ağ etsin

---

# 3. RGB

---

# Nümunə

```css id="2qcrw3"
color:rgb(255,0,0);
```

---

# İzah

| Rəqəm | Mənası        |
| ----- | ------------- |
| 255   | maksimum rəng |
| 0     | rəng yoxdur   |

---

# 4. Backgrounds

---

# Fon rəngi

```css id="qhaj5x"
background-color:black;
```

---

# Fon şəkli

```css id="08n8z1"
background-image:url("bg.jpg");
```

---

# Şəklin təkrarlanmaması

```css id="g3nxhx"
background-repeat:no-repeat;
```

---

# Şəklin ortada olması

```css id="qqryjd"
background-position:center;
```

---

# Şəklin bütün ekranı tutması

```css id="h06s3r"
background-size:cover;
```

---

# Böyük Praktika

```html id="lnn6rn"
<!DOCTYPE html>
<html>
<head>

<style>

body{
    background-color:black;
    color:white;
}

h1{
    color:yellow;
}

</style>

</head>
<body>

<h1>Kino Saytı</h1>

<p>Ən yaxşı filmlər</p>

</body>
</html>
```

---

# Dərsin sonunda tapşırıq

Şagird yaratmalıdır:

* rəngli sayt
* fon
* fərqli rəngli yazılar

---

# Ev tapşırığı

“Kino saytı” hazırlamaq:

* qara fon
* ağ yazılar
* rəngli başlıq

---

# Dərs 3 — Borders, Outline, Margin, Padding

## Dərsin müddəti:

⏰ 1 saat 30 dəqiqə — 2 saat

---

# Dərsin planı

| Mövzu         | Vaxt   |
| ------------- | ------ |
| Border        | 30 dəq |
| Border Radius | 15 dəq |
| Outline       | 15 dəq |
| Margin        | 20 dəq |
| Padding       | 20 dəq |
| Praktika      | 20 dəq |

---

# 1. Border

Border — elementin çərçivəsidir.

---

# Nümunə

```css id="4n0g7e"
border:2px solid red;
```

---

# İzah

| Hissə | Mənası   |
| ----- | -------- |
| 2px   | qalınlıq |
| solid | düz xətt |
| red   | rəng     |

---

# Border növləri

```css id="x2vryc"
border-style:solid;
border-style:dashed;
border-style:dotted;
```

---

# Praktika

Şagirdlər:

* qırmızı border
* mavi border
* dotted border

yaratsınlar.

---

# 2. Border Radius

Küncləri yumrulaşdırır.

```css id="im50w7"
border-radius:10px;
```

---

# Praktika

Şagirdlər:

* 10px
* 20px
* 50px

yoxlasınlar.

---

# 3. Outline

Outline border kimidir.

```css id="l3k49m"
outline:3px solid blue;
```

---

# 4. Margin

Elementin çöl boşluğudur.

```css id="g0cb9e"
margin:20px;
```

---

# İzah

Margin elementləri bir-birindən uzaqlaşdırır.

---

# 5. Padding

Elementin iç boşluğudur.

```css id="rb4skj"
padding:20px;
```

---

# İzah

Padding texti borderdən uzaqlaşdırır.

---

# Vizual izah

```text id="mb0rme"
Margin -> çöldə
Border -> çərçivə
Padding -> iç boşluq
Text -> məzmun
```

---

# Böyük Praktika

```html id="0kck3f"
<!DOCTYPE html>
<html>
<head>

<style>

.box{
    width:300px;

    border:3px solid red;

    padding:20px;

    margin:30px;

    border-radius:10px;

    background-color:gray;
}

</style>

</head>
<body>

<div class="box">

Salam uşaqlar

</div>

</body>
</html>
```

---

# Dərsin sonunda tapşırıq

3 fərqli box yaradın:

* fərqli border
* fərqli radius
* fərqli padding
* fərqli margin

---

# Ev tapşırığı

“Oyun saytı” hazırlamaq:

* qara fon
* boxlar
* border
* padding
* margin
* radius istifadə etmək
