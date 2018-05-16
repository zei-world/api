---
title: WooCommerce (FR)
position: 2
---

**Vous utilisez WordPress avec l'extension WooCommerce ? Suivez les étapes suivantes :**

1. Installez le plugin Zei sur WordPress
  * Allez dans "Extensions" > "Ajouter" et cherchez "zei", ensuite cliquez sur "Installer"
  * Ou [téléchargez le plugin ici](https://wordpress.org/plugins-wp/zero-ecoimpact-woocommerce/) et installez-le sur
  WordPress : "Extensions" > "Ajouter" > "Mettre une extension en ligne"
  * Ou envoyez le contenu de [ce dépôt](https://github.com/zei-world/api-woocommerce){:target="_blank"} dans un dossier "zei-wc" situé dans "/wp-content/plugins/" de votre installation WordPress (par FTP par exemple)
2. Allez dans [Zei](https://zei-world.com){:target="_blank"} > votre Profil Public d'entreprise > "Mes outils" > "Gestion et utilisation de l'API"
3. Ensuite, dans votre panel d'administration WordPress, allez dans "WooCommerce" > "Réglages" > "Intégration" et remplissez avec vos identifiants API ZEI (clé API et API secret)
4. A partir de là vous serez en mesure de gérer vos offres : (pour vos récompenses, référez-vous à la section suivante)
  * Pour lier tous vos produits à une même offre, renseignez l'option "Global offer" dans WooCommerce" > "Réglages" > "Intégration".
  * Pour lier un produit spécifique à une offre, éditez ce produit et renseignez l'option "Zei offer" dans l'onglet "Général".
5. Laissez la magie se produire !

**Codes promo pour les récompenses**

Les codes édités sur ZEI doivent fonctionner sur votre boutique, pour cela vous devez donc éditer un code promo WooCommerce :

1. Tout d'abord, vous avez besoin de connaitre l'identifiant de votre récompense (ils sont tous listés sur la page concernant l'API sur ZEI)
2. Dans votre panel d'administration WordPress, allez dans "WooCommerce" > "Codes promo" > "Ajouter un codes promo"
3. Nommez-le EXACTEMENT de la manière suivante : "zei_reward_42" (42 étant l'identifiant de la récompense)
4. Editez le coupon de la manière que vous voulez (correspondant à votre récompense sur ZEI)
5. Laissez la magie se reproduire !
