# Twinee
1. Добавление раздела [[йоу]]
2. Добавлние картинки персонажа <img src="https://github.com/sigmno/twine/blob/main/kandinsky-download-1761046070300-no-bg-preview%20(carve.photos).png?raw=true">
```
<img src="https://github.com/sigmno/twine/blob/main/kandinsky-download-1761046070300-no-bg-preview%20(carve.photos).png?raw=true](https://github.com/sigmno/twine/blob/main/ya.jpg">
```
3.Добавление фона
```
tw-story{
background-image: url('https://github.com/sigmno/twine/blob/main/%D1%84%D0%BE%D0%BD.png?raw=true')
background-size: cover
}
```
4. Добавление подложки у текста
```
<div class ="text-box">
#текст
<div>
```
```
.text-box{
background-color: rgba(0,0,0, 0.7);
color:white;
padding:10px;
border-radius: 10px;
margin-top: 10px;
pasition:fixed;
bottom:20px;
left:50%;
transform: translateX(-50%);
width:80%;
max-width:800px;
z-index:100;
}
```
