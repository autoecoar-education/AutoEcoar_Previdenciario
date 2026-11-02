# Documentação e Evidências — Aposentadoria da Pessoa com Deficiência

**Módulo:** Aposentadoria PCD
**Versão:** 0.1
**Status:** Minuta técnica — pendente de validação jurídica
**Documento:** 07 de 08

---

## 1. Finalidade

Estabelecer critérios para identificar, classificar, registrar e avaliar documentos relevantes à análise da aposentadoria da pessoa com deficiência.

## 2. Princípios de análise

- Rastreabilidade da origem documental;
- Integridade e preservação do conteúdo;
- Identificação de datas e períodos;
- Distinção entre fato, declaração e inferência;
- Análise conjunta das evidências;
- Registro de divergências;
- Revisão humana.

## 3. Categorias documentais

Organizar os documentos nas seguintes categorias:

1. Identificação e dados cadastrais;
2. Histórico previdenciário e contributivo;
3. Documentação médica;
4. Documentação terapêutica;
5. Documentação educacional;
6. Documentação profissional;
7. Documentação social e funcional;
8. Registros administrativos do INSS;
9. Avaliações biopsicossociais;
10. Outros documentos relevantes.

## 4. Documentos previdenciários

Verificar, conforme o caso:

- CNIS;
- CTPS física ou digital;
- Guias de recolhimento;
- Carnês e comprovantes;
- CTC;
- PPP e documentos de atividade especial;
- Processos administrativos anteriores;
- Cartas de concessão e indeferimento;
- Decisões judiciais pertinentes.

## 5. Evidências da deficiência

Podem ser relevantes, conforme o período e a finalidade:

- Laudos e relatórios médicos;
- Exames;
- Relatórios terapêuticos;
- Registros escolares;
- Avaliações funcionais;
- Registros de adaptações;
- Histórico de apoios recebidos;
- Descrição de barreiras enfrentadas;
- Documentação profissional e social.

Nenhum documento isolado deverá determinar automaticamente o grau da deficiência.

## 6. Registro padronizado

Para cada documento, registrar:

| Campo | Descrição |
|---|---|
| ID | Identificador interno |
| Tipo | Categoria documental |
| Emissor | Origem |
| Data | Emissão |
| Período relacionado | Intervalo a que se refere |
| Conteúdo relevante | Síntese objetiva |
| Fonte | Arquivo ou referência |
| Limitações | Ausências ou restrições |
| Integridade do arquivo | Não verificada, conferida, questionada ou incompleta |
| Autenticidade/origem | Não verificada, confirmada por fonte apropriada, questionada ou indeterminada |
| Relevância para o fato | Direta, indireta, contextual, inexistente ou indeterminada |
| Abrangência temporal | Período efetivamente sustentado pelo documento |
| Localização da evidência | Página, seção, item ou parágrafo |
| Versão/hash | Versão do arquivo e SHA-256, quando pertinente |
| Situação da análise | Pendente, analisado ou questionado |

### 6.1. Integridade e autenticidade documental

A análise deverá distinguir a integridade ou autenticidade do documento da relevância e da força de seu conteúdo para comprovar determinado fato.

Um documento formalmente íntegro não comprova automaticamente:
- a veracidade material de todas as declarações nele contidas;
- a ocorrência de um fato em período diferente daquele expressamente abrangido;
- a existência de deficiência, seu grau ou sua data de início;
- a permanência de determinada condição ao longo de todo o histórico.

Sempre que pertinente, registrar:
- origem e forma de obtenção;
- emissor e identificação profissional ou institucional, quando aplicável;
- assinatura, certificação ou mecanismo de validação disponível;
- integridade do arquivo e existência de páginas ausentes;
- versão do documento;
- localização precisa do conteúdo utilizado: página, seção, item ou parágrafo;
- hash SHA-256 do arquivo, quando necessário para controle de integridade.

O hash permite verificar se o arquivo foi alterado; não comprova a veracidade do conteúdo nem, isoladamente, a autenticidade de sua origem.

A IA não deverá declarar autenticidade documental sem procedimento de verificação apropriado. Utilizar estados como: não verificado, verificação realizada, questionado ou incompleto.

### 6.2. Relevância e qualidade da evidência

A avaliação deverá ser qualitativa e vinculada ao fato que se pretende demonstrar. Considerar, conforme o caso:

