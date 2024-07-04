### DCCP

**Nome do Protocolo:** Datagram Congestion Control Protocol (DCCP)

**O que é:** Protocolo de transporte que fornece controle de congestionamento e gerenciamento de fluxo para aplicativos que utilizam datagramas, como transmissões de mídia em tempo real e jogos online. **Opera sobre a camada IP, utilizando portas para identificar endpoints e incorpora várias técnicas de controle de congestionamento, incluindo TCP-like e TCP-Friendly Rate Control (TFRC).**

**Atividade Prática:** 
Simulação do protocolo DCCP em C++. A atividade envolveu a troca de pacotes do sistema de congestionamento TCP-like, simulando uma dinâmica cliente-servidor com troca de pacotes (DCCP Request, DCCP Response, DCCP Ack, DCCP Data e DCCP Reset, DCCP Close, DCCP CloseReq).

### IEEE 802.11

**Nome do Protocolo:** IEEE 802.11

**O que é:** Wi-Fi

**Detalhe Técnico:** **Utiliza ondas de rádio ou infravermelho para transmissão na camada física.**

**Atividade Prática:** 
Não especificado.

### CARP

**Nome do Protocolo:** Common Address Redundancy Protocol (CARP)

**O que é:** Protocolo para aumentar a disponibilidade de um serviço ao compartilhar um endereço IP único entre vários servidores. **Opera na camada 3 do modelo OSI, utilizando uma técnica de endereço IP virtual (VIP) que circula entre vários nós.**

**Atividade Prática:** 
Simulação do funcionamento do protocolo em um ambiente virtual com duas máquinas virtuais Ubuntu, configurando IPs físicos e VIPs. A máquina mestre foi derrubada para a backup assumir como host principal.

### SCTP

**Nome do Protocolo:** Stream Control Transmission Protocol (SCTP)

**O que é:** Protocolo de transporte (camada 4) que compete com TCP e UDP. **Funciona por várias "streams" ou vias, resolvendo o problema de HoL-Blocking do TCP, e pode associar mais de um endereço IP a uma máquina (multihoming).**

**Atividade Prática:** 
Simulação do protocolo SCTP com OMNeT++ dentro de uma VM Lubuntu. Simulação do 4-Way-Handshake, troca de dados e término de associação, e multihoming forçando a continuação da associação por um IP secundário.

### VLAN 802.1q

**Nome do Protocolo:** VLAN 802.1q

**O que é:** Divisão lógica de uma rede local (LAN) em múltiplos domínios de broadcast independentes. **Permite que administradores de rede dividam e agrupem hosts com base em requisitos funcionais e de segurança, utilizando switches de camada 2.**

**Atividade Prática:** 
Conexão de roteadores MikroTik Hap a grupos de computadores, configurando IPs fixos e VLANs. Testes de ping entre clientes das mesmas e diferentes VLANs, demonstrando a comunicação correta e isolamento.

### ATM

**Nome do Protocolo:** Asynchronous Transfer Mode (ATM)

**O que é:** Tecnologia de comutação de pacotes utilizada para trafegar voz, vídeo e dados. **Divide dados em células de tamanho fixo de 53 bytes, permitindo garantia de qualidade de serviço (QoS) por meio de alocação de largura de banda.**

**Atividade Prática:** 
Caminhamento de pacotes representando células ATM, trafegando de mesa em mesa em uma rede simulada. Ao final, os pacotes foram reagrupados e a mensagem original remontada.

### SST

**Nome do Protocolo:** Structured Stream Protocol (SST)

**O que é:** Protocolo de rede de alto desempenho para comunicação eficiente e confiável. **Oferece transferência de dados estruturada, controle de congestionamento adaptável, detecção e correção de erros robustos, suporte para multicast e baixa latência.**

**Atividade Prática:** 
Simulação de envio de arquivos via SST em um modelo cliente-servidor. Demonstração da criação de subfluxos leves a partir de fluxos existentes.

### PPPoE

**Nome do Protocolo:** Point-to-Point Protocol over Ethernet (PPPoE)

**O que é:** Protocolo de rede (camada 3) que encapsula quadros PPP dentro de quadros Ethernet. **Utilizado em conexões de banda larga, gerenciando autenticação do usuário e gerenciamento de sessões em uma comunicação cliente-servidor.**

**Atividade Prática:** 
Comunicação via PPPoE entre máquinas virtuais cliente e servidor. Configuração de arquivos de servidor e cliente, autenticação e troca de pacotes PPPoE, acesso à internet e verificação de pacotes via tcpdump.

### L2CAP

**Nome do Protocolo:** Logical Link Control and Adaptation Protocol (L2CAP)

**O que é:** Protocolo da camada de enlace utilizado no Bluetooth para transmitir pacotes de dados entre dispositivos. **Gerencia segmentação e remontagem de dados, multiplexação de canais, controle de fluxo e qualidade de serviço (QoS).**

**Atividade Prática:** 
Uso do aplicativo mobile nrfConnect para simular conexões Bluetooth entre dispositivos, enviando sinais, testando a qualidade da conexão e observando o funcionamento do L2CAP.

### STP

**Nome do Protocolo:** Spanning-Tree Protocol (STP)

**O que é:** Protocolo da camada 2 do modelo OSI para evitar loops de broadcast na rede. **Seleciona as melhores rotas entre caminhos disponíveis, bloqueando redundâncias para evitar loops.**

**Atividade Prática:** 
Criação de uma rede simulada no programa Cisco, demonstrando o funcionamento do STP e desativação do protocolo para demonstrar uma rede loopada.
