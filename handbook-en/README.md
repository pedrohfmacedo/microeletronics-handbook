<<<<<<< HEAD
## Mini Dictionary in Microeletronics (EN)
=======
# Microelectronics Glossary
>>>>>>> 99c3469 (version 0.1)

Mini dictionary and technical glossary for Microelectronics, VLSI, ASIC Design, Verification and Physical Design.

---

# Languages

* [Português](#português)
* [English](#english)

---

# Português

## Índice

* [A](#a-pt)
* [B](#b-pt)
* [C](#c-pt)
* [D](#d-pt)
* [E](#e-pt)
* [F](#f-pt)
* [G](#g-pt)
* [H](#h-pt)
* [I](#i-pt)
* [J](#j-pt)
* [K](#k-pt)
* [L](#l-pt)
* [M](#m-pt)
* [N](#n-pt)
* [O](#o-pt)
* [P](#p-pt)
* [Q](#q-pt)
* [R](#r-pt)
* [S](#s-pt)
* [T](#t-pt)
* [U](#u-pt)
* [V](#v-pt)
* [W](#w-pt)
* [X](#x-pt)

---

<a name="a-pt"></a>

<details markdown="1">
<summary><b>A</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *ABV* | Assertion-Based Verification | Método de verificação que usa assertions para validar comportamentos e regras do projeto digital. |
| *architecture* | architecture | É o que o programador vê, ou seja, o que o processador faz (ISA, registradores, tipo de dados). |
| *ASCII* | American Standard Code for Information Interchange | Padrão de codificação de caracteres em valores numéricos. |
| *ASIC* | Application-Specific Integrated Circuit | Circuito integrado projetado com finalidade específica. |
| *Assertions* | Assertions | Verificações usadas para garantir que o circuito obedeça condições e comportamentos esperados durante a simulação. |
| *ATPG* | Automatic Test Pattern Generation | Processo automático de geração de vetores de teste para detectar falhas no circuito. |

</details>

---

<a name="b-pt"></a>

<details markdown="1">
<summary><b>B</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *Band Gap* | Band Gap | Diferença de energia entre a banda de valência e a banda de condução (eV). |
| *Band Theory* | Band Theory | Modelo usado para explicar a condução em sólidos e o comportamento dos elétrons. |
| *BBD* | Block Based Design | Metodologia de projetos orientada a blocos, usada em ASICs complexos e IPs. |
| *BCD* | Binary-Coded Decimal | Codificação de decimal para 4 bits binários. |
| *BDD* | Binary Decision Diagram | Estrutura gráfica usada para representar e manipular funções booleanas. |
| *BEOL* | Back-End of Line | Etapa da fabricação responsável pelas interconexões metálicas entre os dispositivos do chip. |
| *BF16* | bfloat16 | Formato reduzido muito usado em IA, mantendo expoente grande e mantissa menor. |
| *BFM* | Bus Functional Model | Modelo usado em verificação para simular o comportamento funcional de interfaces e barramentos. |
| *Big Endian* | Big Endian | Formato onde o byte mais significativo é armazenado primeiro na memória (ex: MIPS). |
| *BILBO* | Built-In Logic Block Observer | Estrutura de teste usada para geração de padrões e análise de respostas em BIST. |
| *BIST* | Built-In Self-Test | Técnica onde o próprio circuito realiza testes internos automaticamente. |
| *Bit* | Binary Digit | Menor unidade de informação digital (0 ou 1). |
| *BJT* | Bipolar Junction Transistor | Transistor que utiliza elétrons e lacunas para amplificar ou chavear sinais elétricos. |
| *Block Diagram* | Block Diagram | Representação gráfica de um sistema usando blocos funcionais e suas conexões. |
| *Budget* | Budget | Restrição de projeto que define o caminho de desenvolvimento (timing, power ou area). |
| *BUS* | Barramento | Meio físico de conexão entre blocos, regido por um protocolo. |
| *By-Pass Capacitor* | Bypass Capacitor | Capacitor usado para filtrar ruídos e estabilizar a alimentação elétrica do circuito. |
| *Byte* | Byte | Conjunto de 8 bits usado para representar dados e caracteres digitais. |

</details>

---

<a name="c-pt"></a>

<details markdown="1">
<summary><b>C</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *CAD* | Computer-Aided Design | Software para projetar, desenhar e verificar sistemas para projeto de circuitos integrados. |
| *Capactive Crosstalk* | Capacitive Crosstalk | Interferência entre dois sinais próximos causada pela capacitância parasita. |
| *Capture path* | Capture Path | Caminho do clock usado no ponto final do caminho registrador para registrador. |
| *CBS* | Cycle-Based Simulators | Simuladores que executam o circuito ciclo a ciclo, focando em desempenho. |
| *CCS* | Composite Current Source | Modelo de timing mais acurado que o NLDM. |
| *CDC* | Clock Domain Crossover | Cruzamento de domínio de clock; transferência de sinal entre diferentes domínios. |
| *CELL* | Cell | Qualquer tipo de componente ou unidade de um projeto CI (ex: mux, transistor). |
| *Cell Delay* | Cell Delay | Atraso do dado ao passar da entrada para a saída da célula. |
| *Clock gating* | Clock Gating | Técnica para economizar energia desligando o clock em partes do circuito. |
| *Clock gating path* | Clock Gating Path | Caminho do clock input port até o clock gating. |
| *Clock group* | Clock Group | Grupo de caminhos diferentes de sinais de clock. |
| *Clock jitter* | Clock Jitter | Variação do skew no tempo. |
| *Clock latency* | Clock Latency | Diferença entre skew e slew. |
| *Clock path* | Clock Path | Caminho do pino de clock até o pino de clock sequencial. |
| *Clock slew* | Clock Slew | Diferença de tempo na chegada do clock em diferentes partes do circuito. |
| *CMP* | Chemical Mechanical Planarization | Processo químico-mecânico que causa erosão/rebaixamento na fabricação. |
| *CMOS* | Complementary Metal-Oxide-Semiconductor | Tecnologia que usa NMOS e PMOS para baixo consumo de energia. |
| *Combinational Logic Circuits* | Combinational Logic Circuits | Circuitos lógicos cuja saída depende apenas das entradas atuais. |
| *Constraints* | Constraints | Especificações definidas pelo budget do projeto (timing, power, etc.). |
| *CORE* | Core | Coração do CI; fornece a funcionalidade básica. |
| *Corners* | PVT Corners | Combinações específicas de Processo, Tensão e Temperatura para análise de extremos. |
| *CPLD* | Complex Programmable Logic Device | PLD com múltiplos blocos lógicos e interconexões previsíveis. |
| *Critical path* | Critical Path | Caminho mais lento do circuito; determina a frequência máxima. |
| *CTS* | Clock Tree Synthesis | Etapa do fluxo físico que cria e otimiza a rede de distribuição do clock. |
| *CU* | Control Unit | Unidade responsável por controlar e coordenar as operações do sistema digital. |
| *Cut Edge* | Bridge Edge | Aresta cuja remoção desconecta partes do grafo. |
| *Cut Vertex* | Articulation Point | Vértice cuja remoção aumenta o número de componentes conectados do grafo. |

</details>

---

<a name="d-pt"></a>

<details markdown="1">
<summary><b>D</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *DAG* | Directed Acyclic Graph | Grafo direcionado sem ciclos usado para representar dependências e decisões lógicas. |
| *Data path* | Data Path | Caminho do dado da porta de entrada até FF, memória, latch, etc. |
| *DB* | Database Library | Arquivo de entrada com bibliotecas de células padrão para síntese e implementação física. |
| *DDC* | Design Compiler Database | Arquivo de entrada do Physical Design gerado na síntese lógica. |
| *DEF* | Design Exchange Format | Descreve a implementação física do design (placement, roteamento e conexões). |
| *DET* | Double Edge Triggered | Técnica onde o flip-flop captura dados nas duas bordas do clock. |
| *DFM* | Design for Manufacturability | Regras e diretrizes para serem cumpridas na etapa de fabricação. |
| *DFT* | Design for Testability | Técnica de design para testabilidade, incluindo inserção de scan chain. |
| *DH* | Design House | Empresa especializada em etapas do VLSI que projeta para terceiros. |
| *DIBL* | Drain Induced Barrier Lowering | Efeito onde a tensão do dreno reduz a barreira do canal, aumentando leakage. |
| *Die* | Die | Área útil usada pelo chip no wafer. |
| *DRAM* | Dynamic Random Access Memory | Memória densa que armazena dados em capacitores e precisa de refresh. |
| *DRC* | Design Rule Check | Regras de fabricação que o layout deve obedecer. |
| *DSCL* | Digital Standard Cell Library | Conjunto de células padrão digitais (lógica, layout e timing). |
| *DSM* | Deep Submicron | Tecnologias de fabricação com dimensões bem menores que 1 micrômetro. |
| *DSP* | Digital Signal Processing | Processamento digital de sinais para manipular áudio, vídeo e dados digitais. |
| *DTA* | Dynamic Timing Analysis | Técnica para analisar timing utilizando vetores de teste (mais lenta). |
| *DUT* | Device Under Test | Circuito ou sistema sendo testado e verificado durante simulação. |
| *DUV* | Device Under Verification | Circuito sendo verificado durante o processo de validação funcional. |
| *Duty Cycle* | Duty Cycle | Razão entre o tempo em nível alto e o período total de um sinal periódico (%). |
| *DVE* | Discovery Visualization Environment | Ferramenta da Synopsys para depuração e análise de simulações RTL. |
| *DVT* | Design Validation Test | Etapa de validação para verificar o funcionamento correto do circuito. |

</details>

---

<a name="e-pt"></a>

<details markdown="1">
<summary><b>E</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *EBS* | Event-Based Simulators | Simuladores que processam mudanças de sinais e eventos ao longo do tempo. |
| *EDA* | Electronic Design Automation | Conjunto de ferramentas/software utilizadas no fluxo de desenvolvimento do CI. |
| *Edge Dies* | Edge Dies | Dies das bordas do wafer, possivelmente descartados por falhas esperadas. |
| *edge* | Edge | Borda, período de transição do sinal (transitório). |
| *edge triggered* | Edge Triggered | Sensível à borda. |
| *Electromigration* | Electromigration | Deslocamento gradual de átomos de metal devido à alta corrente elétrica. |
| *Encoding* | Encoding | Processo de atribuir uma palavra digital para cada valor quantizado. |
| *ERC* | Electrical Rule Check | Verificação elétrica para detectar violações elétricas no layout. |
| *ESD* | Electrostatic Discharge | Descarga de eletricidade estática que pode danificar o chip. |
| *Event* | Event | Ação no tempo zero; mudança instantânea em determinado ponto. |

</details>

---

<a name="f-pt"></a>

<details markdown="1">
<summary><b>F</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *Fabless* | Fabless Chip Companies | Empresas que criam projetos usando EDA e fabricam em foundries (ex: Apple, AMD, Nvidia). |
| *Fabs* | Fabrication Plants | Fábricas que projetam, fabricam e vendem chips (IDMs) (ex: Intel). |
| *False path* | False Path | Caminho existente, mas não funcional. |
| *Fan-in* | Fan-in | Número de entradas de uma porta; afeta a resistência. |
| *Fan-out* | Fan-out | Número de saídas de uma porta; afeta a capacitância. |
| *FDSOI* | Fully Depleted Silicon-On-Insulator | Tecnologia com canal totalmente depletado sobre isolante, reduzindo leakage. |
| *FEOL* | Front-End of Line | Etapa de fabricação onde transistores e dispositivos ativos são construídos. |
| *FF* | Flip-Flop | Circuito sequencial acionado pela borda do clock que armazena 1 bit. |
| *FIFO* | First In First Out | Estrutura de dados onde o primeiro elemento a entrar é o primeiro a sair. |
| *FinFET* | Fin Field-Effect Transistor | Transistor 3D com canal em forma de "fin", melhor controle eletrostático. |
| *Flat Zone* | Flat Zone | Borda do wafer cortada para identificação. |
| *Floorplan* | Floorplan | Roteamento de vias para alimentação; define localização e tamanho dos módulos. |
| *Foundry* | Foundry | Fábricas que produzem chips para terceiros (ex: Samsung, TSMC). |
| *FP* | Floating Point | Representação numérica com sinal, expoente e mantissa para números reais. |
| *FP16* | Half Precision | Formato de 16 bits (1 sinal, 5 expoente, 10 mantissa - IEEE 754). |
| *FP32* | Single Precision | Formato de 32 bits (1 sinal, 8 expoente, 23 mantissa). |
| *FP64* | Double Precision | Formato de 64 bits com maior precisão e alcance numérico. |
| *FPGA* | Field-Programmable Gate Array | Dispositivo reconfigurável com blocos lógicos e interconexões programáveis. |
| *FRAM* | Frame | Similar ao LEF; descreve o formato físico das células. |
| *FSM* | Finite State Machine | Modelo lógico sequencial baseado em estados e transições. |

</details>

---

<a name="g-pt"></a>

<details markdown="1">
<summary><b>G</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *GAL* | Globally Asynchronous Logic | Arquitetura onde blocos diferentes funcionam de forma assíncrona entre si. |
| *Gate level* | Gate Level | Nível de representação digital usando portas lógicas e conexões. |
| *GDSI* | Graphic Design System I | Formato antigo/obsoleto para representar layout físico. |
| *GDSII* | Graphic Design System II | Formato padrão atual para representar layout físico. |
| *GDSOUT* | GDSII Output | Formato final do layout físico enviado para fabricação. |
| *GIBL* | Gate Induced Barrier Lowering | Efeito onde o campo elétrico da porta reduz a barreira, causando fuga. |
| *Gray* | Gray Code | Codificação binária onde apenas um bit muda entre valores consecutivos. |
| *GRID* | Grid | Malha de referência usada no layout para alinhar e posicionar células. |
| *GTECH* | Generic Technology | Biblioteca padrão de células genéricas da EDA para síntese intermediária. |
| *GUI* | Graphical User Interface | Interface gráfica para interação visual com softwares e sistemas digitais. |

</details>

---

<a name="h-pt"></a>

<details markdown="1">
<summary><b>H</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *Hard Block* | Hard Block | Bloco físico já pronto, otimizado para alta performance e baixo consumo. |
| *HBM* | Human Body Model | Simulação de descarga elétrica usando o modelo humano. |
| *HDL* | Hardware Description Language | Linguagem para descrever comportamento de circuitos digitais. |
| *Hi-Z* | High Impedance | Estado onde a saída do circuito fica eletricamente desconectada. |
| *Hillock* | Hillock | Protuberância: aumento da largura da interconexão metálica causando curto. |
| *HVT* | High Threshold Voltage | Transistores com tensão de limiar alta (menos energia, mais lentos). |

</details>

---

<a name="i-pt"></a>

<details markdown="1">
<summary><b>I</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *I/O* | Input/Output | Interface responsável pela entrada e saída de sinais do chip. |
| *ICE* | In-Circuit Emulator | Dispositivo que emula o processador do sistema, integrado ao núcleo. |
| *ICG* | Integrated Clock Gating | Célula padrão para implementar clock gating sem glitches. |
| *ICs* | Integrated Circuits | Circuitos integrados. |
| *IDD Test* | IDD Test | Teste que mede a corrente elétrica consumida para detectar falhas. |
| *IDMs* | Integrated Device Manufacturers | Empresas que projetam, fabricam e vendem seus chips (ex: Micron, Intel). |
| *IEEE 754* | IEEE 754 | Padrão mais usado para representação de números em ponto flutuante. |
| *Ingot* | Ingot | Lingotes cilíndricos de silício puro, matéria-prima para semicondutores. |
| *IPs* | Intellectual Property | Blocos de circuitos projetados, verificados e reutilizáveis. |
| *IR Drop* | IR Drop | Queda de tensão causada pela resistência das trilhas de alimentação. |
| *IR Noise* | IR Noise | Variação ou queda indesejada de tensão na rede de alimentação. |
| *ISA* | Instruction Set Architecture | Conjunto de instruções implementadas por uma arquitetura computacional. |

</details>

---

<a name="j-pt"></a>

<details markdown="1">
<summary><b>J</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *JTAG* | Joint Test Action Group | Padrão de boundary scan para teste e depuração de chips e placas. |

</details>

---

<a name="k-pt"></a>

<details markdown="1">
<summary><b>K</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *K-Map* | Karnaugh Map | Método gráfico usado para simplificar expressões booleanas e circuitos lógicos. |

</details>

---

<a name="l-pt"></a>

<details markdown="1">
<summary><b>L</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *Launch path* | Launch Path | Caminho do clock usado no ponto inicial do caminho registrador para registrador. |
| *Layer* | Layer | Níveis de materiais empilhados no chip, cada um com função específica. |
| *Layout* | Layout | Planta do circuito integrado. |
| *LE* | Logical Effort | Método usado para estimar atraso e otimizar velocidade em portas lógicas. |
| *LEF* | Library Exchange Format | Descreve geometria simplificada das células para place & route. |
| *LFSR* | Linear Feedback Shift Register | Registrador com realimentação para gerar padrões pseudoaleatórios. |
| *LIB* | Liberty Timing File | Arquivo (.lib) com timing, potência e função lógica das células padrão. |
| *Little Endian* | Little Endian | Formato onde o byte menos significativo é armazenado primeiro (ex: RISC-V). |
| *LPE* | Layout Parasitic Extraction | Extração de parasitas elétricos do layout após roteamento. |
| *LRM* | Language Reference Manual | Documento oficial que define regras, sintaxe e comportamento de uma linguagem. |
| *LSB* | Least Significant Bit | Bit menos significativo, localizado mais à direita. |
| *LSSD* | Level-Sensitive Scan Design | Técnica de DFT baseada em latches sensíveis a nível. |
| *LVF* | Liberty Variation Format | Extensão do Liberty para modelar variações estatísticas (PVT). |
| *LVS* | Layout Versus Schematic | Verifica se o layout físico corresponde ao esquemático. |

</details>

---

<a name="m-pt"></a>

<details markdown="1">
<summary><b>M</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *Mailbox* | Mailbox | Estrutura para troca de mensagens entre processos (fila FIFO). |
| *Mask* | Mask | Máscaras usadas no processo de litografia e dopagem. |
| *Mask Data* | Mask Data | Arquivo final que descreve todas as máscaras do chip (OASIS ou GDSII). |
| *Mask Layer* | Mask Layer | Camadas das máscaras, representadas por diferentes cores. |
| *Maximum Clock* | Maximum Clock Frequency | Maior frequência de clock suportada sem erros de timing. |
| *Mealy Model* | Mealy Machine | Máquina de estados onde a saída depende do estado atual e das entradas. |
| *Metastability* | Metastability | Instabilidade do sinal quando o dado muda próximo à borda do clock. |
| *Metastable* | Metastable | Dado com valor incerto, podendo ser o anterior ou atual. |
| *mi* | Minterm | Produto que inclui todas as variáveis de entrada. |
| *Mi* | Maxterm | Soma que inclui todas as variáveis de entrada. |
| *microarchitecture* | microarchitecture | Como a arquitetura é implementada (pipeline, ALU, unidade de controle). |
| *Minimum Clock* | Minimum Clock Period | Menor período de clock permitido sem violar timing. |
| *Moore Model* | Moore Machine | Máquina de estados onde a saída depende apenas do estado atual. |
| *MOSFETs* | Metal-Oxide-Semiconductor Field-Effect Transistor | Transistor usado para chaveamento e amplificação. |
| *MPGA* | Mask Programmable Gate Array | Dispositivo programado por máscara na fabricação. |
| *MSB* | Most Significant Bit | Bit mais significativo, localizado mais à esquerda. |
| *MTTF* | Mean Time To Failure | Tempo médio para falha; indica a vida útil do CI. |
| *Multi Cycle path* | Multi Cycle Path | Caminho onde o sinal pode levar mais de um ciclo de clock. |

</details>

---

<a name="n-pt"></a>

<details markdown="1">
<summary><b>N</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *NDM* | New Data Model | Banco de dados físico usado pelo IC Compiler II durante Place & Route. |
| *NDR* | Non-Default Rules | Dimensionamento adequado dos nets com regras não padrão. |
| *Net delay* | Net Delay | Tempo total para carregar ou descarregar os parasitas da rede. |
| *Net timing arcs* | Net Timing Arcs | Atraso real do caminho (soma dos atrasos da rede e célula). |
| *Netlist* | Netlist | Produto da transformação do RTL pela EDA usando constraints e tecnologia. |
| *Nets* | Nets | Conexões elétricas que interligam células e componentes. |
| *NLDM* | Non-Linear Delay Model | Modelo de timing não linear (menos acurado). |
| *NLPM* | Natural Language Programming Linter | Biblioteca com modelagem de potência. |
| *NMOS* | N-channel Metal-Oxide-Semiconductor | Transistor que conduz quando a tensão no gate é alta. |
| *NORA* | NO-RAce Logic | Técnica de lógica dinâmica que evita condições de corrida. |

</details>

---

<a name="o-pt"></a>

<details markdown="1">
<summary><b>O</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *OASIS* | Open Artwork System Interchange Standard | Formato open-source para representar design físico. |
| *OBDD* | Ordered Binary Decision Diagram | BDD com ordem fixa de variáveis em todos os caminhos. |
| *OCV* | On-Chip Variation | Variação das características elétricas dentro do chip (processo, tensão, temperatura). |
| *One's Complement* | One's Complement | Representação de números negativos invertendo todos os bits. |
| *OSAT* | Outsourced Semiconductor Assembly and Test | Fábricas que encapsulam e testam chips das foundries. |
| *OTP* | One-Time Programmable | Memória programável apenas uma vez. |
| *OVI* | Open Verilog International | Organização responsável pela padronização inicial do Verilog. |
| *OVL* | Open Verification Library | Biblioteca de assertions reutilizáveis para verificação. |

</details>

---

<a name="p-pt"></a>

<details markdown="1">
<summary><b>P</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *P&R* | Place and Route | Etapa que posiciona as células e realiza as conexões entre elas. |
| *Package* | IC Package | Encapsulamento físico do chip para proteger o die e conectar ao externo. |
| *Pads* | Pads | Bordas do chip para conectar sinais I/O, VDD/GND, etc. |
| *Path Delay* | Path Delay | Tempo total gasto por um sinal ao percorrer um caminho. |
| *PBD* | Platform Based Design | Metodologia orientada a plataforma (alto nível de abstração). |
| *PDEF* | Physical Definition File | Arquivo com informações físicas do projeto (dimensões, pinos, posicionamento). |
| *PDK* | Process Design Kit | Conjunto de arquivos caracterizados fornecidos pela foundry. |
| *PDN* | Power Distribution Network | Rede de distribuição de energia do chip. |
| *PDV* | Physical Design Verification | Verificação física do layout antes do signoff. |
| *PI* | Primary Input | Entrada principal de sinais em um circuito digital. |
| *PI/PO* | Pins | Pontos de conexão do circuito (entrada ou saída). |
| *Placement* | Placement | Processo de alocar as Standard Cells no design proposto. |
| *PLD* | Programmable Logic Device | Categoria de dispositivos digitais programáveis. |
| *PLI* | Programming Language Interface | Interface para integrar linguagens externas com simuladores Verilog. |
| *PMOS* | P-channel Metal-Oxide-Semiconductor | Transistor que conduz quando a tensão no gate é baixa. |
| *PNPN* | PNPN Junction | Estrutura de quatro camadas usada em tiristores. |
| *PO* | Primary Output | Saída principal de sinais de um circuito digital. |
| *Polycrystalline* | Polycrystalline | Estrutura atômica do silício onde os cristais são fundidos. |
| *POM* | Product of Maxterms | Forma canônica booleana representada pelo produto de maxtermos. |
| *ports* | Ports | Interface de um módulo. |
| *POS* | Product of Sums | Função escrita como AND de várias ORs. |
| *PPA* | Power, Performance, and Area | Principais métricas para definição de um projeto de CI. |
| *PROM* | Programmable Read-Only Memory | ROM que pode ser programada uma única vez pelo usuário. |
| *PU* | Processing Unit | Unidade responsável pelo processamento e execução de operações. |
| *Pulse Width* | Pulse Width | Tempo entre o estado ativo e inativo do clock. |
| *PUN* | Pull-Up | PMOS em paralelo ligado ao VDD (parte superior do CMOS). |
| *PVT* | Process Voltage Temperature | Variações que afetam o comportamento do CI (caracterizado no PDK). |

</details>

---

<a name="q-pt"></a>

<details markdown="1">
<summary><b>Q</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *QoR* | Quality of Results | Métrica para avaliar qualidade do projeto (desempenho, área, potência, timing). |
| *QoS* | Quality of Silicon | Qualidade final do chip fabricado (desempenho, confiabilidade, consumo). |
| *Quantization* | Quantization | Conversão de valores analógicos em níveis discretos digitais. |
| *Quine-McCluskey Approach* | Quine-McCluskey Method | Método tabular para simplificar expressões booleanas. |

</details>

---

<a name="r-pt"></a>

<details markdown="1">
<summary><b>R</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *RAM* | Random Access Memory | Memória volátil de acesso rápido para leitura e escrita. |
| *Recovery time* | Recovery Time | Tempo mínimo para o reset estar desativado antes da borda do clock. |
| *Removal time* | Removal Time | Tempo mínimo para o sinal assíncrono continuar ativo após a borda do clock. |
| *Resistive Parasitics* | Resistive Parasitics | Resistência parasita relacionada à distribuição de alimentação. |
| *Reticles* | Reticles | Ferramenta com imagem de padrão para expor o wafer ou mask. |
| *ROBDD* | Reduced Ordered Binary Decision Diagram | OBDD otimizado (remoção de redundâncias). |
| *ROM* | Read-Only Memory | Memória não volátil para armazenar dados fixos. |
| *RTL* | Register Transfer Level | Nível de abstração para representar projetos digitais em HDL. |
| *RVT* | Regular Threshold Voltage | Transistores com tensão de limiar padrão (equilíbrio). |

</details>

---

<a name="s-pt"></a>

<details markdown="1">
<summary><b>S</b></summary>

| Sigla/Termo | Nome completo | Descrição |
| --- | --- | --- |
| *Scan Chain* | Scan Chain | Inserção de FF + MUX no processo de DFT. |
| *SCL* | Standard Cell | Células padrão caracterizadas pertencentes ao PDK. |
| *Scribe line* | Scribe Line | Espaços não funcionais entre dies para serra de corte. |
| *SDC* | Synopsys Design Constraints | Arquivo padrão (TCL) para definir restrições de PPA. |
| *SDF* | Standard Delay Format | Estrutura de dados com o atraso real do circuito. |
| *Semaphore* | Semaphore | Mecanismo de sincronização para acesso a recursos compartilhados. |
| *Sequential Logic Circuits* | Sequential Logic Circuits | Circuitos cuja saída depende das entradas atuais e do estado anterior. |
| *Shortest path* | Shortest Path | Caminho de menor tempo (melhor caso). |
| *Sign and Magnitude* | Sign and Magnitude | Representação binária com bit de sinal e bits de valor. |
| *Signoff* | Signoff | Etapa final de verificação e aprovação antes da fabricação. |
| *Signal slew* | Signal Slew | Tempo necessário para ocorrer uma transição. |
| *Silicon Wafer* | Silicon Wafer | Fatia do lingote usada como base para fabricação de CI. |
| *Single cycle path* | Single Cycle Path | Caminho que dura menos de um ciclo de clock. |
| *Site* | Site | Unidade básica de posicionamento (grid) para standard cells. |
| *SKEW* | Skew | Velocidade de transição do dado; diferença entre tempo de saída e chegada. |
| *Slack* | Slack | Diferença entre tempo necessário e tempo de chegada (negativo = violação). |
| *SoCs* | System-on-Chip | Chip que integra vários componentes em um único CI. |
| *Soft Block* | Soft Block | Bloco descrito em HDL, configurável e adaptável. |
| *SOI* | Silicon on Insulator | Tecnologia com transistor sobre camada isolante para reduzir perdas. |
| *SOM* | Sum of Minterms | Forma canônica booleana representada pela soma de mintermos. |
| *SOP* | Sum of Products | Função escrita como OR de várias ANDs. |
| *SPEF* | Standard Parasitic Exchange Format | Arquivo com parasitas extraídos (R e C). |
| *SPICE MODEL* | SPICE Model | Representação matemática do comportamento elétrico de um dispositivo. |
| *SPLD* | Simple Programmable Logic Device | PLD simples com poucos recursos para lógica básica. |
| *SRAM* | Static Random Access Memory | Memória rápida baseada em flip-flops (não precisa de refresh). |
| *STA* | Static Timing Analysis | Técnica para verificar timing do circuito digital. |
| *Stage* | Stage | Etapa ou nível de processamento em um circuito ou pipeline. |
| *State* | State | Conjunto de informações armazenadas que define o comportamento futuro. |
| *Stimulus* | Stimulus | Conjunto de sinais ou entradas aplicados ao circuito em teste. |
| *Storage* | Storage | Capacidade ou mecanismo para armazenar dados digitais. |

</details>

---

<a name="t-pt"></a>

<details markdown="1">
<summary><b>T</b></summary
