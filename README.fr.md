# Github Achievements

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Tous les badges GitHub expliqués + un bac à sable pour les débloquer

Chaque insigne, chaque niveau

Insigne Comment le gagner
|---|---|---|
Fermer un numéro dans les 5 minutes suivant son ouverture
**YOLO**
Requêtes de tirage de fusion 2 / 16 / 128 / **1024**
**Pair Extraordinaire**
Réponses acceptées dans les discussions
* Starstruck * Stars on your repose * 16 / 128 / **512** / 4096
**Open Sourcerer**
**Heart On Your Sleeve**
**Promoteur public**
**Membre du programme Développeur**
**Mars 2020 / Arctic Code Vault**

Le chemin le plus rapide vers chaque insigne

Tirer rapidement (2 minutes)*
Ouvrez un problème dans l'un de vos repos → fermez immédiatement. Les déclencheurs d'insigne au prochain scan.

* (2 minutes)*
Ouvrir un PR sur votre repo → le fusionner **sans demander de révision**. C'est fait.

Pull Shark * (le badge de broyage)*
Chaque PR fusionné compte — y compris sur votre propre repos. Scripter la boucle create/merge et la ralentir sous la limite anti-abuse (~10-15 fusions/min soutenues, ou GitHub bloque temporairement la création de contenu).

Paire Extraordinaire * (le sournois)*
Le trailer `Co-authored-by:` doit être dans **les commits du PR**, et non le commit de fusion:
```
Co-authored-by: friend <12345+theiruser@users.noreply.github.com>
```
Chaque PR fusionné avec un commit co-auteur compte une fois vers le 48.

* (celui qui mord en arrière) *
Les discussions doivent avoir une catégorie **Q&A** et quelqu'un doit *accepter* votre réponse. Marquer votre propre réponse sur votre propre discussion **ne compte pas** — l'acceptation doit provenir de l'auteur de la discussion ou d'un autre responsable. Les approches à deux comptes ou communautaires fonctionnent.

Starstruck *(ne peut pas être falsifié)*
Les étoiles proviennent de vrais utilisateurs — expédiez quelque chose que les gens veulent, faites la promotion dans les bons endroits. Le projet frère de cette repo [Snitch](https://github.com/aixisstudio/Snitch) est un exemple vivant.

La boîte à sable

Cette repo a un robot ** auto-merger** (processus `pull_request_target`). Pour gagner l'activité YOLO/Pull Shark en toute sécurité *ici*:

1. Fourche cette repo
2. Modifier le `sandbox.md` dans votre fourche (ajouter une ligne — n'importe quoi)
3. Ouvrir un PR ** qui ne touche que `sandbox.md`**
4. Le bot le fusionne automatiquement — vérifiez votre compte fusion-PR

> Seuls les changements `sandbox.md` sont fusionnés automatiquement, pour des raisons de sécurité évidentes.

FAQ

- **Quand les badges apparaissent-ils?** GitHub recalcule les réalisations en lots — de quelques heures à environ 3 jours après l'activité de déclenchement.
- **Mise à niveau?** Oui — le badge s'élève automatiquement lorsque vous franchissez les seuils.
- Je peux perdre un badge ? Les badges basés sur le niveau (Starstruck, Pull Shark, Pair Extraordinaire, Galaxy Brain) recalculent – tomber sous un seuil vous démote. Supprimé repos arrêt de compter.
- **Est-ce contre les règles?** Le TOS de GitHub interdit les pourriels et les abus. Les badges sont cosmétiques, les normes communautaires sont ce qu'ils sont. Pratiquer de façon responsable — un profil avec le diamant Pull Shark et 3 adeptes soulève les sourcils, et non l'admiration.

Mécanique vérifiée (test communautaire)

Ce qui compte Qu'est-ce qui ne va pas
|---|---|---|
Pull Shark , PR fusionné sur n'importe quelle repo que vous ne possédez pas... ou qui possède , retourne , brouillons ,
Paire Extraordinaire `Co-authored-by:` dans le commit de fusion
Galaxy Brain Réponse acceptée dans la discussion sur les questions-réponses
Un cœur sur votre manche Toute réaction sur votre contenu Réactions sur les autres
Fusionner avec zéro avis demandé

La réalité des limites de taux

GitHub recalcule les réalisations sur un cron retardé — les fusions au badge peuvent prendre 24-48h. La vitrine `/settings/appearance` peut prendre du temps une semaine. Ne paniquez pas si une action terminée ne s'affiche pas instantanément.

Agriculture éthique

- Une repo privée de bac à sable vous donne Pull Shark/YOLO/Pair légitimement — c'est votre propre repo, vos propres PR.
- Galaxy Cerveau exige vraiment la question d'un autre humain OU un second compte vous demandant.
- Heart On Your Sleeve a besoin de vraies personnes qui réagissent.

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
