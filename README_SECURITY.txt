Pack sécurité pour le dépôt `moonrushbase.base`

Contenu:
- SECURITY.md : Politique de divulgation responsable (avec contact et clé PGP placeholder).
- .github/ISSUE_TEMPLATE/security.md : Template d'issue privée pour signaler une vulnérabilité.
- .github/CODEOWNERS : Fichier pour assigner automatiquement les mainteneurs (remplacez @hawaniabuilder si nécessaire).

Installation rapide :
1. Déplacez les fichiers à la racine de votre dépôt GitHub.
2. Poussez un commit :
   git add SECURITY.md .github/ISSUE_TEMPLATE/security.md .github/CODEOWNERS README_SECURITY.txt
   git commit -m "Add security pack: SECURITY.md, issue template, CODEOWNERS"
   git push

Remarques :
- Remplacez le bloc PGP placeholder par votre vraie clé PGP si nécessaire.
- Vérifiez le contenu de CODEOWNERS et remplacez le GitHub handle si besoin.
