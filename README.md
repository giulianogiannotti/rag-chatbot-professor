# 🤖 Chatbot RAG para la Página de un Profesor

## 📌 Descripción
Este repositorio contiene un **prototipo de chatbot basado en Retrieval-Augmented Generation (RAG)**.  
Está diseñado para responder preguntas en **español** utilizando información extraída de:  
- La página web oficial de un profesor.  
- Documentos PDF (pautas de examen y materiales del curso).  

El proyecto utiliza **LangChain**, **FAISS** y **HuggingFace embeddings** para la recuperación de documentos, combinado con el modelo **LLaMA-2 de Replicate** para generar respuestas en lenguaje natural.

---

## ⚙️ Funcionalidades
- 🔎 **Web scraping** de la página oficial del profesor.  
- 📄 **Procesamiento de PDFs** con metadatos asociados.  
- ✂️ **División de texto** en fragmentos para mejorar la búsqueda.  
- 🧠 **Embeddings + FAISS** para búsqueda semántica.  
- 🤖 **Chatbot basado en RAG** que responde preguntas en español.  
- 🎯 Posibilidad de filtrar respuestas según el documento fuente.  

---

## 🛠️ Instalación y Requisitos
Asegúrate de tener **Python 3.9+** instalado y luego ejecuta:

```bash
pip install -r requirements.txt
