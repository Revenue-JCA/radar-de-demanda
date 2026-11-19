# Hélios · Radar de Demanda

Shows, festivais, feriados, provas e jogos que movimentam viagens, com o tempo de cada praça e a leitura de vendas × chuva × eventos. Revenue · Grupo JCA.

- Eventos: `data/eventos.json` (d, d2, n, p, c, i, s, img, fonte). Fotos em `img/` (160×160 em `t/`, grandes em `f/`).
- O HELIOS lê `data/eventos.json` e abre esta página na aba Demanda (`?embed=1&tema=escuro|claro&dia=AAAA-MM-DD&praca=Cidade`).
- Tempo: Open-Meteo (previsão de 14 dias, atualizada a cada 30 min, e registro histórico).
- Abas: Visão geral, Demanda (calendário e destaques), Previsão (uma praça por vez) e Agenda.
