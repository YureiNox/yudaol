# Hi ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif)My name is Yudaol

<button onclick="translateToEnglish()">Traduire en anglais</button>
<button onclick="translateToFrench()">Traduire en français</button>

<script>
function translateToEnglish() {
  const textToTranslate = prompt("Entrez le texte à traduire en anglais:");

  fetch(`https://api.cognitive.microsofttranslator.com/translate?api-version=3.0&to=en`, {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
      'Ocp-Apim-Subscription-Region': 'northeurope',
    },
    body: JSON.stringify([{ 'text': textToTranslate }]),
  })
  .then(response => response.json())
  .then(data => {
    const translatedText = data[0].translations[0].text;
    alert(`Traduction en anglais:\n${translatedText}`);
  })
  .catch(error => {
    console.error('Erreur lors de la traduction:', error);
    alert('Erreur lors de la traduction. Veuillez réessayer.');
  });
}

function translateToFrench() {
  const textToTranslate = prompt("Entrez le texte à traduire en français:");

  fetch(`https://api.cognitive.microsofttranslator.com/translate?api-version=3.0&to=fr`, {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
      'Ocp-Apim-Subscription-Region': 'northeurope',
    },
    body: JSON.stringify([{ 'text': textToTranslate }]),
  })
  .then(response => response.json())
  .then(data => {
    const translatedText = data[0].translations[0].text;
    alert(`Traduction en français:\n${translatedText}`);
  })
  .catch(error => {
    console.error('Erreur lors de la traduction:', error);
    alert('Erreur lors de la traduction. Veuillez réessayer.');
  });
}
</script>

Passionate about computer science, robotics, electronics, and cybersecurity
I started programming with HTML, creating several small websites. Later, I transitioned to Python, Bash, C, and other languages, exploring Linux and its various commands
* 🌍  I'm based in Switzerland
* ✉️  You can contact me at [yudaol.zero@gmail.com](mailto:yudaol.zero@gmail.com)
* 🚀  I'm currently working on [App\_installer\_for\_flipperzero](http://github.com/Yudaol/app_installer_for_flipperzero)
* 🧠  I'm learning C, C# and C++
* 🤝  I'm open to collaborating on all of my project

### Skills


<p align="left">
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a><a href="https://www.php.net/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/php-colored.svg" width="36" height="36" alt="PHP" /></a><a href="https://docs.microsoft.com/en-us/cpp/?view=msvc-170" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/c-colored.svg" width="36" height="36" alt="C" /></a><a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="36" height="36" alt="Git" /></a><a href="https://www.oracle.com/java/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/java-colored.svg" width="36" height="36" alt="Java" /></a><a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a><a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="36" height="36" alt="CSS3" /></a><a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="NodeJS" /></a><a href="https://www.oracle.com/uk/index.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/oracle-colored.svg" width="36" height="36" alt="Oracle" /></a><a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" /></a><a href="https://dotnet.microsoft.com/en-us/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/dot-net-colored.svg" width="36" height="36" alt=".NET" /></a><a href="https://store.arduino.cc/?gclid=Cj0KCQjw2eilBhCCARIsAG0Pf8uueBifykWcsSS4LPESeGQfxGVKJYnzV7bz471XfknQJy_1VINVWM8aAkLtEALw_wcB" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/arduino-colored.svg" width="36" height="36" alt="Arduino" /></a><a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/aws-colored.svg" width="36" height="36" alt="Amazon Web Services" /></a><a href="https://www.blender.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/blender-colored.svg" width="36" height="36" alt="Blender" /></a><a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" /></a><a href="https://www.linux.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="36" height="36" alt="Linux" /></a><a href="https://apple.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/macos-colored.svg" width="36" height="36" alt="MacOS" /></a><a href="https://pytorch.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/pytorch-colored.svg" width="36" height="36" alt="PyTorch" /></a><a href="https://www.raspberrypi.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/raspberrypi-colored.svg" width="36" height="36" alt="Raspberry Pi" /></a><a href="https://www.adobe.com/uk/products/photoshop.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/photoshop-colored.svg" width="36" height="36" alt="Photoshop" /></a><a href="https://ethereum.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/ethereum-colored.svg" width="36" height="36" alt="Ethereum" /></a><a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/googlecloud-colored.svg" width="36" height="36" alt="Google Cloud" /></a></p>

### Socials

<p align="left"> <a href="https://www.github.com/Yudaol" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /> </picture> </a> <a href="http://www.instagram.com/YudaolZero" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="undefined" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" width="32" height="32" /> </picture> </a> <a href="https://www.x.com/YudaolZero" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/twitter-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/twitter.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/twitter.svg" width="32" height="32" /> </picture> </a> <a href="https://www.youtube.com/@yudaol" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="undefined" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/youtube.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/youtube.svg" width="32" height="32" /> </picture> </a></p>

### Badges

<b>My GitHub Stats</b>

<a href="http://www.github.com/Yudaol"><img src="https://github-readme-stats.vercel.app/api?username=Yudaol&show_icons=true&hide=&count_private=true&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&show_icons=true" alt="Yudaol's GitHub stats" /></a>

<a href="http://www.github.com/Yudaol"><img src="https://github-readme-streak-stats.herokuapp.com/?user=Yudaol&stroke=ffffff&background=1c1917&ring=0891b2&fire=0891b2&currStreakNum=ffffff&currStreakLabel=0891b2&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true" /></a>

<a href="https://github.com/Yudaol" align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yudaol&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20%Languages" alt="Top Languages" /></a>

<b>Top Repositories</b>

<div width="100%" align="center"><a href="https://github.com/Yudaol/Adbtool" align="left"><img align="left" width="45%" src="https://github-readme-stats.vercel.app/api/pin/?username=Yudaol&repo=Adbtool&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en" /></a><a href="https://github.com/Yudaol/App_installer_for_flipperzero" align="right"><img align="right" width="45%" src="https://github-readme-stats.vercel.app/api/pin/?username=Yudaol&repo=App_installer_for_flipperzero&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en" /></a></div><br /><br /><br /><br /><br /><br /><br />
