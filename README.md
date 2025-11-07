Um modo de visualização minimalista, sem distrações, com câmera automatizada — perfeito para transmitir ou gravar partidas sem a “poluição” da interface do Mestre. A ideia é atribuir um usuário não-jogador ao módulo; quando um navegador entra com esse usuário, o Foundry apresenta uma UI enxuta com os recursos abaixo.

Recursos

Vários modos de câmera

Automático: acompanha os tokens dos personagens do grupo na cena, ajustando o enquadramento para mantê-los em foco.

Dirigido: espelha a câmera do Mestre o tempo todo.

Rastreamento ciente de combate (modo Automático): segue o combatente atual, seus alvos e quaisquer templates medidos.

Foco por usuário (opcional): durante o combate, pode seguir a visão do usuário que controla o combatente ativo.

Rastreamento seletivo de tokens: o Mestre pode clicar com o botão direito nos tokens selecionados e usar o ícone de câmera no HUD para fixar o foco.

Integração de voz/vídeo no jogo: foca os tokens de quem está falando e exibe um indicador de fala acima do token (Mestres usam o token atualmente selecionado, se houver).

Controle de pop-outs compartilhados: diários/imagens mostrados aos jogadores podem se fechar automaticamente após um tempo, ou manualmente pela barra de ferramentas do Stream View.

Troca dinâmica de modo: alterne o modo de câmera a qualquer momento pela barra do Stream View.

Configuração

Crie um usuário dedicado (ex.: Stream). Esse usuário não deve possuir atores/tokens.

Conceda permissão Observador a esse usuário para todos os atores dos jogadores, garantindo que a visão do stream seja a mesma do grupo.

Em Settings → Configure Settings → Module Settings → Stream View, selecione Stream User e salve.

Abra uma nova sessão de navegador, entre como o usuário Stream e use essa janela para gravar/transmitir.

OBS Studio

Adicione uma Browser Source apontando para a URL web do seu Foundry.

Clique com o botão direito na fonte → Interact → faça login como o usuário Stream.

Organize sua cena e vá ao ar.

Observação (Windows): use OBS Studio ≥ v27.2 para capturar o Foundry via Browser Source de forma confiável.

A Fazer

Gravar vídeos de demonstração curtos mostrando os recursos.

Investigar detecção de atividade de voz no Discord; não há solução simples, especialmente em Foundry hospedado.
