---
description: >-
  Mac üzerinden klasörlere sağ tıklayıp Visual Studio Code ile aç aksiyonu,
  butonu oluşturmak
---

# ⚙️ Visual Studio Code ile Aç

## 🤖 Automator Oluşturma

* 🔎 Sırasıyla ⌘ + Space tuşlarına basın ve çıkan alana `automator` yazın

![](<../.gitbook/assets/image (1).png>)

* 📄 `New Document` butonuna basıp ardından `Quick Action` butonunu seçin

![](<../.gitbook/assets/image (2).png>)

## 🔘 Quick Action Tanımlama

* ⚙️ Workflow receves current `files or folders` in `Finder` ayarını tanımlayın
* 👨‍💻 Ardından sol üstteki arama alanından `Run Shell Script` öğesini seçin
* ⚙️ `open -n -b "com.microsoft.VSCode" --args "$*"` scriptini `as arguments` özelliği ile ayarlayın

![](<../.gitbook/assets/Screen Shot 2021-08-19 at 18.24.19.png>)

![](<../.gitbook/assets/image (4).png>)

## 🎉 Kaydedin ve çıkın, artık tamamdır

![](<../.gitbook/assets/image (6).png>)

