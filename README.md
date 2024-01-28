# kafka producer and consumer et programmation fonctionnelle avec spring boot

ce projet est une application Spring Boot qui utilise kafka pour envoyer et recevoir des messages, et utilise également la programmation fonctionnelle avec Spring Boot.

## captures d'écrans :

la première capture d'écran montre 2 fenêtres, la première montre l'éditeur dans le navigateur Web et la seconde montre le consommateur dans le terminal.

![1 publish via console-consumer ](https://github.com/Yahyaa55/JEE_Activity_six/assets/100850367/0c6062ff-f61d-4aa4-8f50-c1386c8064bb)

la deuxième capture d'écran montre le terminal du consommateur, où nous pouvons voir votre message personnalisé identifié dans le pageEvent Consumer Bean de notre service.

![2 service ](https://github.com/Yahyaa55/JEE_Activity_six/assets/100850367/9e475aec-67a7-4d66-988e-391b72f1b238)

la troisième capture d'écran montre le producteur dans le terminal et le terminal du consommateur, où nous pouvons voir notre message personnalisé

![3 prod to client aka consumer](https://github.com/Yahyaa55/JEE_Activity_six/assets/100850367/9b24ce42-6a65-4c81-8fa1-9ed426d8ecb3)

la quatrième capture d'écran montre la fonction Function<PageEvent, PageEvent> pageEventPageEventFunction qui est utilisée pour transformer 
le message reçu par le consommateur, et le terminal du consommateur, où l'on peut voir le message json transformé par la fonction.

![4 supplier](https://github.com/Yahyaa55/JEE_Activity_six/assets/100850367/3198ebae-d0a3-4e96-9cad-facf336b5798)

la cinquième capture d'écran montre la fonction Function<PageEvent, PageEvent> kstreamPageEventPageEventFunction qui est utilisée pour transformer le message reçu par le consommateur, 
et le terminal du consommateur, où l'on peut voir le message json transformé par la fonction.

![5 Function png](https://github.com/Yahyaa55/JEE_Activity_six/assets/100850367/2f068d19-2373-4af5-ae6b-542fbd03650b)

la dernière capture d'écran montre les analyses dans le terminal du consommateur, où l'on peut voir le nombre d'événements par page. et le graphique d'analyse dans le navigateur Web qui montre 
le nombre d'événements par page en temps réel à l'aide de la bibliothèque smoothie.js.

![7 graphs](https://github.com/Yahyaa55/JEE_Activity_six/assets/100850367/ecfec473-5f7d-420f-ac49-c87c1c427773)

