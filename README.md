<p align="center">
  <img src="https://aevum-launcher.fr/assets/logo-mark.png" width="110" alt="Aevum Launcher">
</p>

<h1 align="center">Aevum Launcher</h1>

<p align="center">
  <strong>Trouve ton prochain serveur Minecraft et rejoins-le en un clic.</strong><br>
  Vanilla ou moddé : Aevum installe le jeu, Java, le loader et les mods pour toi.
</p>

<p align="center">
  <a href="https://github.com/AEVUM-Launcher/Launcher-update/releases/latest"><img src="https://img.shields.io/github/v/release/AEVUM-Launcher/Launcher-update?style=for-the-badge&label=version&color=25d4e4" alt="Dernière version"></a>
  <a href="https://github.com/AEVUM-Launcher/Launcher-update/releases"><img src="https://img.shields.io/github/downloads/AEVUM-Launcher/Launcher-update/total?style=for-the-badge&color=25d4e4" alt="Téléchargements"></a>
  <a href="https://discord.gg/XqM8DKAS5Z"><img src="https://img.shields.io/badge/Discord-rejoindre-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
</p>

<p align="center">
  <a href="https://aevum-launcher.fr">Site officiel</a> ·
  <a href="https://github.com/AEVUM-Launcher/Launcher-update/releases/latest">Télécharger</a> ·
  <a href="https://discord.gg/XqM8DKAS5Z">Support</a> ·
  <a href="#english">English</a>
</p>

<p align="center">
  <img src="https://aevum-launcher.fr/assets/launcher-catalogue.png" width="900" alt="Catalogue de serveurs dans Aevum Launcher">
</p>

---

## 📥 Télécharger

Les fichiers d'installation se trouvent dans la **[dernière release](https://github.com/AEVUM-Launcher/Launcher-update/releases/latest)**, section *Assets*.

| Système | Fichier à prendre |
|---|---|
| **Windows 10 / 11** | `Aevum-Launcher-setup-x.y.z.exe` |
| **macOS** (Apple Silicon : M1, M2, M3…) | `Aevum-Launcher-setup-x.y.z-arm64.dmg` |
| **macOS** (Intel) | `Aevum-Launcher-setup-x.y.z-x64.dmg` |
| **Linux** (Debian, Ubuntu, Mint…) | `Aevum-Launcher-setup-x.y.z.deb` |
| **Linux** (autres distributions) | `Aevum-Launcher-setup-x.y.z.AppImage` |

> Les fichiers `.blockmap`, `.zip` et `latest*.yml` servent aux mises à jour automatiques : tu n'as pas besoin de les télécharger.

**Le launcher est gratuit.** Jouer ne demande ni abonnement ni achat.

## 🛠️ Installation

**Windows** : lance le `.exe`. Si Windows SmartScreen affiche un avertissement, clique sur *Informations complémentaires* puis *Exécuter quand même*.

**macOS** : ouvre le `.dmg` et glisse Aevum Launcher dans *Applications*. Si macOS bloque la première ouverture, fais un clic droit sur l'application puis *Ouvrir*.

**Linux (.deb)** :
```bash
sudo apt install ./Aevum-Launcher-setup-x.y.z.deb
```

**Linux (.AppImage)** :
```bash
chmod +x Aevum-Launcher-setup-x.y.z.AppImage
./Aevum-Launcher-setup-x.y.z.AppImage
```

Une fois installé, **le launcher se met à jour tout seul** à chaque nouvelle version.

## 🔐 Vérifier ton téléchargement

Les installateurs ne sont pas encore signés numériquement, d'où les avertissements de Windows et macOS. À partir de la prochaine version, chaque release contient un fichier **`SHA256SUMS.txt`** avec l'empreinte de chaque installateur. Compare-la avec celle du fichier que tu as téléchargé :

- **Windows (PowerShell)** : `Get-FileHash .\Aevum-Launcher-setup-x.y.z.exe`
- **macOS** : `shasum -a 256 Aevum-Launcher-setup-x.y.z-arm64.dmg`
- **Linux** : `sha256sum -c SHA256SUMS.txt --ignore-missing`

Si l'empreinte ne correspond pas, ne lance pas le fichier et préviens-nous sur Discord.

## 🧩 Sécurité des mods

