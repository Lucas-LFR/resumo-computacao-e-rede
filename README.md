# resumo-computacao-e-rede

COMPUTAÇÃO E REDE:
DOMÍNIO DE OBJETIVO
° Comparar tipos de computação, incluindo instâncias de contêiner, máquinas virtuais e funções.
°Desrever os recusos exigidos para as máquinas virtuais. 
°Definir pontos de extremidade públicos e privados.
°Descrever as opções de máquina virtual, incluindo VMs, conjuntos de dimensionamento de máquinas virtuais, conjuntos de disponibilidade de máquinas virtuais e a Área de trabalho virtual do Azure

- SERVIÇOS DE COMPUTAÇÃO DO AZURE
  ° A Computação do Azure é um serviço sob demadna que fornce recursos de computação, como discos, processadores, memória, rede e sistemas operacionais.

      Virtual    Aplicativo    Contêiner    Serviços de      Área de trabalho 
      Virtuais    Serviços     Instâncias   Kurbernets do    Virtual do Azure
                                            Azure(AKS)

 - MÁQUINAS VIRTUAIS DO AZURE
°As VMs são emulações de software de computadores físicos.
°Inclui processador virtual, memória, armazenamento e rede.
°Oferta de IaaS que oferece personalização e controle total.   

 - CONJUNTOS DE DIMENSIONAMENTO DE VMs
°Os conjuntos de dimensionamento oferecem uma oportunidade de balanceamento de carga para dimensionar os recusos automaticamente.

 - CONJUNTOS DE DISPONIBILIDADE DE VM
°Utilizado para ter uma alta disponibilidade.
°São mantidas em RACK's diferentes.
°São separadas em linhas diferentes chamadas de D.A(Domínio de Atualização.
°A ideia é separar 3 domínios de falhas
°Utilizado mais contra ENERGIA

 - ÁREA DE TRABALHO VIRTUAL DO AZURE
°A área de trabalho Virtual do Azure é uma virtualização de área de trabalho e aplicativo executada na nuvem.
°Crie um ambiente completo de virtualização da área de trabalho sem precisar executar outros servidores de gateway.
°Reduza o risco de que o recurso seja deixado para trás.
°Implantações reais de várias sessões

 - SERVIÇOS DE CONTÊINERES DO AZURE
°Os contêineres do Azure fornecem um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder a alterações sob demanda.
°Os contêineres são muitos utilizando no ambiente onpremisse

 - AZURE FUNCTIONS
°AZURE FUNCTIONS:Uma oferta de PaaS que dá suporte a operações de computação sem servidor.
  O código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos invativos.
°As funções podem ser utilizadas quando você precisa executar um trabalho em resposta à um EVENTO geralmente executamos a partir de uma solicitação chamada REST.
°As funções vão ser dimensionadas com base na demanda.
°A function me ajuda a tomar uma proxima decisão se é executar algo ou gerar alerta.

 - COMPARAR OPÇÕES DE COMPUTAÇÃO DO AZURE
Máquinas virtuais
    °Servidor baseado em nuvem que dá suporte a ambientes Windows ou Linux.
    °Útil para migrações de lift-and-shift para nuvem.(lift-and-shift = Levar como estar)
    °Pacote do sistema operacional completo, incluindo o sistema operacional do host.
Área de Trabalho Virtual
    °Fornece uma experiência de área de trabalho do windows baseada em nuvem.
    °Aplicativos dedicados para conexão e uso ou acessíveis de qualquer navegador moderno
    °O logon de vários clientes permite que vários usuários façam logon no mesmo computador desde que utilizem as mesmas aplicações
4:00

