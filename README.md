# PHX STATUS

Bot de monitoramento de status e disponibilidade para Discord.

[Adicionar ao Discord](https://discord.com/oauth2/authorize?client_id=1567392038285082737&permissions=84992&integration_type=0&scope=bot+applications.commands) · [Acessar o site](https://darkerzinn.github.io/phxstatus/)

## Sobre o bot

O PHX STATUS monitora o site e os serviços da Phoenix Service Tool. Ele mantém um painel de status que se atualiza automaticamente e pode enviar avisos ao canal configurado quando um serviço fica online ou offline.

Cada servidor configura o bot de forma independente e pode escolher entre português e inglês.

> **Projeto independente:** o PHX STATUS não é oficial, patrocinado nem afiliado à Phoenix Service Tool.

## Recursos

- **Painel automático:** publica e atualiza o painel de status.
- **Alertas de disponibilidade:** avisa no canal configurado quando um serviço muda entre online e offline.
- **Configuração por servidor:** idioma, monitoramento, alertas e canal de logs são definidos para cada servidor.
- **Verificação manual:** permite solicitar uma checagem imediata.

## Comandos

| Comando | Descrição |
| --- | --- |
| `/painel criar` | Cria o painel de status no servidor. |
| `/painel remover` | Remove o painel de status. |
| `/config` | Configura idioma, monitoramento, alertas e canal de logs. |
| `/info` | Mostra informações do bot e do monitoramento. |
| `/verificar` | Executa uma verificação imediatamente. |

## Adicionar ao servidor

[Convide o PHX STATUS](https://discord.com/oauth2/authorize?client_id=1567392038285082737&permissions=84992&integration_type=0&scope=bot+applications.commands) e autorize o acesso ao servidor desejado pelo Discord.

## Site e documentos

- **Site:** https://darkerzinn.github.io/phxstatus/
- **Termos de Serviço:** https://darkerzinn.github.io/phxstatus/terms.html
- **Política de Privacidade:** https://darkerzinn.github.io/phxstatus/privacy.html

O site é estático e está hospedado pelo GitHub Pages. Este repositório contém os arquivos do site e sua documentação; o código executável do bot não está incluído.

## Dados e hospedagem

O bot usa um banco SQLite hospedado na Discloud. Segundo a configuração informada pelo responsável, o banco guarda somente configurações por servidor, incluindo o canal de logs selecionado. O conteúdo das mensagens de log não é armazenado no banco. As configurações são mantidas sem prazo automático de expiração e a exclusão é tratada manualmente mediante solicitação pelo e-mail informado na Política de Privacidade.

## Arquivos do site

| Arquivo | Finalidade |
| --- | --- |
| `index.html` | Página inicial do PHX STATUS. |
| `styles.css` | Estilos responsivos do site. |
| `logophxstatus.png` | Logo usada na navegação. |
| `terms.html` | Termos de Serviço. |
| `privacy.html` | Política de Privacidade. |

## Publicação

O GitHub Pages publica a raiz da branch `main`. Para atualizar o site, envie as alterações dos arquivos do site para essa branch.
