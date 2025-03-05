# Acesso Remoto via Remote View para Dispositivos Android

#### Aplicativo Remote View: Acesso Remoto para Dispositivos Android

Agora, administradores podem acessar remotamente a tela de dispositivos Android diretamente pelo portal. Após instalar o app Remote View, ele é configurado automaticamente e conectado ao servidor, garantindo uma experiência simples e ágil. O usuário do dispositivo pode autorizar conexões solicitadas pelo portal, e, ao aceitar, a transmissão da tela é iniciada. Essa funcionalidade facilita o suporte técnico de forma prática e eficiente.

Mais informações na seção [Acesso Remoto](../../portal/configuracoes/editar-politica/configuracoes-gerais/acesso-remoto.md).

#### Configuração de Remote View em Políticas Android

Foi implementada a integração do Remote View nas políticas Android, possibilitando acesso remoto aos dispositivos. Ao ativar a configuração "Acesso Remoto" durante a criação da política:

* **Criação Automática de Grupos**: Um grupo vinculado à empresa e à política é gerado automaticamente.
* **Configuração de Registro**: O ID do grupo e a URL do QR Code de registro do agente são armazenados.
* **Envio Automático de Configuração**: A URL de registro é enviada automaticamente ao app Remote View nas configurações gerenciadas.

#### Acessando Dispositivo Android via Remote View

Administradores podem realizar suporte técnico remoto em dispositivos Android. Destaques:

* Opção de Acesso Remoto: Disponível na lista de dispositivos para aqueles com a configuração "Acesso Remoto" ativa na política.
* Janela de Conexão: Após iniciar o acesso remoto, o sistema envia um push ao dispositivo e abre uma janela de controle remoto com funcionalidades como acesso à área de trabalho e arquivos.
* Validações de Configuração: Caso o Acesso Remoto esteja desativado na política ou o app Remote View não esteja conectado, a funcionalidade será desabilitada e mensagens explicativas serão exibidas para orientar ajustes necessários.\
  Mais informações na seção [Opções de gerenciamento de dispositivos](../../portal/dispositivos/lista-de-dispositivos/opcoes-de-gerenciamento-de-dispositivos.md).

Essas atualizações otimizam o suporte remoto, melhorando a experiência de gestão e resolução de problemas em dispositivos Android.
