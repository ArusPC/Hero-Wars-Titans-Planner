<a id="haut"></a>
# VERSION ET INTEGRITE-SHA256
### Identité
* PROJET : Hero-Wars-Titans-Planner
* VERSION : v1.01
* AUTEUR : Bubo Band
* Source officielle : https://github.com/ArusPC/Hero-Wars-Titans-Planner/releases/tag/v1.01

## Clé SHA-256
> Le classeur LibreOffice Calc document maître `Hero-Wars-Titans-Planner-v1.01-FR.ods` doit être inclus dans l'archive de distribution. La somme SHA-256 suivante permet de vérifier que l'**archive de distribution** téléchargée correspond exactement à celle publiée officiellement.

**Fichier de l'archive**&nbsp;: `Hero-Wars-Titans-Planner-v1.01-FR.7z`  
**Clé SHA-256&nbsp;:** 14819269478c14a61750884ea411251fde3b638c8b718a7ec417629394860279

## Vérification d'intégrité SHA-256
> Il est fortement conseillé de vérifier l'intégrité du fichier d'archive `Hero-Wars-Titans-Planner-v1.01-FR.7z` avant toute utilisation.  
**Si la vérification échoue, ne considérez pas l'archive comme vérifiée**.
### 🖐️ Vérification manuelle
Repérez la clé SHA-256 de référence indiquée ci-dessus dans la section « Clé SHA-256 », puis comparez-la avec&nbsp;:

* **Windows** (PowerShell)&nbsp;:  
  ```PowerShell
  Get-FileHash "Hero-Wars-Titans-Planner-v1.01-FR.7z" -Algorithm SHA256
  ```
* **Linux**&nbsp;:  
  ```bash
  sha256sum Hero-Wars-Titans-Planner-v1.01-FR.7z
  ```
* **macOS** - La commande native est *shasum -a 256* ; la commande *sha256sum* n'est disponible que si les *GNU Coreutils* ont été installés&nbsp;:
  ```bash
  shasum -a 256 Hero-Wars-Titans-Planner-v1.01-FR.7z
  ```
**La somme SHA-256 affichée doit être identique à celle indiquée ci-dessus dans la section « Clé SHA-256 ».**

### ⚙️ Vérification automatique (Linux et macOS)
Pour vérifier automatiquement l'intégrité de l'archive, téléchargez les deux fichiers suivants depuis la publication officielle sur GitHub&nbsp;:
* `Hero-Wars-Titans-Planner-v1.01-FR.7z`
* `Hero-Wars-Titans-Planner-v1.01-FR.7z.sha256`

Assurez-vous que les deux fichiers correspondent à la même publication officielle et, au besoin, téléchargez-les de nouveau.
**Placez les deux fichiers dans le même dossier**.

**Linux -** Ouvrez un terminal dans ce dossier et exécutez&nbsp;:
```bash
sha256sum -c Hero-Wars-Titans-Planner-v1.01-FR.7z.sha256
```
**macOS -** Ouvrez un terminal dans ce dossier et exécutez&nbsp;:
```bash
shasum -a 256 -c Hero-Wars-Titans-Planner-v1.01-FR.7z.sha256
```

**Résultat attendu :** le message **`OK`** confirme que la somme SHA-256 calculée pour l'archive correspond à la valeur de référence inscrite dans le fichier `Hero-Wars-Titans-Planner-v1.01-FR.7z.sha256`.

[⬆ Retour en haut](#haut)
