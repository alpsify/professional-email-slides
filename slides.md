---
theme: default
background: ./img/pexels-photo-2387793.jpeg
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: E-mails professionels
mdc: true
---

# E-mails professionnels

<div class="flex row justify-center">
  <img src="/img/alpsify-logotextualhorizontal-white.png" class="h-10 rounded shadow"/>
</div>


---
transition: fade-out
---

# Qu'est-ce qu'un e-mail professionnel ?

C'est une adresse e-mail qui est rattachée à un nom de domaine qui vous appartient. Vous en êtes le propriétaire et vous pouvez la configurer comme vous le souhaitez.

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

**Les autres types d'adresses e-mail**

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
  <Box title="Visibilité" text="Promouvoir votre nom, votre marque ou votre entreprise." v-click/>
  <Box title="Fléxibilité" text="Vous pouvez créer plusieurs adresses e-mail.<br/><br/>Aucune limite." v-click/>
  <Box title="Pérénnité" text="Tant que vous avez le nom de domaine, vous gardez les adresses e-mail." v-click/>
  <Box title="Simplicité" text="Vous avez deux environnements complètement différents." v-click/>
  <Box title="Sécurité" text="Vos e-mails personnels et professionnels sont séparés. Vos e-mails ont moins de probabilité de finir dans les spams." v-click/>
</div>


---
layout: image-left
image: ./img/pexels-photomix-company-226746.jpg
---

# Sécurité

Une sécurité renforcée pour l'adresse de messagerie principale est essentielle.

<Box title="Phishing & scamming" text="Induire en erreur le destinataire d'un message en lui faisant croire qu'il est envoyé par un tiers de confiance." v-click/>

<div class="grid grid-cols-2">
  <Box title="Mot de passe fort" text="12 caractères minimum, avec l'utilisation de caractères spéciaux et de majuscules." v-click/>
  <Box title="Double authentification" text="Mobile, authenticator app, SMS, email" v-click/>
</div>

--- 
layout: image-right
image: ./img/phishing.png
---

# Phishing & scamming
<br/>
<p v-click>Les fuites de données interviennent majoritairement via l'être humain qui utilise l'ordinateur. Ce ne sont pas les analyses des données faites par les fournisseurs qui vont compromettre votre entreprise.</p>

<h2 v-click>Mettez à jour vos navigateurs et vos logiciels.</h2>

---

# Les fournisseurs

Voici les solutions disponibles actuellement.
<br/>

<div class="grid grid-cols-3 gap-10">
<div class="flex flex-col gap-2 text-center" v-click>
    <img src="/img/proton.png" />
    <p>Confidentialité et sécurité pour votre entreprise</p>
    <p>Pas de suite bureautique. (VPN, Drive, Calendar)</p>
    <p>Ergonomie et interface agréable</p>
  </div>
  <div class="flex flex-col gap-2 text-center" v-click>
    <img src="/img/google-workspace.png" />
    <p>Facile d'utilisation et de configuration</p> 
    <p>Suite de bureautique</p>
    <p>Ergonomie et interface agréable</p>
    <p>Identification des spams et analyse des fichiers entrants</p>
  </div>
  <div class="flex flex-col gap-2 text-center" v-click>
    <img src="/img/microsoft-office.png" />
    <p>Configuration et gestion compliquée</p>
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

Utilisation d'une adresse e-mail professionnelle chez votre hébergeur avec un client de messagerie tel que Microsoft Outlook.

<div class="grid grid-cols-3 gap-3">
  <Box title="IMAP ou POP" text="Actions appliquées sur le serveur ou sur vos appareils. Ce choix a un impact sur les fonctionnalités et la possibilité de sauvegarde des e-mails." v-click/>
  <Box title="Prix très bas" text="Prix bas car aucune protection et aucun outil complémentaire de base. Souvent bien plus cher par la suite." v-click/>
  <Box title="Confidentialité" text="Tant que vous n'utilisez pas d'outils tiers, la confidentialité sera respectée (selon le fournisseur/hébergeur)." v-click/>
  <Box title="Configuration compliquée" text="La configuration et la maintenance de ce type d'installation sont compliquées et nécessitent un spécialiste." v-click/>
  <Box title="Protection basse" text="Cette solution ne vous permet pas d'avoir les systèmes de filtrage des leaders du marché. Possibilité de s'équiper en parallèle -> implique une analyse par un tiers." v-click/>
</div>


---

# Gestion des emails
Comment organiser et gérer sa boîte e-mail au quotidien ?

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
3. Redirection des e-mails
4. Labellisation des e-mails en provenance de l'ancienne adresse e-mail (si possible selon fournisseur)
5. Signalement du changement à votre carnet d'adresse

<br/>

<div v-click>

### Important

Il faut absolument effectuer le transfert en une seule fois, ne pas conserver deux adresses e-mail en parallèle et essayer de les séparer progressivement.

</div>

---

# Sauvegarde
Comment conserver vos e-mails importants ?

- Archiver vos conversations avec les labels
- Exporter si nécéssaire
- Conserver uniquement le nécéssaire

---

<div class="flex h-full justify-center items-center">
  <img src="/img/alpsify-logotextualhorizontal-white.png" class="h-15 rounded shadow"/>
</div>