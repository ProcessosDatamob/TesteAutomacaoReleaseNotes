---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Configurações Gerais - Android - Work Profile

Work Profile é um modo de gerenciamento exclusivo para dispositivos pessoais, ele permite que um usuário com o seu dispositivo pessoal possa criar um ambiente seguro para utilizar aplicativos de trabalho, garantindo segurança necessária para as informações da empresa e a privacidade do usuário, uma vez que o dispositivo é pessoal.

Para isso, o usuário precisa realizar o download do aplicativo **Android Device Policy** na loja de aplicativos e ler o QR CODE da política com o modo gerenciamento “**Android - Work Profile**”. Ao final do provisionamento, o dispositivo apresentará aplicativos de trabalho com o ícone do perfil de trabalho (maleta azul) e os aplicativos particulares sem ícones.

{% hint style="warning" %}
**IMPORTANTE**

* Não é necessário realizar o Factory reset no dispositivo para realizar o provisionamento, basta realizar o download do aplicativo “ **Android Device Policy**” e seguir os passos de provisionamento.
* Ao realizar o comando “**Remover Dispositivo**” no menu agrupado da tela “**Lista de Dispositivos**”, o perfil de trabalho no dispositivo e os aplicativos de trabalho serão removidos. Não será realizado o reset do dispositivo.
* O usuário possui autonomia para remover o perfil de trabalho através do dispositivo, sem que seja necessário autorização do Administrador.
* O Android Go oferece suporte a cenários de implantação totalmente gerenciados e dedicados. No entanto, o perfil de trabalho (BYOD) é opcional e, portanto, ausente na maioria dos dispositivos Go.
{% endhint %}

As configurações gerais são agrupadas nos tipos:

