# ft_linux (Création d'une distribution Linux From Scratch)


Le but de ce projet est de construire une distribution Linux opérationnel, basé sur [Linux From Scratch](https://fr.linuxfromscratch.org/),
je me suis permis d'ajouter un environnement de bureau appelé GNOME avec divers applications pour une expérience utilisateur optimale.


![blfs](https://github.com/user-attachments/assets/b0b34473-8a43-4bec-87c8-4bed6d0904cb)

Mozilla Firefox est installé en tant que navigateur à gauche, avec à droite NetworkManager, un service qui permet de mettre en place plusieurs des réseaux manuellement et automatiquement, en Wi-Fi ou filaire.


![gdm](https://github.com/user-attachments/assets/836dd6e1-4a66-484d-baf1-a34162614e6c)


![menuconfig](https://github.com/user-attachments/assets/4373aa9c-3348-4e54-9708-1853781eb0ee)

Une distribution Linux pour se lancer nécessite un noyau Linux, avec une configuration précise, la machine a également besoin de divers drivers (comme par exemple pour avoir du son, pour avoir accès à internet ou pour faire fonctionner un périphérique), pour cela, un menu de configuration est disponible,
une fois configuré, la compilation du noyau est possible et le système peut par la suite être lancé comme tout système d'exploitation.

Le téléchargement d'un noyau Linux vanilla peut se faire depuis le site kernel.org: [git Linus Torvalds](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/).


![grub](https://github.com/user-attachments/assets/83bdca12-98d1-4eba-a352-a9eb4da6f50f)

Un programme d'amorçage est également installé pour permettre le lancement de multiples systèmes d'exploitation, ici Linux avec une version 6.7 et une version 6.11 non-stable.
