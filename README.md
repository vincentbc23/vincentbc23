<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B3D2E,50:12715B,100:1FA67A&height=190&section=header&text=Vincent%20Collares&fontSize=44&fontColor=FFFFFF&fontAlignY=36&desc=Dados%20%E2%80%A2%20Machine%20Learning%20%E2%80%A2%20LLMs%20e%20RAG&descSize=18&descAlignY=58" width="100%" alt="Vincent Collares"/>

<a href="https://github.com/vincentbc23">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3500&pause=900&color=1FA67A&center=true&vCenter=true&width=620&lines=Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o+%40+UFLA;Vice-presidente+do+NIAD+(IA+e+Ci%C3%AAncia+de+Dados);GraphRAG+com+Neo4j+e+LLMs+locais;Buscando+est%C3%A1gio+em+Dados+%2F+IA" alt="Typing SVG"/>
</a>

<br/>

<a href="https://www.linkedin.com/in/vincent-collares"><img src="https://img.shields.io/badge/LinkedIn-vincent--collares-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:vincent.b.collares@gmail.com"><img src="https://img.shields.io/badge/Email-Fale%20comigo-1FA67A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Lavras%2C%20MG-Brasil-0B3D2E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Lavras, MG"/>

</div>

---

## 👋 Sobre mim

Sou estudante de **Ciência da Computação na UFLA** e técnico em Informática pelo IFSULDEMINAS. Trabalho com **dados, machine learning e sistemas com LLMs**: RAG, GraphRAG e modelos rodando localmente em hardware modesto. No **NIAD**, o Núcleo de Estudos em Inteligência Artificial e Ciência de Dados da UFLA, entrei como trainee e hoje sou vice-presidente.

- 🔬 **Iniciação científica:** mapeamento de competências da UFLA com GraphRAG (Edital PRPI INOV@ÇÃO UFLA)
- ☕ **Produto:** CaféX, um chatbot no WhatsApp que conecta o pequeno produtor de café a quem resolve o problema da lavoura
- 🎤 **Palestras:** RAG na SE7I/UFLA e banner do NIAD no CONEX 2026
- 🎯 **Procurando:** estágio em Dados / IA

---

## 🚀 Projetos em destaque

### 🔬 Mapeamento de competências da UFLA · GraphRAG
Grafo em **Neo4j** com os currículos Lattes de **2.890 professores** da UFLA (**~1,5 milhão de nós** e **~2,3 milhões de arestas**), modelado a partir do XSD oficial do CNPq, com resolução de entidades e deduplicação de publicações. Em cima dele, uma camada de GraphRAG com LLM e embeddings locais (Ollama) para encontrar pesquisadores por tema. *Repositório privado.*

`Neo4j` `Cypher` `Python` `Docker` `Ollama` `GraphRAG`

### Dados, ML e LLMs

| Projeto | Descrição | Stack |
|:--|:--|:--|
| ☕ [**rag-cafe**](https://github.com/vincentbc23/rag-cafe) | RAG de fornecedores da cadeia do café: busca híbrida (filtro SQL + BM25 + embeddings), rerank por localização e avaliação, e métricas de recuperação (Hit@1, P@3). Roda em GPU de 8 GB | `SQLite FTS5` `bge-m3` `Qwen3.5-4B` `SGLang` |
| 🔥 [**predicao-incendios-cerrado**](https://github.com/vincentbc23/predicao-incendios-cerrado) | Classificação do risco e regressão da intensidade (FRP) de incêndios no Cerrado mineiro com dados do INPE e do ERA5, e explicabilidade com SHAP. Projeto em equipe no Zetta Lab; fiz os modelos | `XGBoost` `scikit-learn` `SHAP` `GeoPandas` |
| 🧠 [**niad-rag-palestras**](https://github.com/vincentbc23/niad-rag-palestras) | Demos das minhas palestras de RAG: pipeline passo a passo, busca lexical × vetorial × híbrida, prompt injection e avaliação com Recall@3 / Precision@3 | `Ollama` `Jupyter` `NumPy` |
| 🌳 [**xgboost-vs-random-forest**](https://github.com/vincentbc23/xgboost-vs-random-forest) | Análise comparativa de XGBoost e Random Forest em três problemas de classificação, com relatório | `XGBoost` `scikit-learn` `pandas` |
| 📊 [**ml-seguranca-educacao-mg**](https://github.com/vincentbc23/ml-seguranca-educacao-mg) | Modelos preditivos de criminalidade e educação em Minas Gerais com dados públicos (SEJUSP, INEP, IBGE) e recomendações de políticas públicas | `pandas` `scikit-learn` `Plotly` |

### Aplicações com IA no ar

| Projeto | Descrição | Demo |
|:--|:--|:--:|
| 🎙️ [**niad-voz**](https://github.com/vincentbc23/niad-voz) | Síntese de voz em português com Kokoro-82M, API em FastAPI e deploy em Docker | [▶ Testar](https://vincentbc23-niad-voz.hf.space) |
| ♟️ [**niad-xadrez**](https://github.com/vincentbc23/niad-xadrez) | Xadrez contra o Stockfish com 8 níveis calibrados por Elo e barra de avaliação em tempo real | [▶ Jogar](https://niad-xadrez.onrender.com) |
| ⭕ [**niad-jogo-da-velha**](https://github.com/vincentbc23/niad-jogo-da-velha) | Jogo da velha contra uma IA que decide as jogadas com Monte Carlo Tree Search | [▶ Jogar](https://niad-jogo-da-velha.onrender.com) |
| 🛰️ [**radar-vagas**](https://github.com/vincentbc23/radar-vagas) | Busca vagas na Gupy, Greenhouse e Lever, filtra por área, nível e modalidade e avisa só as novas no Telegram, 3x por dia | GitHub Actions |

---

## 🛠️ Tecnologias

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,js,postgres,sqlite,docker,fastapi,flask,react,linux,git,githubactions&perline=12" alt="Tecnologias"/>

<br/><br/>

<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/XGBoost-1B6AC6?style=flat-square" alt="XGBoost"/>
<img src="https://img.shields.io/badge/SHAP-FF0D57?style=flat-square" alt="SHAP"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" alt="Plotly"/>
<img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"/>
<img src="https://img.shields.io/badge/SGLang-6E40C9?style=flat-square" alt="SGLang"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>

</div>

---

## 🤝 NIAD · UFLA

Como vice-presidente, organizei o processo seletivo do núcleo, um curso intensivo de Aprendizado de Máquina aberto ao público e a participação do NIAD no UFLA de Portas Abertas. Os repositórios `niad-*` são as demos que levamos para eventos e palestras.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1FA67A,50:12715B,100:0B3D2E&height=110&section=footer" width="100%" alt=""/>
