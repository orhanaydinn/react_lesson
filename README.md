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
</html>
