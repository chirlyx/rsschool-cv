# Katsiaryna Kaluhina

![image](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![image](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![image](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### Contact information

___Phone:___ +375 33 302 99 95

___Email:___ katsiaryna.kaluhina@gmail.com

## Profile

---

Enthusiastic beginner Frontend Developer, eager to put the gained knowledge into
practice and take up new technical challenges. The positive traits include patience
and resilience alongside with creativity and system thinking. Teamplayer and also
independently responsible.

## Education

---

__Bachelor of Science in Economics in Electronic
Business, Belarussian State University of Informatics
and Radioelectronics__

Sep 2019 - Present

__RS School JavaScript/Front-end 2023Q1 Courses__

Mar 2023 - Present

## Technical Skills 

---

| **Knowledge area** | **Level** |
|--------------------|-----------|
| HTML5, CSS3        | Basic     |
| JavaScript         | Basic     |
| Git, Github        | Basic     |
| Figma              | Basic     |
| Adobe Photoshop    | Basic     |

## Code Example

---

__Extract the domain name from a URL KATA from CODEWARS:__ Write a function that when given a URL as a string, parses out just the domain name and returns it as a string. 

![image](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=Codewars&logoColor=white)

```js 
function domainName(url){
  if (!/^https?:\/\//.test(url)) {
      url = "http://" + url;
    }
  return new URL(url).hostname.match(/[^w{3}\.][a-z0-9-]+[^\.]/)[0];
}
```