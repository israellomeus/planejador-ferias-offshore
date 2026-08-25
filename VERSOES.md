# Histórico de versões

Controle editável das versões do Planejador de Férias. Atualizar este arquivo a cada nova alteração relevante para facilitar exportações futuras.

## V1.0 - Planejamento individual
- Cálculo individual de férias offshore.
- Projeção da escala 14x14.
- Calendário visual individual.
- Exportação do resumo individual em PNG.

## V1.1 - Melhorias individuais
- Campo de nome do colaborador.
- Campo de vencimento das férias.
- Opção de desembarque por helicóptero.
- Nome do colaborador incluído no arquivo exportado.
- Mês/ano escolhido incluído no resumo exportado.

## V2.0 - Planejamento da equipe
- Nova página para planejamento da equipe.
- Cadastro de múltiplos colaboradores.
- Planejamento anual com calendário corrido.
- Campo de função em dropdown.
- Campo de mês de interesse por colaborador.
- Campo de embarcação.
- Exemplo padrão da equipe.

## V2.1 - Alertas e cruzamentos
- Alertas por mesmo ciclo de férias.
- Alertas por mesma função no mesmo ciclo/mês.
- Avisos simples dentro do card do colaborador.
- Escolha manual do ciclo quando houver mais de uma opção no mês.
- Ajuste da lógica para considerar ciclo de embarque, e não apenas dias isolados.

## V2.2 - Exportações da equipe
- Exportação da equipe em PNG.
- Exportação para impressão A4.
- Exportação em Excel.
- Exportação/importação dos dados preenchidos.
- Nome da embarcação incluído nos arquivos exportados.
- Identificação dos arquivos exportados como `I.LOMEUS - V2.4`.

## V2.3 - Interface e responsividade
- Ajustes de cores e paleta visual.
- Abas separadas para planejamento individual e equipe.
- Botões com aparência mais clara.
- Botões para recarregar exemplo e limpar colaboradores.
- Melhorias de responsividade em desktop, tablet e celular.
- Aviso de uso apenas para consulta e planejamento.

## V2.4 - Controle de versões
- Arquivos editáveis criados para manter a contagem das versões.
- Rodapé da página ajustado para exibir a versão atual: `VERSÃO: V2.4`.
- Arquivos exportados ajustados para exibir `I.LOMEUS - V2.4`.
- Base preparada para exportação futura do histórico.
## V2.5 - Estabilizacao
- Sanitizacao dos IDs importados para evitar valores inseguros em atributos HTML.
- Validacao basica do arquivo importado: estrutura, funcao, datas, mes de interesse e limite de colaboradores.
- Planejamento individual ajustado para exportar e exibir o ciclo selecionado pelo usuario.
- Arquivo JSON exportado passa a gravar a versao atual da aplicacao.
- Rodape da pagina ajustado para `VERSAO: V2.5`.
- Arquivos exportados ajustados para exibir `I.LOMEUS - V2.5`.

## V2.6 - Calendario individual
- Calendario individual ajustado para usar preenchimento completo da celula por periodo.
- Marcadores pequenos removidos do calendario individual para melhorar leitura visual.
- Destaque de hoje mantido com contorno discreto.
- Rodape da pagina ajustado para `VERSAO: V2.6`.
- Arquivos exportados passam a exibir `I.LOMEUS - V2.6`.

## V2.7 - Ajuste visual de dias especiais
- Dia de desembarque no calendario individual passa a usar a mesma cor de folga antes.
- Texto do desembarque ajustado para duas linhas: Desembarque e Folga antes.
- Dias vendidos passam a manter a mesma cor mesmo quando houver retorno a escala/embarque.
- Texto de embarque padronizado em maiusculas dentro das celulas.
- Rodape da pagina ajustado para `VERSAO: V2.7`.
- Arquivos exportados passam a exibir `I.LOMEUS - V2.7`.

