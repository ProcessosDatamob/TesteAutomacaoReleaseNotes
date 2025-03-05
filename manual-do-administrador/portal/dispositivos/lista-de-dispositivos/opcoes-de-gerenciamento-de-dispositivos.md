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

# Opções de gerenciamento de dispositivos

### Comandos e Ações do Dispositivo

Ao clicar nos três pontinhos "**...**" à direita na listagem dos dispositivos, são exibidas aparecem as opções de consulta e configurações do dispositivo, como ilustrado na imagem abaixo:

<figure><img src="../../../../.gitbook/assets/image (406).png" alt="" width="188"><figcaption></figcaption></figure>

As opções disponíveis variam de acordo com o Modo de Gerenciamento da política na qual o dispositivo estiver vinculado e estão em destaque na imagem a seguir:

<table><thead><tr><th width="272.28506787330315">Modo de Gerenciamento</th><th>Opções disponíveis</th></tr></thead><tbody><tr><td><strong>Android</strong></td><td>Alterar Política<br>Ativar/ Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo<br>Gerar Nova Senha do Dispositivo<br>Remover Dispositivo (WIPE)<br>Gerenciar Informações<br>Controle Remoto</td></tr><tr><td><strong>Android Block SIM</strong></td><td><p>Alterar Política<br>Ativar/Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo</p><p>Gerar Nova Senha do Bloqueio de Tela<br>Remover Bloqueio de Tela</p><p>Remover Bloqueio de Chip<br>Remover Dispositivo (WIPE)<br>Gerenciar </p></td></tr><tr><td><strong>Android Work Profile</strong></td><td>Alterar Política<br>Remover Dispositivo (WIPE)<br>Gerenciar </td></tr><tr><td><strong>Windows</strong></td><td>Remover Dispositivo<br>Acesso Remoto<br>Gerenciar</td></tr><tr><td><strong>Linux</strong></td><td>Remover Dispositivo<br>Acesso Remoto<br>Gerenciar</td></tr></tbody></table>

As opções que estão em destaque na figura são detalhadas nas próximas subseções:

### **Alterar Política**

Ao escolher a opção **Alterar Política**, aparecerá no centro da tela uma caixa de diálogo para a escolha da política a ser atribuída ao dispositivo. Escolha a política entre as políticas listadas e clique em atualizar para mudar a política do dispositivo.

A política define configurações, incluindo critérios de hardware, software, sistema operacional, segurança etc. Para saber mais sobre Políticas, leia a seção de configurações deste manual.

<figure><img src="../../../../.gitbook/assets/image (261).png" alt=""><figcaption></figcaption></figure>

### **Desativar Dispositivo**

Ao enviar o comando **Desativar Dispositivo**, todos os aplicativos que não são Google serão desativados, serão permitidas chamadas telefônicas e o status do dispositivo muda para desativado. Para desativar um dispositivo utilize a opção "**Desativar Dispositivo**" no menu de opções do dispositivo. Esta opção aparece somente para dispositivos que estão no status "**Ativo**". Uma tela de confirmação será exibida conforme apresentado abaixo.

<figure><img src="../../../../.gitbook/assets/image (262).png" alt=""><figcaption></figcaption></figure>

Clique no botão "**Desativar**" para confirmar a operação.

### **Ativar Dispositivo**

Esta opção aparece somente para dispositivos que estão no status "**Desabilitado**". Para ativar um dispositivo desabilitado clique em "**Ativar Dispositivo**" nas opções de gerenciamento do dispositivo.

Confirme a atualização clicando em "**Ativar**" na caixa de diálogo, conforme apresentado na sequência.

### **Desligar Tela do dispositivo**

A opção "**Desligar Tela**" envia um comando para desligar a tela do dispositivo. Ao clicar na opção "**Desligar Tela**" o comando é executado diretamente e uma mensagem aparecerá na tela para informar que o comando foi enviado ao dispositivo.

### **Reiniciar Dispositivo**

Esta operação envia um comando para reiniciar o dispositivo. Escolha a opção "**Reiniciar Dispositivo**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando. A mensagem exibida é mostrada abaixo.

<figure><img src="../../../../.gitbook/assets/image (263).png" alt=""><figcaption></figcaption></figure>

### **Gerar nova senha do Bloqueio de Tela**

