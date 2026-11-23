# Site web de Oche Up!

Site statique de l'application iOS **Oche Up!** (accueil, assistance, politique de confidentialité), en français et en anglais,
publié avec GitHub Pages (Settings → Pages → Source : **GitHub Actions** ; un push sur `main` déploie `website/`).

```
website/
  index.html  assistance.html  confidentialite.html      français
  en/index.html  en/support.html  en/privacy.html        English
  css/style.css  assets/  CNAME (ocheup.jepico.fr)
```

Adresses pour App Store Connect : voir `appstore/textes-fiche.md` dans le dépôt de l'app.
DNS (OVH, zone `jepico.fr`) : CNAME `ocheup` → `jet4git.github.io.`.
Toute modification de contenu se fait dans **les deux langues**. Prévisualiser : `cd website && python3 -m http.server 8000`.
À faire à la publication : remplacer le badge « Bientôt sur l'App Store » par le lien de la fiche.
