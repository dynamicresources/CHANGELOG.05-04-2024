# CHANGELOG - 05/04/2024
### 🤔 O que foi feito ?

## Alterado / Corrigido
1. ### Dynamic Notification:
    - Problemas de outras notificações não aparecerem na tela após uma ser criada.

2. ### Dynamic AC:
    - Tempo de confirmação do AC Breaker.
    - Forma de detecção do módulo anti-changedata.
    - Callback na config para resources protegidos dentro dos módulos.
    - Todos os métodos de detecção via debugHook foram protegidos.Notification foi vinculado ao sistema.
    - Início do módulo anti-fly (protegendo o jogador ao fazer login).

## Adicionado
1. ### Dynamic Notification:
    - Animação própria para aparecer / sumir a notificação.
    - Som personalizados para cada tipo de notificação.
    - Sistema de contagem para as notificações (máximo 99).
    - Exports para o lado `server - side`, podendo levar um jogador ou uma tabela de jogadores para receber a notificação.

2. ### Dynamic AC:
    - Novo módulo `anti-gui`.

## Aonde alterar ?
1. ### Dynamic Notification:
    - **Todos** os arquivos do sistema.

2. ### Dynamic AC:
    **Todos** os arquivos do sistema (matenha as configurações *(módulos e sensiveis)* salvas para evitar problemas).

## Observação
1. Caso tenha quaisquer problemas com o **AC**, nos contate via [ticket](https://discord.com/channels/1141441934896930958/1188401987310596197).
2. Caso você não seja um cliente e deseja adquirir o **AC**, abra um carrinho em [produtos](https://discord.com/channels/1141441934896930958/1141457027588165842) e qualquer duvida não hesite em [abrir ticket](https://discord.com/channels/1141441934896930958/1188401987310596197).
3. Quaisquer atualizações feitas no **AC** é necessário **não** ter nenhum jogador dentro do seu servidor, então reserve um dia da semana para manutenção do sistema.
4. Antes de colocar o **AC** dentro do seu servidor oficial, execute testes em um servidor local juntamente ao seus staffs para adaptação do sistema a jogabilidade dos usuários.