Esta opção permite ao administrador configurar a senha do bloqueio de tela do Block SIM para permitir a alteração remota da senha. Com essa funcionalidade, o administrador pode definir uma nova senha diretamente pelo portal e enviá-la para os dispositivos associados à política Block SIM. Essa senha pode incluir letras, números e símbolos, oferecendo maior complexidade e segurança.\
O dispositivo deve estar registrado em uma política com Block SIM ativo e o aplicativo Block SIM deve estar instalado e ativado no dispositivo.

1. Na Lista de Dispositivos, clique nos três pontinhos "...".
2. Clique na opção “Gerar Nova Senha do Bloqueio de Tela".&#x20;

<figure><img src="../../../../.gitbook/assets/image (11).png" alt="" width="153"><figcaption></figcaption></figure>

3. Preencha e confirme a nova senha do Bloqueio de Tela, utilizando letras, números e símbolos.&#x20;

<figure><img src="../../../../.gitbook/assets/image (10).png" alt="" width="489"><figcaption></figcaption></figure>

4. Confirme a alteração da senha, e ao confirmar, o comando será enviado via push ao \<NomeProduto> para aplicação no dispositivo.
5. O dispositivo receberá o comando via push.

Quando a senha for alterada o Block SIM receberá a nova senha, ativará o bloqueio de tela com a nova senha definida.

{% hint style="info" %}
**Limitações com o Block SIM**

Quando o dispositivo estiver configurado em uma política com o Block SIM ativo, as chamadas recebidas não poderão ser atendidas sem desbloquear a tela primeiro.&#x20;

#### **Orientação**

Caso o atendimento de ligações seja necessário mesmo com a tela bloqueada:

1. Avalie se a política Block SIM é adequada para esses casos específicos.
2. Comunique essa limitação aos usuários finais.
{% endhint %}

### **Remover Bloqueio de Tela**

Esta operação envia um comando para remover o bloqueio de tela do dispositivo. Escolha a opção "**Remover Bloqueio de Tela**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando.

{% hint style="info" %}
**OBSERVAÇÃO**

Esta opção só ficará disponível para dispositivos ativados com política em modo de gerenciamento Android Block SIM.
{% endhint %}

### **Gerar nova senha do dispositivo**

O sistema permite que seja gerada uma nova senha para o dispositivo. Para realizar esta operação, escolha a opção "**Gerar Nova Senha do Dispositivo**" conforme mostrado na imagem apresentada na sequência.

Preencha os campos "**Nova Senha**" e "**Confirmar nova senha**" com valores iguais para que o botão "**Confirmar**" esteja habilitado. Opcionalmente, e conforme a necessidade, poderão ser marcadas as opções:

* Não pedir credenciais de usuário na inicialização do dispositivo;
* Bloquear o dispositivo após a redefinição da senha.

A tela para gerar nova senha do dispositivo é mostrada a seguir.

<figure><img src="../../../../.gitbook/assets/image (264).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao selecionar a opção "Não pedir credenciais de usuário na inicialização do dispositivo", a senha não será solicitada durante o processo de inicialização. A senha será necessária apenas para desbloquear a tela do dispositivo.

**Inicialização Segura (Secure Boot)**: a senha solicitada na inicialização é uma medida de segurança implementada pelo Secure Boot. Esta funcionalidade protege o processo de inicialização contra ataques de segurança provenientes de códigos mal-intencionados, como malware e ransomware.
{% endhint %}

### **Remover Bloqueio de Chip**

Esta opção permite que o administrador envie um comando para remover o bloqueio de chip (SIM) de um dispositivo, liberando o acesso do usuário ao dispositivo.&#x20;

Na tela "Lista de Dispositivos", selecione a política “Android - Block SIM” e a opção "Remover Bloqueio de Chip", o sistema exibirá uma mensagem de confirmação para o envio da remoção do bloqueio de chip, permitindo confirmar ou cancelar. Após enviar o comando de remoção, o dispositivo receberá um push com o comando, o \<NomeProduto>  captura o comando e envia para o Block SIM. O usuário do dispositivo, precisa clicar no push ou abrir o aplicativo Block SIM para realizar a remoção do bloqueio<mark style="color:blue;">.</mark>

<figure><img src="../../../../.gitbook/assets/image (430).png" alt="" width="375"><figcaption></figcaption></figure>



### Reinicio de Bloqueio de CHIP

A funcionalidade de "Reinício de Bloqueio de CHIP" permite que, após a remoção do bloqueio do CHIP SIM em um dispositivo, o administrador possa bloquear o CHIP novamente.&#x20;

