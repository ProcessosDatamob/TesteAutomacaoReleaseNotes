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

# Informações do Dispositivo

Na tela de "**Dispositivos**" dentro de "**Lista de Dispositivos**" é possível ter acesso as informações do dispositivo, clicando no botão de **Mais informações**:

<figure><img src="../../../../.gitbook/assets/image (398).png" alt=""><figcaption></figcaption></figure>

Após clicar no ícone acima, será exibida a seguinte tela, <mark style="color:red;">onde teremos acesso as Informações do dispositivo, o portal trará as informações exibidas</mark> <mark style="color:red;"></mark><mark style="color:red;">**de acordo com o tipo de dispositivo gerenciado**</mark><mark style="color:red;">, garantindo uma visão detalhada e relevante para cada sistema operacional.</mark>&#x20;

<figure><img src="../../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
A data que aparece em **Última Atualização** no canto superior direto a tela de Informações do dispositivo, é a data de atualização do dispositivo no Google, ou seja, se refere a comunicação da AMAPI  com o portal. Os dados que são atualizados são:

* Detalhes
* Instalação
* Relatório de Não conformidade
{% endhint %}



<figure><img src="../../../../.gitbook/assets/image (427).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (391).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (465).png" alt=""><figcaption></figcaption></figure>

Abaixo detalharemos as informações que contém em cada um dos campos das imagens acima:

### Detalhes

* **Usuário -** nome do usuário cadastrado no portal;
* **Identificação -** Identificação cadastrada para o dispositivo;
* **Grupo -** grupo cadastrado para o dispositiv&#x6F;**;**
* **Departamento** - É um campo de texto livre, ou seja, o administrador pode digitar o que desejar. Indica a unidade ou departamento da organização ao qual o dispositivo está atribuído;
* **Telefone do Usuário** - É um campo de texto livre, ou seja, o administrador pode digitar o que desejar. Indica o número de telefone associado ao usuário do dispositivo;
* **IMEI -** número interno e único em cada dispositivo. No Android 10 já não é possível capturar esta informação do dispositivo porque utilizamos outro método para receber esta informação com o Enriquecimento de URL;
* **ICCID -** número do chip SIM;
* **Número de série -** número de série do dispositivo;
* **Licença -** número da Licença;
* **Modelo -** modelo do dispositivo;
* **Fabricante** - nome do fabricante do dispositivo;
* **Sistema Operacional -** sistema operacional do dispositivo;
* **Versão do Android** - versão do Android do dispositivo;
* **Senha de Acesso Temporário** - Esta senha temporária, é gerada ao ativar a Configuração ["Acesso Temporário ao Dispositivo"](../../configuracoes/editar-politica/modo-quiosque.md) no Modo Quiosque. A senha deverá ser fornecida ao usuário do dispositivo e será atualizada no portal a cada 5 minutos,  com opção de copiar e exibição do tempo restante até a senha expirar. Sendo assim, caso foi definido o tempo de 10 minutos para o usuários acessar o dispositivo, caso ultrapasse esses 10 minutos, ele não conseguirá utilizar a mesma senha, pois ela já terá atualizado. No dispositivo, com a senha em mãos, o usuário deverá acessar as **Configurações Iniciais**, clicar na opção **Acesso Temporário** e digitar a senha no campo **"Código"**.

<figure><img src="../../../../.gitbook/assets/image (347).png" alt=""><figcaption></figcaption></figure>

### Instalação

* **Status Aplicado -** status do registro do dispositivo, se o dispositivo está totalmente registrado, o status será "Ativo";
* **Data de Registro -** data de registro dos dispositivos;
* **Modo de gerenciamento -** exibe o modo de gerenciamento utilizado;
* **Versão do app -** versão do Aplicativo de Gestão instalado no dispositivo;
* **Nome da Política no Portal** **-** nome da política atribuída ao dispositivo;
* **Nome da Política no Dispositivo -** nome da política atribuída no dispositivo;
* **Versão da política Aplicada -** versão da política;
* **Data de sincronização da Política -** exibirá a data da sincronização da política;
* **Em conformidade -** é a aderência do dispositivo a todas as configurações de políticas atribuídas a ele. Se alguma configuração não foi aplicada, o valor desta opção será "Não".&#x20;
* **Data da Última Comunicação -** exibirá a data em que o dispositivo se comunicou a última vez com o portal. Estes dados, serão exatamente o que estiver no dispositivo na hora da última comunicação.

