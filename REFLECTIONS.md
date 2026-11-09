# Réflexions TD5 — Dashboards logistiques

## 1. Quel décideur sera le plus en désaccord

Je pense que le responsable des opérations (coûts) sera le plus en désaccord avec les deux autres. Ouvrir un entrepôt coûte cher à court terme, alors que le responsable RSE et le responsable stratégie voudront probablement ouvrir un entrepôt plus près des clients pour réduire les distances. Il pourrait aussi vouloir fermer Lille si cet entrepôt semble peu utilisé.

## 2. L'hypothèse la plus difficile à défendre

Les coûts (0,12 EUR par tonne-km et 40 EUR par tonne et par an) sont les plus difficiles à défendre : ils ne viennent d'aucune source, alors que le facteur CO2 (0,10 kg par tonne-km) est dans une fourchette publiée par le ministère et l'ADEME (0,047 à 0,12). Le stockage représente pourtant 58 % du coût de Lyon, donc tout le dashboard coûts repose sur un chiffre inventé. La demande basée sur la population est aussi fragile, mais au moins elle est clairement présentée comme une approximation.

## 3. Deux KPI qui poussent vers des actions différentes

Pour Lille, les KPI CO2 et coûts indiquent 0 kg de CO2 et 0 EUR de transport : cet entrepôt ne livre aucune autre ville, donc il semble inutile et on pourrait vouloir le fermer. Mais le KPI réseau dit le contraire : fermer Lille fait passer la distance moyenne de 168,04 km à 174,43 km, parce que ses 233 098 habitants devraient alors être livrés depuis Paris. Un même entrepôt paraît inutile avec un KPI et utile avec un autre.

## 4. Est-ce que je recommanderais la route n°1 ?

La route n°1 est Marseille ← Lyon, avec 1 211 830 kg de CO2 par an, soit presque 20 % du total du réseau. Je vérifierais avant de la recommander : ce chiffre vient surtout de la grande population de Marseille (873 076 habitants), pas de la distance (277,6 km, moins que Toulouse à 359,9 km). Surtout, Marseille est justement un emplacement candidat pour un nouvel entrepôt : si on l'ouvre, cette route disparaît complètement. Il faudrait donc d'abord décider du réseau avant d'optimiser cette route. Si on garde Lyon, l'axe Lyon-Marseille (vallée du Rhône) est un bon candidat pour le transport par train.

## 5. Quel levier pour l'entrepôt le plus coûteux

L'entrepôt le plus coûteux est Lyon : 13 476 013 EUR par an, dont 7 788 952 EUR de stockage (58 %) et 5 687 061 EUR de transport (42 %). Le stockage est la plus grosse part, mais je toucherais d'abord au transport. Dans ce modèle, le stockage coûte 40 EUR par tonne partout, donc il ne dépend que du volume livré. Par contre, le transport coûte 29,2 EUR par tonne à Lyon contre seulement 10,9 EUR à Paris : c'est ce qui explique que Lyon coûte 69,21 EUR par tonne au total contre 50,91 EUR pour Paris. Lyon livre des villes très lointaines (Bordeaux à 435,8 km, Strasbourg à 382,3 km, Toulouse à 359,9 km).

## 6. Ma recommandation pour le réseau

J'ouvrirais un entrepôt à Marseille. C'est le meilleur scénario : la distance moyenne passe de 168,04 km à 115,03 km (environ -32 %), contre 139,89 km pour Bordeaux. Marseille récupère Toulouse, Nice, Montpellier et Toulon, et la route la plus polluante et la plus coûteuse (Marseille ← Lyon) disparaît. Je garderais Lille, car le fermer augmente la distance moyenne (174,43 km). Par contre, Bordeaux reste servi depuis Lyon à 435,8 km, et ça ne change pas avec Marseille : c'est la limite de cette option.

L'avertissement sur le coût d'ouverture ne change pas mon choix, mais je le présenterais comme une première recommandation à valider par une étude financière, pas comme une décision finale. Ouvrir un entrepôt coûte cher et nos coûts sont inventés, donc on ne peut pas encore dire si l'économie de transport rembourse l'investissement.

Pour la réflexion 1, j'avais à moitié raison. Les trois dashboards indiquent finalement la même direction (la route Marseille ← Lyon est n°1 en CO2 et en coût, et Marseille est le meilleur scénario réseau), donc le vrai désaccord ne porte pas sur Marseille. Il porte sur Lille : le dashboard coûts le fait paraître inutile, alors que le dashboard réseau montre qu'il faut le garder. Et le vrai opposant à l'ouverture serait plutôt le service financier, à cause du coût d'investissement que personne ne mesure ici.

## 7. Mon 4e graphique

J'ai ajouté au dashboard coûts un graphique en barres horizontales du coût de transport par tonne livrée, pour chaque entrepôt. Il répond à une question que le graphique empilé ne montre pas clairement : quel entrepôt est inefficace en transport, indépendamment de sa taille ? Le graphique empilé montre des montants totaux, donc Lyon paraît cher en partie parce qu'il livre beaucoup de tonnes. En divisant par les tonnes, on voit que Lyon coûte 29,2 EUR par tonne en transport contre 10,9 EUR pour Paris, alors que le stockage est identique partout. J'ai choisi des barres horizontales triées parce qu'il s'agit de comparer quelques valeurs entre elles ; un camembert n'aurait pas de sens, car ces valeurs ne sont pas des parts d'un total.
