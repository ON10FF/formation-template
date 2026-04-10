# 📄 Template Landing Page — Formation en ligne
### Pack Templates Pro · par [Votre Boutique]

---

## Avant de commencer

Ce fichier contient toutes les instructions pour personnaliser votre landing page **sans toucher au code**. Chaque modification se fait en remplaçant les textes entre `[crochets]` dans le fichier `index.html`.

Ouvrez `index.html` avec un éditeur de texte simple :
- **Windows** → Notepad++ (gratuit) ou VS Code
- **Mac** → TextEdit ou VS Code
- **En ligne** → [vscode.dev](https://vscode.dev) (aucune installation requise)

---

## Checklist de personnalisation

Faites les modifications dans cet ordre. Cochez chaque étape au fur et à mesure.

### ✅ Étape 1 — Les informations de base

Recherchez et remplacez ces éléments dans tout le fichier :

| Ce que vous cherchez | Ce que vous mettez |
|---|---|
| `[Votre Nom]` | Votre prénom et nom (ou pseudo) |
| `[Nom de la Formation]` | Le titre exact de votre formation |
| `[LIEN_CHARIOW]` | L'URL de votre produit sur Chariow |
| `2025` (dans le footer) | L'année en cours |

> 💡 **Astuce** : Utilisez le raccourci `Ctrl+H` (ou `Cmd+H` sur Mac) pour faire un remplacement global dans tout le fichier d'un seul coup.

---

### ✅ Étape 2 — La section HERO (première impression)

C'est la partie la plus importante. Le visiteur décide en 3 secondes s'il reste ou part.

**Badge de niche** (ligne ~50)
```
[Niche — Ex: Marketing Digital · E-Commerce · Freelance]
```
Remplacez par votre domaine. Exemple : `Marketing Digital · Afrique`

**Titre principal** (ligne ~55)
```
Apprenez à [Résultat principal] en [X jours/semaines]
```
Exemple : `Apprenez à créer votre business en ligne en 30 jours`

> ⚠️ Le titre doit contenir UN résultat clair et UN délai précis. Évitez le vague.

**Sous-titre** (ligne ~62)
Répondez à cette question : *"Pour qui c'est, et qu'est-ce qui rend cette méthode différente ?"*

**Chiffres de preuve sociale** (lignes ~70-80)
```
+[XXX] apprenants      → Ex: +247 apprenants
4.9/5 (XX avis)        → Ex: 4.9/5 (38 avis)
```
Si vous débutez et n'avez pas encore de chiffres : commencez avec vos bêta-testeurs (offrez 2-3 accès gratuits contre des avis honnêtes).

---

### ✅ Étape 3 — La section PROBLÈME

Listez 3 douleurs réelles de votre cible. Soyez très précis — évitez les généralités.

❌ Mauvais : *"Vous n'arrivez pas à gagner de l'argent en ligne"*  
✅ Bon : *"Vous avez essayé de vendre sur Facebook mais vos posts sont ignorés"*

Les 3 emojis proposés (😓 😤 😰) peuvent être changés selon votre ton.

---

### ✅ Étape 4 — Les statistiques de la formation

```
[X]h     → Nombre d'heures de vidéo. Ex: 6h
[X]      → Nombre de modules. Ex: 4
[X]      → Nombre de ressources bonus. Ex: 12
```

Si votre formation n'a pas encore de vidéo (ebook ou PDF), remplacez "heures de contenu vidéo" par "pages de contenu" ou "chapitres".

---

### ✅ Étape 5 — Le programme (modules)

Pour chaque module, remplissez :
- **Le titre** : court et orienté résultat. Ex: *"Trouver vos premiers clients"*
- **La description** : une ligne qui explique l'objectif du module
- **Les leçons** : 3 leçons par module minimum. Soyez précis dans les titres.

> 💡 Les titres de leçons qui commencent par un verbe d'action se vendent mieux.  
> Ex : *"Configurer votre page de vente en 20 minutes"* plutôt que *"La page de vente"*

---

### ✅ Étape 6 — Votre photo et présentation

**La photo** (ligne ~195)
Remplacez le bloc carré coloré avec votre initiale par une vraie photo :
```html
<!-- Remplacez ce bloc : -->
<div class="w-32 h-32 rounded-2xl bg-gradient-to-br ...">
  [P]
</div>

<!-- Par ceci : -->
<img src="assets/photo.jpg" alt="Votre Nom" 
     class="w-32 h-32 rounded-2xl object-cover" />
```
Placez votre photo dans le dossier `assets/images/` et adaptez le nom du fichier.

**Votre bio** : 3-4 phrases maximum. Parlez de votre parcours, d'un résultat concret que vous avez obtenu, et de combien de personnes vous avez aidées.

**Les réalisations** (badges) : remplacez par 3 faits mesurables.  
Exemples : `✓ 200+ clients accompagnés`, `✓ 5 ans d'expérience`, `✓ Certifié Google Ads`

---

### ✅ Étape 7 — Les témoignages

**Si vous avez déjà des clients :**
Copiez-collez leurs messages WhatsApp ou commentaires tels quels. L'authenticité bat toujours le style.

**Si vous démarrez (zéro avis) :**
1. Offrez 2 à 3 accès gratuits à des proches ou membres de votre communauté
2. Demandez-leur de tester la formation et de vous donner un retour écrit honnête
3. Utilisez ces retours comme témoignages (avec leur accord)

**Les avatars colorés** : remplacez la lettre entre crochets `[I]` par l'initiale du prénom du témoignage.

---

### ✅ Étape 8 — L'offre et le prix

**Le prix barré** (valeur perçue) :
Calculez la somme de la valeur de chaque élément inclus. Ce chiffre doit être 3 à 5x supérieur au prix de vente pour que la remise paraisse crédible.

**Le prix de vente** :
Pour le marché africain, voici des fourchettes courantes sur Chariow :
- Ebook / guide PDF → 3 000 – 8 000 FCFA
- Mini-formation (< 3h) → 8 000 – 20 000 FCFA
- Formation complète → 20 000 – 60 000 FCFA
- Coaching + formation → 50 000 FCFA et plus

**Le lien Chariow** (`[LIEN_CHARIOW]`) :
Récupérez l'URL de votre page produit Chariow et remplacez les deux occurrences dans le fichier (bouton hero et bouton offre).

**La garantie** :
7 jours est le minimum conseillé. 14 jours convertit mieux. Une garantie affichée augmente les ventes sans augmenter les remboursements — les clients qui achètent en confiance ne demandent pas remboursement.

---

### ✅ Étape 9 — La FAQ

Répondez aux 4 objections les plus fréquentes dans votre niche. Les questions universelles qui fonctionnent toujours :

1. *"Je suis débutant, est-ce fait pour moi ?"*
2. *"Combien de temps faut-il consacrer par jour ?"*
3. *"Est-ce que j'ai accès à vie au contenu ?"*
4. *"Comment se passe le paiement depuis [pays] ?"*

---

### ✅ Étape 10 — Le sticky CTA (barre en bas)

Ce bandeau apparaît automatiquement quand le visiteur a scrollé 600px vers le bas. Mettez-y votre titre de formation et votre prix de lancement — c'est un rappel permanent d'acheter.

---

## Personnalisation avancée (optionnel)

### Changer la couleur d'accent

La couleur principale est l'**ambre/doré** (`amber`). Pour changer :

Recherchez `amber` dans le fichier et remplacez par une couleur Tailwind de votre choix :
- `amber` → doré (défaut)
- `orange` → orange vif
- `violet` → violet
- `emerald` → vert émeraude
- `sky` → bleu ciel
- `rose` → rose/rouge

### Ajouter un timer de compte à rebours

Si vous voulez créer une offre limitée dans le temps, ajoutez ce bloc avant le bouton CTA dans la section offre :

```html
<div class="text-center mb-6">
  <p class="text-gray-400 text-sm mb-2">Offre expire dans</p>
  <div id="timer" class="text-3xl font-black text-amber-400 tracking-widest">
    00:00:00
  </div>
</div>

<script>
  // Durée du timer en secondes (ici 24h)
  let timeLeft = 24 * 60 * 60;
  const timerEl = document.getElementById('timer');
  const interval = setInterval(() => {
    if (timeLeft <= 0) { clearInterval(interval); return; }
    const h = String(Math.floor(timeLeft / 3600)).padStart(2, '0');
    const m = String(Math.floor((timeLeft % 3600) / 60)).padStart(2, '0');
    const s = String(timeLeft % 60).padStart(2, '0');
    timerEl.textContent = `${h}:${m}:${s}`;
    timeLeft--;
  }, 1000);
</script>
```

### Remplacer le favicon

Ajoutez cette ligne dans le `<head>` du fichier :
```html
<link rel="icon" type="image/png" href="assets/favicon.png" />
```

---

## Structure des fichiers

```
template-formation/
├── index.html          ← Fichier principal (tout est ici)
├── README.md           ← Ce guide
└── assets/
    └── images/         ← Mettez vos images ici
        ├── photo.jpg       (votre photo de formateur)
        └── mockup.png      (capture ou image de la formation)
```

---

## Mise en ligne

Une fois personnalisée, vous avez deux options :

**Option A — Héberger la page vous-même**
Uploadez le dossier sur un hébergeur gratuit comme [Netlify](https://netlify.com) ou [Vercel](https://vercel.com). Vous obtenez un lien en HTTPS que vous partagez.

**Option B — Utiliser la page de vente Chariow**
Copiez les textes de chaque section dans l'éditeur de page Chariow. La template vous sert alors de modèle de rédaction et de structure.

---

## Besoin d'aide ?

Contactez-nous à : `[votre-email@domaine.com]`  
Temps de réponse : sous 24h

---

*Template créée avec soin par [Votre Boutique] · Tous droits réservés*
