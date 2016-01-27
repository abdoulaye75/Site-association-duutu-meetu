<div class="jumbotron">
<div class="container">

<form class="col-lg-6" action="traitement.php" method="post">
<legend> <h3> Pour nous contacter ou nous soutenir </h3> </legend>
<span> NB : les champs marqués par un * sont obligatoires </span>

<div class="form-group">
<label for="nom"> Nom * : </label>
<input id="nom" type="text" class="form-control" required="required"/>
</div>

<div class="form-group">
<label for="prenom"> Prénom * : </label>
<input id="prenom" type="text" class="form-control" required="required"/>
</div>

<div class="form-group">
<label for="email"> Email * : </label>
<input id="email" type="email" class="form-control" required="required"/> <span class="help-block pull-right"> Votre email doit contenir un "@" </span>
</div>

<div class="form-group">
<label for="telephone"> Téléphone portable : </label>
<input id="telephone" type="tel" class="form-control"/>
</div>

<div class="form-group">
<label for="select"> Objet du message * : </label>
<select id="objet" class="form-control" required="required">
<option> Demande d'adhésion </option>
<option> Soutien ou don </option>
<option> Autre </option>
</select>
</div>

<label for="textarea"> Votre message * : </label>
<textarea id="message" class="form-control" rows="8" placeholder="Tapez votre message ici" required="required"> </textarea>
<br/>

<button class="btn btn-primary" type="submit"> Envoyer </button>
<button class="btn btn-danger" type="reset"> Tout effacer </button>

</form>
</div>
</div>