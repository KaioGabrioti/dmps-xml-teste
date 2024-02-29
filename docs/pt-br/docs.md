Preencha corretamente este template para que os usuários consigam utilizar o seu conteúdo. As informações serão expostas na página do Plugin no Portal da StackSpot.

## DMPS-XML-TESTE

Escreva uma descrição clara e breve do conteúdo Plugin. 

Exemplo:
> Este Plugin contém instruções de como preencher as informações para usar os Plugins na plataforma StackSpot.

## Pré-requisitos

- Descreva em uma lista todos os itens e ações necessárias antes de aplicar Plugin.

Tags XML básicas de um Job:
1. <diagram-state>: tag que se refere ao posicionamento dos elementos de jobs-steps na interface FICO do DMPS.
2. <job-specification-version>: tag que se refere a configurações de versioes e organização do job na interface FICO do DMPS.
3. <name>: tag que se refere ao nome do job na interface FICO do DMPS.
4. <description>: tag que se refere a descricao do job na interface FICO do DMPS.
5. <job-params>: tag que se refere as configurações de infraestrutura do job na interface FICO do DMPS, os <parameters> possuem sempre <name> e <value> correspondente a sua construção na interface FICO do DMPS.
6. <tags>: tag que se refere as tags que ajudam na identificacao e classificacao do job pelo campo de busca da interface FICO do DMPS.
7. <job-steps>: tag que se refere os job steps que possuem na interface FICO do DMPS desse job com suas configurações de acordo com o tipo de job step.

Tags XML básicas de um Job Step:
1. <description>: tag que se refere a descricao do job step na interface FICO do DMPS.
2. <job-step-id>: tag que se refere ao identificador unico do job step na interface FICO do DMPS.
3. <job-step-version>: tag que se refere a versão do job step na interface FICO do DMPS.
4.  <configuration>: tag que se refere a configuração do job step na interface FICO do DMPS.
5. <job-step-links>: tag que se refere as configurações de streams do job step, tanto seus streams de entrada quanto de saida utilizado de um job step para o outro.
6. <step-type>: tag que se refere ao tipo de job step podendo ser INBOUND, TRANSFORMATION e OUTBOUND
7. <tuple-processing-type>: tag que se refere ao tipo de processamento de tuple deste job step podendo ser ...
8. <job-step-builder-class>: tag que se refere ao tipo de classe do job step
9. <schedulable>: tag que se refere ao ...
10. <requires-data-source>: tag que se refere ao uso de data source no job step

## Uso

Descreva as etapas para o usuário utilizar este Plugin:

1. Quais as entradas
2. Quais os métodos usar
3. Quais os recursos
4. E se necessário, adicione as dependências do seu Plugin.

Exemplo: 
Na pasta do seu aplicativo, aplique o **plugin-doc-template** para preencher os arquivos abaixo:

1. Execute o comando:
`
stk apply plugin /Users/Home/plugin-doc-template
`

2. Preencha as informações do Plugin seguindo os exemplos de modelo de arquivo x;

## Release Notes

Esta seção só é necessária se você publicar uma nova versão do Plugin. Apenas adicione o que foi modificado ou adicionado.

Exemplo:
### plugin-doc-template v1.0.0

#### Features
Novos templates foram adicionados.
