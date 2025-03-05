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

# Aplicativos

A guia de configurações de aplicativos permite gerenciar configurações, permissões, definir o modo de instalação, bem como, incluir e excluir aplicativos.

A tela "**Editar política**" posicionada na guia "**Aplicativos**" é apresentada na sequência.

<figure><img src="../../../../../.gitbook/assets/Captura de tela 2024-02-29 160922.png" alt=""><figcaption></figcaption></figure>

As telas apresentam as seguintes partes, conforme numeração na figura:

1. **Modo de seleção dos aplicativos na Play Store -** permite controlar como os aplicativos serão exibidos nos dispositivos registrados nesta política. No modo "Restrito", os usuários só podem visualizar e instalar da Google Play Store os aplicativos listados abaixo. Os outros aplicativos serão removidos e não estarão disponíveis nos dispositivos.

{% hint style="info" %}
**NOTA**

Ao selecionar a opção “**Aberta**” os aplicativos adicionados na política apresentarão o tipo de instalação: **Instalação Forçada**, pois entende que todos os aplicativos já estão disponíveis.
{% endhint %}

2. Use a caixa de pesquisa para localizar aplicativos dentro da lista exibida.
3. Listagem de aplicativos incluídos.
4. **Tipos de instalação -** escolha o tipo de instalação de cada dispositivo. Os tipos de instalação são:&#x20;

* **Disponível -** o aplicativo fica disponível para instalação, o usuário tem a opção de instalá-lo conforme sua conveniência. Não é instalado automaticamente no dispositivo.
* **Pré-instalado -** o aplicativo é instalado no dispositivo automaticamente. Quando o usuário for utilizar o dispositivo as ferramentas ou configurações necessárias já estarão instaladas.
* **Instalação Forçada-** o aplicativo é instalado automaticamente no dispositivo sem a intervenção do usuário. O usuário não pode desinstalar o aplicativo, se o fizer, o sistema irá instalar novamente, garantindo que as ferramentas necessárias estejam sempre presentes e ativas.
* **Bloqueado -** a instalação de certos aplicativos é explicitamente impedida. O usuário não poderá instalar ou acessar esses aplicativos ou configurações restritos no dispositivo.

{% hint style="info" %}
**NOTA**

Importante ressaltar que o tipo de instalação “Pré-Instalado” de um aplicativo, acontece uma única vez no dispositivo. Ou seja: quando um aplicativo é pré-instalado é deletado pelo usuário, ao alterar a política que tenha o mesmo aplicativo com o tipo de instalação “pré-instalado” o aplicativo não será apresentado no dispositivo pois ele já foi removido anteriormente.

Para que o aplicativo seja apresentado no dispositivo com o tipo de instalação “pré-instalado” é necessário realizar o comando “Remover Dispositivo (WIPE)” no portal ou factory reset através do dispositivo”.
{% endhint %}