Isso possibilita que, após a remoção do bloqueio, o administrador possa trocar o CHIP do dispositivo e aplicar um novo bloqueio, garantindo a flexibilidade de gestão e segurança dos dispositivos gerenciados.

{% hint style="info" %}
**OBSERVAÇÃO**

Após a remoção do bloqueio, é possível reiniciar um bloqueio sem resetar o dispositivo, sem a necessidade de formatar o dispositivo.
{% endhint %}

### **Remover Dispositivo (WIPE)**

Esta operação permite excluir um dispositivo, ela limpa os dados e configurações do dispositivo. Os dispositivos excluídos não aparecem na lista de dispositivos da empresa. A opção "Remover Dispositivo" aparece na lista de opções do dispositivo na tela de listagem de dispositivos (menu "Dispositivos", opção "Listar Dispositivos").

No caso de remoção de dispositivos no <mark style="color:red;">Windows e Linux</mark> o sistema enviará um comando de remoção para o dispositivo no servidor e no Portal.

{% hint style="info" %}
**NOTA**

Uma mensagem é exibida na tela para informação e advertência. A operação não pode ser desfeita, portanto, confirme somente quando tiver certeza de que deseja eliminar o dispositivo.
{% endhint %}

{% hint style="warning" %}
**Procedimento para Wipe em dispositivos com "Block SIM"**

Ao realizar o comando de Wipe em dispositivos com a política "Block SIM", é necessário seguir duas etapas para garantir que a ação seja executada corretamente:

1. **Desbloquear o chip:** Antes de realizar o Wipe, é necessário desbloquear o chip.
2. **Executar o Wipe:** Após o desbloqueio, confirme novamente para realizar o Wipe.

**Nota:** Se o "Block SIM" estiver configurado com senha, será necessário o PUK do chip. Caso o comando de desbloqueio não funcione, negue o desbloqueio para acessar diretamente a tela do Wipe.
{% endhint %}

### **Remover Dispositivo com** CHIP Bloqueado

Ao enviar o comando de remoção de um dispositivo que esta ativado em uma política Android Block SIM e com o CHIP bloqueado, o usuário administrador será alertado para que possa enviar um comando de remover o bloqueio do CHIP antes de remover o dispositivo do portal.

<figure><img src="../../../../.gitbook/assets/Tela Remover Dispositivo - WIPE - Block SIM.png" alt=""><figcaption></figcaption></figure>

Será exibida a mensagem:  _Este dispositivo pode estar com o CHIP SIM bloqueado._

_Deseja enviar um comando de remoção do "Bloqueio do CHIP”?_

Ao clicar na opção SIM , o comando de remoção do bloqueio de CHIP é enviado e é exibida a mensagem: _Comando enviado com sucesso! Aguarde para tentar remover o dispositivo novamente._&#x20;

Então o sistema aguarda a confirmação antes de permitir a remoção do dispositivo.&#x20;

{% hint style="info" %}
O usuário do dispositivo, precisa clicar no push ou abrir o aplicativo Block SIM para realizar a remoção do bloqueio.
{% endhint %}

Caso o administrador optar por não enviar o comando, será exibida a seguinte mensagem: _Ao remover este dispositivo, o uso dos dados móveis do CHIP SIM do usuário poderá ficar bloqueado!_

_Você deseja mesmo remover este dispositivo? Essa ação não poderá ser desfeita._&#x20;

<figure><img src="../../../../.gitbook/assets/Tela Remover Dispositivo - WIPE - Caminha NÃO Block SIM.png" alt=""><figcaption></figcaption></figure>

Então após optar por enviar o comando de desbloqueio do chip e o portal já tiver recebido a confirmação da remoção do Bloqueio do CHIP no dispositivo, então  o sistema exibirá a seguinte mensagem:

_Você deseja mesmo remover este dispositivo? Essa ação não pode ser desfeita_

E serão exibidas as opções “Remover" e "Cancelar"

Dessa forma, essa funcionalidade ajuda a evitar problemas de bloqueio de CHIP que possam surgir ao remover dispositivos da gestão.

<figure><img src="../../../../.gitbook/assets/image (14).png" alt="" width="205"><figcaption></figcaption></figure>

## **Acesso Remoto**

O recurso de Acesso Remoto permite que os administradores gerenciem dispositivos <mark style="color:red;">Windows e Linux</mark> diretamente pelo portal. Essa funcionalidade possibilita o controle remoto do dispositivo, incluindo acesso à área de trabalho, terminal e diretórios.

