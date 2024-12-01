# WELCOME🙏🏻


```javascript
const reyk = {
  name: 'Reyk Zepper',
  profession: 'ECM Consultant',
  skills: [ 'Archivierung', 'Datenbanken' ],
  passions: [ 'Programmieren', 'Tiere', 'Natur' ],
  favoriteAnimals: [ 'Hunde' ],
  programmingLanguages: [ 'JavaScript', 'Python' ],
  isTechNerd: true,
  code: [Function: code],
  interactWithAnimals: [Function: interactWithAnimals],
  exploreNature: [Function: exploreNature],
  liveLife: [Function: liveLife]

 code(language) {
    return `loves to code in ${language}.`;
  },

  interactWithAnimals() {
    return `Verbringt gerne Zeit mit ${this.favoriteAnimals.join(' und ')}.`;
  },

  exploreNature() {
    return 'Erkundet die Natur und findet Inspiration für neue Ideen.';
  },

  liveLife() {
    const codingActivities = this.programmingLanguages
      .map((lang) => this.code(lang))
      .join(' ');
    const animalInteraction = this.interactWithAnimals();
    const natureExploration = this.exploreNature();
    return `${codingActivities} ${animalInteraction} ${natureExploration} Liebt, was er tut, mit voller Passion!`;
  },
};

console.log(reyk);
console.log(reyk.liveLife());
}
```



# technologies, tools & stats

![react logo](Assets/icons8-react-native-30.png)
![js logo](Assets/icons8-javascript-30.png)
![html logo](Assets/icons8-html-5-is-a-software-solution-stack-that-defines-the-properties-and-behaviors-of-web-page-30.png)
![css logo](Assets/icons8-css3-30.png)
![node.js logo](Assets/icons8-node.js-30.png)
![vs code logo](Assets/icons8-visual-studio-code-2019-30.png)
![git logo](Assets/icons8-git-30.png)
![github code logo](Assets/icons8-github-30.png)
![apple logo](Assets/icons8-mac-os-30.png)
![windows logo](Assets/icons8-windows-11-30.png)

<!-- >__.cleanCODE__  
>  &nbsp; __.codeCLEAN__ -->
---
