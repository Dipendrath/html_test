# html_test
This is a test repo to put my html porject
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="Submit" method="post">
        <label for="username">Username</label>
        <input type="email" id="username" name="username"><br>
        Date: <input type="date"><br>
        File:<input type="file"><br>
        Range:<input type="range"><br>
        Poke Me:<input type="button" value="pooked"><br>
        Submit:<input type="submit"><br>
        <labe for="male">Male:</labe>
        <input type="radio" id="male
        " name="gender" value="male"><br>
        <label for="female">Female:</label>
        <input type="radio" id="female" name="gender" value="female"><br>
        <label for="other">Other:</label><br>
        <input type="radio" id="other" name="gender" value="other"><br>
        <labe for="c">C</labe>
        <input type="checkbox" name="language" id="c" value="c">
        <label for="java">Java</label>
        <input type="checkbox" name="language" id="java" value="java">
        <labe for="python">Python</labe>
        <input type="checkbox" mame="language" id="python" value="python"><br>
        <!--Example for dropdown-->
        <label for="country"> Select</label>
        <select name="county" id="country">
            <Option value="India">India</Option>
            <option value="US">US</option>
            <option value="UK">Uk</option>
            <option value="Other">Other</option>
        </select><br> 
        <textarea name="story" id="story" rows="4" cols="40">type your text here</textarea>
    </form>
</body>
</html>
