# Software Engineer Intern (Front End) - Task Assessment
Write your answers in plain text for the general questions. If the questions require you to write code, please attach the files with the file name like ‘JS_QuestionNumber’ or attach the codepen, codesandbox, jsfiddle or any online code editor links with the same name. Please attempt all the HTML/JS questions and the general questions. Please do not copy and paste answers.

## General Questions
1. What excites or interests you about coding? What did you learn this week? 
2. What is a recent technical challenge you experienced and how did you solve it? 
3. Talk about your preferred development environment (tools and technologies you prefer using) or a cool project that you've recently worked on (if any). 
4. What is your general expectation from this internship program? 
5. What mediums do you prefer to learn programming?

## HTML/JS Questions
### 1. Create a simple webpage with a functioning calculator with basic functions like addition, subtraction, multiplication and division. (No need to focus hard on the
design. Functionality is key) 

### 2. Find any errors in this code snippet and correct them:

``
removeStudentsWithoutGrade(studentsInfo)
; const studentsInfo = [
{ id: 1, name: ‘student1’, grade: 0 }, { id: 2, name:
‘student2’, grade: 2 }, { id: 3, name: ‘student3’, grade: 4 } {
id: 4, name: ‘student4’, grade: 3 }, { id: 5, name: ‘student5,
grade: 0 }, ]; studentsInfo.push({ id: 99, name: ‘student99’,
grade: 100 }); const removeStudentsWithoutGrade =

(items) => {
return items.filter(item => !!item.grade) || []; }
studentsInfo = [];
console.log(removeStudentsWithoutGrade); ``
