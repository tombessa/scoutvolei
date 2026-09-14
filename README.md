# Scout Vôlei TRT

Painel móvel para registrar placar e indicadores de partidas de vôlei do TRT.

## Fluxo

1. Informe o adversário e inicie o set.
2. Toque em **Ponto TRT** ou **Ponto adversário**.
3. Classifique o ponto ou escolha **Nenhum indicador**.
4. Use **Fim do set** para avançar ou **Fim de jogo** para encerrar a partida.

## Indicadores

- Pontos de ace
- Aces sofridos
- Erros de saque
- Erros de ataque ou bloqueio
- Pontos de ataque
- Pontos de bloqueio

Os sets encerrados podem ser tocados para consultar suas estatísticas. A exportação gera planilha Excel ou relatório em PDF. No PDF, os detalhes ponto a ponto são opcionais.

## Armazenamento

Os dados ficam no armazenamento local do navegador. Exporte a partida antes de limpar os dados do navegador ou iniciar uma nova partida.

## Vercel

O projeto é estático e não precisa de comando de build. Na Vercel:

1. Escolha **Add New > Project**.
2. Importe o repositório `tombessa/scoutvolei`.
3. Mantenha **Framework Preset** como `Other`.
4. Deixe o comando de build e o diretório de saída em branco.
5. Conclua em **Deploy**.

Depois que o repositório estiver conectado, novos commits na branch `master` gerarão novas implantações automaticamente.
