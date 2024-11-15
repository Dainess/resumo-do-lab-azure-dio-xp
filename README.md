# Resumos dos Labs de Azure Bootcamp DIO XP

## Localizando Serviços por Categoria

O lab nos deu um overview em geral de: 

- como criar uma conta na Azure
  
- Uma explicação do que é a computação em nuvem (cloud) em termos gerais e que problema ela vem a resolver
  Principalmente uma questão de localização geográfica, escalabilidade e menores custos de entrada
  
- ensinou a diferença entre CapEx e OpEx
  - CapEx são as despesas de capital e vão incorrer principalmente quando você for instalar coisas privadas, on-premise, por conta própria.
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
  Você pode confiar que o sistema vai ficar de pé e é resiliente a falhas
  Você pode prever o quanto custa, qual o desempenho que você vai ter, que você vai ter um suporte disponível
  Segurança digital é uma questão muito midiática, é o que mantém seus dados seguyros, que mantém hackers longe de você
  Lembrando que o provedor cloud é responsável por prover as ferramentas, e o contratante é o responsável por implementá-las
- Governança e gerenciamento
  Governança é sobre implementação de modelos de regras para controle de informação e práticas, seja por uma decisão de gestão da empresa, seja por compliance
  Já gerenciabilidade é sobre a facilidade para implementar a decisão sobre a aolocação de recursos
  Você vai ter a opção de fazer tanto o gerenciamento via portal quanto via código no Azure
- Laboratório
  Mostrou pra gente onde vê o tempo de inatividade aceitável
  Opções de disponibilidade
