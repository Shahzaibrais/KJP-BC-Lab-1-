# KJP-BC-Lab-2-
Students = {
Name : ["Shahzaib","Afzal","Faisal"],  
Section : "Section A",  
Marks :[78,64,80],  
Attendance : [25,15,18] }
{     console.log(Students.Section) console.log (Students.Name[2])}
if (Students.Attendance[2] >= 20 &amp;&amp; Students.Marks[2] >= 90)
{     console.log("A+") }
else if (Students.Attendance[2] >= 20 &amp;&amp; Students.Marks[2] >= 80){      
console.log("A") } 
else if (Students.Attendance[2] >= 20 &amp;&amp; Students.Marks[2] >= 70) { 
console.log("B+")      } 
else (Students.Attendance[2] &lt; 20 &amp;&amp; Students.Marks[2] >= 60)  { 
console.log("F") 
}
