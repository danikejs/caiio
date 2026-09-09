# Visão Geral do Jogo

- título: Ping Pong 2D
- ideia_geral: "Jogo de tênis de mesa em 2D onde o jogador controla uma raquete para rebater a bola e marcar pontos."
- jogador_faz: "Mover a raquete e rebater a bola para evitar que o adversário marque pontos."
- controles_sugeridos: "Teclado (W/S ou setas) e/ou mouse/toque (arrastar verticalmente)."
- unidade_de_jogo: "Partida (melhor de N pontos)."

- estado_decisao: FECHADO
- origem: "Justificativa: lacuna estratégica — ascensão do tênis de mesa no Brasil (Hugo Calderano, Bruna Takahashi) e familiaridade da equipe com 2D; registra-se oportunidade de aproveitar o hype mundial do esporte. (Aluno, 2026-09-09)"
- objetivo_imediato: "Ganhar campeonatos de tênis de mesa utilizando técnicas reais do esporte."
 
- experiencia_desejada: "Misto — fluido e competitivo, mas acessível e casual: competitivo o suficiente para transmitir tensão e domínio técnico, sem exigir todas as habilidades da vida real; fácil de aprender e divertido para sessões curtas."
- experiencia_estado: FECHADO
- experiencia_origem: "Aluno: busca equilíbrio entre fluidez competitiva e acessibilidade casual (2026-09-09)."

- core_loop:
	- mover: "Mover-se entre esquerda, centro e direita."
	- rebater: "Bater na bola exigindo timing; inputs dentro de uma janela influenciam direção/velocidade."
	- efeitos: "Aplicar efeito/colocar spin na bola."
	- especiais: "Aprender a utilizar bolas especiais com propriedades distintas."
	- estado: PROVISÓRIO
	- origem: "Aluno: descreveu ações principais (2026-09-09); necessita definição observável de janelas de timing e magnitudes de efeito."
	- estado: FECHADO
	- origem: "Aluno: descreveu ações principais (2026-09-09); janela de timing definida como 'Habilidade' (±100 ms) e foco em bolas especiais/efeitos)."
	- timing_rebater: "Habilidade — Janela estreita: ±100 ms (foco em skill e profundidade competitiva)."
	- especiais_inspiracao: "Pimbolas — o aluno solicitou comportamento similar ao jogo 'Pimbolas'."
	- especiais_estado: PROVISÓRIO
	- especiais_pendencias: "Confirmar lista de tipos de bolas especiais, seus efeitos observáveis, duração e condições de uso."

> Decisão fechada com justificativa fornecida pelo aluno.
