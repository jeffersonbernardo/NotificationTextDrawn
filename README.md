# NotificationTextDrawn
Muito dos Servidores Atuais Estão Optando por TextDrawn nas suas Game Modes pra deixar o servidor mais bonito e com um toque de realidade ou comparação com o Fivem.

Pensando nisso eu trouxe um Script de Notificação em TextDrawn.
# Como Funciona?
A cada resposta do servidor com o "Player" vai aparecer uma notificação personalizada.
# Instalação
Pra usar as Mensagens em TextDrawn você vai ter que trocar todas mensagens que tiver SendClientMessage pela mensagem que você preferir.

Vou colocar os Exemplos de Mensagens:

        ShowInfo, ShowError, SuccesMsg

Quando escolher a mensagem que você quer colocar retire as cores das mensagem antiga SendClientMessage vou deixar outro exemplo de como é pra ser logo abaixo.

Incorreto:  
        
    SendClientMessage(playerid, -1, "{009CFF}Emprego de motorista de onibus!");

Correto:

    ShowInfo(playerid, "Emprego de motorista de onibus!");
