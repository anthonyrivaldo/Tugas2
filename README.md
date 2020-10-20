# Tugas2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
    <form method="POST" action="daftar.php">
        <fieldset id="fieldset">
            <legend id="legend" class="Akun">Akun</legend>
            <style type="text/css">
            i {
              }

            .Akun{
                font-size large;
                color: blue;
                font-weight: bol;
            }
            .Data{
                color: crimson;
            }
            </style>
            <table>
                <tr>
                     <td id="text1"><label for="uname" class="Data">Username</label></td>
                     <td><input type="text" name="username" id="user" placeholder="masukkan username"></td>
                </tr>
                <tr>
                    <td id="text1"><label for="pass" class="Data">Password</label></td>
                    <td><input type="password" name="Password" id="pass" placeholder="masukkan password"></td>
                </tr>
                <tr>  
                    <td id="text1"><label for="cpass" class="Data">Konfirmasi Password</label></td>
                    <td><input type="password" name="konfirmasi passwrd" id="cpass" placeholder="masukkan password"></td>
                </tr>
             </table>
        </fieldset>
        <br>
        <fieldset id="fieldset">
            <legend id="legend" class="Akun">Data</legend>
            <table>
                <tr>
                    <td id="text1"><label for="nama" class="Data">Nama</label></td>
                    <td><input type="text" name="nama" id="nama" placeholder="masukkan nama"></td>                
                </tr>
                <tr>
                    <td id="text1"><label for="date" class="Data">Tanggal Lahir</label></td>
                    <td><input type="date" name="tanggal"></td>
                </tr>
                <tr>
                    <td id="text1"><label for="gender" class="Data">Gender</label></td>
                    <td><input type="radio" name="gender">Laki-Laki</td>
                    
                </tr>
                <tr>
                    <td id="text1"><label for="gender"></label></td>
                    <td><input type="radio" name="gender">Perempuan</td>
                </tr>
                <tr>
                    <td id="text1"><label for="hobi" class="Data">Hobi</label></td>
                    <td><input type="checkbox" name="">Membaca</td>
                </tr>
                <tr>
                    <td id="text1"><label for="hobi"></label></td>
                    <td><input type="checkbox" name="">Bernyanyi</td>
                </tr>
                <tr>
                    <td id="text1"><label for="hobi"></label></td>
                    <td><input type="checkbox" name="">Travelling</td>
                </tr>
                <tr>
                    <td id="text1"><label for="hobi"></label></td>
                    <td><input type="checkbox" name="">Menari</td>
                </tr>
                <tr>
                    <td id="text1"><label for="hobi"></label></td>
                    <td><input type="checkbox" name="">Bermain Bola</td>
                </tr>
                <tr>
                   <td><input type="submit" value="Login" name="Submit" id=""></td>
                    <td><input type="reset" value="Reset" name="Reset" id=""></td>
                </tr>
            </table>
        </fieldset>
        












    </form>
    
</body>
</html>
