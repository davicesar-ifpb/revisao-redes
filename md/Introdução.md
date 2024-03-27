# Introdução redes

### 1. Definição da Internet e Protocolos:

- A Internet é uma rede global de computadores interconectados que permite a comunicação e o compartilhamento de informações.
- Protocolos são conjuntos de regras que definem como os dados são transmitidos e recebidos na rede, garantindo a comunicação eficiente entre dispositivos.

### 2. Periferia da Rede: Sistemas Finais, Redes de Acesso e Meios Físicos:

- Os **sistemas finais**, como computadores e dispositivos móveis, são os pontos de extremidade da rede _(hosts)_.
- As redes de acesso são responsáveis por conectar os sistemas finais à infraestrutura de rede, utilizando diferentes tecnologias, como cabos, Wi-Fi, fibra óptica, entre outros.
- Os **meios físicos** são os meios de transmissão utilizados para enviar dados pela rede, como cabos de cobre, fibra óptica e ondas de rádio.

### 3. Núcleo da Rede: Comutação de Pacotes/Circuitos e Estrutura da Internet:

- A comutação de pacotes é um método de transmissão de dados em que as informações são divididas em pacotes independentes que seguem caminhos diferentes pela rede e são reagrupados no destino.
- **A estrutura da Internet é composta por uma rede de roteadores interconectados que encaminham os pacotes de dados entre os sistemas finais.**

### 4. Desempenho: Perdas, Atrasos e Taxa de Transferência:

- O desempenho de uma rede é afetado por fatores como perdas de pacotes, atrasos na transmissão e taxa de transferência, que determinam a eficiência e a qualidade da comunicação.

### 5. Camadas de Protocolos e Modelo de Referência:

- As camadas de protocolos dividem as funcionalidades de comunicação em diferentes níveis, facilitando o desenvolvimento, manutenção e interoperabilidade de sistemas de rede.
- O modelo de referência, como o modelo OSI ou TCP/IP, organiza essas camadas em uma estrutura hierárquica para padronizar a comunicação entre dispositivos.
    
    >O modelo de referência é uma abstração que **organiza as funcionalidades de comunicação em camadas distintas**, cada uma com responsabilidades específicas. Os dois modelos mais conhecidos são o Modelo OSI (Open Systems Interconnection) e o Modelo TCP/IP (Transmission Control Protocol/Internet Protocol).
    >
    > #### Modelo OSI:
    >O Modelo OSI é composto por **sete camadas**: *física, enlace, rede, transporte, sessão, apresentação e aplicação*.
    Cada camada tem funções bem definidas e se comunica com as camadas adjacentes para garantir a transmissão eficiente dos dados.
    A abordagem em camadas permite que diferentes fabricantes desenvolvam tecnologias compatíveis, pois cada camada opera de forma independente e se baseia em interfaces padronizadas.
    >
    > #### Modelo TCP/IP:
    >
    >O Modelo TCP/IP é mais simples, dividido em **quatro camadas**: *rede, transporte, aplicação e interface de rede*.
    Ele é amplamente utilizado na Internet e em redes locais, sendo mais prático e eficiente em ambientes reais de rede.
    Apesar de ter menos camadas que o OSI, o TCP/IP consegue realizar as mesmas funções essenciais de comunicação.
    **A organização em camadas desses modelos permite a padronização da comunicação entre dispositivos, facilitando o desenvolvimento de redes complexas e a interoperabilidade entre diferentes sistemas**. Cada camada se concentra em aspectos específicos da comunicação, como o roteamento de pacotes, o controle de erros, a formatação de dados e a interação com as aplicações, garantindo um fluxo de informações eficiente e confiável.
    >
    >Essa estrutura hierárquica e modular dos modelos de referência é fundamental para o funcionamento adequado das redes de computadores, pois simplifica a complexidade da comunicação e promove a escalabilidade e a flexibilidade dos sistemas de rede.

### 6. Histórico e Evolução das Redes de Computadores:

- O histórico das redes de computadores abrange desde os primórdios da comunicação digital até a evolução da Internet, passando por marcos importantes como a criação da ARPANET e o desenvolvimento de tecnologias de rede.
    > - **ARPANET (1969)**:   
    >   - A ARPANET foi a precursora da Internet, desenvolvida pela ARPA (Advanced Research Projects Agency) dos Estados Unidos.
    >   - Criada em 1969, a ARPANET foi a primeira rede a utilizar comutação de pacotes e protocolos de comunicação para interligar computadores em diferentes locais.