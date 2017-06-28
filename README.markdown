# Fontconfig Setup for Adobe Source Han and Google Noto Fonts
These are the Fontconfig rules that make Adobe Source Han fonts and Google Noto * CJK fonts installation easier

It can:

* Make Adobe Source Han fonts considered equal as their Google Noto * CJK equivalent
* Make subset otf fonts considered equal as (Super )OTC fonts(which has different font family name)(not implemented yet)

<https://github.com/Lin-Buo-Ren/Fontconfig-Setup-for-Adobe-Source-Han-and-Google-Noto-Fonts>

## Font Family Names
### Super OTC
All locales and font weights packed in one and only one file

* Sans-serif
    * Source Han Sans
    * Noto CJK Sans
* Serif
    * Source Han Serif
    * Noto CJK Serif

## Language-specific OpenType/CFF (OTF)
Complete glyphs for every locale, only the default locale is set differently.  Font weights are separated in different files

* TC
    * Source Han Serif TC
    * Noto Serif CJK TC
* SC
    * Source Han Serif SC
    * Noto Serif CJK SC
* JP
    * Source Han Serif JP
    * Noto Serif CJK JP
* KR
    * Source Han Serif KR
    * Noto Serif CJK KR

## OpenType/CFF Collection (OTC)
Similar as "Language-specific OpenType/CFF", but packed all font weights in the same file

Font family names be same as Language-specific OpenType/CFF (OTF)

## Region-specific Subset OpenType/CFF (Subset OTF)
Only contain glyphs of a locale.  Font weights are separated in different files

* TW
    * Source Han Serif TW
    * Noto Serif TC
* CN
    * Source Han Serif CN
    * Noto Serif SC
* JP
    * Source Han Serif JP
    * Noto Serif JP
* KR
    * Source Han Serif KR
    * Noto Serif KR

Note the difference of naming in Google Noto fonts variants

## 原作者<br>Original Author
林博仁 &lt;<Buo.Ren.Lin@gmail.com>&gt;

## 智慧財產授權條款<br>Intellectual Property License
[Creative Commons BY-SA 4.0+](http://creativecommons.org/licenses/by-sa/4.0/).

```
這個專案介紹文件是基於專案介紹文件範本
This README is based on Project README Template

http://github.com/Lin-Buo-Ren/Project-README-templates
```
