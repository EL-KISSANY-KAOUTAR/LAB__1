LAB 1 : Mise en place du lab (Mobexler + snapshot clean)

Objectif : 

Importer la VM Mobexler dans VirtualBox, configurer le réseau, vérifier le bon fonctionnement et créer un snapshot de référence (baseline propre).


Étape 1 — Téléchargement de Mobexler (OVA)

Télécharger l'image virtuelle Mobexler au format OVA puis vérifier son intégrité avant l'importation dans VirtualBox.

1. Téléchargement de l'OVA

1.1 Téléchargement

Télécharger l'image virtuelle depuis le lien officiel

<img width="278" height="83" alt="image" src="https://github.com/user-attachments/assets/cbf7fad7-707a-43f4-af9d-8f0c8eb3ffef" />

Après le téléchargement, le fichier Mobexler.ova est présent sur la machine locale.

Étape 2 — Importer l’OVA dans VirtualBox/VMware

Étape 2 — Importation dans VirtualBox
2.1 Import de l'OVA

Ouvrir VirtualBox

 - Cliquer sur File → Import Appliance
 - Sélectionner le fichier Mobexler.ova
 - Cliquer sur Next, puis Import
 - Attendre la fin de l'importation


2. Configuration réseau

Après l'importation :

Sélectionner la VM Mobexler.
Cliquer sur Settings → Network.
Adaptateur 1 : NAT
Adaptateur 2 : Host-Only Adapter

Étape 3 — Premier démarrage + connexion

<img width="231" height="247" alt="image" src="https://github.com/user-attachments/assets/804939fb-6699-4923-98d5-83d3c56402d8" />

La machine virtuelle a démarré correctement et affiche l'écran d'authentification. Le mot de passe utilisé est mobexler conformément à la documentation du laboratoire. L'accès au système a été effectué avec succès.

Étape 4 — Vérifier le réseau (tests “santé”)

<img width="363" height="60" alt="image" src="https://github.com/user-attachments/assets/c72f663c-a115-4399-9652-553b6bd93e8c" />

Ping vers 8.8.8.8 réussi.

Étape 5 — Créer le snapshot “CLEAN” (baseline)

Depuis la fenêtre de VirtualBox, sélectionner le menu VM.

<img width="157" height="163" alt="image" src="https://github.com/user-attachments/assets/3d1a1dac-b443-476e-b22f-22b8d33cc22d" />

Dans le menu VM, cliquer sur Snapshot afin d'ouvrir le gestionnaire de snapshots.

<img width="112" height="40" alt="image" src="https://github.com/user-attachments/assets/abc22f0c-cc8b-42e1-9cde-087b00d06408" />

<img width="360" height="232" alt="image" src="https://github.com/user-attachments/assets/f66bbd0c-fcf8-4c80-b29c-425c4418e7c2" />






