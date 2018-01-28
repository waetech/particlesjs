# particlesjs
This tutorial was on using particles.js with javascript, some html and css.  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style.css">
    <title>Particles Login</title>
</head>
<body>
    <div id="particles-js"></div>
       <div id="login">
           <form>
               <div>
                   <label for="username">Username</label>
                   <br>
                   <input type="text" placeholder="Username">
                 </div>

                 <div>
                     <label for="password">Password</label>
                     <br>
                     <input type="text" placeholder="Password">
                 </div>

                 <div>
                     <input type="submit" value="login">
                 </div>
           </form>
       </div>
 <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
 <script>
 particlesJS.load('particles-js', 'particles.json', function(){
   console.log('particles.json loaded...');
 });
 </script> 
</body>
</html>