{% hint style="info" %}
Os dados que são atualizados no portal quando a **Data da Última Comunicação** é atualizada são:

* Consumos
* Permissões
* Conectividade
* SIM
* Aplicativos instalados
* Dashboard (exceto localização)
* Hardware - Bateria e armazenamento
* Permissões - Todas
* Conectividade - Todos os dados listados em Conectividade
{% endhint %}

### Hardware

* **Memória Total** **-** quantidade total de memória RAM disponível no dispositivo.
* **Memória Disponível** **-** quantidade de memória RAM atualmente livre e disponível para uso no dispositivo.
* **Armazenamento Interno Total -** quantidade total de armazenamento interno que o dispositivo possui.
* **Armazenamento Interno Disponível -** quantidade de armazenamento interno atualmente livre e disponível para uso no dispositivo.
* **Armazenamento Total no Cartão SD** - quantidade total de armazenamento disponível no cartão SD inserido no dispositivo.
* **Armazenamento Disponível no Cartão SD** - quantidade de armazenamento atualmente livre e disponível no cartão SD inserido no dispositivo.
* **Processador** - informações sobre o processador do dispositivo, incluindo o modelo e a velocidade.
* **Saúde da Bateria** - estado geral da bateria do dispositivo, indicando sua capacidade e condição.
* **Ciclo de Carga da Bateria** - número de ciclos completos de carga e descarga que a bateria do dispositivo já passou.

### Permissões

* **Acesso ao Dados de Uso -**  Os status podem ser sim ou não, caso o usuário não ative esta permissão, o aplicativo não irá capturar as consumos de dados e tempo de uso dos aplicativos.
* **Ignorar Otimização de Bateria -** Os status podem ser sim ou não, caso o usuário não ative esta permissão, o aplicativo poderá ser afetado pelas configurações de otimização de bateria, parar de capturar as localizações do dispositivos e parar de enviar as informações para o Portal.
* **Escrita de Configurações do Sistema -** Os status podem ser sim ou não, caso o usuário não ative esta permissão, o aplicativo Kiosk Launcher Manage**r** não permitirá que o usuário alterar algumas configurações do sistema quando estiver no modo Quiosque.
* **Leitura de SMS -** Os status podem ser sim ou não, caso o usuário não ative esta permissão, o aplicativo não irá capturar as informações dos SMS enviados.
* **Agendar Alarmes** - Os status podem ser sim ou não, caso o usuário não ative esta permissão, o aplicativo não executará as seguintes funcionalidades: notificação de mensagens e documentos recebidos, instalação remota de aplicativos, registro de geolocalização do dispositivo, remoção de bloqueio de CHIP.&#x20;
* **Instalação de Apps de Fontes Desconhecidas -** essa permissão é opcional e pode ser ativada durante a configuração inicial. Se o usuário optar por não ativá-la, o aplicativo não poderá realizar a instalação de aplicativos de forma remota.
* **Sobreposição de Tela -** esta permissão também é opcional durante a ativação. Se não for ativada, o aplicativo não poderá exibir mensagens de confirmação ao realizar a instalação de aplicativos remotamente.

### Conectividade

