# my-first-readme

Repo explaining README.md

``` javascript
const handleWin = (letter) => {
  gameIsLive = false;
  if (letter === "x") {
    statusDiv.innerHTML = `${letterToSymbol(letter)} has won!`;
  } else {
    statusDiv.innerHTML = `<span>${letterToSymbol(letter)} has won!</span>`;
  }
};
```


``` css
.grid {
    background-color: salmon;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 15px;
    margin-top: 50px;
}

```

``` index.html
<div class="grid">
    <div class="box" id="box-1"></div>
    <div class="box" id="box-2"></div>
    <div class="box" id="box-3"></div>
    <div class="box" id="box-4"></div>
    <div class="box" id="box-5"></div>
    <div class="box" id="box-6"></div>
    <div class="box" id="box-7"></div>
    <div class="box" id="box-8"></div>
    <div class="box" id="box-9"></div>
</div>
```
| Function | Description |
| ----------- | ----------- |
| 'handleWin(') | Handle win of either player |
| 'checkGameStatus()' | Check status after each turn |


~
## Steps to install on local computer
1. Go to repo on Github profile
2. 'Fork' and 'clone' repo
3. Clone to local machine 
``` text
git clone (link)
```
4. Go to file diretory
5. Open file in browser
``` text
open (file)
```
