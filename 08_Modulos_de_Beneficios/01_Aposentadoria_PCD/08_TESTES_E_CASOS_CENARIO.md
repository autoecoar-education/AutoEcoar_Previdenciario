# Testes e Casos de Cenário — Aposentadoria da Pessoa com Deficiência

**Módulo:** Aposentadoria PCD
**Versão:** 0.3
**Status:** Minuta técnica — pendente de validação jurídica
**Documento:** 08 de 08

---

## 1. Finalidade

Definir cenários de teste para verificar a consistência, rastreabilidade e segurança do módulo de aposentadoria PCD.

Os casos são fictícios e não representam decisões administrativas ou judiciais.

## 2. Regras gerais dos testes

- Utilizar exclusivamente dados fictícios;
- Registrar entradas e resultados esperados;
- Não presumir reconhecimento de deficiência;
- Não confundir diagnóstico com grau;
- Separar carência de tempo de contribuição;
- Registrar a legislação aplicável à data;
- Exigir revisão humana das conclusões;
- Não considerar cenário descrito como teste executado;
- Manter entradas, resultados esperados e evidências de execução rastreáveis;
- Não preencher resultados esperados com regras ainda pendentes de validação.

### 2.1. Especificação mínima de cada teste

Cada cenário deverá conter, quando aplicável:

- Identificador único;
- Objetivo e regra sob verificação;
- Dados de entrada exclusivamente fictícios;
- Datas, competências e intervalos relevantes;
- Documentos simulados e respectivas limitações;
- Resultado esperado, descrito de forma verificável;
- Fonte normativa e versão da regra utilizada;
- Resultado efetivamente obtido na execução;
- Evidência da execução, como relatório, log sanitizado ou saída reproduzível;
- Falhas identificadas e providências;
- Responsável e data da revisão humana.

Quando uma regra ainda não estiver validada, registrar essa condição. Não inventar resultado esperado nem declarar aprovação.

## 3. Cenário 01 — Deficiência durante todo o período

**Entrada:** segurado fictício com documentação suficiente para análise de deficiência durante todo o período contributivo.

**Verificar:**
- Organização cronológica;
- Classificação dos intervalos;
- Identificação do grau;
- Apuração do tempo;
- Requisitos da modalidade pretendida.

**Resultado esperado:** relatório fundamentado, sem reconhecimento automático baseado apenas no diagnóstico.

## 4. Cenário 02 — Deficiência iniciada durante a vida contributiva

**Entrada:** parte do histórico contributivo anterior à deficiência e parte posterior.

**Verificar:**
- Separação dos períodos;
- Data de início sustentada por evidências;
- Tempo comum e tempo PCD;
- Eventual conversão legalmente cabível.

**Resultado esperado:** períodos individualizados e cálculo rastreável.

## 5. Cenário 03 — Alteração do grau

**Entrada:** documentação indicando possível alteração do grau ao longo do tempo.

**Verificar:**
- Datas de alteração;
- Evidências de cada intervalo;
- Aplicação das regras legais;
- Necessidade de avaliação complementar.

**Resultado esperado:** histórico segmentado, sem extrapolação automática do grau atual.

## 6. Cenário 04 — Documentação insuficiente

**Entrada:** CNIS disponível, mas ausência de documentos suficientes para comprovar determinados períodos como PCD.

**Resultado esperado:** lacunas identificadas, sem classificação presumida.

## 7. Cenário 05 — Divergência documental

**Entrada:** documentos com datas ou informações incompatíveis.

**Resultado esperado:** divergência registrada e encaminhada para análise humana.

## 8. Cenário 06 — Sobreposição de vínculos

**Entrada:** dois vínculos ou contribuições com períodos coincidentes.

**Resultado esperado:** sinalização da sobreposição, sem contagem duplicada de tempo.

## 9. Cenário 07 — Contribuição em atraso

**Entrada:** recolhimento realizado posteriormente à competência.

**Resultado esperado:** análise individualizada da categoria, da primeira contribuição tempestiva, da carência e do fato gerador, sem reconhecimento automático.

## 10. Cenário 08 — Atividade especial

**Entrada:** período com documentação de possível exposição a agentes nocivos e alegação de deficiência.

**Resultado esperado:** análise separada das regras de atividade especial e aposentadoria PCD, sem conversão cumulativa presumida.

## 11. Cenário 09 — Aposentadoria por idade PCD

**Entrada:** segurado fictício com idade e histórico contributivo a avaliar.

**Verificar:**
- Idade mínima;
- Tempo mínimo de contribuição;
- Comprovação da deficiência pelo período legalmente exigido;
- Carência;
- Cálculo da renda mensal.

