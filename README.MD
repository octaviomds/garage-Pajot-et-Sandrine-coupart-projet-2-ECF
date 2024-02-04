## Pre-requisites.  
Nous connectons notre base de données de serveur MySQL à l'aide de la fonction PHP mysqli_connect() qui prend quatre arguments, à savoir notre "nom de serveur", "nom d'utilisateur", "mot de passe" et "base de données".
(php)
## Installation
appliquer le CSS et le style dans votre page Web selon vos propres exigences d'application.La première étape et la plus élémentaire consiste à créer une connexion à la base de données. Le nom du fichier PHP utilisé ici est "lbconnect.php" et le nom de la base de données utilisé est administrateur.
<?php 
   
    $servername = "localhost";  

    $username = "root";  

    $password = ""; 

   
    $database = "administrateur"; 

   
     // Create a connection  

     $conn = mysqli_connect($servername,  

         $username, $password, $database); 

   
    if($conn) { 

        echo "success";  

    }  

    else { 

        die("Error". mysqli_connect_error());  

    }  
?>

## Usage

Code PHP pour concevoir le formulaire d'inscription:  

<?php 
   
    $servername = "localhost";  

    $username = "root";  

    $password = ""; 

   
    $database = "utilisateurs"; 

   

     $conn = mysqli_connect($servername,  

         $username, $password, $database); 

   
    if($conn) { 

        echo "success";  

    }  

    else { 

        die("Error". mysqli_connect_error());  

    }  
?>
