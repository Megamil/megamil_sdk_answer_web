# Megamil SDK para Web

Bem-vindo ao Megamil SDK para Web, uma ferramenta poderosa para incorporar uma funcionalidade de chat em seu site. Este SDK foi desenvolvido para fornecer uma experiência de chat intuitiva e personalizável para os usuários do seu site.

## Instruções de Integração

Para integrar o Megamil SDK em seu site, siga estas simples instruções:

### Passo 1: Inclua os Arquivos CSS e JavaScript

Adicione os seguintes links ao cabeçalho do seu documento HTML:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/Megamil/megamil_sdk_answer_web/main/assets/megamil_sdk.css">
    <script src="https://cdn.rawgit.com/Megamil/megamil_sdk_answer_web/main/assets/megamil_sdk.js" 
      data-sdk="megamil" 
      data-sdk-token="SEU-TOKEN" 
      data-placeholder="Faça uma pergunta"
      data-error-message-default="Desculpe, tivemos um problema"
      data-unicode-icon-send="&#x1F680;"
      data-unicode-icon-open="&#x1F680;"
      data-ia-name="[Megamil IA Web] "
      data-chat-color="#F0F0F0"
      data-from-me-color="#1abc9c"
      data-from-them-color="#3498db"
      data-from-me-text-color="#ffffff"
      data-from-them-text-color="#ffffff"
      data-unicode-icon-close="&#x58;"></script>
  </head>
```

Se preferir faço o download dos arquivos `megamil_sdk.css` e `megamil_sdk.js` em seu projeto e aponte para eles localmente, porém pode não estar sempre com a última atualização ativa.

### Passo 2: Configuração dos Atributos

Certifique-se de configurar os atributos necessários no script:

- `data-sdk`: **Não alterar** - Indica o SDK que está sendo utilizado.
- `data-sdk-token`: **Substituir com seu token** - Forneça seu token único para autenticação.
- `data-placeholder`: **Opcional** - Especifica o texto do espaço reservado no campo de texto do chat.
- `data-error-message-default`: **Opcional** - Define uma mensagem padrão em caso de erros.
- `data-unicode-icon-send`: **Opcional** - Código Unicode para o ícone do botão de enviar.
- `data-unicode-icon-open`: **Opcional** - Código Unicode para o ícone do botão de abrir o chat.
- `data-unicode-icon-close`: **Opcional** - Código Unicode para o ícone do botão de fechar o chat.
- `data-ia-name`: **Opcional** - Nome para a IA.
- `data-chat-color`: **Opcional** - Cor do botão flutuante e do modal.
- `data-from-me-color`: **Opcional** - Cor para o balão de fala do usuário.
- `data-from-them-color`: **Opcional** - Cor para o balão de fala da IA.
- `data-from-me-text-color`: **Opcional** - Cor para o texto do usuário.
- `data-from-them-text-color`: **Opcional** - Cor para o texto da IA.

### Passo 3: Aproveite o Chat!

Com esses passos simples, você terá uma experiência de chat totalmente funcional em seu site, proporcionando uma interação eficaz com os visitantes.

## Resultado
<div style="overflow: hidden; white-space: nowrap;">
    <img src="prints/web_example.png" width="200">
</div>