- Les mods **CurseForge** et **Modrinth** sont reconnus par leur empreinte et téléchargés depuis ces plateformes.
- Les mods ajoutés par un créateur **non vérifié** sont validés par l'équipe avant d'être distribués aux joueurs.
- Le launcher contrôle l'empreinte de **chaque fichier** téléchargé (mods, configs, bibliothèques) et rejette tout fichier modifié ou incomplet.

## ✨ Ce que fait Aevum

- 🔎 **Un catalogue de serveurs** vanilla et moddés, à parcourir par style et par langue.
- ⭐ **Des avis et des votes** de la communauté pour choisir avant de rejoindre.
- ⚡ **Jouer en un clic** : Java, le loader (Forge, NeoForge, Fabric…) et les mods sont installés et vérifiés automatiquement.
- 👥 **Amis et messages** pour voir sur quel serveur jouent tes amis.
- 🧰 **Un espace créateur** pour ajouter ton serveur gratuitement et le gérer depuis le launcher.
- 🔐 **Connexion Microsoft officielle** : ton mot de passe n'est jamais envoyé à Aevum.
- 💻 **Windows, macOS et Linux.**

## 🧱 Tu as un serveur ?

Télécharge Aevum, ouvre l'**espace Créateur** et crée ta fiche. Un serveur vanilla peut être ajouté en quelques minutes, sans exclusivité : tu gardes ton site, ton Discord et tes outils.

## 🐞 Un problème ?

- Bug, version ou loader manquant : **[ouvre un ticket sur Discord](https://discord.gg/XqM8DKAS5Z)**.
- Le jeu ne se lance pas : dans le launcher, va dans *Paramètres → À propos → Réparer les fichiers du jeu*.

> ⚠️ Aevum est encore en développement : n'hésite pas à signaler ce qui ne va pas !

## 🔒 À propos de ce dépôt

Ce dépôt sert uniquement à **publier les versions officielles** d'Aevum Launcher (installateurs et fichiers de mise à jour automatique). Le code source d'Aevum est **propriétaire** et n'est pas publié ici.

Aevum Launcher s'appuie sur le projet open source [Helios Launcher](https://github.com/dscalzi/HeliosLauncher) de Daniel D. Scalzi, distribué sous licence MIT.

## 📄 Informations légales

[Mentions légales](https://aevum-launcher.fr/legal/mentions-legales.html) ·
[Confidentialité](https://aevum-launcher.fr/legal/confidentialite.html) ·
[CGU](https://aevum-launcher.fr/legal/cgu.html) ·
[CGV](https://aevum-launcher.fr/legal/cgv.html) ·
[Remboursement](https://aevum-launcher.fr/legal/remboursement.html)

Aevum Launcher est un projet indépendant. Ce n'est pas un produit officiel Minecraft : il n'est ni approuvé par Mojang Studios ou Microsoft, ni associé à eux.

---

<a id="english"></a>

## 🇬🇧 English

**Aevum Launcher** helps you find your next Minecraft server and join it in one click. Vanilla or modded, Aevum installs the game, Java, the loader and the mods for you. **It's free**: playing requires no subscription or purchase.

### Download

Grab the installer from the **[latest release](https://github.com/AEVUM-Launcher/Launcher-update/releases/latest)** (*Assets* section):

| System | File |
|---|---|
| **Windows 10 / 11** | `Aevum-Launcher-setup-x.y.z.exe` |
| **macOS** (Apple Silicon) | `Aevum-Launcher-setup-x.y.z-arm64.dmg` |
| **macOS** (Intel) | `Aevum-Launcher-setup-x.y.z-x64.dmg` |
| **Linux** (Debian/Ubuntu) | `Aevum-Launcher-setup-x.y.z.deb` |
| **Linux** (other) | `Aevum-Launcher-setup-x.y.z.AppImage` |

The `.blockmap`, `.zip` and `latest*.yml` files are used by the auto-updater; you don't need them. Once installed, the launcher **updates itself**.

### Verify your download

Installers are not code-signed yet, which is why Windows and macOS show warnings. Starting with the next version, every release includes a **`SHA256SUMS.txt`** file listing each installer's fingerprint. Compare it with your file (`Get-FileHash` on Windows, `shasum -a 256` on macOS, `sha256sum -c SHA256SUMS.txt --ignore-missing` on Linux). If it doesn't match, don't run the file and let us know on Discord.

### Mod safety
