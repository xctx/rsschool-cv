# Curriculum vitae
--- 
## PERSONAL INFORMATION
 > Dzmitry Kamenski
 > phone: +375295382064

## SUMMARY
 Experienced system administrator and passionate programmer, specialized in developing  and supporting various IT projects, seeking to dive into challenging new work. 
 Proven ability to drive projects to completion and provide support for them along with strong troubleshooting skill as well as the ability to work well with little oversight single or in collaboration - it makes me valuable addition to any team. 

 ## SKILLS
* Networks, Linux, bash, apache, nginx, MySQL, SQLite, PostgreSQL; 
* HTML5, CSS3, JavaScript, PHP; 
* Adobe Photoshop; 
* MS Windows, AD, MS SQL Server; 
* VB, AutoIT, Delphi, batch file; 
* Troubleshooting / Customers support; 
* Security focused approach / Pentesting (sqlmap)

## CODE EXAMPLE
```
function findWordSequence(headTail){
 
  var headTail = headTail+headTail[0];  // tail is a head, lets add it
  
  // traversing wordList to match the word by provided pattern
  const findWord = (start, fin, len) => { 
    for (var i=0; i<wordList.length; i++){
      if ((wordList[i].length == len) &&
          (wordList[i][0] == start) &&
          (wordList[i][wordList[i].length-1] == fin)
         ){
         return wordList[i];
          }
    }
    return 0; // return 0 if no word has been found
  }
  
  var wordPatterns = []; // [start,fin,len]
  var text = headTail.toLowerCase().match(/[a-z]/g);   // parse all letters 
  var text2 = headTail.toLowerCase().match(/\d{1,}/g); // and word lengths
   
  for (var i=0;i<text2.length;i++){ // fill wordPatterns 
    wordPatterns[i] = [text[i],text[i+1],text2[i]];
  }
  
  for (i=0; i<text2.length; i++){ // traverse wordList to find words chain
    var x = findWord (wordPatterns[i][0],wordPatterns[i][1],wordPatterns[i][2]);
    if (x == 0){
      wordPatterns=[]; // if at least one word is missed, we make array empty
      break;
    }
    wordPatterns[i] = x;
  }

  return wordPatterns;
}
```

## WORK EXPERIENCE
15/08/2002–Present Software engineer, JSC "Mozyr Oil Refinery" 
* Server & Network infrastructure deployment (AD, Firewall); 
* Data migration & System backups maintainance; 
* MS Windows Server, SQL Server administration; 
* Local server development (ASP, HTML, CSS, JS, SQL); 
* Applied software development (MS SQL, SQLite, VBA, JS, Python); 
* Troubleshooting, customers support; 
* IT accidents investigation.

01/08/2010–01/10/2016 Co-founder, developer, Video Flirt limited
* front-end design (Adobe Flash, HTML, CSS); 
* site promotion, SEO; 
* customers support. 

01/09/2003–Present Part-time freelancer (remote)
* Web-development (WordPress, OpenCart, HTML, CSS, JS, PHP, SEO)
* Windows & Web automation tools development (AutoIT, VB, Delphi, PHP).

## EDUCATION AND TRAINING
01/09/1996–30/06/2002 Belarusian State University of Informatics & Radioelectronics, FITC, systems engineer  

## PERSONAL SKILLS
Good communication skill, team player, English A2