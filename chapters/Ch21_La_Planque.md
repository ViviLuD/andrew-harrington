     1|Chapitre 21 — La Planque
     2|# Chapitre 21 – Les Fichiers Effacés
     3|
     4|
     5|
     7|
     8|Timeline : T+9h → T+12h
     9|
    10|──────────────────────────────────────────────────
    11|
    12|Séquence 1 — Le Campus
    13|
    14|Le campus de l'EPFL à 09 h 22. Les bâtiments modulaires s'étendaient en damier sur le plateau — verre, béton blanc, et la lumière crue du matin suisse. Étudiants en groupes, vélos, thé (Oolong, 90-95°C), des gobelets en carton. Une normalité que la tempête solaire de l'aube semblait n'avoir jamais touchée.
    15|
    16|
    17|
    18|Andrew traversa l'esplanade à grandes enjambées, la valise de la plaque 0007 toujours dans la main. La compression sous ses vêtements lui rappelait son rythme cardiaque — stable, mais tendu. Il n'avait pas remis les DUNU Brain Dance. Il voulait entendre les sons du campus : les freins hydrauliques d'un bus électrique, les rires de deux étudiants, le bourdonnement des climatisations. Le monde continuait pendant que des fichiers s'effaçaient.
    19|
    20|
    21|
    22|Siggui et Helgi étaient restés à l'aéroport — formalités de douane, transfert de la valise, toute la paperasse qu'une plaque de photonique de 14 millions de francs attirait comme un aimant. Andrew les rejoindrait plus tard. D'abord, James.
    23|
    24|James l'attendait à l'entrée du bâtiment de photonique. Il était appuyé contre la porte vitrée, les bras croisés, une tasse de thé froid à la main — vert, du Gunpowder, à moitié bu, abandonné depuis une heure.
    25|
    26|— Tu as fait bon voyage ? demanda James d'un ton neutre.
    27|
    28|— Le mode photonique a tenu. Juste assez.
    29|
    30|— Juste assez, répéta James. C'est ce qu'on dit quand on a failli cramer.
    31|
    32|Andrew haussa une épaule. Il posa la valise sur le sol carrelé du hall, le temps de sortir le FiiO M23 de sa poche. Il ne lança aucune musique — juste le geste. Le toucher de l'appareil. Le poids familier. Un point d'ancrage.
    33|
    34|
    35|
    36|— Parle-moi des fichiers.
    37|
    38|James poussa la porte vitrée, le fit entrer dans le hall. L'intérieur était frais, climatisé, avec l'odeur caractéristique des laboratoires de pointe — désinfectant, métal froid, et la subtile ionisation des équipements haute tension.
    39|
    40|
    41|
    42|— Deux fichiers de la base de données interne, dit James en marchant vers les ascenseurs. Pas l'interface OMEGA — les logs de calibration de l'ordinateur photonique. Les enregistrements bruts des trois dernières semaines.
    43|
    44|— Les calibrations de phase ?
    45|
    46|— Exactement.
    47|
    48|Ils montèrent au troisième étage. Les couloirs défilaient derrière les portes vitrées — bureaux, laboratoires, salles de réunion, où les chercheurs regardaient leurs écrans sans se douter qu'un cargo islandais transportait leur destin entre ses cales.
    49|
    50|
    51|
    52|— La tempête solaire a déclenché une coupure d'alimentation de 47 millisecondes sur le réseau interne, dit James. Pendant ces 47 ms, le système de sauvegarde de la base a basculé sur batterie. Quelqu'un a profité de cette fenêtre.
    53|
    54|— Quelqu'un sur le réseau interne.
    55|
    56|— Oui.
    57|
    58|L'ascenseur s'ouvrit sur un couloir plus étroit, aux murs tapissés de câbles et de conduits de fibre optique. James le guida vers la salle des serveurs — une porte blindée, code, empreinte palmair.
    59|
    60|Andrew posa la paume sur le lecteur. La porte cliqueta.
    61|
    62|Ils entrèrent.
    63|
    64|Le bruit les frappa comme un mur : le vrombissement des climatiseurs, les ventilateurs des baies serveur, le souffle continu des systèmes de refroidissement liquide. L'air était sec et froid. Des rangées de serveurs noirs s'alignaient comme les tombes d'un cimetière technologique, leurs diodes clignotant au rythme d'un cœur électronique.
    65|
    66|Andrew s'arrêta au centre de la salle, les mains sur les hanches.
    67|
    68|— Montre-moi les logs d'accès.
    69|
    70|James s'assit devant une console, fit glisser ses doigts sur le clavier. L'écran afficha une matrice de timestamps, d'identifiants, d'adresses MAC.
    71|
    72|— L'effacement a eu lieu à 07 h 23 min 47 s. Le temps que la tempête soit à son apogée. L'attaquant a utilisé un compte administrateur dormant — celui de Klaus Richter, un chercheur parti en retraite il y a six mois.
    73|
    74|— Le compte était toujours actif ?
    75|
    76|— Le service IT l'a désactivé. Mais l'attaquant l'a réactivé via une vulnérabilité dans le portail d'authentification LDAP. Un patch non déployé sur le module de synchronisation SAML — un audit de sécurité de février le mentionnait.
    77|
    78|— Et on n'a pas patché.
    79|
    80|— Non.
    81|
    82|Andrew se passa la main sur la nuque. La compression de son bras gauche était une pression constante, une mémoire.
    83|
    84|— Six mois, dit-il. Un chercheur parti depuis six mois, et son compte est toujours dans le système avec les privilèges administrateur. Ce n'est pas une coïncidence que ce soit le compte utilisé aujourd'hui.
    85|
    86|— L'attaquant savait qu'il serait actif.
    87|
    88|— Et la tempête solaire a fourni la couverture.
    89|
    90|Andrew regarda l'écran. Les logs défilaient. Des lignes de texte vert sur fond noir. 07 h 23 min 47 s. Connexion. 07 h 23 min 51 s. Ouverture de session. 07 h 23 min 54 s. Commande de suppression — `rm -rf /var/lib/photonic_calibration/logs/*`. 07 h 23 min 56 s. Déconnexion.
    91|
    92|Quatre secondes. Quatre secondes pour trouver le bon fichier, exécuter la commande, et disparaître.
    93|
    94|— C'est professionnel, dit Andrew. C'est pas un étudiant qui s'amuse.
    95|
    96|— Non.
    97|
    98|— Qu'est-ce qui a été pris, exactement ?
    99|
   100|James changea d'écran. Les graphiques s'affichaient — des courbes de phase, des fréquences, des alignements de mesure.
   101|
   102|— Les calibrations des jours 14, 15 et 16. Trois semaines de données de stabilité photonique. Les profils d'émission de la plaque avant son déploiement.
   103|
   104|Andrew sentit le poids de la plaque dans sa valise. Quelqu'un avait effacé les informations qui permettraient de comprendre comment la plaque 0007 avait été construite, configurée, optimisée. Sans ces logs, un concurrent — ou un adversaire — pourrait encore reconstituer le design, mais il lui faudrait des mois d'ingénierie inverse.
   105|
   106|Mais quelqu'un d'autre — celui qui avait effacé les logs — avait peut-être fait une copie avant de supprimer.
   107|
   108|— On a une sauvegarde ? demanda Andrew.
   109|
   110|— Oui. Hors ligne. Magnus a insisté après l'incident de février. Les sauvegardes du jour 14 au jour 16 sont à l'abri dans le coffre du Rectorat.
   111|
   112|— Fais-les ramener. Et verrouille l'accès à cette salle. Personne entre sans ton code.
   113|
   114|James acquiesça. Andrew regarda les serveurs un long moment. La valise de la plaque 0007 reposait contre son mollet, une présence silencieuse.
   115|
   116|— Deux fichiers, murmura-t-il. C'est tout ce qu'ils ont pris. Les autres données — des téraoctets de recherches — ils n'y ont pas touché.
   117|
   118|— Ils savaient exactement ce qu'ils cherchaient, dit James.
   119|
   120|— Et ils l'ont trouvé.
   121|
   122|──────────────────────────────────────────────────
   123|
   124|Séquence 2 — Café et Théorèmes
   125|
   126|Ils s'installèrent dans le bureau de James au deuxième étage. La pièce était petite — un bureau métallique, une chaise ergonomique usée, une bibliothèque croulant sous les manuels de physique et de cryptographie. Sur le mur, un tableau blanc couvert d'équations qu'Andrew n'avait pas le temps de déchiffrer.
   127|
   128|James mit une bouilloire en marche. Il sortit deux tasses — une pour lui, une pour Andrew — et une boîte de Tieguanyin qu'il avait gardée dans son tiroir.
   129|
   130|— Tu as prévu le thé, dit Andrew.
   131|
   132|— Je te connais. La plaque est posée, le vol est fini, t'as besoin de redescendre.
   133|
   134|Andrew prit la tasse, inspira le parfum. La vapeur monta. Il compta jusqu'à sept, comme toujours. La chambre d'écho de son rituel.
   135|
   136|— Le doyen veut te voir, dit James. Une réunion à 11 h. Le président de l'EPFL aussi. Et une visioconférence avec quelqu'un du Département fédéral de la défense — Armasuisse.
   137|
   138|— Armasuisse. Bien sûr.
   139|
   140|— La plaque 0007 est sous contrat de recherche. Ils ont le droit de savoir.
   141|
   142|— Et après avoir su, ils ont le droit de prendre.
   143|
   144|James haussa une épaule et but son thé.
   145|
   146|— Le problème, c'est pas Armasuisse, dit Andrew. Le problème, c'est les fichiers effacés.
   147|
   148|— Ça et le fait que la même signature de connexion a été utilisée sur le réseau du CERN hier.
   149|
   150|Andrew reposa sa tasse.
   151|
   152|— Le CERN.
   153|
   154|— Connexion à 03 h 14. Durée : 2 minutes. Accès à une base de données de physique des particules. Rien de sensible — des données de calibration du LHC, déjà publiques pour la plupart. Mais la signature LDAP est identique. Même vulnérabilité exploitée.
   155|
   156|— Une reconnaissance, dit Andrew.
   157|
   158|— Ou un message.
   159|
   160|Andrew se frotta les tempes. Il sentait la fatigue du vol dans ses épaules, dans ses poumons — l'air sec de la cabine pressurisée, le stress du mode photonique, l'atterrissage. Il avait besoin d'une douche. De huit heures de sommeil. De ne pas penser aux implications de ce que James venait de dire.
   161|
   162|— Qui d'autre est au courant ?
   163|
   164|— Toi. Moi. Magnus, parce qu'il a les sauvegardes. Et toi, tu viens de le dire à la plaque 0007 en entrant dans la salle des serveurs.
   165|
   166|— Je n'ai pas — Andrew s'arrêta. Il regarda ses doigts autour de la tasse. La plaque n'était pas allumée. Le mode photonique était désactivé depuis l'atterrissage. Elle n'aurait pas pu capter quoi que ce soit.
   167|
   168|— Je rigole, dit James avec un sourire las. Détends-toi.
   169|
   170|— C'est pas drôle.
   171|
   172|— Si, un peu.
   173|
   174|Andrew but son thé. Amer. Parfait.
   175|
   176|──────────────────────────────────────────────────
   177|
   178|Séquence 3 — Le Bureau du Doyen
   179|
   180|La réunion commença à 11 h 03, avec sept minutes de retard — un protocole de courtoisie académique.
   181|
   182|La salle du conseil du Rectorat était tout en bois verni, cuir et la lumière tamisée. Une table d'acajou de six mètres de long, douze chaises assorties, et une vue imprenable sur le Léman par la baie vitrée. Les montagnes du Jura se découpaient à l'horizon, nettes comme un diagramme.
   183|
   184|Autour de la table, ils étaient cinq. Le doyen Ulrich, costume bleu, barbe grise, un regard derrière des lunettes sans monture. La présidente Marie-Claude Fontvieille, tailleur sombre, mains croisées sur la table, l'expression de quelqu'un qui a déjà pris sa décision avant la fin de la réunion. Magnus Fischer, le chef de la sécurité informatique, mal à l'aise dans son pull de développeur, les yeux rouges — il n'avait pas dormi. Un colonel d'Armasuisse, en civil, que personne n'avait présenté mais qui prenait des notes sans lever les yeux. Et James, debout près de la fenêtre, adossé au mur, sa tasse de thé à la main.
   185|
   186|Andrew était seul de son côté de la table.
   187|
   188|Le doyen Ulrich toussa pour ouvrir la séance.
   189|
   190|— Docteur Harrington, dit-il. Le transport de la plaque 0007 à Genève s'est déroulé sans incident majeur. Nos équipes confirment que l'intégrité du prototype est intacte. Permettez-moi de vous féliciter pour ce succès.
   191|
   192|Andrew attendit. Un compliment académique était rarement gratuit.
   193|
   194|— Cependant, poursuivit Ulrich, nous avons été informés d'une anomalie. Une intrusion dans notre système de calibration. Deux fichiers effacés.
   195|
   196|— Je suis au courant.
   197|
   198|— Nous avons confié l'enquête à Magnus et à son équipe. Mais le timing — l'effraction pendant la tempête solaire — soulève des questions. Avez-vous une hypothèse sur l'origine de cette intrusion ?
   199|
   200|
   201|
   202|Andrew compta sept secondes. Il regarda la table, les mains croisées du président, les notes du colonel. Chaque visage était une équation avec des inconnues.
   203|
   204|— Le fichier de calibration J14 à J16, dit-il. Les trois semaines qui ont précédé le déploiement. Celui qui a effacé ces fichiers savait ce qu'il cherchait. Il connaissait la structure de la base. Il connaissait l'existence du compte de Richter.
   205|
   206|— C'est une attaque ciblée, résuma le colonel d'Armasuisse sans lever les yeux de son carnet.
   207|
   208|
   209|
   210|— Oui.
   211|
   212|— Et vous avez une idée de qui la mène ?
   213|
   214|— Oui.
   215|
   216|— Allez-vous nous la communiquer ?
   217|
   218|Andrew regarda le colonel. Il soutint son regard sept secondes.
   219|
   220|Le colonel finit par lever les yeux de son carnet.
   221|
   222|
   223|
   224|— Ce n'est pas de la rétention d'information, dit Andrew. C'est de la prudence. Si j'ai raison, la source de l'attaque a infiltré des réseaux que vous ne voulez pas compromettre en révélant ce que je sais.
   225|
   226|Le colonel le regarda, sans répondre.
   227|
   228|La présidente Fontvieille décroisa les mains.
   229|
   230|— Docteur Harrington, dit-elle. Cette université a investi six ans de recherche et 14 millions de francs suisses dans le projet OMEGA. L'ordinateur photonique que vous avez conçu est peut-être l'invention la plus importante issue de l'EPFL depuis le deep learning. Je ne laisserai personne — infiltration, tempête solaire ou non — compromettre l'héritage de cette institution.
   231|
   232|— Je n'ai pas l'intention de le compromettre non plus.
   233|
   234|— Alors qu'allons-nous faire ?
   235|
   236|Andrew se tourna vers James. James hocha la tête, un geste à peine visible.
   237|
   238|— La plaque 0007 est active, dit Andrew. Son mode photonique a été testé en vol. Il fonctionne. Ce que les attaquants ont pris — les logs de calibration jours 14-16 — c'est un plan partiel. Ils ont la structure, mais pas l'état actuel.
   239|
   240|— Et qu'est-ce que ça signifie concrètement ?
   241|
   242|— Ça signifie qu'on verrouille tout. On coupe le réseau de calibration de l'accès internet. On met la plaque 0007 dans le coffre photonique. On active les protocoles de quarantaine.
   243|
   244|Le colonel d'Armasuisse releva la tête.
   245|
   246|— Des protocoles que vous avez élaborés ?
   247|
   248|— James et moi, oui.
   249|
   250|— Sans nous consulter.
   251|
   252|— Vous consultez maintenant.
   253|
   254|Le silence qui suivit fut plus long que sept secondes. La présidente Fontvieille regarda par la fenêtre, les montagnes, le lac.
   255|
   256|— Très bien, dit-elle finalement. Faites.
   257|
   258|Le colonel referma son carnet sans ajouter un mot.
   259|
   260|
   261|
   262|Andrew se leva. Il prit sa tasse de thé, encore chaude, et but une gorgée.
   263|
   264|— James a besoin d'accès complet au système de logs réseau des trois derniers mois. Magnus, vous travaillez avec lui. Je veux le moindre paquet suspect, la moindre requête LDAP venue de l'extérieur. On a une empreinte. On la suit.
   265|
   266|Il se tourna vers la porte. Puis il s'arrêta.
   267|
   268|— Une dernière chose, dit-il.
   269|
   270|— Oui ? fit le doyen.
   271|
   272|— Les fichiers effacés. Si les attaquants les ont copiés avant suppression — ce qui est probable — ils ont une fenêtre de 72 heures pour exploiter les données de calibration. Après ça, la plaque sera reconfigurée avec un nouveau jeu de phase. Inutilisable pour eux.
   273|
   274|— 72 heures.
   275|
   276|— On a 72 heures pour trouver qui a fait ça et les arrêter. Ou tout ce qu'on a construit devient une cible.
   277|
   278|Il posa sa tasse vide sur la table et sortit.
   279|
   280|──────────────────────────────────────────────────
   281|
   282|Séquence 4 — La Décision
   283|
   284|Dans le couloir, James le rattrapa.
   285|
   286|— 72 heures, c'est un peu serré.
   287|
   288|— C'est un peu serré, oui.
   289|
   290|— Tu veux dire qu'on ne sait pas du tout combien de temps on a.
   291|
   292|— C'est aussi ce que je veux dire.
   293|
   294|Ils marchèrent en silence jusqu'à la sortie du bâtiment. La lumière de Genève était plus forte maintenant — onze heures du matin, le soleil au zénith. Les étudiants vaquaient. Un groupe faisait du slackline entre deux platanes.
   295|
   296|Andrew s'assit sur un banc, sortit le FiiO M23, enfila les DUNU Brain Dance. Il sélectionna *Chillout Lounge* (Suno AI) de Zimmer, enclencha la piste. Le piano. Les premières notes.
   297|
   298|Il regarda le lac. Il regarda les montagnes. Il compta les secondes avec la musique.
   299|
   300|— Qu'est-ce que tu vas faire ? demanda James.
   301|
   302|Andrew ne répondit pas tout de suite. Il laissa la musique remplir son cortex, isoler le bruit, concentrer la pensée.
   303|
   304|— Je vais parler à la plaque, dit-il finalement.
   305|
   306|— La plaque 0007 ?
   307|
   308|— Elle a enregistré quelque chose pendant le vol. Les capteurs de phase ont capté des fluctuations qui ne viennent pas de la tempête. Je les ai vues dans les logs de monitoring.
   309|
   310|— Quel genre de fluctuations ?
   311|
   312|— De la communication.
   313|
   314|James le regarda sans comprendre.
   315|
   316|— La plaque a écouté, dit Andrew. Elle a capté des signaux cohérents dans la même bande. Pas les nôtres. Quelqu'un d'autre émettait dans la même longueur d'onde que notre photonique.
   317|
   318|— La même bande que la nôtre ?
   319|
   320|— La même bande que la nôtre.
   321|
   322|Andrew retira les DUNU Brain Dance et se leva.
   323|
   324|— On a un espion qui marche avec notre matériel. Et il sait exactement où on habite.
   325|
   326|──────────────────────────────────────────────────
   327|
   328|*Fin du Chapitre 21 – Les Fichiers Effacés*