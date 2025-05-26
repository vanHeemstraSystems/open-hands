# Documentation

Lisez les documents:[VanHeemstrasystems-Repository](https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/)

## 100 - Installer ReadTheDocs

Exécutez la commande suivante:

    $ pip install sphinx sphinx_rtd_theme recommonmark

Suivant pour créer l'exécution des documents:

    $ cd docs
    $ make html

Vos documents seront créés à l'intérieur`docs/build`.

## 200 - Autogénération des lectures

1) Assurez-vous qu'il y a un`.readthedocs.yml`fichier à la racine de votre référentiel GitHub.

2) Connectez votre référentiel GitHub à ReadTheDocs à<https://readthedocs.org/>

1.  Aller à[Lecture](https://readthedocs.org/)et créer un compte
2.  Cliquez sur "Importer un projet"
3.  Connectez votre compte GitHub si vous n'avez pas déjà
4.  Sélectionnez votre référentiel dans la liste
5.  Configurer les paramètres de votre projet

## 300 - Construisez votre documentation

1.  Poussez vos modifications à Github
2.  ReadTheDocs créera automatiquement votre documentation
3.  Visitez votre page de projet sur ReadTheDocs pour voir le résultat

## 400 - Configurer les webhooks (facultatif)

ReadTheDocs doit configurer automatiquement les webhooks, mais sinon:

1.  Accédez à vos paramètres de référentiel sur github
2.  Aller à webhooks
3.  Ajoutez un webhook avec l'URL de vos paramètres de projet ReadTheDocs

## 500 - dépannage

-   **La construction échoue**: Vérifiez les journaux de construction sur ReadTheDocs
-   **Missing content**: Assurez-vous que tous les fichiers sont inclus dans votre`toctree`
-   **Problèmes de mise en forme**: Vérifiez que votre marque / texte restructuré est valide
-   **Images not showing**: Vérifiez que les chemins vers les images sont corrects

## 600 - Maintenir votre documentation

-   Mettez à jour vos fichiers de documentation au besoin
-   Poussez les modifications à GitHub
-   ReadTheDocs reconstruia automatiquement
-   Use ReadTheDocs' versioning feature to maintain documentation for different releases

## 700 - déclencher une construction sur les lectures de lecture

Sur[Lecture](https://readthedocs.org/), après la connexion pour accéder à votre entrée de référentiel GitHub (par exemple,`https://app.readthedocs.org/projects/YOUR-GITHUB-REPOSITOY-NAME/`) et à partir du menu en pointillé (...) Choisissez**Reconstruire la version**.

## 800 - Conseils

-   **Images**: Déplacer les images vers`docs/source/_static/`et mettre à jour les références
-   **Blocs de code**: Assurer la mise en évidence appropriée de la syntaxe est spécifié
-   **Références croisées**: Mettre à jour pour utiliser le système de référence de Sphinx
-   **Métadonnées**: Ajoutez des métadonnées appropriées à chaque page pour un meilleur référencement

## 900 - Problèmes communs

-   **Broken links**: Vérifiez tous les liens après la conversion
-   **Images manquantes**: Assurez-vous que tous les chemins d'image sont mis à jour
-   **Construire des échecs**: Vérifiez les journaux de création de lecture pour les erreurs
-   **Formatage des différences**: Certaines fonctionnalités de Markdown peuvent rendre différemment en Sphinx

## 1000 - Afficher la documentation

Visite<https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/>