* [Bloqueio Total](configuracoes-gerais-android-work-profile.md#bloqueio-total)
* Localização
* [Rede](configuracoes-gerais-android-work-profile.md#rede)
* [Restrições de Senha - Dispositivo](configuracoes-gerais-android-work-profile.md#restricoes-de-senha-dispositivo)
* [Restrições de Senha - Perfil de Trabalho](configuracoes-gerais-android-work-profile.md#restricoes-de-senha-perfil-de-trabalho)
* [Segurança](configuracoes-gerais-android-work-profile.md#seguranca)
* [Tela](configuracoes-gerais-android-work-profile.md#tela)
* [Tela de Bloqueio](configuracoes-gerais-android-work-profile.md#tela-de-bloqueio)
* [VPN](configuracoes-gerais-android-work-profile.md#vpn)

<mark style="background-color:orange;">NOVA IMAGEM</mark>

<figure><img src="../../../../.gitbook/assets/Captura de tela 2025-01-14 153526.png" alt=""><figcaption></figcaption></figure>

### Bloqueio Total

Essa funcionalidade permite ao usuário administrador configurar um bloqueio total do dispositivo fora de um período de tempo específico ou ao atingir o limite de dados móveis. Assim, permitindo que seja realizado o bloqueio do dispositivo quando o usuário não estiver no horário de trabalho e quando o limite de dados móveis definido para o ciclo atual é atingido.

Estando na aba "**Configurações**" da tela "**Editar Políticas**", clique em "**Bloqueio Total**" para ver as opções de configuração.

<figure><img src="../../../../.gitbook/assets/image (400).png" alt=""><figcaption></figcaption></figure>

#### Bloqueio fora do Horário de Trabalho

Para realizar o bloqueio de dispositivos fora do horário de trabalho, siga os passos a seguir:

1. Ative a opção "Bloquear dispositivo fora do horário de trabalho".
2. Preencha o campo "Dias de trabalho", com os dias trabalhados na semana dia de início e dia fim.
3. Preencha o campo "Horário de trabalho", com horário de trabalho inicial e fina<mark style="color:blue;">l.</mark>

<figure><img src="../../../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao deixar os campos em branco o sistema considera o período inteiro do dia.
{% endhint %}

Quando o dispositivo estiver fora horário de trabalho configurado, o \<NomeProduto> ocultará todos aplicativos do dispositivo, exceto o "_**Telefone**_", o “_**\<NomeProduto>**_" e a _“**Play Store**"._

Os aplicativos instalados no dispositivo serão apenas ocultados e exibirá uma notificação fixa no dispositivo com a seguinte mensagem: “Acesso aos apps bloqueado pelo administrador“

Sendo assim, quando o dispositivo estiver fora do horário de trabalho configurado, não será permitido acessar os aplicativos ocultados, porém, permitirá acessar as configurações do dispositivo e será permitido desligar ou reiniciar o dispositivo.

Quando o dispositivo estiver dentro do horário de trabalho configurado, todos os aplicativos voltam a ser exibidos, sem a necessidade de instalar novamente.

#### Bloqueio Limite de Dados

Para ativar o bloqueio do dispositivo por limite de uso dos dados móveis, habilite a opção "Bloquear dispositivo por limite de uso dos dados móveis".

Quando o dispositivo atingir o limite de uso dos dados móveis configurados para o ciclo atual, o \<NomeProduto> ocultará todos os aplicativos do dispositivo, exceto o "Telefone", o "Aplicativo de Gestão" e a "Play Store".

O dispositivo exibirá uma notificação fixa com a mensagem: "_Acesso aos apps bloqueado pelo administrador_". Esta notificação informará ao usuário sobre o bloqueio.

Sendo assim, quando o dispositivo estiver bloqueado por limite de uso de dados, os aplicativos ocultados não poderão ser acessados, porém continuarão instalados, o usuário ainda poderá acessar as configurações do dispositivo e será possível desligar ou reiniciar o dispositivo.

Além disto, ao realizar a instalação de um app via Play Store ou remotamente, o aplicativo será ocultado.

Caso o uso de dados móveis estiver abaixo do limite ou se o administrador desativar a configuração "Bloquear dispositivo por limite de uso dos dados móveis" na política, então o \<NomeProduto> exibirá corretamente todos aplicativos do dispositivo conforme política provisionada.

Se o dispositivo estiver em qualquer uma das condições que requerem a ativação de um Bloqueio Total (fora do horário de trabalho ou atingindo o limite de dados móveis). A configuração e ativação de um Bloqueio Total não anula ou interfere com a configuração e ativação do outro. Ambos os bloqueios podem coexistir e serem aplicados conforme suas respectivas condições.

### <mark style="color:red;">Localização</mark>

<mark style="color:red;">A funcionalidade Compartilhamento de Localização no Work Profile permite que administradores controlem e gerenciem o acesso à localização no Perfil de Trabalho, assegurando maior privacidade e proteção dos dados corporativos.</mark>

<mark style="color:red;">**Desativar Compartilhamento de Localização:**</mark> <mark style="color:red;"></mark><mark style="color:red;">permite desativar o compartilhamento de informações de localização no Perfil de Trabalho, garantindo que os dados de localização não sejam acessados indevidamente. As configurações realizadas são enviadas automaticamente aos dispositivos vinculados à política ao salvar as alterações no portal.</mark>

<figure><img src="../../../../.gitbook/assets/image (489).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">**Rede**</mark>

<mark style="color:red;">A funcionalidade Configurações de Rede Wi-Fi no Work Profile permite que administradores configurem e gerenciem as redes Wi-Fi disponíveis no Perfil de Trabalho, oferecendo maior controle sobre as conexões de rede e reforçando a segurança.</mark>

* <mark style="color:red;">**Configuração Rede Wi-Fi**</mark><mark style="color:red;">:</mark>
  * <mark style="color:red;">Permite adicionar e gerenciar redes Wi-Fi no Perfil de Trabalho diretamente pela política configurada no portal.</mark>
  * <mark style="color:red;">As redes configuradas serão automaticamente enviadas aos dispositivos vinculados à política após salvar as alterações.</mark>

<figure><img src="../../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

### **Restrições de Senha - Dispositivo**

<figure><img src="../../../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="307.8854625550661"></th><th></th></tr></thead><tbody><tr><td><strong>Configuração</strong></td><td><strong>Descrição</strong></td></tr><tr><td>Qualidade da senha</td><td><p>Nesta configuração, temos as seguintes opções disponíveis:</p><p>- Não especificado</p><p>- Biometria</p><p>-Alguma</p><p>-Numérica</p><p>- Numérica Complexa</p><p>- Alfabética</p><p>- Alfanumérica</p><p>- Complexa</p><p><strong>Observação:</strong> Os campos a seguir serão exibidos conforme a opção de Qualidade de Senha selecionada;</p></td></tr><tr><td>Comprimento de histórico de senhas</td><td>Define o número de senhas já usadas que não podem ser reutilizadas</td></tr><tr><td>Máximo de senhas incorretas antes de executar wipe</td><td>Define o máximo de tentativas incorretas antes de executar o Wipe</td></tr><tr><td>Tempo limite de expiração da senha (dias)</td><td>Define quantos dias a senha vai levar para expirar</td></tr><tr><td>Exigir desbloqueio de senha</td><td>Nesta configuração temos as opções: Padrão do dispositivo, ou seja, definida conforme configurado no dispositivo ou todo dia, neste caso a senha será solicitada todo dia</td></tr><tr><td>Comprimento mínimo da senha</td><td>Essa configuração define o tamanho mínimo exigido para as senhas criadas, fortalecendo a segurança dos dados</td></tr><tr><td>Número mínimo de letras exigidas na senha</td><td>Esta configuração define a quantidade mínima de letras necessárias para as senhas, com um número específico de caracteres alfabéticos nas combinações de senha</td></tr><tr><td>Número mínimo de letras minúsculas exigidas na senha</td><td>Essa configuração determina o mínimo de letras minúsculas necessárias em senhas</td></tr><tr><td>Número mínimo de caracteres que não sejam letras (dígitos numéricos ou símbolos) necessários na senha</td><td>Define o mínimo de caracteres não alfabéticos necessários nas senhas</td></tr><tr><td>Número mínimo de dígitos numéricos necessários na senha</td><td>Estipula o número mínimo de dígitos numéricos necessários nas senhas</td></tr><tr><td>Número mínimo de símbolos necessários na senha</td><td>Essa configuração estabelece a quantidade mínima de símbolos exigidos nas senhas, nas combinações de senha</td></tr><tr><td>Número mínimo de letras maiúsculas exigidas na senha</td><td>Estipula a quantidade mínima de letras maiúsculas obrigatórias na senha</td></tr></tbody></table>

### **Restrições de Senha - Perfil de Trabalho**

<figure><img src="../../../../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>

Se a chave estiver habilitada permite ao usuário manter a mesma senha definida para o “**Dispositivo**” no “**Perfil de Trabalho**”.

Quando a opção estiver desativada, obriga ao usuário criar uma senha diferente da senha pessoal, para acessar o perfil de trabalho. São exibidas as mesmas configurações descritas na tabela acima para definição de senha.

<table data-header-hidden><thead><tr><th width="307.8854625550661"></th><th></th></tr></thead><tbody><tr><td><strong>Configuração</strong></td><td><strong>Descrição</strong></td></tr><tr><td>Qualidade da senha</td><td><p>Nesta configuração, temos as seguintes opções disponíveis:</p><p>- Biometria</p><p>- Alguma</p><p>- Numérica</p><p>- Numérica Complexa</p><p>- Alfabética</p><p>- Alfanumérica</p><p>- Complexa</p></td></tr><tr><td>Comprimento de histórico de senhas</td><td>Define o número de senhas já usadas que não podem ser reutilizadas</td></tr><tr><td>Máximo de senhas incorretas antes de executar wipe</td><td>Define o máximo de tentativas incorretas antes de executar o Wipe</td></tr><tr><td>Tempo limite de expiração da senha (dias)</td><td>Define quantos dias a senha vai levar para expirar</td></tr><tr><td>Exigir desbloqueio de senha</td><td>Nesta configuração temos as opções: Padrão do dispositivo, ou seja, definida conforme configurado no dispositivo ou todo dia, neste caso a senha será solicitada todo dia</td></tr><tr><td>Comprimento mínimo da senha</td><td>Nesta configuração temos as opções: Padrão do dispositivo, ou seja, definida conforme configurado no dispositivo ou todo dia, neste caso a senha será solicitada todo dia</td></tr><tr><td>Número mínimo de letras exigidas na senha</td><td>Esta configuração define a quantidade mínima de letras necessárias para as senhas, com um número específico de caracteres alfabéticos nas combinações de senha</td></tr><tr><td>Número mínimo de letras minúsculas exigidas na senha</td><td>Essa configuração determina o mínimo de letras minúsculas necessárias em senhas</td></tr><tr><td>Número mínimo de caracteres que não sejam letras (dígitos numéricos ou símbolos) necessários na senha</td><td>Define o mínimo de caracteres não alfabéticos necessários nas senhas</td></tr><tr><td>Número mínimo de dígitos numéricos necessários na senha</td><td>Estipula o número mínimo de dígitos numéricos necessários nas senhas</td></tr><tr><td>Número mínimo de símbolos necessários na senha</td><td>Essa configuração estabelece a quantidade mínima de símbolos exigidos nas senhas, nas combinações de senha</td></tr><tr><td>Número mínimo de letras maiúsculas exigidas na senha</td><td>Estipula a quantidade mínima de letras maiúsculas obrigatórias na senha</td></tr></tbody></table>

### <mark style="color:red;">Segurança</mark>

<mark style="color:red;">As configurações de segurança no Perfil de Trabalho oferecem controle adicional para administradores sobre a proteção dos dispositivos, incluindo a gestão da verificação de aplicativos e a restrição de alterações em contas. Essas opções garantem maior segurança e estabilidade no uso corporativo.</mark>

<mark style="color:red;">Opções Disponíveis:</mark>

* <mark style="color:red;">**Verificação do Google Play Protect:**</mark> <mark style="color:red;"></mark><mark style="color:red;">define como será aplicada a verificação de aplicativos no dispositivo utilizando o Google Play Protect. Com opções de:</mark>
  * <mark style="color:red;">Forçar a ativação da verificação de aplicativos (padrão): Garante que o recurso de verificação esteja sempre ativo nos dispositivos, sem a possibilidade de desativação pelo usuário.</mark>
  * <mark style="color:red;">Definido pelo usuário: Permite que o usuário escolha se deseja ou não ativar o Google Play Protect.</mark>
* <mark style="color:red;">**Bloquear Alteração de Contas:**</mark> <mark style="color:red;"></mark><mark style="color:red;">impede que os usuários alterem ou removam contas configuradas no Perfil de Trabalho. Ao ativar essa opção, os dispositivos vinculados à política bloqueiam qualquer tentativa de modificação ou remoção de contas corporativas.</mark>
* <mark style="color:red;">**Acesso aos contatos do perfil de trabalho no perfil pessoal:**</mark> <mark style="color:red;"></mark><mark style="color:red;">o Gerenciamento de Contatos entre Perfis permite configurar se aplicativos pessoais podem acessar os contatos armazenados no perfil de trabalho, oferecendo controle adicional sobre a privacidade e o uso de informações corporativas. A configuração está localizada no accordion "Segurança" na aba “Configurações” de uma política "Android - Work Profile" e permite três opções: desativar totalmente o acesso, permitir acesso irrestrito (padrão), ou permitir apenas o acesso por aplicativos de sistema. As alterações realizadas são salvas na política e enviadas automaticamente para os dispositivos vinculados.</mark>

<figure><img src="../../../../.gitbook/assets/image (488).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">Tela</mark>

<mark style="color:red;">Na tela de edição de uma política Work Profile, na aba Configurações, em Tela tem a opção "Desativar captura de tela". Por padrão, a funcionalidade estará desativada, ou seja, a captura de tela não será permitida no Perfil de Trabalho.</mark>

<mark style="color:red;">Configurações disponíveis:</mark>

* <mark style="color:red;">**Desativado (Padrão):**</mark> <mark style="color:red;"></mark><mark style="color:red;">Impede que os usuários realizem capturas de tela no Perfil de Trabalho.</mark>
* <mark style="color:red;">**Ativado:**</mark> <mark style="color:red;"></mark><mark style="color:red;">Permite capturas de tela no Perfil de Trabalho.</mark>

<figure><img src="../../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">Tela de Bloqueio</mark>

<mark style="color:red;">Estando na aba "</mark><mark style="color:red;">**Configurações**</mark><mark style="color:red;">" da tela "</mark><mark style="color:red;">**Edição de Políticas**</mark><mark style="color:red;">", clique em "</mark><mark style="color:red;">**Tela de Bloqueio**</mark><mark style="color:red;">" para ver as opções de configuração da tela de bloqueio. As configurações da tela de bloqueio são descritas na tabela abaixo.</mark>

| **Configuração**                          | **Descrição**                                                                                                                                        |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Desativar todas as configurações          | Desativa todas as opções de personalização da tela de bloqueio, mantendo o dispositivo com configurações padrão.                                     |
| Desativar câmera na tela de bloqueio      | Impede o acesso à câmera diretamente pela tela de bloqueio, aumentando a segurança.                                                                  |
| Desativar notificações                    | Desativa a exibição de notificações na tela de bloqueio em dispositivos com telas de proteção seguras.                                               |
| Desativar notificações editadas           | Impede que notificações modificadas sejam exibidas em telas de proteção seguras.                                                                     |
| Desativar agente de confiança             | Ignora o estado de agentes de confiança, como dispositivos confiáveis, em telas de proteção seguras.                                                 |
| Desativar sensor de impressão digital     | Bloqueia o uso do sensor de impressão digital nas telas de proteção de teclado.                                                                      |
| Desativar edição de texto em notificações | Em dispositivos Android 6 ou anteriores, bloqueia a entrada de texto em notificações na tela de bloqueio. Não afeta versões Android 7 ou superiores. |
| Desativar autenticação facial             | Impede o uso da autenticação facial em telas de proteção seguras.                                                                                    |
| Desativar autenticação da íris            | Bloqueia o uso da autenticação por íris em telas de proteção seguras.                                                                                |
| Desativar autenticação biométrica         | Desativa todos os métodos de autenticação biométrica, como impressão digital, facial e íris, em telas de proteção seguras.                           |

### <mark style="color:red;">VPN</mark>

<mark style="color:red;">A funcionalidade</mark> <mark style="color:red;"></mark><mark style="color:red;">**Configurações de VPN no Work Profile**</mark> <mark style="color:red;"></mark><mark style="color:red;">permite aos administradores maior controle sobre o acesso à rede no Perfil de Trabalho, garantindo que conexões seguras sejam priorizadas. Com essa configuração, é possível bloquear o acesso à internet quando a VPN não estiver ativa, além de gerenciar aplicativos de VPN vinculados à política.</mark>

<mark style="color:red;">Configurações disponíveis:</mark>

* <mark style="color:red;">**Aplicativos de VPN**</mark>
  * <mark style="color:red;">Permite selecionar aplicativos de VPN configurados na política com os status: "Forçado", "Disponível" e "Pré-instalado".</mark>
  * <mark style="color:red;">Apresenta o nome do aplicativo.</mark>
  * <mark style="color:red;">Administradores podem selecionar ou remover aplicativos de VPN da política.</mark>
* <mark style="color:red;">**Bloquear Conexão sem VPN**</mark>
  * <mark style="color:red;">Bloqueia todo o tráfego de rede no Perfil de Trabalho quando a VPN configurada não estiver conectada.</mark>
  * <mark style="color:red;">Essa configuração só estará habilitada quando pelo menos um aplicativo de VPN estiver selecionado.</mark>

<figure><img src="../../../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>
