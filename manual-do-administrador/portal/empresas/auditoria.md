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

# Auditoria

Esta tela do sistema tem como objetivo permitir a visualização e gerar relatórios de algumas ações realizadas no portal.&#x20;

As alterações auditáveis são: mudanças na empresa, registro da empresa na Google, exclusão da empresa na Google, aceitação dos termos de uso e política de privacidade no portal e aceitação do termo de uso e política de privacidade na aplicação. O sistema permite filtrar por data, usuário, atividade e categoria.&#x20;

Para saber como utilizar esta tela siga os passos descritos nesta sessão:

1. Clique no menu “**Empresa**” e selecione o submenu “**Auditoria**”.

<figure><img src="../../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

2. Selecione o intervalo de datas que deseja consultar as informações.
3. Utilizar o campo “Usuários” caso queira consultar informações de um usuário específico.
4. É possível também filtrar por atividade através do campo “Atividades”, sendo que os tipos disponíveis são: Inserção, Exclusão, Edição, Termos de Uso e Política de Privacidade.
5. Pode ser selecionado também o tipo de categoria, sendo elas: Empresa, dispositivo ou Política.
6. Para exportar as informações em Excel, basta clicar no botão “Excel”.

{% hint style="info" %}
**NOTA**

No relatório exportado em Excel tem uma coluna "**Alterações**" onde é possível consultar os campos modificados.
{% endhint %}

7. Para copiar as informações, basta clicar no botão “Copiar”.

<figure><img src="../../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**NOTA**

Clicando em ↑↓ é possível ordenar a coluna de Data e Hora.
{% endhint %}

### **Informação sobre os filtros das ações do portal**

A partir dos filtros é possível identificar as ações do portal que possuem registro, para verificar as alterações realizadas e rastrear as mudanças de comportamento. Quando selecionar uma opção de “**Atividade**” então apresentará as opções de “**Categoria**” que possuem registros conforme combinações descritas na tabela abaixo:

<table><thead><tr><th width="277">Atividade</th><th>Categoria</th></tr></thead><tbody><tr><td>Inserção</td><td><ul><li>Empresa</li><li>Dispositivo</li><li>Política</li></ul></td></tr><tr><td>Edição</td><td><ul><li>Empresa</li></ul></td></tr><tr><td>Exclusão</td><td><ul><li>Dispositivo</li><li>Política</li><li>Usuário</li></ul></td></tr><tr><td>Aceite</td><td><ul><li>Empresa</li><li>Dispositivo</li><li>Usuário</li></ul></td></tr><tr><td>Envio</td><td><ul><li>Empresa</li><li>Dispositivo</li><li>Política</li><li>Usuário</li></ul></td></tr></tbody></table>

{% hint style="info" %}
**NOTA**

Quando selecionar um usuário administrador irá exibir sua atividade e categoria.
{% endhint %}