1. Acesse a Lista de Dispositivos no portal.&#x20;
2. Clique nos três pontinhos "..." de um dispositivo <mark style="color:red;">Windows ou Linux.</mark>&#x20;
3. Selecione a opção Acesso Remoto. Ao selecionar Acesso Remoto, o sistema permitirá:
   * Acessar a Área de Trabalho: Controle remoto completo do dispositivo.
   * Acessar o Terminal de Prompt: Execução de comandos diretamente no terminal.
   * Acessar Diretórios: Gerenciamento de arquivos e pastas do dispositivo.

{% hint style="info" %}
**NOTA**

Esse recurso facilita o gerenciamento remoto, permitindo resolver problemas, aplicar configurações e realizar manutenções de forma eficiente, sem a necessidade de acesso físico ao dispositivo.
{% endhint %}

### <mark style="color:red;">Controle Remoto</mark>

<mark style="color:red;">O recurso Remote View permite que administradores configurem políticas Android para habilitar o acesso remoto a dispositivos. Essa funcionalidade é essencial para realizar suporte técnico e manutenção de dispositivos de forma eficiente e centralizada.</mark>

<mark style="color:red;">Ao criar uma política Android com o Acesso Remoto ativado, o sistema configura automaticamente um grupo exclusivo associado ao ID da empresa e ao nome da política. Além disso, é gerada uma URL de registro do agente para o aplicativo Remote View, que é enviada diretamente nas configurações gerenciadas do app.</mark>

<mark style="color:red;">Com isso, os administradores podem utilizar o Remote View para acessar e controlar remotamente os dispositivos associados à política, garantindo maior flexibilidade e agilidade no gerenciamento remoto.</mark>

1. <mark style="color:red;">Clique em Controle Remoto.</mark>



<figure><img src="../../../../.gitbook/assets/image (491).png" alt=""><figcaption></figcaption></figure>

2. Clique em Acessar Emdereço.

<figure><img src="../../../../.gitbook/assets/image (492).png" alt=""><figcaption></figcaption></figure>

3. Você será redirecionado para uma página, onde poderá acessar remotamente o dispositivo selecionado.

## **Gerenciar**

Ao clicar na opção **Gerenciar**, será exibida a tela **Gerenciar Dispositivo.**

<figure><img src="../../../../.gitbook/assets/Captura de tela 2024-08-01 140102.png" alt=""><figcaption></figcaption></figure>

