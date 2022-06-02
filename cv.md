<h1 align="center">Zelenevskaya Marina</h1>

***
<p align="center">
<img src="https://media.giphy.com/media/p1RQmiH7X0mQ2QWOv6/giphy.gif" width="30%"></p>

***
## **CONTACT** ##
* **Address:** Belarus, Minsk
* **Phone:** +375293490159
* **E-mail:** mzelianeuskaya@yandex.ru
* **Discord:** Zelenevskayamarina#5123
* **CodePen:** [Zelenevskayamarina](https://codepen.io/zelenevskayamarina)

***
## **ABOUT ME** ##
I have experience in personnel management in a large international construction corporation, which is engaged in the design and construction of industrial facilities around the world. I received not only managerial skills, but also communication skills – the opportunity to work with a large and friendly team. But I decided that I wanted to try myself in something new, to change my specialty – to become a programmer! I hope that one day I will be able to apply my knowledge and professional skills not only in management, but also in programming, because I have a great desire to learn and develop.

***
## **EDUCATION AND QUALIFICATIONS** ##
* 2005–2010 – [Belarusian State University of Informatics and Radioelectronics](https://bntu.by/), business administration
* 2021–present – [Belarusian State University of Informatics and Radioelectronics](https://iti.bsuir.by/), information systems software

***
## **WORK EXPERIENCE** ##
* 2010–2012 – Director, CHUP «Planet of Diplomas». Minsk, Republic of Belarus
* 2012–2014 – Assistant Consul, Embassy of the Republic of Belarus in the People's Republic
of China, Ministry of Foreign Affairs. Beijing, China
* 2015–2020 – Recruitment Manager, Representative office of JSC «China Engineering Corporation
САМС» (China) in Belarus. Minsk, Republic of Belarus
* 2020–2021 – Head of Human Resources and Migration Department, Branch of JSC «China Engineering Corporation САМС» (China) in the Samara region. Togliatti, Russian Federation

***
## **SKILLS** ##
**Professional skills:** 
* HTML / CSS
* JavaScript
* C#, C languages

**Additional tools and technologies:** 
* Source code editors – Visual Studio, Visual Studio Code
* Configuration management task automation program – PowerShell
* Text editor – Notepad++
* Graphic online editor – Figma
* Version control system – Git
* Web service for hosting IT projects and their joint development – GitHub
* BEM methodology

***Additional information:*** In order to make up at a good speed, and at the same time with high quality, you need to have not only experience, but also a certain set of technologies and programs.

***
## **CODE EXAMPLES** ##
***JavaScript task solution:*** There's no such thing as private properties on a coffeescript object! But, maybe there are? Implement a function createSecretHolder(secret) which accepts any value as secret and returns an object with ONLY two methods 
getSecret() which returns the secret
setSecret() which sets the secret

```js
function createSecretHolder(secret) {
  let secr = secret
  function setSecret(n) {
    secr = n
  }
  function getSecret() {
    return secr
  }
  let obj = {
    setSecret: setSecret,
    getSecret: getSecret
  }
  return obj
}
```

***JavaScript task solution:*** You will be given a list of objects. Each object has type, material, and possibly secondMaterial. The existing materials are: paper, glass, organic, and plastic. Your job is to sort these objects across the 4 recycling bins according to their material (and secondMaterial if it's present), by listing the type's of objects that should go into those bins.

```js
function recycle(array) {
  const bin = [[],[],[],[]];
  array.forEach(item => {
    if(item.material === "paper" || item.secondMaterial === "paper"){
      bin[0].push(item.type);
    }if(item.material === "glass" || item.secondMaterial === "glass"){
      bin[1].push(item.type);
    }if(item.material === "organic" || item.secondMaterial === "organic"){
      bin[2].push(item.type);
    }if(item.material === "plastic" || item.secondMaterial === "plastic"){
      bin[3].push(item.type);
    }
  });
  return bin;
}
```

***
## **LANGUAGESS** ##

* **English:** B1 – Intermediate  
* **Chinese:** A2 – Upper Elementary 

***

You can check my **GitHub** profiles: [@mzelenevskaya](https://github.com/mzelenevskaya) and  [@zelenevskayamarina](https://github.com/Zelenevskayamarina)

***