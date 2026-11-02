# Cálculo da Renda Mensal — Aposentadoria da Pessoa com Deficiência

**Módulo:** Aposentadoria PCD
**Versão:** 0.2
**Status:** Minuta técnica — pendente de validação jurídica e operacional
**Documento:** 05 de 08

---

## 1. Finalidade

Definir os procedimentos para apuração preliminar do salário de benefício e da renda mensal inicial (RMI) nas modalidades de aposentadoria da pessoa com deficiência previstas na Lei Complementar nº 142/2013.

O cálculo deverá ser transparente, reproduzível e acompanhado de memória detalhada.

O sistema deverá distinguir:

- Salários de contribuição;
- Período básico de cálculo;
- Média contributiva;
- Salário de benefício;
- Coeficiente legal;
- Fator previdenciário, quando aplicável;
- Renda mensal inicial;
- Limites mínimo e máximo do benefício;
- Reajustes posteriores à concessão.

## 2. Fundamentos normativos

A análise deverá considerar, conforme a data e a situação concreta:

- Lei Complementar nº 142/2013, especialmente art. 8º;
- Lei nº 8.213/1991;
- Decreto nº 3.048/1999, especialmente arts. 32, 35, 36 e 70-J;
- Emenda Constitucional nº 103/2019, especialmente arts. 22 e 26;
- Instrução Normativa PRES/INSS nº 128/2022, em sua redação vigente;
- Normas complementares aplicáveis ao cálculo previdenciário.

A legislação deverá ser conferida na redação vigente na data de referência do cálculo. O sistema deverá registrar a fonte normativa, a versão consultada e a data da conferência.

## 3. Modalidades abrangidas

O documento contempla:

1. Aposentadoria da pessoa com deficiência por tempo de contribuição;
2. Aposentadoria da pessoa com deficiência por idade.

Os cálculos deverão ser realizados separadamente. O sistema poderá comparar os resultados quando o segurado preencher os requisitos de mais de uma modalidade.

## 4. Conceitos fundamentais

### 4.1. Salário de contribuição

É a base contributiva utilizada para apuração previdenciária em cada competência, observados os limites, regras e atualizações legais aplicáveis.

### 4.2. Período básico de cálculo

É o intervalo de competências cujos salários de contribuição serão considerados na apuração do salário de benefício, conforme a legislação aplicável à data de referência.

### 4.3. Salário de benefício

É a base de cálculo sobre a qual incidem os percentuais legais da modalidade de aposentadoria.

### 4.4. Renda mensal inicial

É o valor inicial do benefício, calculado a partir do salário de benefício e dos coeficientes legais, com aplicação dos limites previdenciários pertinentes.

**O percentual aplicado ao salário de benefício não significa pagamento equivalente ao último salário, à última remuneração ou à totalidade dos salários de contribuição.**

## 5. Organização dos salários de contribuição

O sistema deverá:

- Reunir as remunerações e contribuições por competência;
- Identificar a origem de cada informação;
- Atualizar monetariamente os salários conforme os índices oficiais aplicáveis;
- Identificar competências sem remuneração;
- Examinar indicadores e pendências;
- Verificar limites mínimo e máximo;
- Registrar contribuições concomitantes;
- Identificar valores sujeitos a complementação ou validação;
- Preservar os valores originais e os valores atualizados.

Nenhuma remuneração poderá ser criada, estimada ou substituída sem fundamento documental e normativo.

## 6. Apuração do salário de benefício

O salário de benefício deverá ser apurado conforme a legislação aplicável ao período e à data em que os requisitos foram implementados.

**Controvérsia do Tema 389 da TNU:** a questão submetida a julgamento é se o art. 26 da EC nº 103/2019 revogou o critério do art. 29 da Lei nº 8.213/1991 para a aposentadoria PCD prevista na LC nº 142/2013. Na consulta ao portal oficial do CJF realizada para esta revisão, o Tema 389 permanecia com situação "Em Julgamento", sem tese firmada. A existência de votos ou maioria parcial noticiada não equivale a tese definitiva.

Por isso, o módulo não deverá fixar automaticamente a média de 100% dos salários como regra definitiva para todos os casos posteriores à EC nº 103/2019, nem aplicar automaticamente a média dos 80% maiores salários. Deverá manter parametrizações alternativas, identificar a regra e a data de referência de cada cenário, registrar a fonte e bloquear conclusão jurídica definitiva até a publicação de tese ou validação profissional atualizada.