1. Nesta tela estão agrupadas os Comandos e Ações do dispositivo que já detalhamos anteriormente, de acordo com o Modo de Gerenciamento ou Sistema Operacional. O comportamento de cada funcionalidade , será igual na tela "Lista de Dispositivos"
2. Serão exibidas as opções de Voltar e Atualizar, sendo que ao clicar sobre Atualizar, serão atualizadas as informações e será exibida a data de atualização das informações ao passar o mouse sobre o botão atualizar.
3. <mark style="color:red;">As abas com opções para edição e informações do dispositivo são exibidas de forma personalizada, de acordo com o tipo de dispositivo gerenciado. Isso permite que apenas informações relevantes sejam apresentadas para cada sistema operacional. As abas disponíveis podem incluir:</mark>\
   \- [Informações](opcoes-de-gerenciamento-de-dispositivos.md#informacoes) \
   \- [Aplicativos](opcoes-de-gerenciamento-de-dispositivos.md#aplicativos) \
   \- [Bateria](opcoes-de-gerenciamento-de-dispositivos.md#bateria) \
   \- [Armazenamento Livre](opcoes-de-gerenciamento-de-dispositivos.md#armazenamento-livre) \
   \- [Geolocalização ](opcoes-de-gerenciamento-de-dispositivos.md#geolocalizacao) \
   \- [Não Conformidades](opcoes-de-gerenciamento-de-dispositivos.md#nao-conformidades)

Abaixo segue a explicação de cada uma delas:

#### **Informações**

Ao abrir a tela Gerenciar Dispositivo , a primeira aba "**Informações**" vira Pré selecionada, nesta aba, é possível editar dados do dispositivo: Usuário, Identificação, selecionar um Grupo, Departamento, Telefone do Usuário e selecionar uma Localidade.

<figure><img src="../../../../.gitbook/assets/image (450).png" alt=""><figcaption></figcaption></figure>

Além de poder editar os dados, são exibidas mais abaixo listas com Detalhes, Instalação, Hardware, Permissões, Conectividade e SIM, relacionados ao dispositivo gerenciado, as informações são trazidas de acordo com o modo de gestão selecionado.

<figure><img src="../../../../.gitbook/assets/image (387).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (426).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (389).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (466).png" alt=""><figcaption></figcaption></figure>

As seções estão detalhadas na página de [Informações do Dispositivo](informacoes-do-dispositivo.md): "Detalhes", "Instalação", "Hardware", "Permissões", "Conectividade", "SIM" e "Localidade".

{% hint style="info" %}
**OBSERVAÇÃO**

É possível acessar rapidamente a tela de edição de uma política no dispositivo clicando no nome da política, que funciona como um link.

![](<../../../../.gitbook/assets/image (396).png>)
{% endhint %}

#### **Aplicativos**

Na aba "**Aplicativos**", é possível acessar a lista de todos os aplicativos instalados no dispositivo, contendo as seguintes informações: ícone, nome, consumo de dados móveis, consumo de dados em WiFi e tempo de uso. Os dados de consumo e tempo de uso são registrados dentro do ciclo. É possível pesquisar um aplicativo específico utilizando o campo de pesquisa, exportar relatórios completos ou da página, além de copiar as informações da lista. Ao clicar nos três pontinhos é possível visualizar o gráfico de "Histórico de Consumo" do aplicativo durante o ciclo.

<figure><img src="../../../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

#### **Bateria**

Na aba "**Bateria**", é possível selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados da bateria em formato de gráfico.

<figure><img src="../../../../.gitbook/assets/image (393).png" alt=""><figcaption></figcaption></figure>

#### **Armazenamento Livre**

Na aba "**Armazenamento Livre**" é possível visualizar a memória livre no armazenamento interno do dispositivo ao selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados de armazenamento em formato de gráfico.

<figure><img src="../../../../.gitbook/assets/image (394).png" alt=""><figcaption></figcaption></figure>

#### Geolocalização

Ao acessar a aba "Geolocalização", será possível filtrar as localizações utilizando os filtros: Localizar, Data, Fuso horário e Precisão. Ao clicar em "Buscar", um mapa será exibido, mostrando as geolocalizações registradas, se houver.

Para visualizar as localizações geográficas de um dispositivo, siga os passos descritos:

1. Selecione a opção Localizar: Por Data ou Agora\
   Se selecionar a opção de "Localizar Por Data", siga os passos a seguir:
2. Selecione a data em que as localizações foram registradas;
3. Especifique o fuso horário em que deseja visualizar as localizações;
4. Selecione o limite de precisão das localizações;
5. Clique no botão “Buscar” para exibir as localizações no mapa, de acordo com filtro especificado;
6. O sistema exibirá as localizações com marcadores formando o percurso realizado pelo usuário do dispositivo. Os marcadores possuem cores diferentes, que indicam o tipo da localização. Utilize a legenda do para identificar o tipo:

* **Posição inicial da leitura do GPS** – primeira localização do dispositivo registrada no dia;
* **Posição atual ou última posição coletada no dia** – última localização do dispositivo registrada no dia;
* **Lugar onde o usuário passou** – localizações registradas no dia, entre a primeira e a última.

7. Clique no marcador para visualizar as informações da localização.
8. Utilize os recursos do mapa para otimizar a visualização.

<figure><img src="../../../../.gitbook/assets/image (395).png" alt=""><figcaption></figcaption></figure>

#### Não Conformidades

Nesta aba, serão listadas todas as não conformidades do dispositivo com informações detalhadas da Configuração, Motivo da Não Conformidade e Detalhe da Não Conformidade.&#x20;

{% hint style="info" %}
**OBSERVAÇÃO**

A aba "Não Conformidades" ficará desabilitada se o dispositivo não possuir nenhuma inconformidade.
{% endhint %}

E em cada item de não conformidade listado será exibida a informação de Nome do Pacote, Caminho do Campo, Valor Atual, Motivo da Falha na Instalação, Contexto de Wi-Fi e Contexto de senha da política.

<figure><img src="../../../../.gitbook/assets/image (403).png" alt=""><figcaption></figcaption></figure>

É possível "Exportar" e "Copiar", permitindo exportar as informações do relatório para um arquivo Excel ou copiar as informações para uma área de transferência.

