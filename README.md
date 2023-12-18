# pfSense_StatusMultiWan_Telegram
- Script for pfSense: monitors multi-WAN gateway status and sends notifications via Telegram 


## Donation | Doações

(En)      Support our project via Pix or PayPal. <br />
(Pt-Br) Apoie nosso projeto via Pix ou PayPal: <br />

- Brazilian Pix: d56da244-4dc5-4f77-be6d-28e94fdd46b2 <br />
- Paypal:  https://bit.ly/MonitTelegram <br /><br />


## Screenshot
![Screenshot](https://github.com/macielmeireles/OpnSense-MultiWan-Telegram/blob/main/screenshot.jpg)


### Installation
1) Log in as an administrator via pfSense GUI.
2) Click on System, Patches.
3) Click on Add New Patch.
4) Fill in the `description` field, suggestion: `telegram_status_multiwan`.
5) Fill in the `Patch Contents` field with the content of the file in raw format. For convenience, the link is here: `https://raw.githubusercontent.com/macielmeireles/pfSense_StatusMultiWan_Telegram/main/pfsense_telegram_status_multiwan.patch`.
6) In the `Path Strip Count` field, change to 1.
7) Click on `Save` at the end of the page.
8) Apply, to use click on the apply button next to the name of the chosen patch in item 4.
9) If you prefer, it is possible to click on the revert button.

Easter egg: if you want to see the original message, you can edit the patch by changing the variable `$origMsg = true;`.

<br /><br />

### Instalação
Claro, aqui está a versão em português técnico dos passos:

1) Faça login como administrador via GUI do pfSense.
2) Clique em Sistema, Patches.
3) Clique em Adicionar Novo Patch.
4) Preencha o campo `descrição`, sugestão: `telegram_status_multiwan`.
5) Preencha o campo `Conteúdo do Patch` com o conteúdo do arquivo no formato raw. Para facilitar, o link está aqui: `https://raw.githubusercontent.com/macielmeireles/pfSense_StatusMultiWan_Telegram/main/pfsense_telegram_status_multiwan.patch`.
6) No campo `Contagem de Retirada de Caminho`, altere para 1.
7) Clique em `Salvar` no final da página.
8) Aplique, para usar clique no botão aplicar ao lado do nome do patch escolhido no item 4.
9) Se preferir, é possível clicar no botão reverter.
Em português técnico, você poderia dizer:

Easter egg: Se você quiser ver a mensagem original, pode editar o patch alterando a variável `$origMsg = true;`.