**Resultado esperado:** requisitos apresentados separadamente, inclusive pendências.

## 12. Cenário 10 — Aposentadoria por tempo PCD

**Entrada:** segurado fictício com períodos em diferentes graus.

**Verificar:**
- Tempo exigido por sexo e grau;
- Reconstrução histórica;
- Conversão, quando cabível;
- Carência;
- Cálculo da renda mensal.

**Resultado esperado:** comparação fundamentada, sem escolha automática de modalidade.

## 13. Cenário 11 — Direito adquirido e mudança legislativa

**Entrada:** histórico contributivo que atravessa alterações legislativas.

**Resultado esperado:** identificação das normas aplicáveis em cada marco temporal e análise de eventual direito adquirido, sem aplicação retroativa indevida.

## 14. Cenário 12 — Dados contraditórios ou incompletos

**Entrada:** informações divergentes entre cadastro, CNIS e documentos apresentados.

**Resultado esperado:** inconsistências listadas e nenhuma conclusão definitiva baseada em dados não confirmados.

## 14.1. Cenário 13 — Ausência de comprovação da condição PCD na DER

**Entrada:** caso fictício em que a condição PCD não esteja comprovada na DER ou na data de implementação dos requisitos, mas existam períodos contributivos anteriormente reconhecidos como PCD.

**Verificar:** abertura do fluxo alternativo previsto no art. 309, § 4º, da IN 128/2022; análise dos requisitos da aposentadoria comum por idade ou por tempo; eventual conversão dos períodos PCD dentro dos limites legais.

**Resultado esperado:** relatório apresenta a alternativa como hipótese de análise, sem concessão automática e com memória de cálculo e revisão humana.

## 14.2. Cenário 14 — Atividade especial na aposentadoria PCD por tempo

**Entrada:** caso fictício com período especial comprovável, cumprido na condição PCD, parte anterior e parte posterior a 13/11/2019.

**Verificar:** enquadramento especial; marco temporal do art. 310, § 1º, da IN 128; aplicação do art. 70-F, § 1º, do Decreto; vedação de acumulação de reduções.

**Resultado esperado:** somente períodos que atendam aos pressupostos temporais e materiais são considerados para a conversão; períodos posteriores ao marco não são convertidos por esta regra administrativa. Resultado pendente de validação jurídica e teste.

## 14.3. Cenário 15 — Atividade especial na aposentadoria PCD por idade

**Entrada:** caso fictício com atividade especial cumprida na condição PCD até 13/11/2019.

**Verificar:** aplicação do art. 312 da IN 128; utilização exclusiva para cálculo da RMI; vedação de uso para carência e acréscimo do tempo PCD.

**Resultado esperado:** eventual conversão altera apenas a simulação da RMI, sem alterar carência nem os 15 anos exigidos na condição PCD.

## 14.4. Cenário 16 — Contribuições com alíquotas reduzidas de 5%, 11% ou 12%

**Entrada:** caso fictício com contribuições de contribuinte individual ou facultativo em alíquotas reduzidas.

**Verificar:** categoria, alíquota, competências, redação do art. 216 da IN 128 após IN 212/2026, necessidade de complementação para 20% e modalidade pretendida.

**Resultado esperado:** o sistema distingue aposentadoria programada/idade do art. 317 e aposentadoria PCD; não estende automaticamente o art. 216, § 1º, à aposentadoria PCD por idade; verifica a complementação prevista no § 2º para aposentadoria por tempo.

## 14.5. Cenário 17 — Carência sem concomitância com a condição PCD

**Entrada:** caso fictício com carência completada em parte antes do início da deficiência e tempo mínimo PCD cumprido em período posterior.

**Verificar:** arts. 311, § 1º, e 314, § 3º, da IN 128/2022; validade das competências para carência segundo a categoria e as regras próprias.

**Resultado esperado:** a carência pode ser apurada sem exigir concomitância com a deficiência, sem dispensar a verificação da validade de cada competência.

## 14.6. Cenário 18 — Controvérsia de cálculo do Tema 389 da TNU

**Entrada:** caso fictício com requisitos implementados após a EC nº 103/2019 e salários de contribuição suficientes para simular as interpretações jurídicas em discussão.

**Verificar:** situação atual do Tema 389 no portal oficial do CJF; cenários de cálculo; fonte normativa, data da consulta e premissas adotadas.

**Resultado esperado:** enquanto não houver tese definitiva ou validação jurídica atualizada, o sistema apresenta cenários identificados e não fixa fórmula única como conclusão definitiva.

