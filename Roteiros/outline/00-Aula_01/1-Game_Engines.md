title:          Game Engines
ID:             3
type:           md
compile:        2


Uma boa parcela do trabalho do desenvolvimento de jogos antigamente era a de criar a *game engine* ou em bom português Motor de jogo, nos primórdios da industria cada jogo tinha sua própria *engine* e pouco era reaproveitado entre um jogo e outro.

Conforme os jogos foram ganhando complexidade, os motores acompanharam essa complexidade, e passou a ser muito custoso criar uma nova aplicação para cada jogo novo que fosse ser implementado, com isso os estúdios passaram a reaproveitar códigos de jogos já lançados, alguns até liberando para uso de terceiros ou licenciando. Um grande exemplo disso foi a *engine* na qual Quake foi feito, que a *IdSoftware* liberou sob a licença GPL, abrindo possibilidades para os diversos jogos "*Quake like*" que vieram posteriormente.

Contudo ainda eram engines específicas para tipos de jogos específicos: jogos de tiro, jogos de estratégia, jogos plataforma, em algum momento começaram a surgir os motores de jogos "agnósticos",  isso é que permitem o desenvolvimento de diversos tipos de *games* na mesma aplicação, o que facilitou muito a vida de novos estúdios

Hoje contamos com diversas opções para trabalhar, e muitas inclusive gratuitas para estudo e/ou desenvolvimento de pequenas empresas, para citar algumas temos a Unity 3D, que utilizaremos no curso, Unreal Engine 5,  CryEngine e Godot que podemos todas utilizar livremente. (ps. Veja as políticas de cada uma delas quando for publicar seu jogo!)

Se tiver mais interesse em saber como as game engines são feitas, como seus subsistemas se relacionam, recomendo o livro Game Engine Architecture  de Jason Gregory,  que ele aborda a fundo inclusive o como implementar esses sistemas, mas isso foge do escopo do nosso curso.

Mas o que tanto são esses sistemas que escrevi até agora? Bom vou citar apenas alguns desses sistemas que são: Simulação de física; Simulação de Partículas; Implementação de Áudio; Implementação de render e shaders; controle de input e por ai vai.