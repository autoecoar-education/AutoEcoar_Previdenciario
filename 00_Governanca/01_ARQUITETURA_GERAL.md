# AUTOECOAR PREVIDENCIÁRIO
## Arquitetura Geral do Sistema

**Versão:** 1.0
**Status:** Proposta inicial de arquitetura

---

## 1. Visão geral

O AutoEcoar Previdenciário será organizado como um sistema modular de apoio à análise de casos previdenciários.

Sua arquitetura será dividida em três camadas:

1. Conhecimento e fundamentação.
2. Inteligência e análise especializada.
3. Controle, auditoria e validação.

Um componente não deverá substituir as responsabilidades dos demais.

## 2. Camada de conhecimento

Responsável por fornecer a base de referência utilizada nas análises.

### Componentes

- Legislação previdenciária;
- Regulamentos e normas administrativas;
- Jurisprudência;
- Doutrina e referências técnicas;
- Metodologia de análise;
- Critérios de interpretação;
- Modelos documentais.

### Regra

Toda informação jurídica relevante deverá ter fonte identificável, data de consulta e indicação de vigência ou período de aplicação.

## 3. Camada de inteligência

Responsável pela execução das tarefas especializadas.

### 3.1. Agente Coordenador

Função:
- Receber a demanda;
- Identificar a natureza do caso;
- Distribuir tarefas;
- Integrar resultados;
- Identificar divergências;
- Encaminhar o resultado para auditoria.

Não deverá criar fatos nem substituir a revisão humana.

### 3.2. Agente de Triagem

Função:
- Identificar a espécie de benefício ou questão previdenciária;
- Identificar os requisitos potencialmente aplicáveis;
- Relacionar documentos necessários;
- Identificar lacunas iniciais.

### 3.3. Agente Documental

Função:
- Catalogar documentos;
- Identificar datas e informações relevantes;
- Separar fatos comprovados de declarações;
- Apontar documentos ausentes, ilegíveis ou contraditórios.

### 3.4. Agente de Cronologia

Função:
- Organizar os acontecimentos;
- Construir a linha do tempo;
- Identificar períodos sobrepostos;
- Relacionar eventos pessoais, laborais, médicos e contributivos quando pertinentes.

### 3.5. Agente Previdenciário-Contributivo

Função:
- Examinar informações do CNIS;
- Organizar vínculos e contribuições;
- Identificar indicadores e pendências;
- Examinar carência, tempo de contribuição e demais requisitos aplicáveis;
- Apontar necessidade de acerto cadastral.

Cálculos deverão ser demonstráveis e passíveis de conferência.

### 3.6. Agente Jurídico

Função:
- Identificar normas aplicáveis;
- Pesquisar jurisprudência pertinente;
- Verificar requisitos legais;
- Identificar divergências interpretativas;
- Fundamentar cenários jurídicos possíveis.

Não deverá apresentar interpretação controvertida como entendimento pacífico.

### 3.7. Agente Especializado em Pessoa com Deficiência

Função:
- Examinar questões previdenciárias relacionadas à condição de pessoa com deficiência;
- Identificar requisitos específicos da legislação aplicável;
- Organizar informações sobre impedimentos de longo prazo e barreiras;
- Identificar elementos relevantes para avaliação biopsicossocial;
- Examinar os requisitos específicos de cada modalidade de benefício.

A existência de diagnóstico ou classificação clínica, isoladamente, não deverá ser tratada como prova automática de todos os requisitos previdenciários.

### 3.8. Agente de Auditoria

Função:
- Conferir consistência dos dados;
- Verificar cálculos e fundamentos;
- Identificar contradições;
- Apontar conclusões sem evidência suficiente;
- Verificar se as limitações foram respeitadas;
- Produzir relatório de auditoria.

## 4. Camada de controle

Responsável por garantir qualidade e rastreabilidade.

### Componentes

- Registro de fontes;
- Histórico de versões;
- Controle de documentos;
- Registro de premissas;
- Relatórios de pendências;
- Auditoria das análises;
- Revisão humana.

Nenhuma análise deverá ser considerada final apenas porque um agente concluiu sua tarefa.

## 5. Fluxo geral de funcionamento

1. Recebimento da demanda.
2. Identificação e classificação do caso.
3. Definição da hipótese previdenciária a investigar.
4. Levantamento documental.
5. Organização da cronologia.
6. Análise contributiva, quando aplicável.
7. Pesquisa jurídica.
8. Análise especializada.
9. Integração dos resultados.
10. Auditoria.
11. Revisão humana.
12. Emissão do relatório técnico de apoio.

O fluxo poderá ser adaptado conforme a natureza do benefício.

## 6. Tratamento de divergências

Quando agentes apresentarem conclusões diferentes:

- As divergências deverão ser registradas;
- As premissas de cada análise deverão ser identificadas;
- As fontes utilizadas deverão ser comparadas;
- Nenhuma divergência deverá ser ocultada;
- O ponto deverá ser encaminhado para revisão humana quando necessário.

## 7. Separação entre metodologia e processos

A metodologia será mantida independentemente dos casos individuais.

Os processos deverão utilizar identificadores pseudonimizados.

O conhecimento adquirido em um caso poderá contribuir para aperfeiçoar a metodologia, desde que não exponha informações pessoais ou confidenciais.

## 8. Modularidade

O sistema deverá permitir a inclusão futura de novos módulos, como:

- Aposentadoria por idade;
- Aposentadoria por tempo de contribuição, conforme regras aplicáveis;
- Aposentadoria da pessoa com deficiência;
- Benefícios por incapacidade;
- Pensão por morte;
- Benefícios assistenciais;
- Revisões e acertos previdenciários.

Cada módulo deverá ter requisitos, fluxos e critérios próprios.

## 9. Princípio de independência

Nenhum agente deverá controlar sozinho todas as etapas de um caso.

A produção de uma conclusão deverá permitir a conferência independente de seus dados, premissas, cálculos e fundamentos.

## 10. Evolução

Esta arquitetura é inicial e deverá ser revisada conforme os testes, resultados das análises e necessidades identificadas.

A implementação tecnológica deverá ocorrer somente depois da validação da metodologia e dos fluxos de trabalho.
