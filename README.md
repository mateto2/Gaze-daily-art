# Gaze

App de celular para observar arte com calma. Todo dia, uma grande pintura em domínio público.

## O ritual do dia

1. **Observar**: a obra em tela cheia, com zoom livre e um tempo sugerido.
2. **Escrever**: a pessoa registra a própria interpretação. Uma IA só verifica se houve esforço genuíno, nunca se a leitura está "certa".
3. **Mural**: libera as leituras de outras pessoas, com detalhes marcados direto na obra.
4. **Críticos**: interpretações conhecidas (resumidas e creditadas), com a obra se aproximando de cada trecho comentado.

Gratuito para a obra do dia. O **Gaze+** libera o arquivo de obras anteriores, o diário pessoal e leituras extras.

## Protótipo

`gaze-prototipo.html` é um protótipo clicável de um dia completo com a Mona Lisa. Abra o arquivo no navegador (a imagem `mona.jpg` precisa estar na mesma pasta).

A verificação de esforço no protótipo usa regras simples no navegador. No app real, ela será feita por uma IA.

## Stack planejada

- React Native + Expo (TypeScript)
- Supabase (login, banco, mural, assinaturas)
- API de IA para verificação de esforço e moderação do mural

## Conteúdo e direitos

- Só obras em domínio público.
- Textos de críticos são resumidos com crédito; citações diretas apenas de textos já em domínio público.
- Imagem da Mona Lisa: reprodução em domínio público via Wikimedia Commons (C2RMF).
