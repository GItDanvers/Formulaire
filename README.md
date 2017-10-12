# Formulaire<section id="formulaire">

<!--libellé nombre personnes-->

		<label for="personne">Nombre de personnes</label> : <input type="number" min="1" max="10" name="Nbre" placeholder="Nbre" id="Nbre">

<!--libellé catégorie-->

		<label for="categorie">Catégorie</label> :
			<select name="categorie" id="categorie">
				<option value="tradichti">Tradichti</option>
				<option value="française">Française</option>
				<option value="burger">Burger</option>
				<option value="vegetarien">Végétarien</option>
				<option value="chinois">Chinois</option>
				<option value="africain">Africain</option>
				<option value="indien">Indien</option>
				<option value="thailandais">Thailandais</option>
				<option value="pizza">Pizza</option>
			</select>

<!--libellé temps-->

		<label for="temps">Choix de votre date de réservation</label> : <input type="date" name="temps">

		<input type="submit" name="Chercher" value="Envoyer" />

	</section>
