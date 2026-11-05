# Pão Caseiro da Claudia

Site responsivo em português, feito com HTML, CSS e JavaScript, usando Vite.

## Desenvolvimento

```sh
npm install
npm run dev
```

## Publicação

`npm run build` gera a pasta `dist`, pronta para hospedagem estática.

## Antes de publicar

- Configure `WHATSAPP_NUMBER` no início de `src/main.js` com o número oficial (país + DDD + telefone, apenas dígitos). Sem número, os botões exibem uma mensagem de contato em breve, sem redirecionar para terceiros.
- Confirme os produtos com a cliente. Os três itens atuais são ilustrativos, pois não foi fornecida uma lista de produtos. Edite o array `products` em `src/main.js`.
- As fotografias são ilustrativas geradas por IA; substitua por fotos reais quando disponíveis.
- A logo usada é o arquivo oficial fornecido no anexo.
- Não foram inventados preços, endereço, horário, avaliações ou condições de entrega.

## Recursos

Filtros por categoria, menu mobile acessível, mensagens individuais de pedido pelo WhatsApp, diálogo com fechamento por Escape, imagens WebP, carregamento tardio de imagens secundárias e suporte a movimento reduzido.
