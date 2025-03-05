# Ajustes e Correções da Versão - V 13.0.0

Nesta versão, foram realizadas correções listadas abaixo:

**Configurações - Gerenciar Políticas - Editar Política - Tela -** Após a formatação e ativação de dispositivos no portal, foi identificado um problema em que os aparelhos não assumiam automaticamente o papel de parede definido como padrão na política, mesmo quando a função "Desabilitar mudança de papel de parede" era desativada. Para resolver essa questão, foi implementado um controle na configuração "Tela" que reaplica automaticamente o papel de parede ao modificar a política, eliminando a necessidade de fazer o upload do papel de parede novamente e garantindo que as configurações sejam aplicadas corretamente.

**Remover Bloqueio de Tela (Block SIM) -** Ao desbloquear a tela, especialmente após o aparelho ter sido desligado, aparecia repetidamente a mensagem: “Fixá-lo para usar somente este aplicativo?” Mesmo ao selecionar a opção de fixar, a mensagem continuava a ser exibida. Para solucionar esse problema, foi ajustado o comportamento do Block SIM para que a mensagem não seja exibida repetidamente após a ativação do aplicativo, permitindo que o usuário utilize o dispositivo normalmente após o desbloqueio.

**Mob Settings -** Havia um erro ao instalar o aplicativo Mob Settings em Modo Quiosque, onde, ao tentar habilitar o Bluetooth, o aplicativo fechava automaticamente, impedindo o acesso às configurações de Bluetooth e o uso dessa função no dispositivo. Para resolver o problema, foi necessário ajustar o comportamento do aplicativo para garantir que as configurações de Bluetooth possam ser acessadas e modificadas corretamente, mesmo com o Modo Quiosque ativo.

[**Voltar ao menu inicial**](./)
