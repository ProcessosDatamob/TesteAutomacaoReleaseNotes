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

# Dashboard

Esta tela do sistema tem como objetivo possibilitar ao usuário a visualização e análise dos diversos dados de consumos e usos coletados dos dispositivos. Para saber como acessar e analisar os dados exibidos no Dashboard, siga os passos descritos nesta seção.

A tela de Dashboard pode ser considerada a “**Tela Inicial**” do sistema, pois é exibida assim que acessa o Portal, mas também pode ser acessada clicando no menu “**Dashboard**”. Em um primeiro acesso, os indicadores de usuários, dispositivos e consumos não terão ainda informações, e estarão zerados.

<figure><img src="../../.gitbook/assets/image (435).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Ao passar o mouse sobre o ícone de informações ao lado de cada gráfico, você pode visualizar uma descrição detalhada que explica os dados apresentados, facilitando o entendimento do conteúdo exibido e o contexto do gráfico.

![](<../../.gitbook/assets/Captura de tela 2024-09-13 135732.png>)
{% endhint %}

Ao acessar a tela, todas as informações serão exibidas separadas por seções. Cada seção corresponde a um dado diferente, coletado do dispositivo e todas as informações são exibidas de acordo com as opções selecionadas no filtro (Empresa, Grupo ou Usuário).

Ao habilitar a opção do filtro “**Roaming internacional**”, no canto superior direito da tela, o sistema exibirá também as informações coletadas quando os dispositivos estiverem utilizando uma conexão em Roaming.

![](<../../.gitbook/assets/1 (10).png>)

Os filtros “Empresa”, “Grupo” e “Usuário” permitem realizar uma análise dos dados dos dispositivos de um nível determinado.

Clique no filtro “**Empresa**”, digite e selecione o nome da empresa para exibir as informações coletadas de todos os dispositivos.

![](<../../.gitbook/assets/2 (7).png>)

Clique no filtro “**Grupo**”, digite e selecione o nome do grupo, para exibir as informações coletadas de todos os dispositivos que fazem parte de um Grupo.

![](<../../.gitbook/assets/3 (4).png>)

Clique no filtro “**Usuário**” digite e selecione o usuário, para exibir as informações coletadas do dispositivo do usuário.

![](<../../.gitbook/assets/4 (2).png>)

No canto superior direito da tela, temos alguns ícones que tem as seguintes funcionalidades:

* **Notificações** - No ícone ![](https://lh7-us.googleusercontent.com/LIqOOPLli_-KQv0gbnkeBAgAG1_EOWziv1kRkMmMtO2dOIvA17vDOpWbmtTw5_2RUg1D-mUt1PWNvciaKyYAHysUPk47UBQ8yIufI8DmrX523Zqn_ntcDKa0ff0KqkWZeeaDLHoJF9MB762IkIm6vw)o administrador pode ver as notificações do portal, por exemplo, ao solicitar a geração de um relatório.&#x20;
* **Admin** - No ícone ![](https://lh7-us.googleusercontent.com/XnN5TtWJIzJYNZfcb_18o7Mzx_RrJYRxyodSpfkBQuPCce64vPyFVeN6g6umpqRYxKpCZ_v8JGiU3iuMYa4vOmakPCagWJmIJFLK3dsOj3f7Ta1mH0KwNpxCTIGDJ5xs1IUicW1Ncuv2XJcBMyJvGg) exibe a opção para que o administrador possa sair do portal e também exibe a versão atual da solução o número da versão.

### **Barra de Status**

A barra de status do Dashboard mostra a situação atual de todos os usuários e licenças da empresa.

<figure><img src="../../.gitbook/assets/image (436).png" alt=""><figcaption></figcaption></figure>

### **Total de Usuários**

Este indicador exibe o número total de usuários de dispositivos que utilizam o aplicativo **\<NomeProduto>.**

#### **Total de Licenças&#x20;**<mark style="color:blue;">**Contratadas**</mark>

Este indicador exibe o número total de licenças disponíveis no **\<NomeProduto>**.

<figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure>

### **Licenças não instaladas no portal**

Este indicador exibe o número total de licenças que não possuem dispositivo registrado no portal. Ou seja, são as licenças disponíveis.

Ao clicar nesse indicador, o sistema exibirá a tela de "**Licenças Contratadas**". Para saber como utilizar essa tela, leia a seção [“**Licenças Contratadas**”](dashboard.md#total-de-licencas).

<figure><img src="../../.gitbook/assets/image (438).png" alt=""><figcaption></figcaption></figure>

### **Dispositivos**

Este indicador exibe o número total de dispositivos que estão ativos no sistema e os dispositivos sem comunicação. Além disso, possibilita ao administrador ter a visibilidade dos dispositivos que estão em Modo Quiosque.

<figure><img src="../../.gitbook/assets/image (439).png" alt="" width="240"><figcaption></figcaption></figure>

* **Total -** Esses dispositivos são considerados “**Ativos**” ao instalar e ativar o aplicativo **\<NomeProduto>.**\
  Ao clicar em "**Total**” o indicador exibirá a tela “**Lista de Dispositivos**” contendo o relatório com as principais informações dos dispositivos ativos.
* **Sem Comunicação -** Este indicador exibe o número total de dispositivos que não estão enviando dados aos servidores a um período prolongado. Ao clicar em "**Sem Comunicação**” o sistema exibe a tela de dispositivos sem comunicação.

<figure><img src="../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

Esta falta de comunicação pode ocorrer quando o dispositivo se encontrar nas seguintes situações:

* Desligado;
* Sem conexão de internet;
* Aplicativo desinstalado;

O cálculo de tempo para considerar o dispositivo sem comunicação é o tempo de sincronismo configurado na empresa + 10 minutos.

Caso o dispositivo fique sem enviar consumos gerais/informações do dispositivo, por um tempo acima do tempo de sincronismo definido + 10 minutos, ele altera o status para **Sem Comunicação.**

Para que o dispositivo volte a comunicar, o administrador pode enviar uma mensagem com o comando **START\_SERVICES** através do menu [Mensagens ](mensagens-e-comandos/)do portal.

Ao clicar no indicador **Sem comunicação ,**&#x6F; sistema exibirá uma tela contendo o relatório com as informações dos dispositivos que estão sem comunicação.

### **Consumo de Dados Móveis**

Este indicador exibe o percentual de consumo de dados móveis dos dispositivos durante o ciclo em relação ao limite total configurado no Perfil de Consumo. Caso não seja configurado um limite no Perfil de Consumo, o gráfico não exibirá o percentual, e o sistema exibirá apenas o valor total de dados em MB utilizados.

### **Consumo de SMS**

Este indicador exibe o percentual de consumo de SMS enviados pelos dispositivos durante o ciclo em relação ao limite total configurado no Perfil de Consumo. Caso não seja configurado um limite no Perfil de Consumo, o gráfico não exibirá o percentual, e exibirá apenas o valor total de SMS utilizados.

### Consumo total de dados

Este gráfico, possibilita visualizar o consumo de dados, incluindo dados móveis, Wi-Fi e dados em roaming, no **Dashboard** do portal. A funcionalidade permite uma análise detalhada do uso de dados nos dispositivos.

O gráfico exibirá:

* **Porcentagem do consumo de dados móveis locais** em relação ao total de dados (móveis + Wi-Fi).
* **Porcentagem do consumo de dados via Wi-Fi** em relação ao total de dados (móveis + Wi-Fi)<mark style="color:blue;">.</mark>

<figure><img src="../../.gitbook/assets/image (440).png" alt="" width="230"><figcaption></figcaption></figure>

**Legenda Exibida:**

* **Total:** Soma de dados móveis e Wi-Fi.
* **Dados móveis locais:** Consumo de dados móveis em redes locais.
* **Wi-Fi:** Consumo total de dados via Wi-Fi.

Ao ativar a opção **Roaming**. O gráfico exibido será atualizado para incluir o **consumo de dados em roaming**.

O gráfico exibirá:

* **Porcentagem de dados móveis locais** (móveis + roaming + Wi-Fi).
* **Porcentagem de dados móveis em roaming** (móveis + roaming + Wi-Fi).
* **Porcentagem de Wi-Fi** (móveis + roaming + Wi-Fi).

<figure><img src="../../.gitbook/assets/image (441).png" alt="" width="233"><figcaption></figcaption></figure>

**Legenda Exibida:**

* **Total:** Soma de dados móveis, Wi-Fi e roaming.
* **Dados móveis locais:** Consumo de dados móveis em redes locais.
* **Dados móveis em roaming:** Consumo de dados móveis em roaming.
* **Wi-Fi:** Consumo total de dados via Wi-Fi.

Ao passar o mouse sobre o gráfico ou legenda no **Dashboard**, o sistema exibirá uma caixa de texto.

A caixa de texto exibirá:

* O **tipo de dado** (móvel, Wi-Fi ou roaming).
* A **porcentagem** em relação ao total de dados.
* O **valor exato** do consumo de dados.

### **Consumo de Dados por Aplicativo**

Este gráfico exibe nome e valor da porcentagem dos 5 aplicativos que mais consumiram dados móveis e os 5 aplicativos que mais consumiram dados em WiFi durante o ciclo, basta clicar na opção de visualização desejada (Dados móveis ou WiFi). Os dados exibidos, são ordenados conforme o percentual.

O valor percentual de cada um dos 5 aplicativos é calculado em relação à soma total de consumo de todos os aplicativos durante o ciclo, os dados são atualizados sempre que acessar a tela.

Ao clicar no botão “Ver lista completa” o sistema exibirá a tela com as informações de todos os aplicativos. Para saber como utilizar essa tela, leia a seção [Aplicativos](configuracoes/editar-politica/aplicativos/) deste manual.

Isso oferece aos usuários uma visão mais detalhada e específica do consumo de dados, permitindo uma análise mais precisa e segmentada, tanto em redes móveis quanto em WiFi.

<figure><img src="../../.gitbook/assets/image (442).png" alt=""><figcaption></figcaption></figure>

### **Consumo de Dados por Usuário**

Este gráfico exibe os 5 usuários que mais consumiram dados móveis e os que mais consumiram dados em WiFi durante o ciclo, basta clicar na opção de visualização desejada (Dados móveis ou WiFi). Os dados exibidos, são ordenados em percentual.

O valor percentual de cada um dos 5 usuários é calculado em relação à soma total de consumo de todos os usuários durante o ciclo.

Ao clicar no botão “Ver lista completa” o sistema exibirá a tela com as informações de consumos da empresa. Para saber como utilizar essa tela, leia a seção [Consumos](empresas/consumo-da-empresa.md) deste manual.

<figure><img src="../../.gitbook/assets/image (443).png" alt=""><figcaption></figcaption></figure>

### **Tempo de Uso por Aplicativo**

Este gráfico exibe os 5 aplicativos que mais foram utilizados durante o ciclo. Este tempo é contabilizado apenas quando o aplicativo está em uso, e não precisa estar consumindo dados. Os aplicativos em segundo plano não são contabilizados nesta análise.

O valor percentual de cada um dos 5 aplicativos é calculado em relação à soma total do tempo de uso de todos os aplicativos durante o ciclo.

Ao clicar no botão “Ver lista completa” o sistema exibirá a tela com as informações de todos os aplicativos.

<figure><img src="../../.gitbook/assets/image (444).png" alt=""><figcaption></figcaption></figure>

### Inventário de Dispositivos

Este indicador mostra a percentagem dos 5 fabricantes de dispositivos ativos. O valor percentual de cada um dos cinco fabricantes é calculado em relação à soma total de todos os dispositivos ativos.

### Sites mais visitados&#x20;

Este indicador mostra a percentagem dos 5 locais mais visitados nos dispositivos durante o ciclo. O valor percentual de cada um dos 5 sítios é calculado em relação à soma total de todos os acessos aos sítios durante o ciclo.

{% hint style="warning" %}
**ATENÇÃO**&#x20;

Os sites visitados são obtidos pelo navegador web padrão do sistema **\<NomeProduto>**. Este navegador é chamado Security Browser e precisa estar instalado e configurado nos dispositivos. Para mais informações sobre administração e configuração do navegador, visite a seção "Security Browser".
{% endhint %}

### **Indicador de Consumo e Histórico**

Este indicador exibe em percentuais os dados móveis e SMS consumidos nos últimos 6 ciclos.

Para realizar a análise individual dos consumos de dados móveis ou SMS, acesse o item **"Consumos"** no menu "**Empresas**".

### **Indicador de Novos Usuários de Dispositivos e Histórico**

Este indicador exibe a quantidade de usuários de dispositivos ativados nos últimos 6 ciclos e a evolução dos novos usuários do ciclo atual em relação aos do trimestre e do semestre.

Para realizar a análise individual dos usuários de dispositivos, clique em "**Lista de Dispositivos**" no menu "[**Dispositivos**](dashboard.md#dispositivos)".

### **Localização dos Dispositivos**

O mapa exibe a última localização dos dispositivos. Para que a localização seja exibida e atualizada, o dispositivo deve estar conectado à internet, deve haver sinal de GPS e a configuração de "**Modo de Localização**" deve estar "**Ativa**" em Localização na política aplicada ao dispositivo.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-09-13 140443.png" alt=""><figcaption></figcaption></figure>

Caso o sistema não carregar as localizações no mapa, clique no botão "Exibir localizações”,  então elas serão exibidas conforme tela abaixo:

<figure><img src="../../.gitbook/assets/image (76).png" alt="" width="281"><figcaption></figcaption></figure>

A regra de agrupamento dos dispositivos é a seguinte:

* Azul: maior igual 5
* Amarelo: maior igual 10
* Vermelho: maior igual 100
* Magenta: maior ou igual a 1.000
* Violeta: maior ou igual a 10.000

O símbolo de gota laranja com um número dentro significa os pontos que o usuário passou em ordem numérica no dia.

Leia a seção “**Gerenciar Políticas**” deste manual para saber como ativar o "**Modo de Localização**" dos dispositivos.

A localização dos dispositivos é exibida com um marcador no mapa, que pode estar na cor verde ou vermelha, dependendo do status do dispositivo (verde = enviando dados e vermelho = sem envio de dados). Para visualizar as informações da localização, clique no marcador.

Utilize os recursos do mapa para otimizar a visualização das localizações.

### **Manuais para Download**

Nesta tela teremos acesso aos manuais para download. Ao clicar no Saiba mais, será exibida a tela com Documentos e Materiais de Apoio.

### **Alguma Dúvida**

Através da sessão “[**Alguma Dúvida**](dashboard.md#alguma-duvida)?”, teremos acesso a tela onde é possível visualizar as perguntas frequentes realizadas pelos usuários:

Ao clicar em Saiba mais, seremos direcionado a tela a seguir, onde é possível realizar uma pesquisa através do campo de digitação livre ou então filtrar por categoria.

Ao rolar a tela mais para baixo, teremos acesso a lista de perguntas frequentes

E no final da página teremos acesso também aos manuais para Download , assim como temos no Dashboard.

<figure><img src="../../.gitbook/assets/Ajuda" alt="" width="452"><figcaption></figcaption></figure>
