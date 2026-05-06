## Abbreviations in Microeletronics

Lista de abreviaturas utilizadas no meio da microeletrônica;

**Índice**

1. [Fundamentos Semicondutores](#idCMOS) 
2. [VDSI](#idVDSI) 
3. [VDSM](#idVDSM) 
4. [Digital_Design](#idDD) 
5. [ASICs](#idASIC) 

***

<a name="idCMOS"></a>

<details>

<summary><b>Em Fundamentos de semicondutores (MOSFET)</b></summary>

| Sigla/Termo | Nome completo | Descrição. |

| ------ | -------------- | ----------. |

|  | Band Gap | Diferença de energia entre a banda de valência e o banda de condução, que define a quantidade mínima de energia necessária para liberar um elétron (eV). |

|  | Band Theory | Um modelo usado para explicar a condição de sólidos e o comportamento dos elétrons. |

|  | Polycrystalline | Estrutura atômica do silício onde os cristais de silícios são fundidos. |

|  | Layer | São os níveis de materiais diferentes empilhados no chip, onde cada camada tem uma função específica na construção dos dispositivos e das interconexões. |

|  | Mask | São as máscaras usadas no processo de litografia e dopagem dos semicondutores, que contém padrões a serem transferidos para o wafer ou outra máscara. |

|  | Silicon Wafer | Uma fatia do lingote usado como base para fabricação dos CI. |

| _ICs_ | Integrated Circuits | Circuitos integrados. |

|  | Ingot | São os lingotes de silícios cilíndricos puro, matéria prima para os semicondutores. |

|  | Die | É a área útil usado pelo chip no Wafer. |

|  | Scribe line | São os espaços não funcionais entre os dies, por onde passa as serras de corte. |

| _TEG_ | Test Element Group | Um padrão que revela as características físicas reais de um chip (C,L,R,Transistores...) para serem testados. |

|  | Edge Dies | São os dies das bordas do wafer, que podem ser descartados por falha esperada no processo de fabricação. |

|  | Flat Zone | Borda do wafer que é cortada para identificar o wafer. |

|  | Foundry | Fábricas que produzem chips para terceiros, para os terceiros. Compram e integram equipamentos de diversos fabricantes, mas não projetam. Responsável pelos processos. Exemplo: Samsung, TSMC. |

| _Fabs_ | Fabrication Plants | Fábrica que produzem chips para si, projetam, fabricam e vendem. Fabricantes de IDMs. Exemplo: Intel. |

| _Fabless_ | Fabless Chip Compaines | Empresas que criam seus projetos (também podem usar IPs) usando EDA e fabricam seus projetos em foundries, podendo vende-los ou ser de uso exclusivos. Exemplo: Apple, QUalcomm, AMD, Nvidia. |

| _IDMs_ | Integrated Device Manufacturers | Eles mesmos projetam, fabricam e vendem seus chips. Exemplo: Micron, Intel, Analog Devices. |

| _WFE_ | Wafer Fab Equipment | Máquinas que fabricam chips. Exemplos: Applied Materials, KLA, LAM, Tokyo Electron e ASML. |

| _OSAT_ | Outsourced Semiconductor Assembly and Test | Fábricas que encapsulam e testam os chips das foundries. |

| _DH_ | Design House | São empresas especializadas em alguma etapa do VLSI, que atuam nas Fabs ou Fabless. Basicamente, projetam para outras empresas e não para sí mesmo. Agindo como uma terceirizada. |

|  | Layout | É a planta do CI. |

|  | Reticles | Ferramenta que contém uam imagem de padrão que precisa ser repetida em etapas para expor todo o wafer ou mask. |

|  | Mask Layer | São as camadas das máscaras, geralmente representado por diferentes cores. Exemplo: Metal, poly, n+diff, Contact.. etc. |

|  | Mask Data | É o arquivo final que descrevem todas as máscaras do chip, geralmente em formato OASIS ou GDSII. |

| _DRC_ | Design Rules Check | São as regras de fabricação da tecnologia utilizada no qual o Layout deve obedecer. Sejam elas, checagem de células, signof, rout, struturas, names, maps.. |

| _PUN_ | Pull-Up | "Puxar para cima". São PMOS conectados em paralelo ligado ao VDD, localizado na parte superior para evitar curto circuito na conexão CMOS. |

| _PDN_ | Pull-Down | "Puxar para baixo". São NMOS conectados em série ligado ao GROUND, localizado na parte inferior para evitar curto circuito na conexão CMOS. |

| _MOSFETs_ | Metal-Oxide-Semiconductor Field-Effect Transistor | Transistor usado para chaveamento e amplificação em circuitos integrados. |

| _CMOS_ | Complementary Metal-Oxide-Semiconductor | Tecnologia que usa NMOS e PMOS para baixo consumo de energia. |

| _PMOS_ | P-channel Metal-Oxide-Semiconductor | Transistor que conduz quando a tensão no gate é baixa. |

| _NMOS_ | N-channel Metal-Oxide-Semiconductor | Transistor que conduz quando a tensão no gate é alta. |

|  | SPICE MODEL | Representação matemáttica de um comportamennto elétrico de um dispositivo. |

| _FinFET_ | Fin Field-Effect Transistor | Transistor 3D com canal em forma de “fin”, oferecendo melhor controle eletrostático e menor leakage. |

| _FDSOI_ | Fully Depleted Silicon-On-Insulator | Tecnologia de transistores com canal totalmente depletado sobre isolante, reduzindo leakage e melhorando controle eletrostático. |

| _VDD_ | Voltage Drain Drain | Sinal "high-voltage", ligado a fonte. |

| _VSS_ | Voltage Source Source | Sinal "low-voltage", ligado ao ground. |

| _VTC_ | Voltage Transfer Characteristics | Curva que mostra a relação entre tensão de entrada e saída de um circuito (ex: inversor CMOS). |

| _Tphl_ | Propagation Delay Time High-to-Low | Tempo para a saída cair de 1→0 após a mudança na entrada. |

| _Tplh_ | Propagation Delay Time Low-to-High | Tempo para a saída subir de 0→1 após a mudança na entrada. |

| _TG_ | Transmission Gate | Chave bidirecional formada por NMOS e PMOS em paralelo, usada para passar sinais sem degradação. |

|  | Fan-in | São os números de entradas de uma porta, que afeta a resistência. Menor fan-in, menor o delay. |

|  | Fan-out | São os números de saídas de uma porta, que afeta a capacitância. Maior fan-out, maior a carga e delay. |

|  | Metastable | Dado passível de metaestabilidade, pode ter um valor incerto, podendo ser o dado anterior ou atual. |

| _NORA_ | NO-RAce Logic | Técnica de lógica dinâmica que evita condições de corrida entre estágios. |

| _OTP_ | One-time programmable | Memória programável apenas uma vez, usada para configuração permanente. |

| _SRAM_ | Static Random Access Memory | Memória rápida baseada em flip-flops, não precisa de refresh. |

| _DRAM_ | Dynamic Random Access Memory | Memória densa que armazena dados em capacitores e precisa de refresh. |

| _RAM_ | Random Access Memory | Memória volátil de acesso rápido para leitura e escrita. |

| _ROM_ | Read-Only Memory | Memória não volátil usada para armazenar dados fixos. |

| _PROM_ | Programmable read-only memory | Tipo de ROM que pode ser programada uma única vez pelo usuário. |

| _DFM_ | Design of Manufacturability | Regras e diretrizers para serem cumpridas na etapa de fabricação. |

| _CAD_ | Computer-Aided Design | Software para projetar, desenhar e verificar sistemas para projeto de circuitos integrados (ICs). |

| _PDK_ | Process Design Kit | Tecnologia fornecida pela foundry que consiste em um conjunto de arquivos caracterizados por ela. |

***

</details>

<a name="idVLSI"></a>

<details>

<summary><b>Em VLSI</b></summary>

| Sigla | Nome completo | Descrição. |

| ------ | -------------- | ----------. |

| _VLSI_ | Very Large-Scale Integration | É toda a sequência de etapas para transformar um descrição de RTL até sua fabricação. |

| _EDA_ | Electronic Design Automation | São os conjuntos de ferramentas/software utilizadas ao longo de todo fluxo de desenvolvimento da elaboração do CI. |

| _GTECH_ | Generic Technology | Biblioteca padrão de celúlas genéricas da EDA utilizadas na etapa intermediária da síntese. |

| _NLDM_ | Non-Linear Delay Model | Modelo mais antigo da .ln (less acurate), modelo não linear. |

| _CCS_ | Composite Current Source | Modelo mais antigo da .ln (more acurate). |

| _NLPM_ | Natural language programming linter | Biblioteca que possui o tipo de modelagem de potência, com dados. |

| _STA_ | Static timing Analysis | Técnica para verificar o timing do circuito digital (fechou ou não?), rápido e exaustivo. |

| _DTA_ | Dynamic timing Analysis | Técnica para analisar timing do cricuito utilizando vetores de testes, testes específicos, mais lento. |

| _HDL_ | Hardware Description Language | Linguagem de programação que possui o paradigma de descrever o comportamento de circuitos digitais e estruturasd e hardwares. |

| _LVF_ | Liberty Variation Format | Extensão do formato Liberty que modela variações estatísticas (processo, tensão, temperatura) para análise de timing mais precisa. |

| _TLF_ | Timing Library Format | Arquivo que descreve características de timing das células padrão |

| _LEF_ | Library Exchange Format | Descreve geometria simplificada das células para uso em place & route |

| _DSCL_ | Digital Standard Cell Library | Conjunto de células padrão digitais (com lógica, layout e timing) |

| _DEF_ | Design Exchange Format | Descreve a implementação física do design (placement, roteamento e conexões) |

| _LIB_ | Liberty Timing File | Arquivo (.lib) que descreve timing, potência e função lógica das células padrão |

| _SDC_ | Synopsis Design Constraints | Formato de arquivo padrão, baseado em TCL desenvolvida pela Synopsis, para definir restições de PPA, utilizado no processo de síntese. |

| _FRAM_ | "Frame" | Similar ao LEF, descreve também o formato físico das células. |

| _GDSII_ | Graphic Design System II | É o formato padrão de arquivo usado para representar o layout físico (Atual). |

| _GDSI_ | Graphic Design System I | É o formato padrão de arquivo usado para representar o layout físico (Antigo/obsoleto) |

| _OASIS_ | Open Artwork system intechange standard | Outro tipo de formato (Open-source) para representar um design físico. |

| _ASCII_ | American Standard Code for Information Interchange | É o padrão de codificação de caracteres em valores númericos. |

| _SCL_ | Standart Cell | São as células padrão caracterizadas pertencentes ao PDK. |

|  | CELL | Quaisquer tipo de "componente" ou unidade de um projeto CI, podendo ser um mux, transitor, etc. |

|  | BUS | Barramento é o meio físico de conexão entre blocos, por onde os sinais passam. Ela é regida por um protcolo, que são as regras de como funciona essa comunicação. |

| _PI/PO_ | Pins | Pontos de conexões do circuito, seja entrada ou saída. |

| _GRID_ | Grid | Malha de referência usada no layout para alinhar e posicionar células e interconexões |

| _LVS_ | Layout Versus Schematic | Verifica se o layout físico corresponde ao esquemático (conectividade e dispositivos) |

| _ESD_ | Electrostatic Discharge | É aquela descarga de eletricidade estática (tipo quando você leva um choque ao tocar algo), que pode danificar o chip, e pinos. |

| _UPF_ | Unified Power Format | Literalmente, um formato/padrão para descrever como a energia pode-se organizar dentro de um CI. |

| _TCL_ | Tool Command Language | Linguagem de script usada para automatizar e controlar ferramentas EDA. |

|  | CORE | O coração do CI, ou melhor, o cérebro. Fornece a funcionalidade básica de um circuito integrado. |

| _HBM_ | Human Body Model | É uma simulação usando o modelo humano quando há uma descarga elétrica no circuito. Pode ser usado em outras ocasiões. |

| _RTL_ | Register Transfer Level | É um nível de abstração da representação de projetos digitais utilizando HDL na etapa de Design. |

|  | SKEW | É a velocidade de transicação do dado, a diferença entre entre o tempo que o sinal sai e chega. |

| _DUTY CYCLE_ | Duty Cycle | Razão entre o tempo em nível alto e o período total de um sinal periódico (geralmente em %) Parâmetro de entrada (input) para análise de timing e projeto de clock. |

| _CTS_ | Clock Tree Synthesis | Etapa do fluxo físico que cria e otimiza a rede de distribuição do sinal de clock no chip. |

| _PPA_ | Power, Performance, and Area | São as principais métricas para definirmos em um projeto de CI, a partir da especificação do projeto. |

| _IPs_ | Intellectual Property | São blocos de circuitos projetados, verificados e reutilizeveis em projetos, no qual uma empresa é detentora do seu design. |

|  | Floorplan | Consiste no roteamento de vias que serão utilizadas para alimentação das standard cell. São determinadas as localizações, formas, tamanhos dos módulos do chip e são estimadas a área do chip, atrasos e congestionamentos de fios, dessa maneira fornecendo a base para o leiaute. |

|  | Placement | Trata do processo de alocar as Standard Cells no design proposto. |

|  | Site | Um site é a unidade básica de posicionamento (grid) onde as standard cells podem ser colocadas no layout. |

| _FPGA_ | Field-Programmable Gate Array | Dispositivo reconfigurável composto por blocos lógicos e interconexões programáveis. |

| _PLD_ | Programmable Logic Device | Categoria de dispositivos digitais programáveis usadas para implementar lógica. |

| _MPGA_ | Mask Programmable Gate Array | Dispositivo programado por máscara na fabricação, com interconexões definidas na foundry. |

| _CPLD_ | Complex Programmable Logic Device | PLD com múltiplos blocos lógicos e interconexões previsíveis, bom para controle. |

| _SPLD_ | Simple Programmable Logic Device | PLD simples com poucos recursos, usado para lógica básica. |

|  | Budget | Uma restrição de projeto, onde definimos o nosso caminho de desenvolvimento, seja ele timing, power ou area. |

***

</details>

<a name="idVDSM"></a>

<details>

<summary><b>Em VDSM</b></summary>

| Sigla | Nome completo | Descrição. |

| ------ | -------------- | ----------. |

| _VDSM_ | Very deep submicron | Uma categoria do VLSI de tecnologias abaixo de 0.25Um. |

| _SoCs_ | System-on-Chip | Chip que integra vários componentes/core/blocos em um único circuito integrado. |

| _Hard Block_ | Hard Block | Bloco físico já pronto dentro do chip, otimizado para alta performance e menor consumo de energia. |

| _Soft Block_ | Soft Block | Bloco descrito em código (HDL), que pode ser configurado e adaptado conforme o projeto. |

| _TDD_ | Time Driven Design | Metodologia de projeto orientado ao tempo, garante que o design e o timing atenda aos requisitos. Usandos em ASIC. |

| _BBD_ | Blocked based Design | Metodologia de projetos orientados a blocos. Você pode projetar os blocos isoladamentes e ajuda no fechamento do clock. Usado em ASIC complexos e IP. |

| _PBD_ | Platform based Design | Metodologia de projetos orientados a plataforma. É um nível de abstração maior, muito usado em SoCs e Plug. |

| _DVT_ | Design Validation Test | Etapa de validação do projeto para verificar se o circuito funciona corretamente antes da fabricação ou entrega final. |

| _DSM_ | Deep submicron | Refere-se a tecnologias de fabricação com dimensões bem menores que 1 micrômetro. |

| _tp_ | Timing Path | É um caminho de ponto a ponto. |

|  | Clock group | Grupo de caminhos diferentes do/de sinal/sinais de clock. |

|  | Slack | Diferença entre o tempo necessário e o tempo de checagem (quando negativo = deu ruim). |

|  | Net timing arcs | É o atraso real do caminho, é a soma dos atrasos da rede e célula. |

|  | Net delay | Tempo total necessário para carregar ou descarregar todos os dados parasitas da rede. |

|  | Cell Delay | É o atraso do dado passar da entrada para saída da célula. |

|  | Transparente latch | Circuito de memória que deixa o sinal passar diretamente enquanto o clock está ativo. |

| _FF_ | flip-flop | Circuito sequencial acionado pela borda do clock que armazena 1 bit de informação, menor unidade que forma a memória. |

|  | Pusle width | Largura do pulso, tempo que o dado se mantém ativo e inativo. |

| _tsu_ | Setup time | Intervalo de tempo antes da borda de clock no qual o dado deve-se manter estável para não ocorrer metaestabilidade |

| _thd_ | Hold time | Intervalo de tempo depois da borda de clock no qual o dado deve-se manter estável para não ocorrer metaestabilidade. |

|  | Signal slew | Tempo necessário para ocorrer uma transação. |

|  | Pulse Width | Tempo entre o estado atibvo e inativo do clock. |

|  | Clock latency | Diferença entre a skew e slew. |

| _HVT_ | High Threshold Voltage | Transistores com tensão de limiar alta, consumem menos energia mas são mais lentos. Localizados nas Standard Cell. |

| _RVT_ | Regular Threshold Voltage | Transistores com tensão de limiar padrão, equilibram desempenho e consumo de energia. Localizados nas Standard Cell. |

|  | Clock slew | É a diferença de tempo na chegada do clock em diferentes partes de um circuito digital. |

|  | Clock jitter | É a variação do skew no tmepo. Ele varia o Skew. |

|  | Recovery time | Tempo mínimo em que o reset deve estar desativado antes da borda do clock. (Assíncrono). |

|  | Removal time | Tempo mínimo que o sinal assíncrono, geralmente o reset, deve continuar ativo após a borda do clock. |

|  | Data path | É o caminho do dado da porta de entrada até ff, memória, latct, porta... |

|  | Clock path | É o caminho do pino de clock/memória até o pino de clock sequencial/memória/célula. |

|  | Clock gating path | Clock input port -> Clock gating. |

|  | Asynchronus path | Porta de entrada do projeto até célula sequencial/set/reset. |

|  | Critical path | O caminho mais lento do circuito, usado para determinar a frequência máxima do circuito. |

|  | False path | Caminho existente, mas não funcional. |

|  | Single cycle path | Caminho do circuito que dura menos de um ciclo. |

|  | Multi Cycle path | Caminho de temporização de projeto no qual o sinal pode levar mais de um ciclo. |

|  | Launch path | Caminho do clock usado no ponto inicial do caminho do registrador para registrador. |

|  | Capture path | Caminho do clock usado no ponto final do caminho do registrador para registrador. |

|  | Shortest path | É o caminho de menor tempo, o melhor caso. |

|  | Capactive Crosstalk | Interferência entre dois sinais próximos, causada pela capacitância parasita entre trilhas/fios no circuito. |

|  | Resistive Parasitcs | Resistência parasita relacionado na distribuição da fonte de alimentação. |

|  | IR Drop | Queda de tensão causada pela resistência das trilhas quando a corrente elétrica passa pela alimentação do chip. |

| _IR Noise_ | IR Noise | Variação ou queda indesejada de tensão causada pela resistência da rede de alimentação do chip. |

| _I/O_ | Input/Output | Interface responsável pela entrada e saída de sinais entre o chip e o ambiente externo. |

| _PDN_ | Power Distribution Network | Rede de distribuição de energia responsável por levar alimentação elétrica para todas as partes do chip. |

| _P&R_ | Place and Route | Etapa do projeto físico que posiciona as células no chip e realiza as conexões entre elas. |

| _DET_ | Double Edge Triggered | Técnica em que o flip-flop captura dados nas duas bordas do clock (subida e descida). |

| _GAL_ | Globally Asynchronous Logic | Arquitetura onde diferentes blocos funcionam de forma assíncrona entre si. |

| _By-Pass Capacitor_ | Bypass Capacitor | Capacitor usado para filtrar ruídos e estabilizar a alimentação elétrica do circuito. |

| _CDC_ | Clock Domain Crossover | Cruzamento do domínio de clock, é a transferência do sinall de clock em diferentes partes do circuito. |

|  | Metastability | É a instabilidade do sinal em circuitos sequenciais quando o dado muda muito próximo da borda do clock. |

| _PVT_ | Process Voltage Temperature | Representa as variações físicas e operacionais que afetam o comportamento de um circuito integrado, caracterizado no PDK. Process (Fast/Slow), Voltage (VDD High/ VDDlow), Temperature (High, Slow). |

| _Corners_ | Process Voltage Temperature | Corners são combinações específicas de PVT (Process, Voltage, Temperature) usadas para analisar o comportamento de um circuito nas condições extremas (pior e melhor caso). |

| _OCV_ | On-Chip Variation | Variação das características elétricas dentro do próprio chip causada por processo, tensão e temperatura. |

|  | Electromigration | É o deslocamento gradual de átomos de metal de um condutor devido ao alto movimento dos elétrons que colidem com eles, resultando numa alta correteq eu flui pelo condugor podendo causar a conexão em curto ou em aberto. |

| _MTTF_ | Mean time to failure | É o tempo médio para falha, é a indicação da vida útil do CI. |

|  | Vold | O efeito da eletromigração reduz a densidade de íons em alguns pontos de interconexão causando um vazio, que leva ao circuito aberto. |

|  | Hillock | Protuberância: Aumento da largura da interconexão metálica entre camadas de metal resultando em um curto circuito. |

| _NDR_ | Nondefault rules | É o dimensionamento adequado dos nets com regras que não são padrão. |

| _Nets_ | Nets | Conexões elétricas que interligam células e componentes dentro do circuito digital. |

| _BJT_ | Bipolar Junction Transistor | Transistor que utiliza elétrons e lacunas para amplificar ou chavear sinais elétricos. |

| _PNPN_ | PNPN Junction | Estrutura semicondutora de quatro camadas usada em dispositivos de chaveamento, como tiristores. |

| _SOI_ | Silicon on Insulator | Tecnologia de fabricação onde o transistor é construído sobre uma camada isolante para reduzir perdas elétricas. |

| _FEOL_ | Front-End of Line | Etapa da fabricação onde os transistores e dispositivos ativos são construídos no wafer. |

| _BEOL_ | Back-End of Line | Etapa da fabricação responsável pelas interconexões metálicas entre os dispositivos do chip. |

| _DIBL_ | Drain Induced Barrier Lowering | Efeito em transistores onde a tensão do dreno reduz a barreira do canal, aumentando leakage. |

| _GIBL_ | Gate Induced Barrier Lowering | Efeito em que o campo elétrico da porta reduz a barreira do transistor, causando corrente de fuga. |

|  | antenna effect | é um problema de fabricação em circuitos integrados onde cargas elétricas acumuladas durante o processo (plasma) se acumulam em interconexões metálicas e podem danificar o óxido de gate dos transistores. |

| _CMP_ | Chemical mechanical planarization | Processo quimico-mecânico que causa a erosão/rebaixamento no processo de fabricação. |

| _QoR_ | Quality of Results | Métrica usada para avaliar qualidade do projeto em desempenho, área, potência e timing. |

| _QoS_ | Quality of Silicon | Qualidade final do chip fabricado considerando desempenho, confiabilidade e consumo. |

| _Tie_ | Tie cell | Células padrão usadas para constantes lógicas (1/VDD ou 0/GND). |

| _TIEHI_ | Tie-high | Células com sinal fixo em 1/VDD. |

| _TIELO_ | Tie-low | Células com sinal fixo em 0/GND. |

***

</details>

<a name="idDD"></a>

<details>

<summary><b>Fundamentos de Designs Digitais</b></summary>

| Sigla | Nome | Descrição. |

| ------- | ------ | -----------. |

| _BCD_ | Binary-Coded Decimal | Codificação de decimal para 4 bits binários. |

| _MSB_ | Most Significant Bit | Bit mais significativo, localizado mais à esquerda. |

| _LSB_ | Least Significant Bit | Bit mais significativo, localizado mais à direita. |

| _Little Endian_ | Little Endian | Formato em que o byte menos significativo é armazenado primeiro na memória. Ex: Risc-V. |

| _Big Endian_ | Big Endian | Formato em que o byte mais significativo é armazenado primeiro na memória. Ex: Mips. |

| _Sign and Magnitude_ | Sign and Magnitude | Representação binária onde um bit indica o sinal e os demais representam o valor. |

| _One's Complement_ | One's Complement | Representação de números negativos obtida invertendo todos os bits do número positivo. |

| _Two's Complement_ | Two's Complement | Representação binária mais usada para números negativos, invertendo os bits e somando 1. |

| _Quantization_ | Quantization | Conversão de valores analógicos em níveis discretos digitais. |

| _Encoding_ | Encoding | Processo de atribuir uma palavra digital para cada valor quantizado. |

| _FP_ | Floating Point | Representação numérica que usa sinal, expoente e mantissa para representar números reais. |

| _IEEE 754_ | IEEE 754 | Padrão mais usado para representação de números em ponto flutuante em hardware digital. |

| _FP32_ | Single Precision | Formato de 32 bits com 1 bit de sinal, 8 de expoente e 23 de mantissa. |

| _FP64_ | Double Precision | Formato de 64 bits com maior precisão e alcance numérico. |

| _FP16_ | Half Precision | Formato de 16 bits usado para reduzir área, memória e consumo. |

| _BF16_ | bfloat16 | Formato reduzido muito usado em IA, mantendo expoente grande e menor mantissa. |

| _Gray_ | Gray Code | Codificação binária em que apenas um bit muda entre valores consectuvios. |

| _K-Map_ | Karnaugh maps | Método gráfico usado para simplificar expressões booleanas e circuitos lógicos. |

| _SOM_ | Sum of Minterms | Forma canônica booleana onde a função é representada pela soma de mintermos. |

| _POM_ | Product of Maxterms | Forma canônica booleana onde a função é representada pelo produto de maxtermos. |

| _mi_ | Minterm | Produto que inclui todas as variáveis de entradas. |

| _Mi_ | Maxterm | Soma de todas as variáveis de entradas. |

| _SOP_ | Sum of Products | Uma função escrita como uma OR de várias Ands. |

| _POS_ | Product of Sum | Uma função escrita como uma ANDs de várias ORs. |

| _Cut Vertex_ | Articulation Point | Vértice cuja remoção aumenta o número de componentes conectados do grafo. |

| _Cut Edge_ | Bridge Edge | Aresta cuja remoção desconecta partes do grafo. |

| _BDD_ | Binary Decision Diagram | Estrutura gráfica usada para representar e manipular funções booleanas. |

| _OBDD_ | Ordered Binary Decision Diagram | BDD em que as variáveis seguem uma ordem fixa em todos os caminhos. |

| _DAG_ | Directed Acyclic Graph | Grafo direcionado sem ciclos usado para representar dependências e decisões lógicas. |

| _ROBDD_ | Reduced Ordered Binary Decision Diagram | OBDD otimizado pela remoção de nós redundantes e subárvores equivalentes. |

| _Quine-McCluskey Approach_ | Quine-McCluskey Method | Método tabular usado para simplificar expressões booleanas. |

| _LE_ | Logical Effort | Método usado para estimar atraso e otimizar velocidade em portas lógicas. |

| _Block Diagram_ | Block Diagram | Representação gráfica de um sistema usando blocos funcionais e suas conexões. |

| _Bit_ | Binary Digit | Menor unidade de informação digital, podendo valer 0 ou 1. |

| _Byte_ | Byte | Conjunto de 8 bits usado para representar dados e caracteres digitais. |

| _X'_ | Don't Care | Condição em que o valor lógico pode ser 0 ou 1 sem afetar o funcionamento do circuito. |

| _Hi-Z_ | High Impedance | Estado em que a saída do circuito fica eletricamente desconectada da linha. |

| _State_ | State | Conjunto de informações armazenadas em um determinado instante que define o comportamento futuro do sistema. |

| _Stage_ | Stage | Etapa ou nível de processamento dentro de um circuito ou pipeline digital. |

| _Storage_ | Storage | Capacidade ou mecanismo usado para armazenar dados e informações digitais. |

| _Sequential Logic Circuits_ | Sequential Logic Circuits | Circuitos lógicos cuja saída depende das entradas atuais e do estado anterior. |

| _Combinational Logic Circuits_ | Combinational Logic Circuits | Circuitos lógicos cuja saída depende apenas das entradas atuais. |

|  | edge | É a borda, que é o período de transicação do sinal. (Transitório). |

|  | edge triggerd | Sensível a borda. |

| _FSM_ | Finite State Machine | Modelo lógico sequencial baseado em estados e transições. |

| _Mealy Model_ | Mealy Machine | Máquina de estados em que a saída depende do estado atual e das entradas. |

| _Moore Model_ | Moore Machine | Máquina de estados em que a saída depende apenas do estado atual. |

| _CU_ | Control Unit | Unidade responsável por controlar e coordenar as operações do sistema digital. |

| _PU_ | Processing Unit | Unidade responsável pelo processamento e execução das operações de dados. |

|  | Clock gating | Técnica usada em circuitos digitais para economizar energia, desligando sinal de clock em partes do circuito. |

| _ICG_ | Integrated Clock Gating | É uma célula padrão (standard cell) usada em microeletrônica para implementar clock gating de forma segura e sem glitches. |

| _Minimum Clock_ | Minimum Clock Period | Menor período de clock permitido para o circuito funcionar corretamente sem violar timing. |

| _Maximum Clock_ | Maximum Clock Frequency | Maior frequência de clock suportada pelo circuito sem erros de timing. |

| _tpcq_ | Propagation delay | Tempo após a borda do clock durante o qual saidá do FF tem garantia de estabilidade. |

| _ta_ | Aperture time | Tempo em trono da borda do clock, durante o qual os dados devem se manter estável. Tsetup + Thold. |

| _tccq_ | Contamination Delay | Tempo após a borda do clock durante o qual a saída do FF pode está instável. |

| _Path Delay_ | Path Delay | Tempo total gasto por um sinal ao percorrer um caminho do circuito. |

***

</details>

<a name="idASIC"></a>

<details>

<summary><b>Em ASIC designs</b></summary>

| Sigla | Nome | Descrição. |

| ------- | ------ | -----------. |

| _ASIC_ | Application-Specific Integrated Circuit | CI projetado com finalidade específica. |

| _Package_ | IC Package | Encapsulamento físico do chip responsável por proteger o die e conectar o circuito ao ambiente externo. |

|  | Pads | São as bordas do chips usadas para conectar sinais de entrada/saída, VDD/GND, comunicações, etc. |

|  | Netlist | É o produto da transformação feita por uma EDA de um RTL, utilizando as constraints do projeto e a tecnologia forneceida (gttech/pdk). |

|  | Gate level | Nível de representação digital em que o circuito é descrito usando portas lógicas e suas conexões. |

| _VHSIC_ | Very High-Speed Integrated Circuit | Circuito integrado desenvolvido para operar em alta velocidade. |

| _VHDL_ | VHSIC Hardware Description Language | Linguagem de descrição de hardware usada para modelar e projetar circuitos digitais. |

|  | ports | É a interface de um módulo. |

|  | architecture | É o que o programador vê, ou seja o que o processador faz. ISA,registradores, tipo de dados.. |

| _ISA_ | Instruction Set Architecture | Conjunto de instruções implementadas por uma arquitetura computacional. |

|  | microarchitecture | É como a arquitetura é implementada, ou seja, como o processador faz. Pipeline, ALU, Unidade de controle... |

| _DUT_ | Device Under Test | Circuito ou sistema que está sendo testado e verificado durante simulação ou validação. |

| _Stimulus_ | Stimulus | Conjunto de sinais ou entradas aplicados ao circuito durante testes e simulações. |

| _Assertions_ | Assertions | Verificações usadas para garantir que o circuito esteja obedecendo condições e comportamentos esperados durante a simulação. |

| _Semaphore_ | Semaphore | Mecanismo de sincronização usado para controlar acesso a recursos compartilhados entre processos. |

| _Mailbox_ | Mailbox | Estrutura usada para troca de mensagens entre processos, funcionando como uma fila FIFO. |

|  | Event | Um evento é ação no tempo zero. Ou seja, uma mudança instântanea que ocorre em determinado ponto. |

|  | Constraints | Especificações definida pelo budget do projeto, podendo conter timing, power, etc.. |

| _TBs_ | Testbenchs (wrappers) | Ambiente de verificação que encapsula o projeto para aplicar testes, estímulos e validar o funcionamento do circuito. |

| _DUV_ | Device Under Verification | Circuito ou sistema que está sendo verificado durante o processo de validação funcional. |

| _CBS_ | Cycle-Based Simulators | Simuladores que executam o circuito ciclo a ciclo, focando em desempenho para projetos grandes. |

| _EBS_ | Event-Based Simulators | Simuladores que processam mudanças de sinais e eventos ao longo do tempo no circuito. |

| _DSP_ | Digital Signal Processing | Processamento digital de sinais usado para manipular áudio, vídeo e dados digitais. |

| _OVI_ | Open Verilog International | Organização responsável pela padronização inicial da linguagem Verilog. |

| _TVM_ | Test Vector Memory | Memória que armazena vetores de teste, usadas junto com ATPG e BIST. |

| _ICE_ | In-Circuit Emulator | Uma caxinha que pode emular o processador do sistema. Pode executar código da memória ala ou um código. Geralmente, integrado ao núcleo. |

| _LRM_ | Language Reference Manual | Documento oficial que define regras, sintaxe e comportamento de uma linguagem de hardware. |

| _PLI_ | Programming Language Interface | Interface que permite integrar linguagens de programação externas com simuladores Verilog. |

| _VCD_ | Value Change Dump | Arquivo usado para armazenar mudanças de sinais durante a simulação digital. |

| _ABV_ | Assertion-Based Verification | Método de verificação que usa assertions para validar comportamentos e regras do projeto digital. |

| _FIFO_ | First In First Out | Estrutura de dados em que o primeiro elemento a entrar é o primeiro a sair. |

| _OVL_ | Open Verification Library | Biblioteca de assertions reutilizáveis usada para verificação de projetos digitais. |

| _VCs_ | Virtual Cores | Blocos reutilizáveis de IP usadas em verificação e integração de projetos ASIC/SoC. |

| _BFM_ | Bus Functional Model | Modelo usado em verificação para simular o comportamento funcional de interfaces e barramentos. |

| _GUI_ | Graphical User Interface | Interface gráfica que permite interação visual com softwares e sistemas digitais. |

| _DVE_ | Discovery Visualization Environment | Ferramenta da Synopsys usada para depuração e análise das simulações do RTL. |

| _SDF_ | Standard Delay Format | Estrutura de dados de saída que contém o atraso real do circuito. |

| _PDEF_ | Physical Definition File | Arquivo de saída/entrada que possui informações físicas do projeto, como dimensões, pinos e posicionamento do chip. |

| _TLU_ | Table Lookup Plus File | Arquivos usadas em análise física para modelar resistência e capacitância das interconexões do chip. |

| _DFT_ | Design for test | Teste de varredeura é uma técnica de design para testabilidade, onde há inserção de FF de varredaruas durante a síntese, para otmizar síntese, timing e checkar fisicamente o projeto. |

| _PI_ | Primary Input | Entrada principal de sinais em um circuito digital. |

| _PO_ | Primary Output | Saída principal de sinais de um circuito digital. |

| _IDD Test_ | IDD Test | Teste que mede a corrente elétrica consumida pelo circuito para detectar falhas de fabricação ou defeitos. |

|  | Scan Chain | Basicamente a inserção de um FF + MUX no processo de DFT. |

| _LSSD_ | Level-Sensitive Scan Design | Técnica de DFT baseada em latches sensíveis a nível para melhorar testabilidade do circuito. |

| _BIST_ | Built-In Self-Test | Técnica em que o próprio circuito realiza testes internos automaticamente. |

| _LFSR_ | Linear Feedback Shift Register | Registrador de deslocamento com realimentação usado para gerar padrões pseudoaleatórios. |

| _BILBO_ | Built-In Logic Block Observer | Estrutura de teste usada para geração de padrões e análise de respostas em BIST. |

| _JTAG_ | Joint Test Action Group | Padrão de boundary scan usado para teste e depuração de chips e placas. |

| _TAP_ | Test Access Port | Interface usada pelo JTAG para acessar funções de teste do circuito. |

| _ATPG_ | Automatic Test Pattern Generation | Processo automático de geração de vetores de teste para detectar falhas no circuito. |

| _ERC_ | Electrical Rule Check | Verificação elétrica realizada na etapa de verificação física para detectar violações elétricas no layout. |

| _Signoff_ | Signoff | Etapa final de verificação e aprovação do projeto antes da fabricação do chip. |

| _LPE_ | Layout Parasitic Extraction | Etapa de extração dos parasitas elétricos do layout após o roteamento físico do chip. |

| _GDSOUT_ | GDSII Output | Formato de arquivo final do layout físico do chip enviado para fabricação. |

| _PDV_ | Physical Design Verification | Etapa de verificação física do layout para validar regras, conectividade e integridade do chip antes do signoff. |

| _DDC_ | Design Compiler Database | Arquivo de entrada do Physical Design gerado na etapa de síntese lógica pelo Design Compiler. |

| _DB_ | Database Library | Arquivo de entrada contendo bibliotecas de células padrão usadas durante síntese e implementação física. |

| _.map_ | TLU+ Mapping File | Arquivo de entrada usado na etapa física para mapear camadas tecnológicas aos modelos parasitas TLU+. |

| _TF_ | Technology File | Arquivo de entrada da etapa de Physical Design contendo regras e informações da tecnologia de fabricação. |

| _SPEF_ | Standard Parasitic Exchange Format | Arquivo de saída do Physical Design contendo parasitas extraídos de resistência e capacitância. |

| _NDM_ | New Data Model | Banco de dados físico de entrada usado pelo IC Compiler II durante Place & Route. |

***

</details>
