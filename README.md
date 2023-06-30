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