* **Tipo da rede conectada (Wi-Fi/Móvel)** - indica se o dispositivo está conectado via Wi-Fi ou rede móvel.
* **Largura de Banda (Móvel)** - a largura de banda disponível para a rede móvel.
* **Largura de Banda (WiFi)** - a largura de banda disponível para a rede Wi-Fi.
* **Latência -** é o tempo que um pacote de dados leva para viajar de sua origem ao destino e retornar. Medimos isso enviando pacotes para google.com, um servidor confiável, para avaliar o desempenho da rede.
* **Configuração de Banda** - configuração específica da banda de frequência utilizada.
* **Rede WiFi conectada** - nome da rede Wi-Fi à qual o dispositivo está conectado.
* **Força de sinal** - a intensidade do sinal da rede conectada.
* **WiFi Roaming -** é a capacidade do dispositivo de se conectar automaticamente a diferentes pontos de acesso Wi-Fi dentro da mesma rede sem perder a conexão.
* **Frequência da banda WiFi** - frequência utilizada pela rede Wi-Fi (por exemplo, 2.4 GHz ou 5 GHz).
* **Velocidade do Link WiFi** - velocidade de conexão com a rede Wi-Fi.
* **Endereço MAC WiFi** - endereço MAC do adaptador Wi-Fi do dispositivo.
* **IP (Wi-Fi Network)** - endereço IP atribuído ao dispositivo na rede Wi-Fi.
* **IPv6 (Wi-Fi Network)** - endereço IPv6 atribuído ao dispositivo na rede Wi-Fi.
* **Rede BSSID** - identificador único da rede Wi-Fi.
* **Operadora da Rede Conectada** - nome da operadora da rede móvel conectada.
* **Roaming Dados Móveis** - indica se o dispositivo está em roaming de dados móveis.
* **IP (Rede móvel) -** endereço IP atribuído ao dispositivo na rede móvel.
* **IPv6 (Rede móvel) -** endereço IPv6 atribuído ao dispositivo na rede móvel.
* **DBM (RSRP - Potencia da Antena)** - medida da potência do sinal da antena.
* **Cell ID** - identificação da célula à qual o dispositivo está conectado.
* **LAC** - código de Área Local.
* **Tecnologia da Antena** - tipo de tecnologia de antena utilizada.

### SIM

* **SIM Conectado -** indica qual dos SIMs está atualmente conectado à rede móvel.
* **Operadora do SIM 1** - nome da operadora do primeiro SIM.
* **Número de Telefone SIM 1** - número de telefone associado ao primeiro SIM.
* **ICCID SIM 1** - identificador exclusivo do cartão SIM 1.
* **IMEI SIM 1** - número de Identificação Internacional de Equipamento Móvel do SIM 1.
* **Número do Assinante SIM 1** - número do assinante associado ao SIM 1.
* **MCC do SIM 1** - código do país móvel do SIM 1.
* **MNC do SIM 1** - código da rede móvel do SIM 1.
* **Operadora do SIM 2** - nome da operadora do segundo SIM.
* **Número de Telefone SIM 2** - número de telefone associado ao segundo SIM.
* **ICCID SIM 2** - identificador exclusivo do cartão SIM 2.
* **IMEI SIM 2** - número de Identificação Internacional de Equipamento Móvel do SIM 2.
* **Número do Assinante SIM 2** - número do assinante associado ao SIM 2.
* **MCC do SIM 2** - código do país móvel do SIM 2.
* **MNC do SIM 2** - código da rede móvel do SIM 2.
* **Operadora do eSIM -** nome da operadora associada ao eSIM.
* **Número de telefone do eSIM -** número de telefone associado ao eSIM.
* **ICCID do eSIM -** identificador exclusivo do eSIM.
* **ID de assinatura do eSIM -** identificador da assinatura associada ao eSIM.

### Localidade

* **Nome** - identifica o nome associado à localidade, como o nome da empresa ou do ponto de interesse.
* **Endereço** - indica o endereço completo da localidade, incluindo rua, número, cidade, estado e CEP.
* **Latitude** - coordenada geográfica que representa a posição norte-sul da localidade no mapa.
* **Longitude** - coordenada geográfica que representa a posição leste-oeste da localidade no mapa.
* **Raio** - distância em metros ao redor da localidade, usada para definir uma área de cobertura ou interesse.
* **Código** - código único ou identificador atribuído à localidade para fins de organização ou referência.
* **Região** - região geográfica ou administrativa onde a localidade está situada.
* **CNPJ** - Cadastro Nacional de Pessoa Jurídica associado à localidade, geralmente utilizado para empresas.
* **Responsável** - nome da pessoa responsável pela localidade, como o gerente ou proprietário.
* **Telefone** - número de telefone de contato da localidade ou do responsável.
* **Email** - endereço eletrônico para contato com a localidade ou o responsável.
* **Distância da Localidade** - medida da distância entre a localização atual ou outra referência e a localidade especificada.
