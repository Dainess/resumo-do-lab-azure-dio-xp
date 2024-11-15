# Resumos dos Labs de Azure Bootcamp DIO XP

## Localizando Serviços por Categoria

O lab nos deu um overview em geral de: 

- como criar uma conta na Azure
  
- Uma explicação do que é a computação em nuvem (cloud) em termos gerais e que problema ela vem a resolver
  Principalmente uma questão de localização geográfica, escalabilidade e menores custos de entrada
  
- ensinou a diferença entre CapEx e OpEx
  - CapEx são as despesas de capital e vão incorrer principalmente quando for se instalar coisas privadas, on-premise, por conta própria.
  Elas significam um custo significativo para começar, mas representam custos muito pequenos comparativamente de manutenção
  - OpEx são ds despesas operacionais, e vão incorrer principalmente quando se adota soluções cloud no seu mix. Eles introduzem uma barreira
  de entrada muito menor, porém os custos de uso escalam de forma muito mais significativa dependendo do consumo. 

- mostrou os três (mais um) modelos de cloud diferentes:
  1) Privada
  2) Pública
  3) Híbrida
  +1) Multicloud

- uma primeira exibição da plataforma Azure por dentro

## Criando máquinas Virtuais na Azure

- Alta disponibilidade
  Service Level Agreement e o quanto vc por contrato tem como garantia de disponibilidade
- Escalabilidade e elasticidade
  Ajustar a capacidade do ambiente para atender a demanda
  Elasticidade se refere a capcidade do ambiente se retrair e expandir dinamicamente de acordo com demandas repentinas e não-previstas
- Previsibilidade, confiabilidade e segurança
  Confia-se que o sistema vai ficar de pé e é resiliente a falhas
  Pode-se prever o quanto custa, qual o desempenho que será obtido, um suporte do provedor cloud estará disponível
  Segurança digital é uma questão muito midiática, é o que mantém seus dados seguyros, que mantém hackers longe dos seus dados
  Lembrando que o provedor cloud é responsável por prover as ferramentas, e o contratante é o responsável por implementá-las
- Governança e gerenciamento
  Governança é sobre implementação de modelos de regras para controle de informação e práticas, seja por uma decisão de gestão da empresa,
  seja por compliance
  Já gerenciabilidade é sobre a facilidade para implementar a decisão sobre a aolocação de recursos
  Há a opção de fazer tanto o gerenciamento via portal quanto via código no Azure
- Laboratório
  Mostrou pra gente onde vê o tempo de inatividade aceitável de acordo com o SLA
  Opções de disponibilidade como exemplo para os acessos que a plataforma dá para documentação
  Zonas de acessibilidade e sua relação com custo, desempenho e SLA

## Configurando uma instância de Banco de Dados na Azure

- IaaS, PaaS, SaaS - Infra, Plataforma e Software
  1) Infra como serviço
     Coloca toda a parte física à sua disposição como um serviço remoto, mas deixa o gerenciamento na sua mão via recursos da plataforma
  2) Plataforma como serviço
     Permite o cliente a focar na aplicação que ele quer desenvolver e deixa recursos necessários (como por exemplo bancos de dados) como
     responsabilidade do provedor cloud (um ambiente de produção e desenvolvimento fornecido pelo provedor cloud)
  3) Software como serviço
     No caso aqui o cliente já está usando diretamente um aplicativo desenvolvido pelo provedor (que nesse caso não é necessariamente um
     provedor de cloud, pois pro cliente nesse menodelo interessa pouco o ambiente e sim a funcionalidade da aplicação). Um exemplo é a
     Adobe Creative Suite, que hoje adota um modelo SaaS onde o cliente paga uma assinatura e recebe atualizações constantes, com uma
     opção cloud na Adobre Creative Cloud
- Responsabilidade compartilhada
  Quando um cliente contrata um provedor cloud, o cliente e o provedor vão compartilhar responsabilidades sobre a operação de acordo com
  o modelo escolhido. Num caso IaaS a responsabilidade do provedor vai ser essencialmente sobre a camada física, já num modelo de SaaS
  o provedor vai cuidar de quase tudo, restando a utilização, o acesso e a personalização como responsabilidades do cliente.
  Quando se escolhe cada uma das opções é uma consideração de quanto acesso se precisa ter, o quanto de tempo o cliente quer gastar
  gerenciando isso e o quanto custa (soluções mais envolvidas da parte do provedor custam mais)
- Exemplo do laboratório: criação de máquinas virtuais
  Dentro da criação das máquinas virtuais, pode-se ver como cada escolha lev ao cliente mais para um dos modelos de serviço. O cliente pode
  escolher configurar tudo, desde  aimagem do sistema operacional, hardware disponível, configurações de rede.
  Já quando cria-se um banco de dados, toda essa construção do lado do servidor fica obscurecido para o cliente, e ele foca em definir o
  banco de dados que ele quer e não onde esse banco vai rodar
  
