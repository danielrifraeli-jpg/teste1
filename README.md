# INVEST KEMP — Landing Page Cinematográfica

Landing page estática, responsiva e pronta para hospedagem em Vercel, Netlify ou hospedagem comum.

## Incluído
- Hero cinematográfico com imagem aérea de Vila Velha e efeito parallax.
- Identidade visual azul-marinho + azul + laranja, baseada nos logos enviados.
- 3 pontos de captura do formulário (hero, seção de cadastro e CTA final).
- CTA fixo no mobile.
- Formulário funcional em modo estático usando localStorage.
- Área administrativa no rodapé, protegida pelo código `7410`.
- Tabela de cadastros e exportação CSV.
- Seções de KEMP, Carlos Simões, Vila Velha, programação, networking e critérios de participação.
- Animações de entrada e navegação suave.

## Importante sobre os cadastros
Nesta versão, o formulário grava os leads no `localStorage` do navegador. Isso permite testar tudo imediatamente, mas não centraliza cadastros de diferentes visitantes.

Para produção, conecte o `submit` a Supabase/Vercel Postgres ou outro banco. A interface administrativa já está preparada visualmente para receber essa integração.

## Imagem de Vila Velha
O hero usa uma imagem aérea externa como background:
https://viajarabrasil.com/wp-content/uploads/2020/05/Foto1-Vila-Velha-A%C3%A9reas.jpg

Recomenda-se substituir por uma foto licenciada/comercial própria antes de publicar, caso o uso da imagem atual não esteja autorizado.

## WhatsApp
O texto informa que a equipe entrará em contato pelo WhatsApp, mas nenhum número foi fornecido. Quando tiver o número oficial, pode-se adicionar um botão de confirmação direta no fluxo de sucesso.

## Publicação
Basta enviar `index.html` e a pasta `assets/` para um projeto Vercel como site estático.
