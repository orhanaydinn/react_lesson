#React Lesson#

<!DOCTYPE html>
<html>


    <body> <!--index.html-->
        <h1>Hello HTML</h1>
        <h2>Hello World!</h2>
        <h6>Hello World 6</h6>
        <p>Hello, I am Orhan</p>
        <br><br>
        <p>Hello, I am Orhan</p>
        

        <ul> <!--create unordered list-->
            <li>Ankara</li>
            <li>İstanbul</li>
            <li>Mersin</li>
        </ul>

        <ol> <!--create list ordered list-->
            <li>Ankara</li>
            <li>İstanbul</li>
            <li>Mersin</li>
        </ol>
    </body>

------------------------------------------------------------------------------------------------------------------------------------
    <body> <!--links.html-->
       <a href="index.html">Main Page</a>  <!--added links-->
       <br>
       <a href="https://www.linkedin.com/in/orhan-aydin/">Orhan Aydin Linkedin</a>
       <br>
       <a href="index.html" target="_blank">Main Page</a>  <!--target="_blank" the link open new page-->
       <br>
       <a href="index.html" target="_blank">
        <img width="75" height="75" alt="No Image" src="https://www.factsmostly.com/wp-content/uploads/2024/08/Summer-Season.webp"></img>
        <!--added image. If you can not image when you open the page alt comment helps to shows information.-->
       </a>
    
    
    </body>
    
------------------------------------------------------------------------------------------------------------------------------------

    <body> <!--formating.html-->
        Orhan <b>Aydin</b> <!-- <b> bold font -->
        <br>
        Orhan <strong>Aydin</strong>  <!-- <strong> bold font -->
        <br>
        Orhan <em>Aydin</em> <!-- <em> italic font -->
        <br>
        Orhan <i>Aydin</i> <!-- <i> italic font -->
        <br>
        Orhan <small>Aydin</small> <!-- <b> small font -->
        <br>
        Orhan <sub>Aydin</sub> <!-- <b> down font -->
        <br>
        Orhan <sup>Aydin</sup> <!-- <b> bottom font -->
        <br>
        Orhan <ins>Aydin</ins> <!-- <b> underlined font -->
        <br>
        Orhan <delete>Aydin</delete> <!-- <b> strikethrough font -->
        <br>
        Orhan <mark>Aydin</mark> <!-- <b> mark font -->
        <br><br><br>

    </body>

------------------------------------------------------------------------------------------------------------------------------------

    <form action="formatting.html"> <!--forms.html-->
    <label>First Name : </label>
    <input name="First Name" type="text" required/> <!--Users can inputs any data-->
    <br>
    <label>Password : </label>
    <input name="First Name" type="password" required/> <!--Users can inputs any data-->
    <br>
    <label>Gender</label>
    <select name="gender">
        <option>Male</option>
        <option>Female</option>
    </select>
    <br>
    <label>Favourite Cars</label>
    <select name="Cars" size="5" multiple>
        <option>Volvo</option>
        <option>BMW</option>
        <option>Mercedes</option>
        <option>Audi</option>
        <option>Ford</option>
    </select>
    <br>
    <label>Biography</label>
    <textarea name="Biography" rows="4" cols="30"></textarea>
    <br>
    <input type="submit" value="Save1"/>
    <br>
    <button>Save2</button>
    <button onClick="alert('Saved')">Save1</button>

    </form>

------------------------------------------------------------------------------------------------------------------------------------
    
    <body> <!--table.html-->
        <table> <!--Create table-->
            <th>Kişi</th> <!--Create Headline-->
            <th>Email</th>
            <tr>
                <td>Orhan Aydin</td>
                <td>orhanaydinmechatronic@gmail.com</td>
            </tr>
            <tr>
                <td>name surname</td>
                <td>name.surname@gmail.com</td>
            </tr>
        </table>
    
    
    </body>

</html>

------------------------------------------------------------------------------------------------------------------------------------
#CSS#
<head>
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
    <style>
        h1{
            color: green;
        }

        body {
            background-color: white;
        }

        div{
            border: 1px solid red; 
            /*border: 1px dotted; */
            /*border: 1px dashed; */
            margin-top: 100px; /*You can change location your text, border e.t with Margin-top, left, right, bottom */
            margin-left: 100px;
            margin-right: 300px;
            padding: 25px; /*padding affect inside the border*/
            background-color: grey;
                table{
            border-collapse: collapse; /*It merges table cell borders into a single border, eliminating the double border effect.*/
            width: 100%;

        }
        table, th, td{
            border: 1px solid black;
        }
        th{
            height: 30px;
        }
        td{
            height: 30px;
            text-align: center;
        }
        }
    </style>
</head>


