# Story 11 : Choix d’une solution MDM

Tableau Comparatif

| Critères             | Microsoft Intune (Endpoint Manager)                        | ManageEngine MDM Plus                                           |
| -------------------- | ---------------------------------------------------------- | --------------------------------------------------------------- |
| **Écosystème**       | Parfaitement intégré à Microsoft 365 / Azure AD.           | Agnostique, s'intègre bien aux environnements hybrides.         |
| **Gestion Android**  | Supporte Android Enterprise (Work Profile, Fully Managed). | Support complet Android Enterprise et Samsung Knox.             |
| **Facilité d'usage** | Interface complexe (Azure), nécessite une expertise.       | Interface intuitive, plus rapide à prendre en main.             |
| **Sécurité**         | Accès conditionnel puissant (lié à l'identité).            | Fort focus sur l'inventaire et le contrôle à distance.          |
| Coût                 | Inclus dans les licences M365 Business Premium/E3/E5.      | Version gratuite jusqu'à 25 appareils, puis licence par device. |

La solution que nous recommandons est Microsoft Intune. Il a été choisi pour sa capacité à isoler les données professionnelles via un profil de travail (Android Enterprise), empêchant ainsi les fuites vers des applications personnelles non autorisées. Grâce à ses politiques d'accès Conditionnel, Intune permet de bloquer automatiquement l'accès aux ressources de l'entreprise si l'appareil est détecté comme rooté ou si le déverrouillage biométrique est désactivé. Sa parfaite intégration à l'écosystème Microsoft 365 offre une console d'administration centralisée, garantissant une mise en conformité continue et une réactivité immédiate en cas de compromission du terminal.





