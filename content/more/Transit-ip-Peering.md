+++
title = "Transit ip et peering"
weight = 7
banner = "img/banners/transit-ip-peering.jpg"
summary = "Les opérateurs télécom disposent de deux services d’interconnexion permettant de se connecter  sur Internet : le peering et le transit. Si ces deux termes répondent à un même besoin, faciliter le trafic internet..."
+++

Les opérateurs télécom disposent de deux services d’interconnexion permettant à leurs réseaux de se connecter directement et indirectement sur Internet : le peering et le transit. Si ces deux termes répondent à un même besoin, faciliter le trafic internet, ils n’en demeurent pas moins différents dans leur aspect.

### Le trafic internet

**Internet est un ensemble de réseaux interconnectés. Ces réseaux utilisent des protocoles communs pour échanger des informations.** Ces grands réseaux comprennent des serveurs internet qui agissent comme des référentiels centraux d’informations et d’autres serveurs qui se chargent de l’acheminement de ces informations. Les routeurs vont, eux, s’assurer que les périphériques installés sur ces réseaux puissent communiquer entre eux.

Lorsqu’un routeur réseau reçoit une requête, il interroge sa table de routage pour déterminer le chemin le plus court pour acheminer les informations. Celui-ci va d’abord regarder sur son propre réseau pour déterminer si la destination s’y trouve. Si ce n’est pas le cas, un routeur « passerelle » va se charger de sortir la requête du réseau.

En sortant de son propre réseau, la requête va devoir trouver sa route au travers d’internet. Internet se constitue d’un empilement hiérarchique de réseaux.

* **Les réseaux de plus haut niveau, backbone de l’internet : Le backbone ou dorsale Internet résulte de l’interconnexion des réseaux de fibres optiques à haut débit des opérateurs télécoms.** En se regroupant, ces opérateurs réseaux vont mettre en place un réseau global comprenant l’ensemble des tables de routage de l’internet mondial (AT&T, Orange, Cogent ...)

* **Viennent ensuite des réseaux plus petits. Tout en bas de ces strates se trouvent des opérateurs, bien souvent les FAI auprès desquels souscrivent les consommateurs et les entreprises, ne pouvant accéder en direct au backbone.** En théorie, leur trafic se limiterait à leur propre réseau. Pour régler ce problème, des réseaux intermédiaires vont se charger d’établir un lien entre les réseaux de plus haut niveau, et ceux plus bas. 

Ces interconnexions permettent à des réseaux, limités en taille, d’acheminer des informations partout dans le monde. Pour autant, ces interconnexions vont se dérouler de plusieurs manières.

### Qu’est-ce que le peering ?
**Ces réseaux de tailles différentes vont donc se lier les uns aux autres. Ceux-ci peuvent nouer des liens directs entre eux. Chacun donne accès à l’autre aux tables de routage de son réseau afin de faciliter l’acheminement de l’information. Toutefois, cet accord ne va fonctionner que pour des réseaux, et des opérateurs, de taille similaire.** Les réseaux de bas niveau ne peuvent mettre en place pareil échange avec des acteurs de plus haut niveau. Les opérateurs nationaux (comme les FAI français) peuvent aussi déployer de larges réseaux nationaux, voir internationaux, en multipliant les accords de peering. Toutefois, sans accès au backbone, ceux-ci ne peuvent garantir un accès global à internet à leurs clients.    

### Qu’est-ce que le transit ip ?
**Le peering ne suffit donc pas parfois pour acheminer un paquet d’un point A à un point B. En effet, il existe une asymétrie entre les réseaux des différents acteurs télécoms. Un accord financier est alors établi pour qu’un opérateur puisse accéder à un plus gros réseau. Ce dernier est nommé transitaire.**

Donc, lorsqu’une entreprise souhaite envoyer ou recevoir des informations sur Internet, elle doit « transiter » par un ou plusieurs réseaux tiers afin d’atteindre sa destination finale. Bien souvent, l’entreprise va traiter avec un FAI située en bas de l’échelle des réseaux. Et cette FAI va nouer des liens avec d’autres opérateurs pour proposer un service d’accès complet à internet.  

Dans ces conditions, la qualité du service proposé par un opérateur sera corrélée aux nombres d’interconnexions nouées avec d’autres réseaux.



<img src="/img/banners/transit-ip-peering.jpg" width="60%" height="60%">


<strong><u>L’interconnexion des réseaux par Peering et Transit</u></strong>

### Niveaux de fournisseurs de transit IP

Les fournisseurs de transit IP sont divisés en trois niveaux. Ces derniers suivent les niveaux des différents backbones constitutifs d’internet :

1. **Les opérateurs de niveau 1 (tier 1)**    
**Les fournisseurs de niveau 1 ont une portée mondiale étendue. Ces fournisseurs se connectent les uns aux autres pour former la « colonne vertébrale » d’Internet.** Les fournisseurs de niveau 1 échangent librement entre eux, mais vont faire payer les acteurs situés en dessous pour leur donner accès à leur réseau. La combinaison de ces fournisseurs de niveau 1 forme un ensemble de tables de routage étendues capables d’acheminer les demandes n’importe où sur Internet.

2. **Les opérateurs de niveau 2 (tier 2)**    
**Les fournisseurs de niveau 2 disposent de grands réseaux avec plusieurs emplacements physiques et centres de données.** Ces acteurs s’échangeront généralement librement les uns avec les autres afin d’étendre leur capacité de diffusion de contenu; et d’éviter au passage les coûts d’utilisation liés à l’accès à un réseau de niveau 1.

3. **Les opérateurs de niveau 3 (tier 3)**    
Les fournisseurs de niveau 3 sont généralement des fournisseurs locaux avec des listes de clients plus petites. **Ils achèteront généralement une plus petite partie du transit IP par l’intermédiaire d’un fournisseur de niveau 2 pour éviter les coûts plus élevés d’aller directement à un FAI de niveau 1.**

### Quelle est la différence entre Transit et Peering
Aucun réseau n’est assez grand pour connecter chaque personne et chaque ordinateur. Le Transit et le Peering se chargent de cette interconnexion. Le Transit et le Peering vont donc déterminer la manière dont le trafic circule sur Internet.

**L’aspect monétaire constitue la différence majeure entre ces deux méthodes.** En effet, le peering est utilisé par des réseaux de même valeur, même si parfois les différences peuvent se régler par un accord financier. Le transit, lui, implique nécessairement une transaction puisqu’il s’agit d’un accord de trafic entre deux réseaux dont la valeur intrinsèque diffère.

