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

# Configurações iniciais e níveis

Ao acessar o **\<NomeProduto>**, o usuário terá acesso às configurações e funcionalidades.

### **Configurações Iniciais**

As primeiras configurações, recomendável a serem realizadas no portal são:

* **Perfil de Consumo** - para que todos os dados capturados possam ser analisados corretamente (detalhado na seção **“Perfil de Consumo”** deste manual).
* **Dia de início do ciclo** - para definir a data de início da contabilização dos dados que serão analisados (detalhado na seção **“Configurações Gerais”** deste manual).

### **Níveis de Configurações**

As configurações podem ser realizadas em três níveis (Empresa/ Grupo/ Usuário) e essas configurações são aplicadas aos dispositivos da seguinte forma:

* **Empresa (Geral)** – Ao criar uma configuração nesse nível o sistema verificará se existe uma regra configurada no nível de usuário. Caso não exista, verifica se existe uma regra configurada no nível de Grupo e, se também não existe, o sistema aplicará nos dispositivos da Empresa a regra configurada no nível da Empresa;
* **Grupo** – Ao criar uma configuração nesse nível, o sistema verificará se existe uma configuração no nível de Usuário, caso não exista, o sistema aplicará nos dispositivos do grupo a regra configurada no nível do Grupo;
* **Usuário** – Ao criar uma configuração nesse nível, o sistema aplicará no dispositivo do usuário a regra configurada.

A figura a seguir mostra a tela de configuração de perfil de consumo que é acessada no menu **"Configurações"**. Um retângulo destaca o acesso às guias “Geral", "Grupos" e "Usuários".

<figure><img src="../../.gitbook/assets/image (220).png" alt="" width="563"><figcaption></figcaption></figure>
