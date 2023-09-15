---
theme: default
background: ./img/pexels-photo-2387793.jpeg
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: Emails professionels
mdc: true
---

# Emails professionels

<div class="flex row justify-center">
  <img src="/img/alpsify-logotextualhorizontal-white.png" class="h-10 rounded shadow"/>
</div>


---
transition: fade-out
---

# Qu'est qu'un email professionel ?

C'est une addresse email qui est rattachée à un nom de domaine qui vous appartient. Vous en êtes le propriétaire et vous pouvez la configurer comme vous le souhaitez.

```text {all}
<locale>@<nomDeDomaine>
```

Exemple

```text {1|2|3|all}
jean.martin@apple.com (boite email)
contact@apple.com (alias ou boite email)
jean.martin+site@apple.com (email virtuel, illimité)
```

<br/>

**Les autres types d'adresse**

|     |     |
| --- | --- |
| <kbd>@orange.fr</kbd> <kbd>@sfr.fr</kbd> <kbd>...</kbd> | emails rattachées à un fournisseur d'accès |
| <kbd>@gmail.com</kbd> <kbd>@hotmail.fr</kbd> <kbd>...</kbd> | emails gratuites |

<!--
Here is another comment.
-->

---
layout: default
---

# Les avantages


<div class="grid grid-cols-3 grid-rows-2 grid-justify-center">
  <Box title="Crédibilité" text="C'est plus sérieux." v-click/>
  <Box title="Visibilité" text="Promouvoir votre nom, marque ou entreprise." v-click/>
  <Box title="Fléxibilité" text="Vous pouvez créer plusieurs adresses emails.<br/><br/>Aucune limite." v-click/>
  <Box title="Pérénnité" text="Temps que vous avez le nom de domaine vous gardez les adresses email." v-click/>
  <Box title="Simplicité" text="Vous avez deux environnements complétements différents." v-click/>
  <Box title="Sécurité" text="Vos emails personnels et professionnels sont séparé. Vos emails on moins de probabilité de finir dans les SPAMs." v-click/>
</div>


---
layout: image-left
image: ./img/pexels-photomix-company-226746.jpg
---

# Sécurité

Avoir une sécurité renforcée pour l'adresse de messagerie maître est essentiel.

<Box title="Phishing & scamming" text="Induire en erreur le destinataire d'un message, en lui faisant croire qu’il est envoyé par un tiers de confiance." v-click/>

<div class="grid grid-cols-2">
  <Box title="Mot de passe fort" text="12 caractères minimum, avec des caractères spéciaux et des majuscules" v-click/>
  <Box title="Double authentification" text="Mobile, authenticator app, SMS, email" v-click/>
</div>

--- 
layout: image-right
image: ./img/phishing.png
---

# Phishing & scamming
<br/>
<p v-click>Les fuites de données interviennent majoritairement via l'humain qui utilise l'ordinateur. Ce n'est pas l'analyse des données faite par les fournisseurs qui va compromettre votre entreprise.</p>

<h2 v-click>Mettez à jour vos navigateurs et logiciels</h2>

---

# Les fournisseurs

Les solutions disponibles actuellement.
<br/>

<div class="grid grid-cols-3 gap-10">
  <div class="flex flex-col gap-2 text-center" v-click>
    <img src="/img/google-workspace.png" />
    <p>Facile d'utilisation et de configuration</p> 
    <p>Suite de bureautique</p>
    <p>Ergonomie et interface agréable</p>
    <p>Identification des SPAMs et analyse des fichiers entrants</p>
  </div>
  <div class="flex flex-col gap-2 text-center" v-click>
    <img src="/img/proton.png" />
    <p>Confidentialité et sécurité pour votre entreprise</p>
    <p>Pas de suite bureautique. (VPN, Drive, Calendar)</p>
    <p>Ergonomie et interface agréable</p>
  </div>
  <div class="flex flex-col gap-2 text-center" v-click>
    <img src="/img/microsoft-office.png" />
    <p>Configuration compliqué</p>
    <p>Suite bureautique</p>
  </div>
</div>

---
layout: image-right
image: ./img/jp-valery-blOLCO2K4M0-unsplash.jpg
---

# Le coût

- nom de domaine ~10€ par an
- abonnement ~6€ par mois
- logiciel de messagerie ? Utilisation via Chrome / Safari / Mozilla -> gratuit
- création / installation / configuration  -> dépendant du prestataire et des besoins

**Environ 100€ par an**

---

# Autre solution (non recommandée)

Utilisation d'une adresse email professionnel chez votre hébergeur avec un client de messagerie type Microsoft Outlook.

<div class="grid grid-cols-3 gap-3">
  <Box title="IMAP ou POP" text="Actions appliquées sur le serveur ou sur vos appareils. Ce choix impacte les fonctionnalités et la possibilité de backup des emails." v-click/>
  <Box title="Prix très bas" text="Prix faible car aucune protection et outils complémentaire de base. Souviens bien plus cher par la suite." v-click/>
  <Box title="Confidentialité" text="Tant que vous n'utilisez pas d'outils tiers la confidentialité sera respectée.(selon fournisseur/hébergeur)" v-click/>
  <Box title="Configuration compliquée" text="La configuration et la maintenance de ce type d'installation est compliqué et nécéssite un spécialiste." v-click/>
  <Box title="Protection basse" text="Cette solution ne vous permet pas d'avoir les système de filtre des leaders du marché. Possibilité de s'équiper en parallèle -> implique une analyse par un tier." v-click/>
</div>


---

# Gestion des emails
Comment organiser et gérer sa boite email au quotidien ?

<div v-click>
Labellisation et filtrage des emails
<img src="/img/email-label.png" class="rounded">
</div>
<br/>
<div v-click>
Désabonnement
<img src="/img/email-unsubscribe.png" class="rounded">
</div>
<br/>
<div v-click>
Gestion des SPAMs
</div>
---

# Migrations

Comment migrer de votre système existant vers un nouveau fournisseur ?

1. Archivage de l'ancienne messagerie
2. Transfert du carnet d'adresse
3. Redirection des emails
4. Labellisation des emails en provenance de l'ancienne adresse email
5. Signalement du changement à votre carnet d'adresse

<br/>

#### Important

Il faut absolument faire le transfert d'un seul coup, ne pas garder 2 adresses email en parallèle et essayer de les séparer petit à petit.

---

# Sauvegarde
Comment conserver vos emails importants ?

- Archiver vos conversations avec les labels
- Conserver uniquement le nécéssaire

