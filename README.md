# Máquina de viralização: conteúdo imobiliário

Base de conhecimento para produzir Reels e vídeos curtos de alto desempenho para o mercado imobiliário brasileiro, com foco inicial em Minha Casa Minha Vida, financiamento, primeiro imóvel e sair do aluguel.

O repositório funciona como o "cérebro" do Claude: os guias dizem **como** um vídeo deve ser construído, as referências mostram **o que** já funciona no mercado, e o prompt diz **o que entregar**.

## Como a máquina funciona

1. **Coletar referências.** Vídeos e perfis que performam bem entram em `referencias/`.
2. **Decompor.** Cada referência relevante é analisada segundo a segundo (gancho, corpo, CTA, edição) e registrada em `analises/`.
3. **Modelar sem copiar.** Os padrões que se repetem são cruzados com os guias de `guias/` para extrair o mecanismo, não o conteúdo.
4. **Planejar.** O Claude usa `prompts/instrucoes-plano-de-acao-30-dias.md` para gerar o plano de 30 dias, salvo em `plano-30-dias/`.
5. **Gravar, publicar e medir.** O resultado real de cada vídeo volta para `analises/` e alimenta o próximo ciclo.

## Estrutura

```
guias/                 Como construir cada parte do vídeo
  01-tour-de-imoveis.md              Estruturas de tour (Quanto custa, POV, Lifestyle)
  02-takes-e-ganchos-de-retencao.md  Banco de ganchos de 0 a 3s e regras de corte
  03-atuacao-e-direcao-de-cena.md    Tom de voz, postura, enquadramento
  04-duvidas-e-dores-do-mercado.md   Pilares educativos e quebra de objeções
  05-motion-design.md                Estilos visuais, mapas animados, legendas
referencias/           O que já funciona no mercado
  biblioteca-referencias-imobiliarias.md  Links, perfis e padrões por estilo de vídeo
  videos-e-estilos-para-benchmarking.md   Categorias de conteúdo e hashtags para analisar
prompts/               Instruções prontas para o Claude
  instrucoes-plano-de-acao-30-dias.md     Papel, metodologia e formato do plano de 30 dias
analises/              Decomposição de referências e resultados dos nossos vídeos
plano-30-dias/         Planos de conteúdo gerados
```

## Como usar com o Claude

- Para gerar um plano: peça ao Claude para seguir `prompts/instrucoes-plano-de-acao-30-dias.md` usando os guias e as referências deste repositório.
- Para um roteiro avulso: indique o tipo de vídeo (tour, educativo, comparativo) e o Claude escolhe a estrutura em `guias/` e um gancho em `guias/02-takes-e-ganchos-de-retencao.md`.
- Para direção visual: cite `guias/05-motion-design.md`.

## Regras

- Não inventar visualizações, métricas ou detalhes que não possam ser verificados.
- Modelar padrões e mecanismos, nunca copiar roteiros de terceiros.
- Links de agregadores são pontos de partida; confirmar sempre na plataforma original.
