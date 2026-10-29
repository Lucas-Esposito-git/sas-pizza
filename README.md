# Forno & Sabor — Front-end demonstrativo

Site mobile-first (HTML, CSS e JavaScript), sem backend e sem instalação de dependências.

## Como testar
Abra `index.html` no navegador. Para executar com servidor local: `npx serve .` ou `python -m http.server 3000` na pasta do projeto e acesse `http://localhost:3000`.

## Como publicar na Vercel
1. Descompacte o ZIP e envie a pasta `forno-sabor-demo` a um repositório GitHub.
2. Na Vercel, clique **Add New → Project**, importe o repositório.
3. Framework Preset: **Other**. Build Command: deixe vazio. Output Directory: `.` (pasta raiz). Deploy.
4. Compartilhe o link `*.vercel.app` no celular.

## Personalização
- `app.js`: objeto `CONFIG` (nome, taxa/tempo de entrega) e lista `MENU` (preços, sabores e imagens).
- `styles.css`: cores no início do arquivo em `:root`.
- `index.html`: título, metadados e fontes.

## Funcionalidades da demonstração
Busca e filtros, seleção de sabor, tamanho e borda, quantidades, carrinho persistido com `localStorage`, retirada/entrega, formulário, escolha de pagamento e confirmação com número de pedido. O histórico do último pedido aparece no acompanhamento.

## Limitações
Este projeto **não** faz pagamentos, consulta CEP, usa backend, envia pedidos, envia WhatsApp ou rastreia motoboy. Tudo é **simulado no navegador**. Não colete dados reais de clientes nesta demonstração. As fotos vêm da Unsplash por URL pública e exigem conexão à internet. Elas são ilustrativas, não fotos da pizzaria; confira a licença/uso de cada foto antes de uma implantação comercial.
