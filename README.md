
# Outputs : les sorties de la transaction

Les outputs sont les nouvelles sorties créées par la transaction. Chaque output associe un montant en satoshis à une condition de dépense, généralement représentée par un script.

Cette condition indique qui pourra dépenser cette sortie et sous quelles conditions.

## Les deux types de sorties les plus courants dans un paiement

1. **Sortie destinée au bénéficiaire :** elle contient le montant que l'expéditeur souhaite envoyer à l'adresse du destinataire.

2. **Sortie de monnaie (change) :** si les inputs totalisent davantage que le paiement et les frais, le reste peut être renvoyé vers une adresse contrôlée par l'expéditeur.

**Exemple illustratif :** une personne utilise un input de 0,01000000 BTC pour envoyer 0,00600000 BTC. Une partie peut être renvoyée à l'expéditeur sous forme de monnaie, tandis qu'une petite différence est prélevée comme frais.

**Attention :** la monnaie rendue n'est pas automatique dans tous les cas. Si la valeur des inputs est exactement égale au paiement plus les frais, aucune sortie de change n'est nécessaire.

