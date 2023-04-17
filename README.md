<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Assignment1</title>
        <style>
            * {
                font-family: "Times";
            }
            #image {
                display: block;
                margin: auto;
                border: 2px;
            }
            table {
            height: 300px;
        }
        </style>
    </head>
    <h1 align="center">Chitkara University</h1>
    <body>
        <p style="font-size: 20px;" align="center">Located 30 kms from <b>Chandigarh</b>, Chitkara University offers a world of
        learning that will help you reach your goals. Choose from our varied industry
        endorsed programs. Learn from an outstanding faculty at our state-of-the-art
        teaching facilities. Explore unlimited opportunities to get placed with one of
        the <i>1500+ campus recruiters and meet other students with dreams as big as
        yours.</i></p>
        <br><br>
        <img src="https://digitallearning.eletsonline.com/wp-content/uploads/2020/04/Chitkara-University.jpg" alt="Error uploading File" width="600" height="250" align="center">
        <h2>Course:</h2>
        <table border="1" cellspacing="0">
            <tr>
                <th>Engineering</th>
                <th>Science</th>
                <th>Commerce</th>
                <th>Others</th>
            </tr>
            <tr>
                <td>B-Tech in CSE</td>     
                <td>Bsc in Maths</td>
                <td>BBA</td>
                <td>Diploma in IT</td>
            </tr>
            <tr>
                <td>B-Tech in ME</td>
                <td>Bsc in chemistry</td>
                <td>MBA in Marketing</td>
                <td>Diploma in civil</td>
            </tr>
            <tr>
                <td>B-Tech in CHE</td>
                <td>Bsc in Physics</td>
                <td>MBA in Finance</td>
                <td>NCC</td>
            </tr>
        </table>
        <h3>Other Services</h3>
        <p align="justify">1. Bus</p>
        <p align="justify">2. Career Counselling</p>
        <p align="justify">3. Sports</p>
        <p align="justify">4. Hostels</p>
        <p align="justify">5. Resturants</p>
        <br><br>
        <h3>Enquiry Form</h3>
        <form action="">
            <label for="name"><font color="blue">Name:</font></label>
            <input type="text">
            <br><br>
            <label for="district"><font color="blue">District:</font></label>
            <input type="text">
            <br><br>
            <label for="state"><font color="blue">State:</font></label>
            <input type="text">
            <br><br>
            <label for="age"><font color="blue">Age:</font></label>
            <input type="age">
            <br><br>
            <label for="date"><font color="blue">DOB:</font></label>
            <input type="date">
            <br><br>
            <label for="email"><font color="blue">Email:</font></label>
            <input type="email">
            <br><br>
            <label for="name"><font color="blue">Gender:</font></label>
            <input type="radio" name="gender" id="">Male
            <br><br>
            <input type="radio" name="gender" id="">Female
            <br><br>
            <textarea name="" id="" rows="15" cols="40" align="center">
                Your Special Enquiry
            </textarea>
            <br><br>
            <button type="submit">
                <font color="blue">
                    Submit
                </font>
            </button>
            <br><br>
        </form>
    </body>
</html>
