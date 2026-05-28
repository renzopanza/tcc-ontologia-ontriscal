# tcc-ontologia-ontriscal
Documentação visual e técnica da ONTRISCAL aplicada ao domínio da Terapia Cognitivo-Comportamental (TCC) no contexto do TCC de Engenharia de Software.

Contexto:
Este repositório serve como um documento complementar para o seguinte Trabalho de Conclusão de Curso:

- Título: Automação da geração de SDD e utilização em IA para TCC, integrando Ontologia e Grafos de Conhecimento
- Curso: Engenharia de Software
- Instituição: Associação Propagadora Esdeva Centro Universitário Academia – UniAcademia
- Ano: 2026
- Autor: Renzo Faedda Panza
- Orientador: Evaldo de Oliveira da Silva

O repositório que contém o desenvolvimento apresentado no TCC está disponível em: https://github.com/evaldo/homogenise

-> ONTRISCAL:

A Ontologia da Estratificação de Riscos em Saúde Mental (ONTRISCAL) foi desenvolvida por Silva (2023) para a utilização na aplicação Homogenise, tendo como fundamentação a ontologia de alto nível Unified Foundational Ontology (UFO). A ONTRISCAL foi construída em colaboração com especialistas em psicologia clínica do Centro Universitário UniAcademia (Juiz de Fora), focando na cobertura dos conceitos da estratificação de risco e tratamento em ansiedade, tendo cobertura para os seguintes domínios:

- Sinais e sintomas clínicos,
- Estratificação de risco em ansiedade,
- Dados sociodemográficos do paciente,
- Técnicas e intervenções da TCC,
- Níveis de risco (Separados em Baixo, Médio e Alto),
- Crenças centrais e pensamentos automáticos;

Referência Original:
DA SILVA, Evaldo de Oliveira. Homogenise: método para modelagem ontológica do conhecimento em pesquisas quali-quanti. 2023.


-> Como este repositório esta relacionado com o TCC:
Durante o desenvolvimento do presente trabalho, a ontologia ONTRISCAL foi adotada como domínio base no mapeamento das variáveis dos dados de TCC a conceitos ontológicos utilizados nos documentos do Dicionário de Dados Semântico, na fundamentação das triplas RDF/OWL que compoem o Grafo de Conhecimento e nas inferências feitas via SPARQL sobre os padrões clínicos da TCC.

-> Estrutura do repositório:

tcc-ontologia-ontriscal/
├── README.md
├── ontologia-ontriscal/
│   ├── ontriscal_gufo_owl.owl
├── imagens-ontriscal/
│   ├── classe-ontriscal-1.png
│   ├── classe-ontriscal-2.png
│   ├── classe-ontriscal-3.png
│   ├── classe-ontriscal-4.png
│   ├── classe-ontriscal-5.png


-> Classes da ONTRISCAL:
A ONTRISCAL possui classes que foram criadas para representarem conceitos e propriedades relevantes para o seu domínio. Os conceitos listados são utilizados para a anotação de dados clinicos, sociodemográficos e níveis de cuidados (Silva, 2023). As classes presentes nesta ontologia se encontram em figuras salvas dentro da pasta 'tcc-ontologia-ontriscal/imagens-ontriscal/'. 

Ambas as imagens são de autoria do autor e foram feitas usando o Protégé¹.

Referências:
DA SILVA, Evaldo de Oliveira. Homogenise: método para modelagem ontológica do conhecimento em pesquisas quali-quanti. 2023.

¹ https://protege.stanford.edu/