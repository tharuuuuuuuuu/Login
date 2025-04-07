# Login
<html>
    <head>
        <title>My First Web Page</title>
    </head>
    <body>
        <center><h1><u>Registation Form</u></h1></center>
        <form style="border: 2px solid black; padding: 20px; border-radius: 5px; max-width: 400px; margin: auto;">
            <label for="name">Full Name: <input type="text" id="name"> </label> <br> <br>
            
            Enter your age: <input type="number" /> <br> <br>
        
            Gender:
            <input type="checkbox" name="gender" id="male"> <label for="male">Male</label>
            <input type="checkbox" name="gender" id="female"> <label for="female">Female</label> <br> <br>
        
            Apply For:
            <input type="radio" name="apply" id="abc"> <label for="abc">ABC</label>
            <input type="radio" name="apply" id="dfc"> <label for="dfc">DFC</label>
            <input type="radio" name="apply" id="ngc"> <label for="ngc">NGC</label> <br> <br>
        
            Mobile Number:
            <input type="tel"> <br> <br>
        
            Date Of Birth:
            <input type="date"> <br> <br>
        
            E-mail: 
            <input type="email"> <br> <br>
        
            <div style="display: flex; justify-content: center; gap: 10px;">
                <input type="submit" value="Submit" style="background-color: black; 
                color: white; 
                border: none; 
                padding: 8px 16px; 
                cursor: pointer; 
                border-radius: 4px;" />
                
                <input type="reset" value="Reset" style="background-color: black; 
                color: white; 
                border: none; 
                padding: 8px 16px; 
                cursor: pointer; 
                border-radius: 4px;" />
            </div>

        </form>
    </body>
</html>