## V2.8 - Ciclo individual e dias embarcados
- Botao de selecao de ciclo no planejamento individual passa a aparecer somente quando houver mais de um ciclo disponivel.
- Dias embarcados no calendario individual deixam de ficar em branco e passam a mostrar `EMBARQUE`.
- Segundo dia vendido mantem texto em duas linhas: `DIA VENDIDO` e `EMBARQUE`.
- Rodape da pagina ajustado para `VERSAO: V2.8`.
- Arquivos exportados passam a exibir `I.LOMEUS - V2.8`.

## V2.9 - Padronizacao visual do calendario individual
- Dias embarcados no calendario individual mantem a cor neutra anterior e passam a mostrar `EMBARQUE`.
- Textos dos periodos no calendario individual padronizados em caixa alta.
- Azul forte removido dos dias embarcados para reduzir poluicao visual.
- Rodape da pagina ajustado para `VERSAO: V2.9`.
- Arquivos exportados passam a exibir `I.LOMEUS - V2.9`.

## V3.0 - Exportacao individual avancada
- Planejamento individual passa a ter filtro de exportacao entre mes/ano inicial e final.
- Exportacao individual em imagem passa a gerar calendario por meses do periodo selecionado.
- Exportacao individual para impressao A4 adicionada com layout limpo para bordo.
- Arquivos individuais exportados destacam colaborador, mes escolhido, ciclo selecionado e periodo exportado.
- Rodape da pagina ajustado para `VERSAO: V3.0`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.0`.

## V3.1 - Ciclos normais no planejamento individual
- Calendario individual passa a considerar os ciclos normais 14x14 antes e depois das ferias.
- Dias fora do periodo especial passam a exibir `FOLGA` ou `EMBARQUE` conforme a escala projetada.
- Visualizacao do calendario individual passa a seguir o intervalo selecionado em `Exportar de/ate`.
- Exportacoes individuais em imagem e impressao passam a incluir os estados normais do ciclo.
- Rodape da pagina ajustado para `VERSAO: V3.1`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.1`.

## V3.2 - Foco visual do calendario individual
- Calendario vertical da pagina volta a abrir pelo periodo de ferias calculado.
- Filtros de exportacao individual deixam de limitar a visualizacao principal da pagina.
- Dias normais de embarque e desembarque recebem tons leves e distintos.
- Exportacoes individuais deixam assinatura e versao apenas no rodape.
- Rodape da pagina ajustado para `VERSAO: V3.2`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.2`.

## V3.3 - Cores leves dos ciclos individuais
- Cor de folga normal ajustada para um neutro claro.
- Cor de embarque normal ajustada para um verde/agua leve, mais diferente da folga.
- Cor de desembarque normal ajustada para lilas leve, sem uso de vermelho.
- Exportacoes individuais em imagem e impressao A4 atualizadas com a mesma paleta.
- Rodape da pagina ajustado para `VERSAO: V3.3`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.3`.

## V3.4 - Inicio manual das ferias individuais
- Planejamento individual passa a permitir escolha manual da data de inicio das ferias.
- Modo manual deixa de aplicar automaticamente segunda-feira seguinte ou regra de helicoptero.
- Sistema calcula o ciclo de desembarque mais recente para a data manual escolhida.
- Alerta adicionado quando a folga antes das ferias passa de 12 dias e compromete o retorno na escala normal.
- Rodape da pagina ajustado para `VERSAO: V3.4`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.4`.

## V3.5 - Formatos de exportacao individual
- Planejamento individual volta a oferecer exportacao do resumo simples das ferias.
- Exportacao com calendario passa a ter texto proprio: `Resumo com calendario`.
- Botao de impressao individual passa a ficar identificado como `Impressao A4`.
- Painel de exportacao individual reorganizado para tres acoes claras.
- Rodape da pagina ajustado para `VERSAO: V3.5`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.5`.

## V3.6 - Leitura das cores de folga e embarcado
- Cor de folga normal reforcada com azul claro mais perceptivel.
- Cor de embarcado ajustada para azul leve com borda mais definida.
- Contraste dos textos `FOLGA` e `EMBARCADO` melhorado no calendario individual.
- Exportacoes individuais em imagem e impressao A4 atualizadas com a mesma leitura visual.
- Rodape da pagina ajustado para `VERSAO: V3.6`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.6`.

## V3.7 - Contraste das cores do calendario individual
- Paleta do calendario individual ajustada para separar melhor folga, embarcado, embarque e desembarque.
- Folga normal passa a usar azul frio com contraste mais definido.
- Embarcado passa a usar verde claro para diferenciar do periodo de folga.
- Exportacoes individuais em imagem e impressao A4 atualizadas com a mesma paleta.
- Rodape da pagina ajustado para `VERSAO: V3.7`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.7`.

