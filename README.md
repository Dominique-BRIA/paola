# 💖 Site Web Romantique - Pour PAOLA ZIBI de la part de DOMINIQUE BRIA

Bienvenue dans le dépôt de votre site web d'amour personnalisé ! Ce site est conçu pour rappeler à votre magnifique compagne **Paola Zibi** à quel point vous l'aimez, avec des animations interactives, un compteur d'amour en direct, un quiz, un générateur de mots doux et une lettre secrète.

---

## ✨ Fonctionnalités Incluses

1. **🌌 Fond Animé aux Étoiles et Cœurs Flottants** : Un effet visuel doux et poétique développé en Canvas 100% autonome.
2. **⏳ Compteur de Temps Magique ("Notre Histoire")** : Calcule en direct les jours, heures, minutes et secondes depuis votre rencontre (avec un bouton `⚙️ Modifier la date` pour ajuster la date exacte directement depuis le site !).
3. **🃏 Cartes 3D Interactives (Flip Cards)** : 6 raisons sincères pour lesquelles vous aimez Paola à découvrir en cliquant.
4. **💌 La Boîte à Mots Doux Magique** : Un générateur aléatoire de déclarations d'amour poétiques.
5. **💘 Le Quiz de Notre Amour** : 3 questions mignonnes avec des confettis à la clé.
6. **🔒 La Lettre Secrète Scellée** : Une enveloppe animée qui s'ouvre au clic pour révéler une déclaration d'amour manuscrite signée **Dominique BRIA**.
7. **💍 Le Bouton "Non" qui S'enfuit** : Une question finale *"Veux-tu continuer à écrire notre éternité ?"* avec un bouton d'hésitation qui esquive la souris/le doigt pour l'obliger à cliquer sur **OUI** avec feux d'artifice !
8. **🎵 Musique d'Ambiance Romantique** : Un lecteur audio génératif doux intégré directement en JavaScript (Web Audio API).

---

## 🚀 Comment Déployer sur VERCEL (en 1 minute top chrono !)

Vous avez **3 méthodes ultra-simples** pour mettre ce site en ligne sur Vercel et envoyer le lien à Paola :

### Méthode 1 : Glisser-Déposer (Le plus facile et rapide)
1. Allez sur [vercel.com](https://vercel.com) et connectez-vous (ou créez un compte gratuit).
2. Cliquez sur le bouton **"Add New..."** puis sélectionnez **"Project"**.
3. Au lieu de connecter un dépôt Git, installez l'outil ou glissez simplement le dossier `paola-love-site` directement sur l'interface Vercel si proposé, OU utilisez la méthode CLI/Git ci-dessous.

### Méthode 2 : Déploiement via le Terminal (Vercel CLI)
Si vous avez le terminal sur votre ordinateur ou dans votre environnement de développement :
```bash
# 1. Installez le client Vercel
npm i -g vercel

# 2. Placez-vous dans le dossier du projet
cd paola-love-site

# 3. Lancez le déploiement
vercel
```
Répondez `Y` (Oui) aux questions par défaut. En 10 secondes, Vercel vous donnera une URL sécurisée (par exemple : `https://pour-paola-zibi-love.vercel.app`) !

### Méthode 3 : Via GitHub (Pour mises à jour continues)
1. Créez un dépôt privé ou public sur [GitHub.com](https://github.com) et nommez-le `pour-paola-zibi`.
2. Envoyez les fichiers `index.html` et `vercel.json` sur ce dépôt.
3. Sur Vercel Dashboard, cliquez sur **"Import Project"**, sélectionnez votre dépôt GitHub.
4. Cliquez sur **Deploy** ! Vercel mettra automatiquement à jour votre site à chaque modification.

---

## 🛠️ Comment Personnaliser Facilement

- **Modifier la date officielle de votre couple** : Directement sur le site en cliquant sur le bouton `⚙️ Modifier la date de notre rencontre` (elle est mémorisée automatiquement) ou en éditant la ligne `new Date("2023-01-01T00:00:00")` dans `index.html`.
- **Changer les déclarations d'amour ou le texte de la lettre** : Ouvrez simplement `index.html` avec n'importe quel éditeur de texte (Bloc-notes, VS Code) et modifiez les textes entre guillemets.
- **Remplacer les illustrations par vos vraies photos de couple** : Vous pouvez glisser vos photos dans un dossier `images/` et remplacer les `src="data:image/jpeg;base64,..."` dans le code par `src="images/notre-photo.jpg"`.

Félicitations Dominique ! Paola va être comblée de bonheur. ❤️
