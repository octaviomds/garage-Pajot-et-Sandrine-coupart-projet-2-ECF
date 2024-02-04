## Pre-requisites.  
Nous connectons notre base de données de serveur MySQL à l'aide de la fonction PHP mysqli_connect() qui prend quatre arguments, à savoir notre "nom de serveur", "nom d'utilisateur", "mot de passe" et "base de données".
(php)
## Installation

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
