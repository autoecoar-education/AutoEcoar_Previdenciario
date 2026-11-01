# AUTOECOAR PREVIDENCIÁRIO
## Carta de Governança — Versão 1.0

**Projeto:** AutoEcoar Previdenciário<br>
**Repositório:** AutoEcoar_Previdenciario<br>
**Versão:** 1.0<br>
**Status:** Documento inicial<br>
**Responsável:** AutoEcoar

---

## 1. Finalidade

Desenvolver uma metodologia estruturada de organização, análise e acompanhamento de casos previdenciários, com apoio de inteligência artificial, pesquisa jurídica e revisão humana.

O sistema deverá promover análises consistentes, rastreáveis, fundamentadas e individualizadas.

## 2. Princípios fundamentais

1. Legalidade: toda análise deve observar a legislação aplicável.
2. Rastreabilidade: conclusões devem indicar suas fontes e fundamentos.
3. Transparência: fatos comprovados, relatos, hipóteses e lacunas devem ser diferenciados.
4. Individualização: cada segurado deve ter sua situação examinada de maneira própria.
5. Segurança: dados pessoais e documentos sensíveis devem ser protegidos.
6. Atualização: legislação, jurisprudência e entendimentos administrativos devem ser verificados quanto à vigência.
7. Revisão humana: nenhuma conclusão automatizada substitui a avaliação profissional.
8. Integridade: o sistema não deve fabricar fatos, documentos, provas ou fundamentos.

## 3. Limites de atuação

O AutoEcoar Previdenciário é um sistema de apoio à organização e análise.

Não substitui:
- Advogado ou profissional habilitado;
- Avaliação médica ou biopsicossocial;
- Perícia oficial;
- Decisão administrativa do INSS;
- Decisão judicial.

Nenhum resultado deve ser apresentado como garantia de concessão de benefício.

## 4. Organização dos dados

Os dados serão classificados em:

- Públicos: legislação, decisões públicas e materiais institucionais.
- Operacionais: metodologia, modelos, prompts e fluxos.
- Restritos: informações individualizadas de processos.
- Altamente sensíveis: documentos médicos, CPF, CNIS integral, documentos de identificação e outros dados pessoais protegidos.

O GitHub deverá armazenar somente documentação metodológica e dados de casos devidamente pseudonimizados.

Documentos originais e dados altamente sensíveis deverão permanecer em armazenamento externo protegido, com controle de acesso e criptografia.

## 5. Identificação dos processos

Cada caso deverá receber um identificador interno próprio.

Exemplo:

AUTO-PCD-0001

O identificador não deverá conter CPF, nome completo ou outra informação que permita identificar diretamente o segurado.

## 6. Regras para análise dos casos

Toda análise deverá:

1. Identificar a questão previdenciária.
2. Organizar a cronologia dos fatos.
3. Identificar documentos existentes e ausentes.
4. Separar fatos comprovados de informações declaradas.
5. Identificar períodos contributivos e demais requisitos aplicáveis.
6. Verificar a legislação vigente na data relevante.
7. Identificar divergências e lacunas.
8. Apresentar cenários juridicamente fundamentados.
9. Registrar riscos e pontos que exigem revisão.
10. Submeter conclusões relevantes à revisão humana.

## 7. Inteligência artificial e agentes

Os agentes deverão atuar com funções delimitadas.

Cada agente deverá possuir:
- Objetivo;
- Escopo;
- Entradas necessárias;
- Procedimentos;
- Fontes autorizadas;
- Critérios de validação;
- Limitações;
- Formato de saída.

Agentes não poderão inventar informações para preencher lacunas documentais.

## 8. Fundamentação jurídica

Toda fundamentação deverá identificar, quando aplicável:

- Norma e dispositivo;
- Redação vigente ou aplicável ao período;
- Data de referência;
- Fonte oficial;
- Jurisprudência pertinente;
- Eventuais divergências interpretativas.

A simples menção a uma lei não será considerada fundamentação suficiente.

## 9. Auditoria e controle

As análises deverão permitir identificar:

- Quem realizou ou revisou cada etapa;
- Quais documentos foram considerados;
- Quais fontes jurídicas foram utilizadas;
- Quais premissas foram adotadas;
- Quais alterações foram realizadas;
- Quais pontos permanecem pendentes.

## 10. Segurança e proteção de dados

O projeto deverá observar a Lei Geral de Proteção de Dados (Lei nº 13.709/2018).

São vedados:
- Envio acidental de documentos pessoais ao repositório;
- Armazenamento de credenciais e senhas;
- Exposição de informações médicas identificáveis;
- Compartilhamento indevido de dados de segurados.

O arquivo .gitignore é uma medida auxiliar, não uma garantia de proteção.

## 11. Evolução da metodologia

Toda alteração relevante deverá ser documentada e versionada.

Mudanças na metodologia não deverão apagar o histórico de decisões anteriores.

## 12. Regra final

A qualidade do AutoEcoar Previdenciário será medida pela consistência, segurança, fundamentação e rastreabilidade de suas análises, e não pela quantidade de conclusões produzidas ou pela promessa de concessão de benefícios.
