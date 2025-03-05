# Configurações Gerais - Linux

<mark style="color:red;">O modo de gerenciamento Linux permite gerenciar dispositivos Linux de forma centralizada, aplicando configurações específicas de uso, segurança e acesso remoto. Essa política oferece controle detalhado sobre os dispositivos Linux, possibilitando a criação de políticas exclusivas que atendem às necessidades corporativas, com funcionalidades como gerenciamento remoto, configuração de políticas e integração com ferramentas de administração.</mark>

#### <mark style="color:red;">Configurações de Consentimento do Usuário do Dispositivo para Linux</mark>

Essa funcionalidade permite configurar opções de consentimento do usuário ao acessar áreas críticas do dispositivo, garantindo maior transparência durante operações de monitoramento. O administrador pode ativar ou desativar opções específicas nas seguintes sessões:

* Área de Trabalho:
  * Solicitar consentimento do usuário ao acessar a área de trabalho.
  * Mostrar barra de ferramentas de conexão.
* Terminal:
  * Solicitar consentimento do usuário ao acessar o terminal.
* Arquivos:
  * Solicitar consentimento do usuário ao acessar os arquivos.

<figure><img src="../../../../.gitbook/assets/image (483).png" alt=""><figcaption></figcaption></figure>

Essas configurações são desativadas por padrão e podem ser ajustadas diretamente no portal, dentro da aba "Configurações" da política. Ao salvar as alterações, as configurações são aplicadas automaticamente aos dispositivos vinculados.

**Configurações Intel® AMT para Linux**

A funcionalidade de **Configuração de Política Intel® AMT** no Linux possibilita ao administrador configurar dispositivos habilitados com a tecnologia Intel AMT diretamente pelo portal, oferecendo maior controle e segurança no gerenciamento remoto de dispositivos Linux.

O sistema oferece diferentes opções de configuração para o Intel AMT, ajustando-se às demandas específicas do ambiente corporativo:

* **Nenhuma:** Escolha esta opção caso o Intel AMT não seja necessário ou se a configuração será realizada fora do sistema.
* **Desativar:** Use esta configuração para desabilitar o Intel AMT, garantindo que o recurso não seja utilizado.
* **Modo de Controle de Cliente Simples (CCM):** Ative o gerenciamento remoto básico, ideal para cenários com permissões limitadas.
* **Modo de Controle de Administrador Simples (ACM):** Habilite o gerenciamento remoto avançado, oferecendo maior acesso e controle para situações mais complexas.

<figure><img src="../../../../.gitbook/assets/image (484).png" alt=""><figcaption></figcaption></figure>

As configurações Intel AMT são aplicadas automaticamente aos dispositivos vinculados ao salvar a política, garantindo que as alterações realizadas sejam refletidas em tempo real, promovendo maior conformidade e eficiência no gerenciamento dos dispositivos Linux.
