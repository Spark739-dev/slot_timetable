# Ex03 Time Table
## Date:
25-09-2025
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
    <html>
     <head>
        
     </head>
     <body>
        <center>
            <img src="logo.png" height="100" width="540" >
           
        </center>
        <br>
        <table border="1"cellspadding="20" bgcolor="cyan" width="500" height="300" align="center">
            <captions><center> <STRONG>SLOT TIME TABLE-VESHWANTH(21224230300)</STRONG></center></captions>
            <th bgcolor="yellow" >Day/Time</th>
            <th bgcolor="Yellow" >Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow"> Wednesday</th>
            <th bgcolor="yellow"> Thursday</th>
            <th bgcolor="yellow"> Friday</th>
            <th bgcolor = "yellow" >Saturday</th>
            <tr><td bgcolor ="yellow" align="center"> 8-10</td>
            <td bgcolor ="cyan" align="center">CLOUD SECURITY</td>
            <td bgcolor ="cyan" align="center">FREE SLOT</td>
            <td bgcolor ="cyan" align="center">Digital Electronics</td>
            <td bgcolor ="cyan" align="center">TOC</td>
            <td bgcolor ="cyan" align="center">FREE SLOT</td>
            <td bgcolor ="cyan" align="center">FREE SLOT</td>
            </tr>
            <tr><td bgcolor ="yellow" align="center"> 10-12</td>
            <td bgcolor ="cyan" align="center">FREE SLOT</td>
            <td bgcolor ="cyan" align="center">FREE SLOT</td>
            <td bgcolor ="cyan" align="center">QA-1</td>
            <td bgcolor ="cyan" align="center">FWAD</td>
            <td bgcolor ="cyan" align="center">Digital Electronics</td>
            <td bgcolor ="cyan" align="center">statistics And Numerical Methods</td>
            </tr>
            <tr><td bgcolor ="yellow" align="center"> 12-1</td>
            <td bgcolor ="cyan" align="center" colspan="6" >Lunch</td>
            </tr>
            <tr><td bgcolor ="yellow" align="center"> 1-3</td>
            <td bgcolor ="cyan" align="center">statistics And Numerical Methods</td>
            <td bgcolor ="cyan" align="center">FREE SLOT</td>
            <td bgcolor ="cyan" align="center">Mentor Meet</td>
            <td bgcolor ="cyan" align="center">FREE SLOT</td>
            <td bgcolor ="cyan" align="center">TOC</td>
            <td bgcolor ="cyan" align="center">FWAD</td>
            </tr>
            <tr><td align="center" bgcolor="yellow"> 3-5</td>
            <td bgcolor="cyan" colspan="5" align="center">FREE SLOT</td>
            <td bgcolor="cyan" align="center">CLOUD SECURITY</td>
        </table>
        
        <br><br><br>
        <table border="1" cellspadding="20" height="300" width="500" align="center">
            
            <th align="center"> S.NO </th> 
            <th align="center"> Subject Code</th>
            <th align="center">  Subject Name</th>
            
            <tr align="center"><td>1</td>
            <td> 19AI414</td>
            <td> Fundamentals of Web Apllication Development</td>
            </tr>
            <tr align="center"><td>2</td>
            <td> 19EN612</td>
            <td> German Basic (GER)</td>
            </tr>
            <tr align="center"><td>3</td>
            <td> 19PH206</td>
            <td> Physics for Information Technology (PHY)</td>
            </tr>
            <tr align="center"><td>4</td>
            <td> 19CY205</td>
            <td> Principles of Chemistry in Engineering (CHE)</td>
            </tr>
            <tr align="center"><td>5</td>
            <td> 19MA201</td>
            <td> Calculus and Matrix Algebra (MAT)</td>
            </tr>
            <tr align="center"><td>6</td>
            <td> 19EY701</td>
            <td> Soft Skill (SS)</td>
            </tr>
            
        </table>

      </body>
    </html>

## OUTPUT
![out img](<WhatsApp Image 2025-09-25 at 19.20.20_e2d21628.jpg>)

![out img](<WhatsApp Image 2025-09-25 at 19.20.39_01a9290a.jpg>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
