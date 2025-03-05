# Mensagens e Comandos

Esta tela do sistema tem como objetivo, possibilitar ao usuário enviar mensagens e comandos para todos os dispositivos da empresa, de um ou mais grupos ou para um ou mais usuários de dispositivos específicos. As mensagens e comandos são enviados via PUSH e não geram consumo de SMS.

Para enviar uma ou mais mensagens, estas serão colocadas em uma fila onde serão agrupadas e enviadas para o dispositivo a cada minuto. Dependendo do volume de mensagens a serem enviadas, o envio para o dispositivo pode demorar um pouco, no entanto, não mais do que 2 minutos para que as mensagens saiam da fila e sejam enviadas.

As mensagens que podem ser enviadas são de texto livre e podem conter até 160 caracteres.

Já os comandos que podem ser enviados não estão disponíveis no Portal, pois executam ações que podem afetar o funcionamento do dispositivo ou do aplicativo.

Alguns dos comandos especiais são:

* **Logon -** Habilita o registro de logs pelo aplicativo.
* **Logoff -** Desabilita o registro de logs pelo aplicativo.

Ao receber um comando, o aplicativo não exibirá o texto do comando enviado.

{% hint style="info" %}
**NOTA**

Para reiniciar os serviços no caso de perda de comunicação do aplicativo, clique em “Nova Mensagem”, envie a mensagem “start\_services" para os dispositivos afetados, quando o aplicativo receber o push com o comando, ele irá inicializar os processos do aplicativo, ativar os alarmes do aplicativo e enviar as informações pertinentes do aplicativo, incluindo Device Info, Consumos, Site e SMS.
{% endhint %}

Para saber como enviar mensagens e comandos, siga os passos descritos nesta seção.

1. Clique no menu “**Mensagens**” para acessar a tela.
2. Para enviar mensagens e comandos, clique no botão "**Nova Mensagem**".

<figure><img src="../../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

3. Para enviar mensagens e comandos para todos os dispositivos da empresa, selecione a empresa.
4. Para enviar mensagens e comandos para os dispositivos de um ou mais grupos, selecione os grupos.
5. Para enviar mensagens e comandos para um ou mais usuários de dispositivos específicos, selecione os usuários de dispositivos.
6. Também é possível enviar a mesma mensagem ou comando, para empresa, grupos e usuários de dispositivos, simultaneamente. Para isso, basta preencher os campos e fazer a combinação que desejar.

{% hint style="info" %}
**OBSERVAÇÃO**

Caso um dispositivo seja informado em dois campos (ex.: grupo e usuário), ele receberá duas mensagens ou comandos.
{% endhint %}

7. Caso queira excluir da seleção a empresa, o grupo ou o usuário de dispositivo, clique no “x” ao lado do item selecionado.
8. Digite a mensagem ou comando.
9. Clique no botão “Enviar”, para colocar a mensagem ou comando na fila de envio.
10. Ao colocar a mensagem ou comando na fila de envio, o sistema exibirá o comando ou a mensagem no relatório de envio.

<figure><img src="../../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

11. Caso queira visualizar uma mensagem ou comando específico, digite o texto no campo “Pesquisar”;
12. Para ordenar as informações exibidas, clique no título da coluna “data”;
13. Para saber mais informações clique nos "..." e escolha "Visualizar Mensagem";
14. Para exportar o relatório dos aplicativos, clique em “Excel”;
15. Para copiar as informações do relatório dos aplicativos, clique em “Copiar”;

<figure><img src="../../../.gitbook/assets/image (207).png" alt=""><figcaption></figcaption></figure>