5. Mais ações ("...") que podem ser realizadas com o aplicativo: [Configurações Gerenciadas](./#configuracoes-gerenciadas), [Permissões](./#permissoes), [Configurações Avançadas](./#configuracoes-avancadas) e [Remover Aplicativo](./#remover-aplicativo).
6. **Adicionar Aplicativos -** permite adicionar aplicativos para gerenciamento, para mais informações acessar o conteúdo [Adicionar Aplicativos](./#adicionar-aplicativos) nesta página.
7. **Restrições de funcionamento -** permite criar restrições de acesso aos apps por horário, para que seja possível definir os horários em que os apps não poderão ser acessados. Para mais informações acessar o conteúdo [Restrições de Funcionamento](./#restricoes-de-funcionamento) nesta página.

### **Configurações Gerenciadas**

Esta funcionalidade permite aos administradores alterar os requisitos de permissão necessários para a execução dos aplicativos. As configurações gerenciadas, possibilitam gerenciar de forma flexível as permissões, adequando-as conforme a necessidade específica de cada aplicação e melhorando a experiência e segurança do usuário final.

Para acessar as configurações gerenciadas de um aplicativo é necessário estar na tela "**Editar Política**" com a guia "**Aplicativos**" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos "...", localizados no final da linha e clique na opção "**Configurações Gerenciadas**".

<figure><img src="../../../../../.gitbook/assets/Captura de tela 2024-04-29 150335.png" alt="" width="179"><figcaption></figcaption></figure>

A tela a seguir será exibida:

<figure><img src="../../../../../.gitbook/assets/Captura de tela 2024-04-29 150749.png" alt=""><figcaption></figcaption></figure>

Nesta tela é possível ver a identificação do aplicativo selecionado e a tela de configuração que foi escolhida ("Configurações Gerenciadas");

{% hint style="info" %}
**NOTA**

As configurações disponíveis, vão ser exibidas conforme o que estiver disponível para cada aplicativo, ou seja, irá variar as configurações disponíveis dependendo do aplicativo selecionado. Em alguns aplicativos por exemplo, vai exibir a mensagem: _Não existem configurações disponíveis para este aplicativo._ Estas configurações de trabalho dependem da empresa que criou a aplicação.
{% endhint %}

### **Permissões**

Para acessar as configurações de permissões de um aplicativo é necessário estar na tela "**Editar Política**" com a guia "**Aplicativos**" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "**Permissões**".

![](<../../../../../.gitbook/assets/10 (2).png>)

Após o passo 2 a tela a seguir será exibida. A lista de permissões, que podem ser configuradas no aplicativo selecionado, é exibida nesta tela.

![](<../../../../../.gitbook/assets/11 (1).png>)

As permissões podem ser configuradas como: Solicitar ao usuário, Ativada ou Negada.

{% hint style="info" %}
**OBSERVAÇÃO**

Se a opção “Permissões" aparecer desabilitada no sistema, é para evitar que o usuário acesse configurações que não são relevantes para sua função. Visando garantir que o usuário não se confunda ou tente ajustar configurações que não estão dentro de suas atribuições ou necessidades específicas dentro do sistema.

Impede que os usuários finais acessem e modifiquem configurações críticas de permissões, reservando esse controle exclusivamente para administradores.&#x20;

![](<../../../../../.gitbook/assets/image (333).png>)
{% endhint %}

### **Configurações Avançadas**

Para acessar as configurações avançadas de um aplicativo é necessário estar na tela "**Editar Política**" com a guia "**Aplicativos**" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "**Configurações Avançadas**".

![](<../../../../../.gitbook/assets/12 (1).png>)

Após o passo 2 a tela a seguir será exibida. Nesta tela temos os seguintes itens:

* **Prioridade de Atualização** - Defina a prioridade de atualização do aplicativo como pré-definida, postergada ou prioritária.
* **Versão mínima -** permite definir uma versão mínima do aplicativo.

![](<../../../../../.gitbook/assets/13 (1).png>)

### **Remover Aplicativo**

Para excluir um aplicativo da política é necessário estar na tela "**Editar Política**" com a guia "**Aplicativos**" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "**Remover Aplicativo**".

![](<../../../../../.gitbook/assets/14 (1).png>)

Após o passo 2 a tela a seguir será exibida para confirmação da exclusão. Clique no botão "Remover" para **remover** o aplicativo da lista.

![](<../../../../../.gitbook/assets/15 (1).png>)

{% hint style="info" %}
**OBSERVAÇÃO**

O aplicativo será removido da listagem de aplicativos da política que está sendo editada, porém ele permanecerá nos Aplicativos Gerenciados, pode ser incluído novamente na política e pode fazer parte das configurações de outras políticas.
{% endhint %}

### **Adicionar Aplicativos**

A opção Adicionar aplicativos terá comportamentos diferentes quando o Modo Quiosque estiver ativado ou desativado.

* **Modo Quiosque Desativado:** Ao clicar no botão "**Adicionar Aplicativos**", caso seja uma política com **Modo Quiosque Desativado**, serão exibidas duas opções, a **Playstore** que contempla a   listagem de aplicativos que foram adicionados usando a [**Google Play Gerenciada**](../../../gerenciamento-de-aplicativos/google-play-gerenciada.md) e a opção **Manual**, que permite adicionar aplicativos de forma manual.

<figure><img src="../../../../../.gitbook/assets/image (129).png" alt="" width="215"><figcaption></figcaption></figure>

* **Modo Quiosque Ativado:** Caso a política que estiver sendo editada for uma política com o **Modo Quiosque** **Ativado**, ao clicar no botão **Adicionar aplicativos**, aparecerão 3 opções para adicionar os aplicativos.

<figure><img src="../../../../../.gitbook/assets/image (311).png" alt="" width="197"><figcaption></figcaption></figure>

* **Sistema**

1. Clique na opção “**Sistema"**, e abrirá a tela “**Aplicativos do sistema**"
2. Selecione a Fabricante e o Dispositivo
3. Selecione um ou mais aplicativos clicando no checkbox
4. Clique no botão "**Adicionar selecionados**"

<figure><img src="../../../../../.gitbook/assets/image (312).png" alt=""><figcaption></figcaption></figure>

* **Playstore**&#x20;

1. Clique na opção “**Playstore**", e abrirá a tela “**Adicionar Aplicativos**"
2. Selecione um ou mais aplicativos clicando no checkbox
3. Clique no botão "**Adicionar selecionados**"

<figure><img src="../../../../../.gitbook/assets/image (313).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**IMPORTANTE**

Os aplicativos precisam ser primeiramente adicionados usando a **Google Play Gerenciada**.&#x20;
{% endhint %}

* **Manual**

1. Clique na opção “**Manual**", e abrirá a tela “**Adicionar Aplicativos Manualmente**"
2. Preencha os campos: Nome do App (opcional), Nome do Pacote e clicar em "**Adicionar**"

O tipo de instalação ficará como "Disponível", e permitirá alterar o tipo de instalação do app para  as opções: Disponível, Pré-instalado, Instalação forçada ou Bloqueado, e vai enviar para o dispositivo o app com o tipo de instalação definido ao salvar a política.&#x20;

{% hint style="info" %}
**NOTA**

Caso o aplicativo não esteja na Google Play, as opções "Pré-instalado" e "Instalação forçada" terão o mesmo efeito que a opção "Disponível". Ou seja, o aplicativo fica disponível para instalação, o usuário tem a opção de instalá-lo conforme sua conveniência. Não é instalado automaticamente no dispositivo.
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/image (314).png" alt="" width="470"><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao criar uma política com modo de gerenciamento Android Block SIM, automaticamente na aba Aplicativos, já estará adicionado o aplicativo Block SIM com modo de instalação Forçada, ou seja, quando o usuário realizar a ativação do \<NomeProduto> utilizando esta política, já será instalado automaticamente o Block SIM, sem que ele precise baixar na Play Store.
{% endhint %}

* **Remota**

Os aplicativos enviados via instalação remota, através do menu ["Instalação Remota de Aplicativos"](../../../gerenciamento-de-aplicativos/instalacao-remota-de-aplicativos.md), serão exibidos na listagem de aplicativos com a Origem  = "Remota" e com o tipo de instalação 'Disponível' com a edição bloqueada.

### Restrições de Funcionamento

Para definir restrições de funcionamento de aplicativos por dias e horários, é necessário clicar no ícone de restrições de funcionamento na linha referente ao aplicativo desejado. A imagem a seguir destaca:&#x20;

1. Ícones para acessar a opção "Restrições de Funcionamento";&#x20;
2. Botão seletor para ativar restrições.

A opção de "Restrições de Funcionamento" está disponível para todos os aplicativos, exceto: aplicativo do sistema \<nome\_produto>, Kiosk Launcher, Block Sim e Remote View.  Quando o aplicativo já possui restrição de funcionamento, o seu ícone de restrição de funcionamento mudará para ![](<../../../../../.gitbook/assets/image (293).png>).

<figure><img src="../../../../../.gitbook/assets/Captura de pantalla 2024-03-07 a la(s) 15.51.55.png" alt=""><figcaption></figcaption></figure>

Para ativar as restrições:

1. Selecione o campo “Ativar restrições".
2. Informe o horário de inicio e fim do período para cada dia, ou selecione o campo "Restringir"  para bloquear o funcionamento o dia inteiro.
3. Clique em "Confirmar" para salvar as alterações. A política enviará as informações de restrições do aplicativo para os dispositivos vinculados<mark style="color:purple;">.</mark>
