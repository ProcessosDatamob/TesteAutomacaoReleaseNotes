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

# Ajustes e Correções da Versão - V 12.0.0

Nesta versão, foram realizadas correções listadas abaixo:

1. **Remover Bloqueio de CHIP (Block SIM) -** Ao enviar comando Remover Bloqueio de Chip pelo menu Dispositivos no portal, estava ocorrendo a remoção do bloqueio de tela de forma indevida;
2. **Remover Bloqueio de Tela (Block SIM) -** Quando o comando Remover Bloqueio de Tela era enviado para o dispositivo pelo menu Dispositivos no portal, o dispositivo continuava pedindo a senha. Mesmo ao tentar inserir a senha anterior, ou qualquer outra senha, o acesso não era liberado.
3. **Configurações - Gerenciar Políticas - Editar Política -** Na aba Aplicativos, o  contador do rodapé da página de aplicativos da política estava incorreto, pois não estava refletindo a quantidade de aplicativos que haviam inclusos na política, ou seja, mostrava um número inferior a real quantidade;
4. **Configurações** - **Gerenciar Redes Wi-fi -** O campo Senha do SSID, estava obrigatório, então ao selecionar uma rede WPA-EAP, que não possui este tipo de senha, sem preencher o campo, o sistema não permitia salvar a rede.
