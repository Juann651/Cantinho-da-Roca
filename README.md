# Cantinho da Roça

Catálogo online de uma loja de produtos naturais e a granel. O cliente navega pelas categorias, vê foto e descrição de cada item e faz o pedido pelo **WhatsApp** com um clique.

Feito com **HTML, CSS e JavaScript puro**, em uma única página, sem framework e sem etapa de build.

## Funcionalidades

- Mais de 110 produtos organizados em 10 categorias: **Temperos, Snacks, Suplementos, Chás, Grãos, Potes, Pães, Condimentos, Corporal e Biscoitos**
- Cada produto mostra foto, nome, descrição curta, avaliação em estrelas, gramagem e preço, além de um menu **⋮** com informações detalhadas
- O botão **🛒 Comprar** abre o WhatsApp da loja para fazer o pedido
- Menu de navegação por categoria (versão para celular com botão ☰)
- Botão "↑ Topo" para voltar ao início
- Links para WhatsApp e Instagram da loja

## Estrutura

```
Cantinho-da-Roca/
├── index.html    # catálogo completo (produtos, menu e scripts)
├── style.css     # estilos
└── imagens/      # fotos dos produtos e ícones
```

## Como rodar

Não precisa instalar nada. Abra a pasta no VS Code e rode o `index.html` com a extensão **Live Server**, ou abra o arquivo direto no navegador.

## Como adicionar ou editar produtos

Cada produto é um bloco no `index.html`, dentro da seção da sua categoria. Para incluir um novo:
1. Coloque a foto na pasta `imagens/`.
2. Copie um bloco de produto existente, na categoria desejada.
3. Troque o nome, a descrição, as informações do menu ⋮, a gramagem, o preço, o caminho da imagem e o link do WhatsApp.

## Personalização

O número de WhatsApp da loja e o link do Instagram estão escritos diretamente no `index.html`. Troque pelos dados reais antes de publicar a sua versão.

## Observação

O catálogo é estático: não há carrinho nem pagamento no site. Todo o atendimento e a finalização do pedido acontecem pelo WhatsApp.
