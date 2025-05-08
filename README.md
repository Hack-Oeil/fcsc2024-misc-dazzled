# FCSC 2024 Dazzled

Une éclairagiste vous met au défi de reconstituer une animation d’un spectacle stockée sur son enregistreur DMX. Elle vous informe que cette fois elle a utilisé des projecteurs motorisés (exemple : https://youtu.be/N-eTCKjO9xc) pour dessiner des symboles sur une toile posée au sol.

Vous réalisez alors une capture réseau (```capture.pcap```) en vous branchant en Ethernet sur son enregistreur.

Pour vous aider, elle vous donne un extrait de la documentation d’un projecteur (```projector.pdf```) ainsi qu’un schéma de sa scène :

```
=================================== Top view ===================================

                                          0.57m
                                       |-----------|
            ._____.     ._____.     ._____.     ._____.
            | 001 |     | 009 |     | 017 |     | 025 |  ---
            |_____|     |_____|     |_____|     |_____|   |
                                                          |
                                                          | 0.67m
            ._____.     ._____.     ._____.     ._____.   |
            | 033 |     | 041 |     | 049 |     | 057 |  _|_
            |_____|     |_____|     |_____|     |_____|


            ._____.     ._____.     ._____.     ._____.
            | 065 |     | 073 |     | 081 |     | 089 |
            |_____|     |_____|     |_____|     |_____|


            ._____.     ._____.     ._____.     ._____.
            | 097 |     | 105 |     | 113 |     | 121 |
            |_____|     |_____|     |_____|     |_____|




================================== Front view ==================================

(stage left)                                           (stage right)
            ._____.     ._____.     ._____.     ._____.
            |_097_|     |_105_|     |_113_|     |_121_|
            |/   \|     |/   \|     |/   \|     |/   \|  ___
             \_O_/       \_O_/       \_O_/       \_O_/    |
                                                          |
                                                          |
                                                          |
                                                          |
                                                          |
                                                          | Height: 2.8m
                                                          |
                                                          |
                                                          |
                                                          |
                                                          |
                                                          |
          Spot size: ~16°                                 |
                                                         _|_
       -----------------------------------------------------------
_______| praticable                                              |________
```


Releverez-vous le défi ?

**Notes :**

10 secondes après le début de l’animation, les projecteurs dessinent la lettre « F » au sol.
“Spot size: ~16°” correspond à l’angle du cône créé par le faisceau lumineux d’un projecteur.
Tous les projecteurs sont identiques, même orientation, ils ne sont que translatés l’un de l’autre (comme ce que ferait une régie sur une vraie scène pour se simplifier la vie).
Nous vous conseillons de ne pas réimplémenter un moteur 3D.
La capture réseau contient également un flux audio RTP qui ne fait pas partie de l’épreuve. Ce son permet de mieux profiter de l’animation une fois reconstituée.
Une variante plus facile de cette épreuve est disponible : ```Illuminated```.



Auteur : erdnaxe

Origine : [Dazzled](https://hackropole.fr/fr/challenges/misc/fcsc2024-misc-dazzled/)


Fichiers:
- [capture.pcap](capture.pcap)
- [projector.pdf](projector.pdf)



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-misc-dazzled.git

> cd fcsc2024-misc-dazzled


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/misc/fcsc2024-misc-dazzled/