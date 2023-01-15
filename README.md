<html>
    <head>
        <title>belajar coding</title>
        <script language="Javascript">
            function cobaKlik()
            {
                alert('Yakin ingin melanjutkan?');
                document.write("<center><h3>Selamat Datang</h3></center>");
            }
        </script>
    </head>
    <body>
        <from action="login from" method="post">
            <fieldset>
            <center><u><legend>Login Account</legend></u></center>
                <p>
                    <label>Email:</label><br>
                    <input type="email" name="email" placeholder="" />
                </p>
                    <label>Password:</label><br>
                    <input type="password" nama="password" placeholder="" />
                <p>
                    <label><input type="checkbox" name="remeber" value="remember" />Ingatkan Saya</label>
                </p>
                <p>
                    <label><input type="submit" name="submit" value="Login" onClick="cobaKlik()" />Sign in</label>
                </p>
            </fieldset>
        </from> 
    </body>
</html>