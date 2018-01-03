---
title: Comment démarrer et arrêter la MoodleBox ?
author:
  - Nicolas Martignoni
type: kb
date: 2017-04-17T20:09:27+00:00
slug: demarrer-arreter-redemarrer
categories:
  - Maintenance
  - Utilisation

---
### Démarrer la MoodleBox

Insérer dans la Raspberry Pi 3 la carte microSD (sur laquelle l'image-disque a été copiée) et brancher l’alimentation ainsi qu’un câble ethernet pour la connexion au réseau. La diode rouge s’allume, puis, après quelques secondes, la diode verte s’allume de façon intermittente.

Il n’y a pas d’autre manipulation à effectuer : dès la fin de son démarrage, la MoodleBox est prête et fonctionnelle.

Si possible, il est recommandé de brancher la MoodleBox au réseau câblé lors de chaque démarrage. Ainsi, les tâches de maintenance nécessitant une connexion à Internet (par exemple la synchronisation de l’horloge interne) se feront de manière complète.

### Arrêter la MoodleBox

Afin de limiter au maximum les risques de corruption de données sur la carte microSD, pour éteindre la MoodleBox, il n'est pas recommandé de débrancher l'alimentation sans précaution. Il est préférable de commander manuellement son arrêt au préalable.

Pour ce faire, après s'être connecté comme administrateur dans le Moodle de la MoodleBox, on visite <a href="http://moodlebox.home/admin/tool/moodlebox/index.php" target="_blank" rel="noopener noreferrer">Administration du site > Serveur > MoodleBox</a> dans l'interface d'administration.

<img class="alignnone size-full wp-image-481" src="https://moodlebox.net/fr/wp-content/uploads/sites/4/2017/04/restart-shutdown.png" alt="" width="722" height="111" srcset="https://moodlebox.net/fr/wp-content/uploads/sites/4/2017/04/restart-shutdown.png 722w, https://moodlebox.net/fr/wp-content/uploads/sites/4/2017/04/restart-shutdown-300x46.png 300w" sizes="(max-width: 722px) 100vw, 722px" />

Dans la section **Rédémarrage et arrêt**, l'interface présente deux boutons, permettant de redémarrer et d'arrêter la MoodleBox. Après avoir cliqué sur le bouton **Arrêter la MoodleBox**, patienter quelques secondes et vérifier que la diode verte ne clignote plus. L'alimentation peut alors être débranchée sans risque.

### Redémarrer la MoodleBox

Après s'être connecté comme administrateur dans le Moodle de la MoodleBox, visiter <a href="http://moodlebox.home/admin/tool/moodlebox/index.php" target="_blank" rel="noopener noreferrer">Administration du site > Serveur > MoodleBox</a> dans le bloc d'administration.

Cliquer sur le bouton **Redémarrer la MoodleBox** et patienter quelques secondes, après quoi vous pourrez vous reconnecter à la Moodlebox.