# tcc-ontologia-ontriscal

> Documentação visual e técnica da **ONTRISCAL** aplicada ao domínio da **Terapia Cognitivo-Comportamental (TCC)**, no contexto do Trabalho de Conclusão de Curso em Engenharia de Software.

![Status](https://img.shields.io/badge/status-desenvolvido-green)
![Ano](https://img.shields.io/badge/ano-2026-blue)
![Curso](https://img.shields.io/badge/curso-Engenharia%20de%20Software-informational)
![Ontologia](https://img.shields.io/badge/ontologia-OWL%20%2F%20gUFO-purple)
![Licença](https://img.shields.io/badge/uso-acadêmico-lightgrey)

---

## 📑 Sumário

- [Sobre o projeto](#sobre-o-projeto)
- [Repositório relacionado](#repositório-relacionado)
- [A ontologia ONTRISCAL](#a-ontologia-ontriscal)
  - [Domínios de cobertura](#domínios-de-cobertura)
  - [Referência original](#referência-original)
- [Relação com o TCC](#relação-com-o-tcc)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Classes da ONTRISCAL](#classes-da-ontriscal)
- [Referências](#referências)
- [Autoria](#autoria)

---

## 📖 Sobre o projeto

Este repositório serve como **documento complementar** ao seguinte Trabalho de Conclusão de Curso:

| Campo | Descrição |
| :--- | :--- |
| **Título** | Automação da geração de SDD e utilização em IA para TCC, integrando Ontologia e Grafos de Conhecimento |
| **Curso** | Engenharia de Software |
| **Instituição** | Associação Propagadora Esdeva — Centro Universitário Academia (UniAcademia) |
| **Ano** | 2026 |
| **Autor** | Renzo Faedda Panza |
| **Orientador** | Evaldo de Oliveira da Silva |

---

## 🔗 Repositório relacionado

- **Implementação (HOMOGENISE):** <https://github.com/evaldo/homogenise>

---

## 🧠 A ontologia ONTRISCAL

A **Ontologia da Estratificação de Riscos em Saúde Mental (ONTRISCAL)** foi desenvolvida por **Silva (2023)** para utilização na aplicação **HOMOGENISE**, tendo como fundamentação a ontologia de alto nível **Unified Foundational Ontology (UFO)**.

A ONTRISCAL foi construída em colaboração com **especialistas em psicologia clínica** do Centro Universitário UniAcademia (Juiz de Fora), focando na cobertura dos conceitos de **estratificação de risco e tratamento em transtornos de ansiedade**.

### Domínios de cobertura

- Sinais e sintomas clínicos;
- Estratificação de risco em ansiedade;
- Dados sociodemográficos do paciente;
- Técnicas e intervenções da TCC;
- Níveis de risco (separados em **Baixo**, **Médio** e **Alto**);
- Crenças centrais e pensamentos automáticos.

### Referência original

> DA SILVA, Evaldo de Oliveira. **Homogenise: método para modelagem ontológica do conhecimento em pesquisas quali-quanti**. 2023.

---

## 🔬 Relação com o TCC

Durante o desenvolvimento do presente trabalho, a ontologia ONTRISCAL foi adotada como **domínio base** em três frentes:

1. No **mapeamento das variáveis** dos dados de TCC a conceitos ontológicos utilizados nos documentos do *Semantic Data Dictionary* (SDD);
2. Na **fundamentação das triplas RDF/OWL** que compõem o Grafo de Conhecimento (GC);
3. Nas **inferências realizadas via SPARQL** sobre os padrões clínicos da TCC.

---

## 📂 Estrutura do repositório

```text
tcc-ontologia-ontriscal/
├── README.md
├── ontologia-ontriscal/
│   └── ontriscal_gufo_owl.owl
└── imagens-ontriscal/
    ├── classe-ontriscal-1.png
    ├── classe-ontriscal-2.png
    ├── classe-ontriscal-3.png
    ├── classe-ontriscal-4.png
    └── classe-ontriscal-5.png
```

---

## 🗂️ Classes da ONTRISCAL

A ONTRISCAL possui classes criadas para representar **conceitos e propriedades** relevantes ao seu domínio. Esses conceitos são utilizados para a anotação de:

- Dados clínicos;
- Dados sociodemográficos;
- Níveis de cuidado *(Silva, 2023)*.

As classes presentes nesta ontologia podem ser visualizadas nas figuras salvas em:

```text
tcc-ontologia-ontriscal/imagens-ontriscal/
```

> 💡 Todas as imagens são de **autoria própria** e foram produzidas utilizando o **Protégé**[^1].

---

## 📚 Referências

- DA SILVA, Evaldo de Oliveira. **Homogenise: método para modelagem ontológica do conhecimento em pesquisas quali-quanti**. 2023.

[^1]: Protégé — *ontology editor* mantido pela Universidade de Stanford. Disponível em: <https://protege.stanford.edu/>.

---

## ✍️ Autoria

**Renzo Faedda Panza**
Graduando em Engenharia de Software — UniAcademia
Orientador: Prof. Evaldo de Oliveira da Silva

> Este repositório é parte integrante do TCC e tem finalidade exclusivamente acadêmica.
