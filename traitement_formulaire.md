<?php

if (isset($_POST['nom'], $_POST['email'], $_POST['message'])) {
    $destinaire = 'koussanekafo.duutumeetu@gmail.com';
    $objet = $_POST['email']. ' vous a envoyé un message !';
    
    $envoi_mail_reussi = mail($destinataire, $objet, $_POST['message']);
    
    if ($envoi_mail_reussi) {
        echo 'Votre mail nous est bien parvenu !';
    }
    else {
        echo 'Nous sommes désolés mais votre message ne nous est pas parvenu ! Veuillez réessayer s'il vous plaît !';
    }
    else {
        echo 'Veuillez remplir le formulaire comme il se doit s'il vous plaît !';
    }
}

?>