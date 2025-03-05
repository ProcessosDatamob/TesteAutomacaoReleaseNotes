# Token de Registro

Para acessar a tela de "Token de Registro" de dispositivos clique no menu "Configurações" na opção "Gerenciar Políticas" e clique nos três pontinhos "..." da política desejada. Fazer o registro do dispositivo dessa forma facilita o enrolamento (enroll) do dispositivo, tornando o processo de configuração inicial mais eficiente e prático. As configurações disponíveis permitem incluir informações detalhadas diretamente no QRCode utilizado para configurar os dispositivos gerenciados. A tela de "Token de Registro" é mostrada a seguir:

<figure><img src="../../../../.gitbook/assets/Captura de tela 2024-04-30 103515.png" alt=""><figcaption></figcaption></figure>

Os itens disponíveis nesta tela são descritos abaixo:&#x20;

1. O Token de Registro da política pode ser copiado e enviado.
2. A configuração Zero Touch da política pode ser copiada para ser inserida no painel Zero Touch.&#x20;
3. O sistema apresentará um campo para a seleção da 'Rede Wi-Fi', esta opção permite ao administrador selecionar uma das redes Wi-Fi configuradas previamente na tela "Gerenciar Redes Wi-Fi". Ao selecionar uma rede, o sistema insere todas as configurações de conexão no QRCode.Os tipos de segurança suportados incluem WPA/WPA2, WEP e nenhuma segurança.\
   Quando o dispositivo é configurado utilizando o QRCode, ele se conecta automaticamente à rede Wi-Fi selecionada. Isso simplifica e acelera o processo de configuração inicial, eliminando a necessidade de inserir manualmente os detalhes da rede no dispositivo.
4. A opção “Habilitar Aplicativos de Sistema" permite habilitar todos os aplicativos de sistema nativos do dispositivo.  Quando esta opção é ativada, o sistema atualizará a imagem do QRCode incluindo a informação para habilitar os aplicativos de sistema.
5. Ao ativar o campo "Pular Criptografia", será inclusa a seguinte informação no QRCode: "_android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION_":  (true/false - padrão “false"),  esta opção controla se a criptografia do dispositivo será ignorada durante a configuração inicial. O sistema também atualizará a imagem do QRCode com a nova configuração e atualizará a configuração do Zero Touch. Após realizar o enroll com o QRCode, o dispositivo ignorará a criptografia do sistema. Essa função pode ser útil em cenários onde a criptografia não é necessária, acelerando o processo de configuração inicial.&#x20;
6. Ao ativar a opção "Usar Dados Móveis" do sistema operacional (SO), será incluída a seguinte informação no QRCode: “android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA": (true/false - padrão “false"), esta opção permite que o dispositivo utilize dados móveis para a configuração inicial. O sistema atualizará a imagem do QRCode com a nova configuração.  Após realizar o enroll com o QRCode, o dispositivo utilizará os dados móveis durante o processo de configuração.\
   Utilizar dados móveis é útil em situações onde uma rede Wi-Fi não está disponível ou quando se prefere usar a rede móvel. Isso assegura que o dispositivo possa completar a configuração inicial mesmo em locais com conectividade Wi-Fi limitada.
7. Ao concluir as configurações, o sistema permitirá salvar ou cancelar o salvamento das configurações, armazenando-as ao finalizar o processo de salvamento.
8. O QR Code da política pode ser lido na tela para o processo de registro de dispositivos ou pode ser copiado e enviado para os usuários dos dispositivos.
