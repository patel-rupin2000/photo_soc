# photo_soc
Simple Social media app where you can see exif image metadata App specially for flexing photography
<h2>Deployed :</h2>
https://shrouded-wave-51845.herokuapp.com/
 
<h1>For local running and modification</h1>

 1  => Clone Repository
 <br>
 2  => Install Packages Running requirements.txt 
 <br>
 3  => Change Firebase Credentials (API keys .....) and import your own credential.json file 
 <br>
 config = {


 Firebase Configurations

 }
 <br>
data = os.path.abspath(os.path.dirname(__file__)) + "/credential.json"
 <br>
 4 => change app.config['SECRET_KEY'] = '*****' to any key 
 <br>
 5  => Run app.py
 <br>
 6  => Go to assign localhost
<h1>Constraints</h1>
1 => only JPG file is allowed
<br>
2 => Kindly upload relevant content
<br>
3 =>It is more relevant to upload image which are captured from DSLR basically images which containts more EXIF information
