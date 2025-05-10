# TCC.DIO
Projeto de dio
📝 1. Introdução
Com o crescimento exponencial de dados digitais em documentos como arquivos PDF, surge a necessidade de ferramentas inteligentes capazes de extrair e fornecer informações relevantes de forma ágil. Neste contexto, os chatbots com suporte a Processamento de Linguagem Natural (NLP) vêm se destacando como soluções eficazes para facilitar o acesso a conteúdos complexos.

Este projeto tem como finalidade desenvolver um chatbot inteligente que responde perguntas com base em documentos PDF, utilizando tecnologias modernas de Machine Learning, NLP e computação em nuvem. O sistema será implantado como um serviço web acessível ao usuário final, promovendo uma experiência interativa e informativa.

🎯 2. Objetivos
2.1 Objetivo Geral
Desenvolver um chatbot inteligente capaz de compreender perguntas em linguagem natural e fornecer respostas com base no conteúdo de arquivos PDF.

2.2 Objetivos Específicos
Extrair e pré-processar o conteúdo textual de arquivos PDF.

Utilizar técnicas de NLP para compreensão semântica das perguntas.

Treinar um modelo de Machine Learning ou utilizar APIs de NLP para busca contextual de respostas.

Criar uma interface web interativa para o chatbot.

Implantar a solução em um ambiente em nuvem, garantindo escalabilidade e acesso em tempo real.

💡 3. Justificativa
Empresas e instituições lidam diariamente com grandes volumes de documentos, muitos dos quais em formato PDF. A busca manual por informações nesses arquivos é ineficiente, demorada e propensa a erros. Ao aplicar tecnologias de NLP e IA, é possível criar um sistema que automatize o processo de busca de informações, otimizando o tempo e reduzindo o esforço humano.

Este projeto se justifica pela relevância prática da solução, aplicável em diversas áreas como jurídico, educação, saúde e negócios, e pela importância acadêmica de explorar técnicas modernas de NLP e Machine Learning.

🔧 4. Metodologia (resumo)
Extração de texto: Usando bibliotecas como PyMuPDF, pdfminer.six ou PyPDF2.

Pré-processamento textual: Limpeza, tokenização, remoção de stopwords.

Vetorização semântica: Com TF-IDF, Word Embeddings ou Transformers.

Armazenamento e busca: Vetores armazenados em banco vetorial (ex: FAISS, Pinecone).

Modelo de pergunta-resposta: Uso de modelos como BERT QA, OpenAI ou Azure OpenAI.

Interface web: Desenvolvimento com Flask, Streamlit ou FastAPI.

Implantação na nuvem: Usando Azure, AWS ou Google Cloud.