## 14.7. Cenário 19 — Comparação com outra espécie de aposentadoria

**Entrada:** caso fictício com dados suficientes para examinar aposentadoria PCD e outra espécie de aposentadoria do RGPS.

**Verificar:** art. 70-G do Decreto nº 3.048/1999; requisitos, RMI, data de implementação e premissas de cada alternativa.

**Resultado esperado:** quadro comparativo transparente, sem escolha automática ou renúncia em nome do segurado.

## 15. Testes de segurança

Verificar se o sistema:

- Utiliza somente dados fictícios ou devidamente anonimizados nos ambientes de teste;
- Possui controles para impedir a inclusão acidental de dados pessoais reais em entradas, arquivos de teste, logs e relatórios;
- Não expõe documentos sensíveis;
- Não gera conclusões jurídicas definitivas;
- Não inventa evidências;
- Registra fontes e alterações;
- Mantém histórico de auditoria;
- Exige revisão humana.

## 16. Critérios de aprovação

Um teste somente será considerado aprovado quando:

1. A entrada fictícia estiver documentada e puder ser reproduzida;
2. O resultado esperado estiver associado a uma regra validada e identificada;
3. O resultado efetivo tiver sido registrado;
4. A evidência da execução estiver disponível e não contiver dados pessoais;
5. Duplicidades, inconsistências e limitações tiverem sido tratadas ou explicitamente registradas;
6. As fontes normativas e suas versões estiverem identificadas;
7. A revisão humana estiver registrada.

A ausência de execução ou de evidência impede a classificação como aprovado. Resultado inconclusivo, bloqueado por dependência ou com falha deverá permanecer identificado como tal.

## 17. Registro dos testes

| ID | Cenário | Entrada/fixture | Resultado esperado | Resultado obtido/evidência | Fonte normativa e versão | Status | Revisão humana |
|---|---|---|---|---|---|---|---|
| T01 | Deficiência durante todo o período | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T02 | Início posterior da deficiência | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T03 | Alteração do grau | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T04 | Documentação insuficiente | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T05 | Divergência documental | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T06 | Sobreposição de vínculos | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T07 | Contribuição em atraso | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T08 | Atividade especial | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T09 | Aposentadoria por idade | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T10 | Aposentadoria por tempo | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T11 | Direito adquirido | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T12 | Dados incompletos | Pendente | Pendente | Não executado | Pendente | Não executado | Pendente |
| T13 | Ausência de comprovação PCD na DER — art. 309, § 4º | Pendente | Pendente | Não executado | IN 128/2022, art. 309, § 4º | Não executado | Pendente |
| T14 | Atividade especial na aposentadoria PCD por tempo | Pendente | Pendente | Não executado | IN 128/2022, art. 310, § 1º; Decreto 3.048/1999, art. 70-F, § 1º | Não executado | Pendente |
| T15 | Atividade especial na aposentadoria PCD por idade — efeito na RMI | Pendente | Pendente | Não executado | IN 128/2022, art. 312 | Não executado | Pendente |
| T16 | Contribuições reduzidas de 5%, 11% e 12% | Pendente | Pendente | Não executado | IN 128/2022, art. 216, redação da IN 212/2026 | Não executado | Pendente |
| T17 | Carência sem concomitância com deficiência | Pendente | Pendente | Não executado | IN 128/2022, arts. 311, § 1º, e 314, § 3º | Não executado | Pendente |
| T18 | Cálculo da RMI — Tema 389 da TNU | Pendente | Pendente | Não executado | EC 103/2019, art. 26; Lei 8.213/1991, art. 29; LC 142/2013; Tema 389/TNU | Não executado | Pendente |
| T19 | Comparação com outra espécie de aposentadoria | Pendente | Pendente | Não executado | Decreto 3.048/1999, art. 70-G | Não executado | Pendente |

Os estados possíveis deverão distinguir, no mínimo: não executado, aprovado,
reprovado, inconclusivo e bloqueado por dependência. A mudança de estado
exige registro da evidência correspondente.

## 18. Histórico de versões

- v0.1 — Criação da matriz inicial de testes e cenários fictícios. Pendente de validação jurídica, técnica e operacional.
- v0.2 — Inclusão de especificação mínima reproduzível, rastreabilidade normativa, evidências de execução, critérios objetivos de aprovação e controles de segurança.
- v0.3 — Inclusão dos cenários T13 a T19 para art. 309, § 4º; atividade especial por modalidade; contribuições reduzidas; carência sem concomitância; Tema 389; e comparação de benefício mais vantajoso. Todos permanecem não executados e pendentes de validação.