## V3.8 - Cor de embarque individual
- Cor do estado `EMBARQUE` ajustada para um lilas rosado leve, mais proximo do `DESEMBARQUE`.
- Contraste do texto `EMBARQUE` reforcado sem pesar a leitura do calendario.
- Exportacoes individuais em imagem e impressao A4 atualizadas com a nova cor de embarque.
- Rodape da pagina ajustado para `VERSAO: V3.8`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.8`.

## V3.9 - Texto do segundo dia vendido
- Segundo dia vendido do retorno passa a exibir `DIA VENDIDO / EMBARCADO`.
- Primeiro dia vendido mantem `RETORNO A ESCALA / DIA VENDIDO / + EMBARQUE`.
- Exportacoes individuais passam a usar o mesmo texto corrigido.
- Rodape da pagina ajustado para `VERSAO: V3.9`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.9`.

## V3.10 - Preservacao de cores na exportacao
- Modelos de impressao e exportacao passam a solicitar preservacao exata das cores no navegador.
- Calendario A4 da equipe ajustado para evitar perda das cores de fundo ao gerar arquivo impresso ou PDF.
- Exportacao individual com impressao A4 recebe a mesma protecao de cores.
- Rodape da pagina ajustado para `VERSAO: V3.10`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.10`.

## V3.11 - Ordem mobile do planejamento da equipe
- No celular, botoes de recarregar exemplo, limpar colaboradores e formulario de adicionar colaborador passam a aparecer antes da lista de colaboradores.
- Lista de colaboradores fica em seguida, mantendo o fluxo de cadastro e revisao mais natural em telas pequenas.
- Painel de alertas de cruzamento fica apos a lista no layout mobile.
- Layout desktop preservado com lista e painel lateral.
- Rodape da pagina ajustado para `VERSAO: V3.11`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.11`.

## V3.12 - Ajuste do resumo individual em PNG
- Texto do embarque no resumo individual em PNG passa a ficar alinhado ao fim da linha do tempo.
- Indicacao de `+2d vendidos` passa para uma segunda linha, evitando sobreposicao com a data de embarque.
- Arquivo exportado individual fica mais legivel quando o trecho vendido e pequeno.
- Rodape da pagina ajustado para `VERSAO: V3.12`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.12`.

## V3.13 - Ajuste interno da linha do tempo individual
- Linha do tempo do resumo individual em PNG foi reposicionada para manter os textos dentro do card.
- Data de embarque e indicacao de `+2d vendidos` permanecem em linhas separadas sem sair da caixa.
- Rodape da pagina ajustado para `VERSAO: V3.13`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.13`.

## V3.14 - Paleta simplificada do calendario individual
- Calendario individual passa a usar apenas tres grupos de cor: folga, ferias e embarcado.
- Datas especiais como desembarque, embarque, folga antes, folga apos e dia vendido continuam indicadas pelo texto dentro de cada caixa de data.
- Legendas do calendario individual foram reduzidas para evitar excesso de cores e duplicacao de informacoes.
- Exportacoes individuais em PNG e impressao A4 passam a usar a mesma paleta simplificada.
- Rodape da pagina ajustado para `VERSAO: V3.14`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.14`.

## V3.15 - Paleta simplificada no modulo coletivo
- Modulo de ferias coletivas passa a usar a mesma leitura de cores do modulo individual: folga, ferias e embarcado.
- Embarque e desembarque deixam de ter cores exclusivas na legenda coletiva e permanecem identificados pelo texto dentro das celulas.
- Exportacoes da equipe em PNG e impressao A4 passam a usar a mesma legenda reduzida.
- Rodape da pagina ajustado para `VERSAO: V3.15`.
- Arquivos exportados passam a exibir `I.LOMEUS - V3.15`.
