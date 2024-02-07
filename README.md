# <p align="center">Latex template for thai language </p>

### สิ่งที่ต้องรู้เบื้องต้น

#### Compiler

latex เปรียบเสมือน Markup language ที่ต้องการ compile เพื่อเป็น pdf ดังนั้นต้องใช้เครื่องมืออยู่ 3 อย่าง

1. **Compiler** ที่จะทำการแปลงไฟล์ latex ให้ออกมาในรูปของ pdf
    - Linux - TexLive
    - Windows - MikTeX
    - Mac OS - MacTeX

    compiler มีอยู่หลายตัว สามารถใช้ตัวอื่นก็ได้

2.  นอกจากจะมี **Compiler** มาแล้ว ก็จะมีตัว package manage มาให้ด้วย เพื่อใช้สำหรับติดตั้ง package

3. **Editor** ก็คือโปรแกรมที่ใช้ในการเขียน latex ซึ่งมีอยู่หลายตัวเช่น `TexStudio` หรือจะใช้ `Vscode` ก็ได้ เพราะเป็นเพียงการแก้ไข text file เท่านั้น

### ตัวอย่าง texlive บน Linux

ติดตั้ง texlive

```
$ sudo pacman -S texlive-basic 
$ sudo pacman -S texlive-meta
```
compile ไฟล์ latex เป็น pdf

```
$ xelatex filename.tex
```

ติดตั้ง package

```
$ sudo tlmgr install fontspec  
```


# Inside it
 
- THSarabunNew