# SLFTP Instance Manager

This project allows you to easily and user-friendly manage multiple instances of SLFTP. With this instance manager, you can easily start, stop, restart, check the status of any SLFTP instance, and even connect to a `screen` session where the instance is running.

## Installation

Installing the SLFTP instance manager is quite simple. You can install it directly from this GitHub repository using `curl` or `wget`.

### Using curl

Run the following command in your terminal:

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

### Using wget

Or, if you prefer using `wget`, you can use the following command:

```bash
sh -c "$(wget -O- https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

These commands download the installation script and execute it in a shell. During installation, if the script is run without the full path to the `slftp` binary or the instance name, the script will prompt you to provide them.

## Usage

Once you have installed the SLFTP instance manager, you can manage your SLFTP instances with the `slftp-insmgr` command and one of the following arguments: `self-install`, `self-uninstall`, `self-update`, `slftp-install`.

```bash
slftp-insmgr self-install   # Install 'SLFTP - Instance Manager' (this script) permanently
slftp-insmgr self-uninstall # Uninstall 'SLFTP - Instance Manager' (this script)
slftp-insmgr self-update    # Update 'SLFTP - Instance Manager' (this script) from the GitHub repository
slftp-insmgr slftp-install  # Download and install SLFTP (from the SLFTP GitLab repository)
```

## Supporting Development

This project is entirely free and open source. If you find it helpful, you can support its development by donating on the [donation page](https://github.com/ZarTek-Creole/DONATE). Any contribution, no matter how small, is highly appreciated.

## License

The SLFTP instance manager is an open source project licensed under the [MIT](LICENSE) license.

## Contact

If you have any questions or comments, feel free to open an [issue](https://github.com/ZarTek-Creole/SLFTP-Instance-Manager/issues) on this GitHub repository.

Thank you for choosing the SLFTP instance manager. You're the best!

---

# Dependencies

To use the SLFTP instance manager, you need to have the following tools installed on your system:

- `bash`
- `systemd`
- `screen`
- `curl` or `wget` (for downloading the installation script)

You can check the presence of these tools on your system using the `command -v` command. For example, to check if `systemd` is installed, use `command -v systemctl`.

# SLFTP Instance Manager

Ce projet vous permet de gérer facilement et de manière conviviale plusieurs instances de SLFTP. Avec ce gestionnaire d'instances, vous pouvez facilement démarrer, arrêter, redémarrer, vérifier l'état de n'importe quelle instance de SLFTP, et même vous connecter à une session `screen` où l'instance est en cours d'exécution.

## Installation

L'installation du gestionnaire d'instances SLFTP est assez simple. Vous pouvez l'installer directement à partir de ce dépôt GitHub en utilisant `curl` ou `wget`.

### Utilisation de curl

Exécutez la commande suivante dans votre terminal :

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

### Utilisation de wget

Ou, si vous préférez utiliser `wget`, vous pouvez utiliser la commande suivante :

```bash
sh -c "$(wget -O- https://raw.githubusercontent.com/ZarTek-Creole/SLFTP-Instance-Manager/main/slftp-insmgr)" -- self-install
```

Ces commandes téléchargent le script d'installation et l'exécutent dans un shell. Pendant l'installation, si le script est exécuté sans le chemin complet vers le binaire `slftp` ou le nom de l'instance, le script vous demandera de les fournir.

## Utilisation

Une fois que vous avez installé le gestionnaire d'instances SLFTP, vous pouvez gérer vos instances SLFTP avec la commande `slftp-insmgr` et l'un des arguments suivants : `self-install`, `self-uninstall`, `self-update`, `slftp-install`.

```bash
slftp-insmgr self-install   # Installe 'SLFTP - Instance Manager' (ce script) de manière permanente
slftp-insmgr self-uninstall # Désinstalle 'SLFTP - Instance Manager' (ce script)
slftp-insmgr self-update    # Met à jour 'SLFTP - Instance Manager' (ce script) depuis le dépôt GitHub
slftp-insmgr slftp-install  # Télécharge et installe SLFTP (depuis le dépôt GitLab de SLFTP)
```

## Supporter le développement

Ce projet est entièrement gratuit et open source. Si vous le trouvez utile, vous pouvez soutenir son développement en faisant un don sur la [page de don](https://github.com/ZarTek-Creole/DONATE). Toute contribution, si petite soit-elle, est très appréciée.

## Licence

Le gestionnaire d'instances SLFTP est un projet open source sous licence [MIT](LICENSE).

## Contact

Si vous avez des questions ou des commentaires, n'hésitez pas à ouvrir une [issue](https://github.com/ZarTek-Creole/SLFTP-Instance-Manager/issues) sur ce dépôt GitHub.

Merci d'avoir choisi le gestionnaire d'instances SLFTP. Vous êtes le meilleur !

---

# Dépendances

Pour utiliser le gestionnaire d'instances SLFTP, vous devez avoir les outils suivants installés sur votre système :

- `bash`
- `systemd`
- `screen`
- `curl` ou `wget` (pour le téléchargement du script d'installation)

Vous pouvez vérifier la présence de ces outils sur votre système en utilisant la commande `command -v`. Par exemple, pour vérifier si

 `systemd` est installé, utilisez `command -v systemctl`.
