---
title: Où télécharger l’image-disque ?
author:
  - Nicolas Martignoni
type: kb
date: 2017-04-17T19:19:44+00:00
slug: telecharger-limage-disque
permalink:
  - /help/telecharger-limage-disque/
categories:
  - Premiers pas
aliases:
  - fr/dl

---
### Image disque MoodleBox

<ul class="downloads">
  <li>
  <div class="image-icon">
    <a class="piwik_download" href="{{< ghrelease user="martignoni" repo="moodlebox" data="download_link" >}}"><img class="alignnone wp-image-308 size-full" src="https://moodlebox.net/fr/wp-content/uploads/sites/4/2016/09/MoodleBox-SD-150x150-orange-1.png" width="150" height="150"></a>
  </div>
  <div class="image-info">
    <div class="image-description">
      Image disque MoodleBox pour carte microSD
    </div>
    <div class="image-details">
      Version : <strong>{{< ghrelease user="martignoni" repo="moodlebox" data="version" >}}</strong>
    </div>
    <div class="image-details">
      Version de Moodle : <strong>3.4+ (Build: 20171123)</strong>
    </div>
    <div class="image-details">
      Taille : <strong>{{< ghrelease user="martignoni" repo="moodlebox" data="file_size" >}} Mo</strong>
    </div>
    <div class="image-details">
      Date : <strong>{{< ghrelease user="martignoni" repo="moodlebox" data="file_date" >}}</strong>
    </div>
    <div class="image-details">
      Notes de mise à jour : <strong><a href="https://github.com/martignoni/moodlebox/blob/master/CHANGELOG.md" target="_blank">sur Github</a></strong>
    </div>
    <div class="image-download-links">
      <a class="btn dl-zip piwik_download" href="{{< ghrelease user="martignoni" repo="moodlebox" data="download_link" >}}">Télécharger</a>
    </div>
 </div>
 </li>
</ul>

Après avoir téléchargé l’image-disque, suivez les [instructions pour la copier sur la carte microSD][1] et [démarrez votre MoodleBox][2]. Consultez les [instructions d'installation][5] pour plus d'informations.

Si vous le souhaitez, vous pouvez [soutenir le développement de la MoodleBox][3] en faisant un don, tout à fait facultatif.

L’[image-disque MoodleBox][4]{.piwik_download} est construite sur la base de la distribution <a href="https://www.raspberrypi.org/downloads/raspbian/" target="_blank" rel="noopener noreferrer">Raspbian Stretch Lite pour Raspberry Pi</a>.

### En cas de difficulté

En cas de difficulté de téléchargement, on peut utiliser la ligne de commande pour télécharger l'image-disque, soit avec la commande

`wget -c {{< ghrelease user="martignoni" repo="moodlebox" data="download_link" >}}`

soit avec celle-ci :

`curl -C - {{< ghrelease user="martignoni" repo="moodlebox" data="download_link" >}}`

 [1]: {{< relref "copy-the-disk-image-on-a-sd-card.fr.md" >}}
 [2]: {{< relref "startup-shutdown-restart.fr.md" >}}
 [3]: {{< relref "support-the-moodlebox-project.fr.md" >}}
 [4]: {{< ghrelease user="martignoni" repo="moodlebox" data="download_link" >}}
 [5]: {{< relref "install-the-moodlebox.fr.md" >}}