# Erkin Zununbekov

## Software Developer

:house: Bishkek, Kyrgyzstan  
:telephone: +996770542115  
:email: zununbekov@gmail.com  
![skype](skype.svg) erkin.zununbekov  
![linkedin](in.svg) [LinkedIn](https://www.linkedin.com/in/erkin-zununbekov-555532b8)  

### About me  

I am a software developer with five years of experience mostly in banking. Technologies I worked with are Java, Spring, PL/SQL, Oracle Forms/Reports. Main accomplishments include automation of business processes which reduced overall time of manual work, development of OnlineBank webapp allowing our clients perform financial operations wherever they are, support of third-party app which prevented bank from calls to third-party support.  
Now I am interested in front-end development and would like to start from very beginning - HTML and CSS. Combining previous experience with new knowledge in future definitely can be of great benefit.    

### Skills

* Java
* Spring
* Oracle, PL/SQL
* JavaScript, HTML, CSS
* Git, Linux

### Code sample

This is a code sample of my solution of [Lottery Ticket](https://www.codewars.com/kata/57f625992f4d53c24200070e) kata

```javascript
function bingo(ticket, win){
  return ticket.map(elt => isMiniWin(elt) ? 1 : 0).reduce((cur, next) => cur + next) >= win ? 'Winner!' : 'Loser!';
}
function isMiniWin(ar){ 	
  return ar[0].indexOf(String.fromCharCode(ar[1])) != -1;
}
```

