# Biblioteca de ganchos virais — mercado imobiliário

Base de conhecimento do Projeto Mestre (Vilela Imóveis, zona leste de SP). Objetivo: entender, com evidência, o que faz um vídeo imobiliário prender e espalhar, e usar isso nos imóveis do Bruno, inclusive nos simples.

**Estado em 2026-10-28:** etapa 1 (Instagram) com a primeira rodada completa. Etapas 3 a 5 ainda não começaram.

## Ordem do projeto
1. Instagram ← **rodada 1 feita**
2. Organização da biblioteca do Instagram ← **esta estrutura**
3. TikTok, separado
4. Comparação entre plataformas
5. Aplicação aos imóveis e aos resultados do Bruno

## Índice
| Arquivo | O que tem |
|---|---|
| [metodo.md](metodo.md) | Como os dados foram coletados, o que não dá para ver, como classificar fato / observação / hipótese / desconhecido |
| [instagram/banco-videos.md](instagram/banco-videos.md) | 54 vídeos do IG com link, perfil, seguidores, views, curtidas, comentários, data, duração, mediana do perfil, "x mediana", formato, mecanismo |
| [instagram/analises/](instagram/analises/) | 10 análises individuais (quadro a quadro, sem áudio) |
| [instagram/dados/](instagram/dados/) | Métricas brutas (TSV) e medianas de 52 perfis |
| [ganchos/banco-de-ganchos.md](ganchos/banco-de-ganchos.md) | 24 mecanismos de gancho (G01-G24) com exemplos e confiança |
| [padroes.md](padroes.md) | 13 padrões com nível de confiança, o que confirmam e o que contradizem |
| [hipoteses.md](hipoteses.md) | 10 hipóteses para testar no perfil do Bruno, com métrica |
| [tiktok/banco-videos.md](tiktok/banco-videos.md) | Etapa 3 (só referências preliminares de 19/10) |
| [comparacao-plataformas.md](comparacao-plataformas.md) | Etapa 4 (primeiras pistas) |
| [testes-proprios.md](testes-proprios.md) | Liga os testes do Bruno aos mecanismos; o registro em si fica em `plano-de-ac-o/plano-4000-seguidores/` |
| [CHANGELOG.md](CHANGELOG.md) | Registro de atualizações com data e motivo |

## O que a rodada 1 do Instagram mostrou (resumo)
1. **O motivo para ficar vem antes de 2 s** em quase todos os vencedores: um número, um defeito, uma ação ou uma pergunta (alta confiança).
2. **Defeito real mostrado com a mão** é o formato que mais combina com imóvel imperfeito, e venceu em 5 perfis diferentes (eng.anaclara 789x, larissadabul 414x, doleilao 1.630x).
3. **Quando o preço não surpreende, a condição surpreende:** entrada e parcela fixas na tela (casalcorretorfsa 688x e 14 mil comentários).
4. **Casa simples vence pela moldura, não pelo acabamento:** vida sugerida (joao_bfernandes 349x), potencial (mateusdn), leilão, parcela.
5. **Novos para o banco:** ranking de bairros (brunopira fez sobre a zona leste, 39x), esquete com placar de números no tempo (gabrielfogaca 608x), texto denso em 6 s (gabrielaalenc 1.797x), pedido de marcar/enviar na tela, IA mostrando o que ainda não existe.
6. **Viral isolado não cresce o perfil** (riankoide: 4.799x num vídeo, mediana continua 1,6 mil). Quem cresce repete o formato.
7. **Sem evidência ainda:** react e objeto falante (a busca não achou casos imobiliários fortes).

Nada aqui é garantia. São padrões de vencedores, sem os perdedores para comparar; servem para escolher o que testar.

## Regras da biblioteca
- Fonte de verdade: este repositório. Cópia de leitura em `/mnt/project-files/biblioteca-ganchos/`.
- Antes de adicionar um vídeo, procure o código no banco. Atualize em vez de duplicar e registre no CHANGELOG.
- Nunca inventar link, número, fala ou comentário. Se não viu, escreva "não assistido" ou "desconhecido".