- **Proveniência:** origem identificável e confiável do documento.
- **Contemporaneidade:** proximidade temporal entre o registro e o fato.
- **Diretividade:** se o documento registra diretamente o fato ou apenas apresenta informação indireta ou contextual.
- **Consistência:** compatibilidade com outras evidências, inclusive independentes.
- **Abrangência temporal:** período efetivamente alcançado pelo registro.
- **Contexto:** finalidade, circunstâncias e condições em que foi produzido.
- **Limitações:** lacunas, ambiguidades, ressalvas e informações não avaliadas.

Registrar a relevância para o fato como direta, indireta, contextual, inexistente ou indeterminada, conforme o caso.

Esses critérios não constituem pontuação automática, escala legal de confiabilidade ou presunção de verdade. A análise não poderá substituir a avaliação humana nem resolver divergências por decisão autônoma da IA.

### 6.3. Matriz de evidências por fato e período

Além do cadastro individual dos documentos, manter uma matriz que relacione cada fato relevante ao respectivo intervalo temporal.

| Fato ou questão | Período | Evidências favoráveis | Evidências contrárias | Evidências neutras/contextuais | Lacunas | Avaliação ou pendência | Responsável pela revisão |
|---|---|---|---|---|---|---|---|

A matriz deverá:
- identificar os documentos por seus IDs de cadastro;
- registrar evidências favoráveis e contrárias, sem omitir elementos desfavoráveis ao requerimento;
- distinguir ausência de prova de prova da inexistência do fato;
- indicar quando um documento não alcança todo o período analisado;
- manter divergências não solucionadas como pendências;
- permitir rastrear cada conclusão até o documento e o trecho correspondente.

A IA poderá organizar e apontar relações, contradições e lacunas. Não poderá escolher arbitrariamente entre evidências conflitantes nem transformar hipóteses em fatos comprovados.

## 7. Análise temporal

Distinguir:
- Data de emissão;
- Data do fato descrito;
- Período abrangido;
- Data de início informada;
- Data de eventual alteração da condição.

Documento recente não comprova automaticamente situação idêntica em períodos anteriores.

## 8. Divergências e contradições

Quando documentos apresentarem informações divergentes:

1. Identificar os documentos envolvidos;
2. Registrar precisamente a divergência;
3. Verificar datas e contextos;
4. Avaliar se há explicação documental;
5. Indicar o impacto na análise;
6. Encaminhar para revisão humana.

Não eliminar evidência desfavorável nem selecionar apenas documentos favoráveis.

## 9. Lacunas documentais

O relatório deverá apontar:
- Períodos sem documentação;
- Documentos mencionados, mas não apresentados;
- Informações incompletas;
- Necessidade de esclarecimentos;
- Possíveis fontes legítimas de complementação.

Não preencher lacunas com suposições.

## 10. Relação entre evidência e conclusão

Toda conclusão relevante deverá indicar os documentos que a sustentam.

Separar expressamente:
- Fato documentado;
- Declaração do interessado;
- Informação de terceiro;
- Inferência técnica;
- Hipótese ainda não comprovada;
- Questão pendente de avaliação.

## 11. Proteção e segurança

Observar a LGPD e os princípios de necessidade, finalidade, adequação e segurança.

Não utilizar documentos pessoais reais em exemplos, testes ou commits do repositório.

Arquivos médicos, documentos de identificação e dados previdenciários devem permanecer em ambiente protegido e separado do código-fonte.

## 12. Lista de verificação

- [ ] Documentos identificados e classificados;
- [ ] Datas e períodos registrados;
- [ ] Origem documental identificada;
- [ ] Duplicidades verificadas;
- [ ] Divergências registradas;
- [ ] Lacunas apontadas;
- [ ] Relação com as conclusões documentada;
- [ ] Dados pessoais protegidos;
- [ ] Revisão humana realizada.

## 13. Limites da IA

A IA poderá organizar, resumir e comparar documentos, apontando inconsistências.

Não poderá autenticar documentos, inventar conteúdo, presumir fatos ausentes ou substituir avaliação profissional e administrativa.

## 14. Histórico de versões

- v0.1 — Criação da minuta de documentação e evidências. Pendente de validação jurídica e operacional.
- v0.2 — Inclusão de controles de integridade e autenticidade documental, relevância qualitativa, localização das evidências, controle de versão e matriz por fato e período. Pendente de validação jurídica e operacional.
