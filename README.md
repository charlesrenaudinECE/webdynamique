# webdynamique
# 🌐 Vie d’ECE — Projet Web Dynamique

Projet réalisé dans le cadre du cours de Programmation Web Dynamique à l’ECE, année universitaire 2024–2025.

> Clone du site [Vie de Merde](https://www.viedemerde.fr), adapté à la vie étudiante de l’ECE.

---

## 👨‍💻 Membres du groupe (pseudonyme)

- **Charles**
- **Pierre-Olive**
- **Ahmed Yanis Moulache**
- **Volodimir**

---

## 🎯 Objectif du projet

Développer un site dynamique en **PHP**, **MySQL** et **Bootstrap** permettant aux utilisateurs :
- de publier des anecdotes ("VdECE")
- de les consulter
- de commenter
- de naviguer avec une pagination
- de publier des commentaires sans recharger la page (AJAX)

---

## 🧱 Fonctionnalités

| Fonction                     | Description |
|-----------------------------|-------------|
| Page d’accueil              | Liste paginée des anecdotes |
| Ajouter une VdECE           | Formulaire d’ajout (pseudo + contenu) |
| Voir une VdECE              | Détail + commentaires |
| Ajouter un commentaire      | Formulaire de commentaire avec pseudo |
| AJAX                        | Envoi du commentaire sans recharger la page |
| Bootstrap                   | Mise en page responsive et propre |
| Sessions                    | Pseudo retenu automatiquement pour les formulaires |

---

## 🗃️ Structure du projet

```bash
viedece/
│
├── index.php              # Page d’accueil
├── add_vdece.php          # Formulaire d’ajout d’anecdote
├── show_vdece.php         # Affichage d’une VdECE + commentaires
├── add_comment.php        # Script d’ajout de commentaire (AJAX + fallback)
├── config.php             # ⚠️ Fichier perso, à ne pas versionner
├── config.dist.php        # Exemple de config (BDD, utilisateur)
├── code.sql               # Export de la structure de la base (via phpMyAdmin)
├── README.md              # Ce fichier
 
