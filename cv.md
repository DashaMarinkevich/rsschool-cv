Resume
========================
**Darya Marinkevich**
-------------------------
### Gamarnika Street, 20, Apt.45  ###
### +375 (33) 320-63-67 ###
### Email: dasha_marinkevich@mail.ru ###
### Skype: dasha_marinkevich ###

**About me**

I graduated from the Belarusian State University of Informatics and Radioelectronics in 2017. My specialty in computer science and logistics.

*Purpose:* Obtaining the position of a systems analyst, developing and gaining new knowledge in this area. I am also interested in web development, learning CSS and JS.

I have an analytical mindset, communicative, persistent, able to formulate requirements in accordance with the tasks set.Hardworking and I love to learn.

**Skills**

1. HTML
2. JavaScript
3. Photoshop
4. MS Office,PowerPoint
5. Outlook
6. Java, C#
7. XML, BPMN

**Code examples - defining leap year**

	'use strict';	
	let yearStart = +prompt('Введите год для начала интервала:');
	let yearEnd = +prompt ('Введите год для конца интервала:');
	if(yearStart > yearEnd) {
	  alert('Ошибка ввода! Год начала интервала больше года окончания!');
	}
	else {
	  let result = getLeapYears(yearStart, yearEnd);
	  if(result) {
	    alert('В заданном интервале найдено '+ result +' високосных годов');
	  }
	  else {
	    alert('В заданном интервале отсутствуют восокосные годы');
	  }
	}
	function getLeapYears(yearS, yearE){
	  let kolLeapYear=0;
	  for (let i=yearS;i<=yearE;i++){
	    if(i%4 === 0) {
	      kolLeapYear++;
	      console.log(`Год ${i} является високосным`);
	    }
	    else
	    if (i%100 === 0 && i%400 === 0) {
	      kolLeapYear++;
	      console.log(`Год ${yearS} является високосным`);
	    }
	    else {
	      console.log(`Год обычный`);
	      continue;
	    }
	  }
	  return kolLeapYear;
	}

**Job experience**

I am currently employed in the software development and support company as a data analyst.The key aspect of my job was providing technical data and writing technical documentation. 

*Top Soft, Minsk | 2017 – Present*

Consulting users by phone. Remote PC configuration. Software testing. Development of user manuals. Preparation of documentation for the description of entities, relationships and processes of the subject area.
Participation in setting goals and developing technical specifications.Collection, analysis and documentation of functional requirements for software.
Testing the developed system.
Training of system users.

**Languages**

My level of English is Pre-Intermediate
