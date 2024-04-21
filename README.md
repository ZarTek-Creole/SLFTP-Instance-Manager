# SLFTP Instance Manager

This project allows you to easily and user-friendly manage multiple instances of SLFTP. With this instance manager, you can start, stop, restart, check the status of any SLFTP instance, and even connect to a `screen` session where the instance is running.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Dependencies](#dependencies)
4. [Supporting Development](#supporting-development)
5. [License](#license)
6. [Contact](#contact)

## Installation

Installing the SLFTP instance manager is straightforward. Install it directly from this GitHub repository using `curl` or `wget`.

### Using curl

Execute the following command in your terminal:

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

### Using wget

Alternatively, if you prefer using `wget`, use the following command:

```bash
sh -c "$(wget -O- https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

These commands download the installation script and execute it in a shell. During installation, if the script is run without the full path to the `slftp` binary or the instance name, you will be prompted to provide them.

## Usage

After installing the SLFTP instance manager, manage your SLFTP instances with the `slftp-insmgr` command and one of the following arguments:

```bash
slftp-insmgr self-install   # Install 'SLFTP - Instance Manager' permanently
slftp-insmgr self-uninstall # Uninstall 'SLFTP - Instance Manager'
slftp-insmgr self-update    # Update 'SLFTP - Instance Manager' from the GitHub repository
slftp-insmgr slftp-install  # Download and install SLFTP (from the SLFTP GitLab repository)
```

## Dependencies

To use the SLFTP instance manager, ensure these tools are installed on your system:

- `bash`
- `systemd`
- `screen`
- `curl` or `wget` (for downloading the installation script)

You can check the presence of these tools on your system with `command -v`. For instance, to verify if `systemd` is installed, use:

```bash
command -v systemctl
```

## Supporting Development

This project is entirely free and open source. If you find it helpful, consider supporting its development by donating on the [donation page](https://github.com/ZarTek-Creole/DONATE). Any contribution, no matter how small, is greatly appreciated.

## License

The SLFTP instance manager is an open source project licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or comments, feel free to open an [issue](https://github.com/ZarTek-Creole/SLFTP-Instance-Manager/issues) on this GitHub repository.

Thank you for choosing the SLFTP instance manager. You're the best!

---

# Gestionnaire d'instances SLFTP

Ce projet vous permet de gérer facilement et de manière conviviale plusieurs instances de SLFTP. Avec ce gestionnaire d'instances, vous pouvez démarrer, arrêter, redémarrer, vérifier l'état de n'importe quelle instance de SLFTP, et même vous connecter à une session `screen` où l'instance est en cours d'exécution.

## Table des matières

1. [Installation](#installation)
2. [Utilisation](#utilisation)
3. [Dépendances](#dépendances)
4. [Soutenir le développement](#soutenir-le-développement)
5. [Licence](#licence)
6. [Contact](#contact)

## Installation

L'installation du gestionnaire d'instances SLFTP est simple. Installez-le directement à partir de ce dépôt GitHub en utilisant `curl` ou `wget`.

### Utilisation de curl

Exécutez la commande suivante dans votre terminal :

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

### Utilisation de wget

Ou, si vous préférez utiliser `wget`, utilisez la commande suivante :

```bash
sh -c "$(wget -O- https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

Ces commandes téléchargent le script d'installation et l'exécutent dans un shell. Pendant l'installation, si le script est

 exécuté sans le chemin complet vers le binaire `slftp` ou le nom de l'instance, il vous sera demandé de les fournir.

## Utilisation

Après l'installation du gestionnaire d'instances SLFTP, gérez vos instances SLFTP avec la commande `slftp-insmgr` et l'un des arguments suivants :

```bash
slftp-insmgr self-install   # Installe 'SLFTP - Instance Manager' de manière permanente
slftp-insmgr self-uninstall # Désinstalle 'SLFTP - Instance Manager'
slftp-insmgr self-update    # Met à jour 'SLFTP - Instance Manager' depuis le dépôt GitHub
slftp-insmgr slftp-install  # Télécharge et installe SLFTP (depuis le dépôt GitLab de SLFTP)
```

## Dépendances

Pour utiliser le gestionnaire d'instances SLFTP, assurez-vous que ces outils sont installés sur votre système :

- `bash`
- `systemd`
- `screen`
- `curl` ou `wget` (pour télécharger le script d'installation)

Vous pouvez vérifier la présence de ces outils sur votre système avec `command -v`. Par exemple, pour vérifier si `systemd` est installé, utilisez :

```bash
command -v systemctl
```

## Soutenir le développement

Ce projet est entièrement gratuit et open source. Si vous le trouvez utile, envisagez de soutenir son développement en faisant un don sur la [page de don](https://github.com/ZarTek-Creole/DONATE). Toute contribution, si petite soit-elle, est très appréciée.

## Licence

Le gestionnaire d'instances SLFTP est un projet open source sous licence [MIT](LICENSE).

## Contact

Si vous avez des questions ou des commentaires, n'hésitez pas à ouvrir une [issue](https://github.com/ZarTek-Creole/SLFTP-Instance-Manager/issues) sur ce dépôt GitHub.

Merci d'avoir choisi le gestionnaire d'instances SLFTP. Vous êtes le meilleur !
