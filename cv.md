# Ivan Klochkov
### Frontend Developer
---
### Contact information:
**Phone:** +7(952)-268-28-64<br>
**E-mail:** [klochkov.ivan.sergeevich@gmail.com](mailto:klochkov.ivan.sergeevich@gmail.com)<br>
**Telegram:** [Dokivan](https://t.me/Dokivan)<br>
**Discord:** [IvanDok13](https://discordapp.com/users/IvanDok13#5167/)<br>

---
### About Me:
I worked as a researcher in the field of laser technology for 6 years. Developed various research methods, conducted experiments and made calculations.

In addition to my main job, for 6 years I was involved in and managed a company organizing outdoor events.

I became very interested in front-end development after I saw the work of my friends from the 'InDriver' and  
other large companies.

I love making improvements to workflows, solving complex problems, optimizing anything. I am sure that these skills will allow me to become an excellent developer.

---
### Languages and tools
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="js" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" title="html" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" title="css" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" title="git" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" title="vscode" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" title="npm" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" title="node" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/eslint/eslint-original.svg" title="eslint" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vim/vim-original.svg" title="VIM" width="40" height="40"/>&nbsp;

---
### Code examples:
<a href="https://www.codewars.com/users/rsschool_5bb3f79998ed1d87"><img src="https://www.codewars.com/users/rsschool_5bb3f79998ed1d87/badges/large"></a>

**[Training JS #30: methods of arrayObject---reduce() and reduceRight():](https://www.codewars.com/kata/573156709a231dcec9000ee8)**
*First, from left to right, the tail of an element and the head of the next element are added together. And then, Calculate their product and return it. All elements of arr are positive integer. If a number is less than 10, its head and tail are the same. Return result number*

```javascript
function tailAndHead(arr) {
  let copy = arr.slice();
  let newCopy = copy.reduce((a, b, i) => {
    b += '';
    if (i > 0) a.push((b[0]));
    return a; 
   }, [])
  let newCopyEnd = copy.reduce((a, b, i) => {
    b += '';
    if (i < copy.length - 1) a.push((b[b.length - 1]));
    return a; 
   }, [])
  let sum = newCopy.reduce((a, b, i, arr) => a.concat(+newCopy[i] + +newCopyEnd[i]),[]);
  let res = sum.reduce((a, b) => a * b);
 return res; 
}

console.log(tailAndHead([1,2,3,4,5])); //945
console.log(tailAndHead([111,2345,66,78,900])); //7293
console.log(tailAndHead([35456,782,569,2454,875])); //12012
```
---
### Projects
1. [Traveling-site](https://ivandok13.github.io/traveling-site/)
2. [Image-gallery](https://rolling-scopes-school.github.io/ivandok13-JSFEPRESCHOOL2023Q2/image-galery/)
3. [Pictures-slider](https://ivandok13.github.io/pictures-slider/)
4. [cssMemeSlider](https://ivandok13.github.io/cssMemeSlider/cssMemeSlider/index.html)
5. [Car-Slider-Project](https://ivandok13.github.io/slide-project/)
6. [Morse-decoder](https://github.com/IvanDok13/morse-decoder)
7. [Video Player](https://rolling-scopes-school.github.io/ivandok13-JSFEPRESCHOOL2023Q2/custom-video/)
8. [Library](https://rolling-scopes-school.github.io/ivandok13-JSFEPRESCHOOL2023Q2/library/)
9. [Drag-and-drop](https://ivandok13.github.io/drag-and-drop/)

---
### Courses:
Result School - HTML&CSS<br>
Hexlet - Front-end Developer<br>
PASV - JavaScript<br>

---
### Languages:
- Russian \- Native
- English \- Upper-intermediate

