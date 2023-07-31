# Les Fruits de l'Ardèche 
<HTML>
	<HEAD>
		<TITLE>Les Fruits de l’Ardèche</TITLE>
	</HEAD>

	<BODY>
		Bienvenue sur le site Fruits de l’Ardèche


		Vous pouvez commander les meilleurs jus de fruits naturels
   <figure> <img src="/main/root/abricot.jpg"  alt="abricot">  </figure>

<form>
  <fieldset>
    <legend>choisissez un lot d jus de fruit:</legend>
    <select name=« jus »  id=« jus-select » autocomplete=« off » required>
    <option value=« « >—Veuillez choisir one option—</option>
    <option value=«individuel demarrage essai »>Lot démarrage avec 3 bouteilles jus d’abricot.</option>
    <option value=«famille demarrage essai »>Lot démarrage famille avec 6 bouteilles jus d’abricot.</option>
    <option value=«entreprise demarrage essai »>Lot démarrage Restaurant/Brasserie avec 20 bouteilles jus d’abricot.</option>
    <option value=«lot de dix»>Lot de 10 bouteilles jus d’abricot.</option>
    <option value=«lot de dix»>Lot de 20 bouteilles jus d’abricot.</option>
    <option value=«lot de dix»>Lot de 30 bouteilles jus d’abricot.</option>
    <option value=«lot de dix»>Lot de 50 bouteilles jus d’abricot.</option>
    <option value=«lot de dix»>Lot de 100 bouteilles jus d’abricot.</option>
</select>
</fieldset>
</form>

<form id=paiement>
  <fieldset>
    <legend>Votre identitÃ©</legend>

    <ol>
      <li>
        <label for=nom>Nom</label>
        <input id=nom name=nom type=text placeholder="PrÃ©nom et nom" required autofocus>
      </li>
      <li>
        <label for=email>Email</label>
        <input id=email name=email type=email placeholder="exemple@domaine.com" required>
      </li>
      <li>
        <label for=telephone>TÃ©lÃ©phone</label>
        <input id=telephone name=telephone type=tel placeholder="par ex&nbsp;: +3375500000000" required>
      </li>
    </ol>
  </fieldset>

  <fieldset>
    <legend>Adresse de livraison</legend>
      <ol>
        <li>
          <label for=adresse>Adresse</label>
          <textarea id=adresse name=adresse rows=5 required></textarea>
        </li>
        <li>
          <label for=codepostal>Code postal</label>
          <input id=codepostal name=codepostal type=text required>
        </li>
          <li>
          <label for=pays>Pays</label>
          <input id=pays name=pays type=text required>
        </li>
      </ol>
    </fieldset>
  <fieldset>
    <legend>informations CB</legend>
    <ol>
      <li>
        <fieldset>
          <legend>Type de carte bancaire</legend>
          <ol>
            <li>
              <input id=visa name=type_de_carte type=radio>
              <label for=visa>VISA</label>
            </li>
            <li>
              <input id=amex name=type_de_carte type=radio>
              <label for=amex>AmEx</label>
            </li>
            <li>
              <input id=mastercard name=type_de_carte type=radio>
              <label for=mastercard>Mastercard</label>
            </li>
          </ol>
        </fieldset>
      </li>
      <li>
        <label for=numero_de_carte>N° de carte</label>
        <input id=numero_de_carte name=numero_de_carte type=number required>
      </li>
      <li>
        <label for=securite>Code sécurité</label>
        <input id=securite name=securite type=number required>
      </li>
      <li>
        <label for=nom_porteur>Nom du porteur</label>
        <input id=nom_porteur name=nom_porteur type=text placeholder=« le nom que sur la carte" required>
      </li>
    </ol>
  </fieldset>

  <fieldset>
    <button type=submit>J’achète !</button>
  </fieldset>
</form>


   	</BODY>
</HTML>