O sistema deverá verificar:

1. Quais competências integram o período básico de cálculo;
2. Quais salários de contribuição são válidos;
3. Quais índices de atualização devem ser aplicados;
4. Se há competências que exigem tratamento específico;
5. Se existem hipóteses legais de exclusão;
6. Se a exclusão pretendida é juridicamente admitida para a modalidade analisada;
7. Se a exclusão prejudica o cumprimento do tempo mínimo exigido.

A regra geral de cálculo não deverá ser aplicada automaticamente sem verificar sua compatibilidade com a legislação específica da aposentadoria PCD e com o direito adquirido.

## 7. Aposentadoria PCD por tempo de contribuição

Nos termos do art. 8º da LC nº 142/2013 e do art. 70-J, inciso I, do Decreto nº 3.048/1999, a renda mensal corresponde a:

**100% do salário de benefício.**

O sistema deverá:

- Apurar o salário de benefício;
- Aplicar o coeficiente de 100%;
- Calcular o fator previdenciário, quando cabível;
- Comparar o resultado com e sem fator;
- Adotar o fator somente se resultar em renda mensal mais elevada;
- Registrar a memória de cálculo das duas hipóteses.

O tempo utilizado para verificar o direito à aposentadoria não deverá ser confundido com o período utilizado para calcular a média contributiva.

## 8. Aposentadoria PCD por idade

Nos termos do art. 8º da LC nº 142/2013 e do art. 70-J, inciso II, do Decreto nº 3.048/1999, a renda mensal corresponde a:

**70% do salário de benefício, acrescidos de 1 ponto percentual por grupo de 12 contribuições mensais, até o limite de 100%.**

O sistema deverá:

- Apurar o salário de benefício;
- Identificar a quantidade de grupos completos de 12 contribuições mensais;
- Calcular o coeficiente;
- Limitar o coeficiente ao máximo de 100%;
- Calcular o fator previdenciário, quando cabível;
- Comparar os resultados com e sem fator;
- Aplicar o fator somente se mais vantajoso.

A quantidade de contribuições utilizada para o coeficiente deverá ser identificada e fundamentada conforme a regra legal aplicável. Não deverá ser confundida automaticamente com o tempo mínimo de 15 anos na condição de pessoa com deficiência ou com a carência.

## 9. Fator previdenciário

A LC nº 142/2013 assegura a aplicação do fator previdenciário quando resultar em renda mensal de valor mais elevado.

O sistema deverá calcular, quando aplicável:

1. Renda sem fator previdenciário;
2. Renda com fator previdenciário;
3. Diferença entre os resultados;
4. Resultado mais vantajoso;
5. Dados utilizados no cálculo;
6. Tábua de mortalidade e referência temporal aplicáveis.

A comparação deverá ser demonstrada na memória de cálculo.

O fator não poderá ser aplicado automaticamente quando reduzir a renda mensal.

## 10. Direito adquirido e regras temporais

O sistema deverá identificar a data em que cada requisito foi preenchido e verificar:

- Direito adquirido antes da EC nº 103/2019;
- Regras aplicáveis na data de implementação dos requisitos;
- Regras posteriores à Reforma;
- Data de entrada do requerimento (DER);
- Eventual reafirmação da DER;
- Alterações legislativas posteriores;
- Possibilidade de opção por modalidade mais vantajosa.

A data do requerimento não deverá ser utilizada isoladamente para definir a regra de cálculo quando houver possibilidade de direito adquirido anterior.

## 11. Exclusão de contribuições e competências

A possibilidade de excluir salários de contribuição que reduzam a média deverá ser examinada com cautela.

Antes de qualquer exclusão, o sistema deverá verificar:

- Existência de autorização legal aplicável à modalidade;
- Efeito sobre o tempo mínimo exigido;
- Efeito sobre a carência;
- Efeito sobre o coeficiente;
- Efeito sobre o fator previdenciário;
- Reflexo no valor final;
- Eventuais restrições à utilização do período excluído para outras finalidades.

O sistema não deverá excluir competências automaticamente apenas porque apresentam salários menores.

A compatibilidade das regras gerais de exclusão previstas na EC nº 103/2019 com cada modalidade da aposentadoria PCD deverá ser objeto de validação jurídica específica.

## 12. Limites do benefício

O resultado deverá observar os limites previdenciários aplicáveis, especialmente:

- Piso previdenciário;
- Teto do salário de contribuição e do benefício;
- Limites vigentes na data de início do benefício;
- Regras específicas para segurados especiais;
- Outras restrições legais aplicáveis.

O sistema deverá identificar os valores oficiais correspondentes à data de referência, sem utilizar limites de anos diferentes.

## 13. Comparação entre modalidades

Quando houver possibilidade de mais de uma modalidade, o sistema deverá apresentar quadro comparativo contendo:

| Elemento | Por tempo de contribuição | Por idade |
|---|---|---|
| Requisitos | Grau e tempo mínimo | Idade e tempo mínimo PCD |
| Carência | Apuração própria | Apuração própria |
| Coeficiente | 100% do salário de benefício | 70% + 1% por grupo de 12 contribuições, até 100% |
| Fator previdenciário | Somente se mais vantajoso | Somente se mais vantajoso |
| RMI | Resultado calculado | Resultado calculado |

A comparação deverá considerar as datas de implementação dos requisitos e a legislação aplicável a cada hipótese.

O sistema não deverá recomendar modalidade exclusivamente pelo maior valor estimado sem examinar os requisitos, a segurança documental e os efeitos jurídicos de cada opção.

## 14. Memória de cálculo obrigatória

Cada simulação deverá apresentar:

- Identificação anonimizada do caso;
- Data de referência;
- Modalidade examinada;
- Regra jurídica utilizada;
- Competências consideradas;
- Salários originais;
- Índices de atualização;
- Salários atualizados;
- Média apurada;
- Salário de benefício;
- Coeficiente aplicado;
- Fator previdenciário, se utilizado;
- Comparação com e sem fator;
- Limites aplicados;
- Renda mensal inicial estimada;
- Pendências e ressalvas;
- Fontes normativas;
- Responsável pela revisão.

Os cálculos deverão permitir reprodução por outro profissional.

## 15. Simulações e cenários

Quando houver incerteza documental ou jurídica, o sistema poderá apresentar cenários alternativos, desde que:

- Cada cenário tenha premissas expressas;
- Os períodos controvertidos sejam identificados;
- Não sejam apresentados dados hipotéticos como fatos comprovados;
- Os resultados sejam classificados como estimativas;
- A diferença entre cenários seja explicada;
- A validação profissional permaneça obrigatória.

## 16. Uso de inteligência artificial

A inteligência artificial poderá:

- Organizar salários de contribuição;
- Identificar lacunas e inconsistências;
- Executar cálculos aritméticos com dados validados;
- Comparar cenários;
- Preparar memória de cálculo;
- Apontar regras que exigem validação.

Não poderá:

- Inventar salários ou competências;
- Corrigir dados sem justificativa;
- Escolher regra jurídica sem registrar fundamento;
- Excluir contribuições automaticamente;
- Garantir valor ou concessão do benefício;
- Substituir a revisão profissional.

Toda operação deverá ser rastreável e reproduzível.

## 17. Proteção de dados e segurança

A documentação previdenciária deverá ser tratada conforme a LGPD.

O repositório de desenvolvimento utilizará exclusivamente dados fictícios ou devidamente anonimizados. Não inserir CNIS identificável, CPF, documentos pessoais, dados médicos individualizados ou credenciais no GitHub.

## 18. Validações pendentes

Antes da utilização operacional, deverão ser validados:

1. Período básico de cálculo aplicável a cada marco temporal;
2. Regras de cálculo anteriores e posteriores à EC nº 103/2019;
3. Compatibilidade do art. 26 da EC nº 103/2019 com as modalidades da LC nº 142/2013;
4. Critérios para quantidade de contribuições utilizada no coeficiente da aposentadoria por idade PCD;
5. Aplicação do fator previdenciário e comparação entre resultados;
6. Exclusão de salários de contribuição e seus efeitos;
7. Tratamento de contribuições concomitantes;
8. Competências inferiores ao mínimo;
9. Limites mínimo e máximo na data de referência;
10. Regras específicas para segurado especial;
11. Reajustes e atualização da renda após a concessão;
12. Compatibilidade dos cálculos com os sistemas oficiais do INSS.

---

## Histórico de versões

| Versão | Alteração |
|---|---|
| 0.1 | Criação da minuta de cálculo da renda mensal. |
| 0.2 | Inclusão do controle explícito do Tema 389 da TNU e vedação de parametrização definitiva do salário de benefício enquanto não houver tese firmada ou validação jurídica atualizada. |
