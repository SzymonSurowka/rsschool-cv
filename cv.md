# Szymon Surówka

## Contact information:

- **Phone:** (+48) 509677889
- **E-mail:** szymon121122@gmail.com
- **Linkedin:** [My profile](https://www.linkedin.com/in/szymon-sur%C3%B3wka-7622001a8/#experience)
- **GitHub:** [SzymonSurowka](https://github.com/SzymonSurowka)

## Summary

I work as a Junior Specialist in Financial and Accounting Processes. I would like to change my profession and become Junior Frontend Developer. I treat programming as my new hobby. I would like to create better and better websites, first as a freelancer and then I hope to find a job as a Frontend Developer.

## Skills:

- HTML5, CSS and JavaScript (Basic)
- Git + GitHub
- VS Code

## Code example:

`My code`

```javascript
let imageButtonElement = document.querySelector(".imageButton");
let myImageElement = document.querySelector(".myImage");

imageButtonElement.addEventListener("click", () => {
  myImageElement.remove();
  imageButtonElement.remove();
});

let backgroundButtonElement = document.querySelector(".backgroundButton");
let bodyElement = document.querySelector(".body");
let themeNameElement = document.querySelector(".themeName");

backgroundButtonElement.addEventListener("click", () => {
  bodyElement.classList.toggle("dark");

  themeNameElement.innerText = bodyElement.classList.contains("dark")
    ? "jasne"
    : "ciemne";
});
```
