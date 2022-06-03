# Ekaterina Kuznetsova
__+79091506986 | ek.a.kuznetsova@gmail.com | Moscow, Russia__

junior full-stack developer

### PROFESSIONAL SUMMARY
Want to be a full-stack software engineer in several years, using java & JavaScript, developing robust code for high-volume businesses. An enthusiastic team player and deep creative thinker. In my free time, I go to the gym, prefer productive & healthy lifestyle and enjoy time with family.

### TECH STACK

Skill | Stack
------------ | -------------
Backend | Java, Ruby, Rails 4, Git, GitHub, APIs
Frontend | CSS3, Bootstrap, HTML5, JavaScript
Data Stores | Rake db
Web Servers | Amazon WS
Operating Systems | Mac OC, Windows
IDE | VS Code, IntelliJ IDEA, NetBeans, Sublime Text

### EXPERIENCE

`02.2021 – 06.2021`
__She Codes Luxoft | Moscow, Russia__

Learned basics of java. Create my own game card project and data science with airlines project.

`2014 – 2015`
__Junior ruby on rails developer | freelance | Moscow, Russia__

Simple landing pages & web sites for small businesses and friends (painting studios, personal blogs like pinterest etc)

### OTHER EXPERIENCES

`2012 – 2013`
__Project manager | Scanradar | Moscow, Russia__
Startup service that allows to find executors for solving everyday and business problems using the web version and mobile application. Working with a remote team of 7 people. Develop product map and feature list. Manage team work in task tracker. Set up financial planning for a startup.

`2008 – 2011`
__Researcher | Lomonosov MSU, Faculty of physics, Thermal physics Lab | Moscow, Russia__

Thermophysical research of the lithosphere’s seismologically active zones. Research of heat-transfer properties in different structures. Theory of earthquakes forecast was developed.

`2005 – 2015`
__Math tutor | private & small groups for kids & adults | Moscow, Russia__

### EDUCATION

`2005 – 2011`
__Master of Science (M.Sc.) | Lomonosov Moscow State University (MSU) | Moscow, Russia__
-	Scientific research in Geophysics and publications

### CERTIFICATIONS
`2021-2022`
RS School Course «JavaScript/Front-end» (in progress)

`2021`
She Codes Luxoft
Learned basics of java. Create my own game card project and data science with airlines project.

`2020`
CS50's Introduction to Computer Science | edx.org

`2014`
One month HTML | One Month, Inc

`2013`
One month Rails | One Month, Inc

### PUBLICATIONS & AWARDS
`2010`
Kuznetsova E.A., Petrunin G.I., Popov V.G. / Journal of Applied Physics / Heat-transfer properties in amorphous structures / p.184
`2010`
Kuznetsova E.A., Petrunin G.I., Popov V.G. / Lomonosov Readings-2010, Physics Section / Features of heat-transfer in volcanic and artificial glasses.

### LANGUAGES

Russian (Native), English (Upper Intermediate), German (basic)

### PROFILES

<div id="LinkedIn:">
<a href="https://www.linkedin.com/in/ekaterina-kuznetsova-7759b633/">LinkedIn</a>
| <a href="https://github.com/myspecialspace">My github</a>
</div>

### CODE EXAMPLE
__Replace With Alphabet Position KATA from CODEWARS:__
In this kata you are required to, given a string, replace every letter with its position in the alphabet.

If anything in the text isn't a letter, ignore it and don't return it.

"a" = 1, "b" = 2, etc.

Example
alphabetPosition("The sunset sets at twelve o' clock.")

Should return "20 8 5 19 21 14 19 5 20 19 5 20 19 1 20 20 23 5 12 22 5 15 3 12 15 3 11" (as a string)

```JavaScript
function alphabetPosition(text) {
  let alphabet = "abcdefghijklmnopqrstuvwxyz"
  let alphaNums = [];

  text = text.toLowerCase();

  for (let i = 0; i < text.length; i++){
    let idx = alphabet.indexOf( text[i] );

    if ( idx === -1 ){
      continue;
    }else{
      alphaNums.push( idx +1 );
    }
  }

  return alphaNums.join(" ");
}
```
