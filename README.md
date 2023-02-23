<p align="center">
  
<img src="https://i.imgur.com/IY2JRyY.jpg" alt="LeiamNashProject">
  TikSave <br> a free and fast tiktok video donwloader without watermark</p>

  <br> <br> features:<br>• no watermark download<br>• no need apikey<br>• fast and easy to use<br>• supports multiple request<br>• supports dual titkok link <br> > vt.tiktok<br> > tiktok.com<br>

  <br> <br>

installation
```js
npm i tiksave
```

<br>
  
calling a variable
```js
const tiktok = require("tiksave");
```

<br>

how to use?
```js
tiktok.save("TIKTOK VIDEO URL");
```

<br>

example:
```js
tiktok.save("https://vt.tiktok.com/ZS851mWxt/").then(video => {
  console.log(video);
});
```

<br>

you can also use the await function
```js
async function download () {
  const video = await tiktok.save("https://vt.tiktok.com/ZS851mWxt/");
  console.log(video);
}
download();
```

<br>
<p align="center">
TikSave is a package scrape for ttdownloader this program uses cheerio to have and easy and readable output
  </p>


<br> • [LeiamNash](https://www.facebook.com/LeiamNashRebrth)
