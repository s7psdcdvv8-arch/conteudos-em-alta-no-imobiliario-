# Método de coleta e limites

## Como os dados do Instagram foram coletados (28/10/2026)
1. **Candidatos:** busca por palavra-chave no Instagram, no navegador logado do Bruno (extensão Claude in Chrome). 21 buscas em 26/10 (1.081 posts) e 15 em 28/10 (~650 posts).
2. **Métricas do vídeo:** API web do Instagram aberta pela própria página logada (`/api/v1/media/<id>/info/`): views (play_count), curtidas, comentários, data, duração, legenda. Lidas em 28/10.
3. **Mediana do perfil:** contadores de views da grade de Reels do perfil (13 a 17 Reels mais recentes, sem os fixados), lidos em 28/10. "x mediana" = views ÷ mediana.
4. **Assistir:** o arquivo de vídeo carregado no navegador, quadros extraídos em tempos fixos (0; 0,5; 1; 1,5; 2; 3 s e depois espaçados até o fim) e 3-4 quadros grandes do gancho para ler o texto. **Sem áudio**: a fala só entra quando está escrita na tela.

## Limites
- Compartilhamentos, salvamentos, alcance e retenção de vídeos de outras pessoas não são públicos.
- Views do Instagram contam repetições; no perfil do Bruno a grade soma o Facebook (verificado em 26/10). Não dá para saber se a grade de outros perfis também soma.
- A busca do Instagram favorece o que já deu certo (viés de sobrevivência).
- Comentários não foram lidos nesta rodada (só contados).
- O Instagram limitou chamadas por alguns minutos (erro 429) quando pedi muitas seguidas. Ritmo usado depois: 1 pedido a cada 1-2 s, pausas entre lotes.
- Não há transcrição de fala. Opções para a próxima rodada: (a) o Bruno roda o /watch no Mac (`ferramentas/watch` no repo plano-de-ac-o) com Whisper; (b) baixar os MP4 para o Mac do Bruno, com autorização dele, e transcrever lá.

## Como classificar cada vídeo
- **Fato verificado:** número lido na plataforma, com data.
- **Observação:** o que aparece nos quadros (imagem, texto, gesto), com o tempo.
- **Hipótese:** por que pode ter funcionado, sempre com uma explicação alternativa.
- **Desconhecido:** o que não deu para ver (áudio, retenção, impulsionamento, comentários).

## Antes de criar uma análise nova
Procure o código do vídeo em `instagram/banco-videos.md`. Se já existir, atualize a linha (com a data nova) em vez de criar outra, e registre no `CHANGELOG.md`.
