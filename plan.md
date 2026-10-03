# Plano — Poa Floripa Imóveis

## Escopo
Landing page institucional de uma única rota para comunicar que o site oficial está em construção, apresentar a marca Poa Floripa Imóveis e facilitar o contato imediato por WhatsApp/telefone. A página usa o logo fornecido pelo usuário e preserva sua paleta visual.

## Direção de design
- **Movimento:** editorial costeiro contemporâneo, com sensação de horizonte, espaço e confiança.
- **Princípios:** clareza imediata, elegância sem excesso, acolhimento e contraste acessível.
- **Filosofia de cor:** o turquesa/ciano do logo funciona como assinatura proprietária e transmite proximidade, leveza e referência ao litoral de Florianópolis; o vermelho aparece como acento de energia e ação; o branco cria respiro e confiança.
- **Paradigma de layout:** composição assimétrica em duas áreas — mensagem principal à esquerda e bloco de contato à direita — com uma linha-horizonte decorativa conectando as duas partes, em vez de uma grade centralizada convencional.
- **Elementos de assinatura:** moldura fina inspirada em linhas arquitetônicas, linha-horizonte em arco e acentos vermelhos pontuais nos CTAs e no detalhe da marca.
- **Interação:** CTAs diretos e compreensíveis; o WhatsApp permanece disponível como botão flutuante, com feedback visual discreto no hover/focus.
- **Animação:** entrada suave por opacidade e deslocamento vertical; brilho muito sutil no botão flutuante; sem movimento contínuo que distraia da mensagem.
- **Tipografia:** sans-serif contemporânea, com títulos largos e firmes e corpo com leitura confortável; a hierarquia usa contraste de peso e tamanho, não excesso de estilos.
- **Essência da marca:** imóveis em Florianópolis com atendimento próximo, clareza e olhar local. Personalidade: acolhedora, segura, contemporânea.
- **Voz:** humana, objetiva e otimista. Exemplos: “Estamos preparando algo especial para você.” e “Enquanto isso, fale com a nossa equipe.”
- **Wordmark/logo:** uso do logo fornecido como peça de marca principal, dentro de uma moldura branca que o destaca sobre o campo turquesa.
- **Cor proprietária:** turquesa Poa Floripa, derivado visualmente do fundo do logo (`#12AFCB`).

## Estrutura do projeto
- `index.html`: semântica, conteúdo, SEO básico e marcação da única rota.
- `styles.css`: tokens de cor, composição responsiva, estados de foco e animações.
- `script.js`: ano do rodapé e microinterações sem dependências.
- `server.js`: servidor estático mínimo para o Preview na porta 3000.
- `public/manus-routes.json`: manifesto da rota `/`.
- `app.config.ts`: metadado de logo do projeto.
- `TODO.md`: critérios de entrega derivados do pedido.

## Operação
A página é estática, sem servidor de aplicação ou banco de dados. O Preview roda em `0.0.0.0:3000`; o mesmo conjunto de arquivos pode ser servido como publicação estática posteriormente.
