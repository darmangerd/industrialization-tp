# Exercice 1
### Quelles étapes sont réalisées par cette action ?
- Cloner le dépôt Git dans l'environnement d'exécution.
- Configurer Python 3.10 comme version de Python à utiliser.
- Installer les dépendances Python (en utilisant pip).
- Linter le code Python avec Flake8.
- Exécuter les tests avec pytest.

### Une étape est définie au minimum par 2 paramètres, lesquels sont-ils et à quoi servent-ils ?
Chaque étape est définie par deux paramètres obligatoires : "name" et "run". Le paramètre "name" donne un nom à l'étape et le paramètre "run" définit les commandes à exécuter dans l'étape.

### La première étape contient un paramètre ‘with’, a quoi sert-il ?
Le paramètre "with" est utilisé pour définir des options spécifiques pour une action particulière. Dans l'étape "Set up Python 3.10", le paramètre "with" est utilisé pour définir la version de Python à utiliser en tant qu'option pour l'action "actions/setup-python@v3".
