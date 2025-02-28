# 🔎 Assistente de Pesquisa Inteligente

🚀 **Um sistema automatizado que pesquisa, coleta e gera relatórios baseados em IA!**

## 📌 Visão Geral
Este projeto é um **Assistente de Pesquisa Inteligente** desenvolvido em **Python** e utilizando **Google Colab**, que:
✅ **Gera automaticamente consultas de pesquisa otimizadas**
✅ **Busca resultados relevantes no Google usando a API SERPAPI**
✅ **Extrai textos das páginas encontradas com a Jina AI**
✅ **Gera um relatório detalhado com base nos dados coletados usando OpenRouter AI**
✅ **Fornece uma interface interativa via Gradio**

## 🛠 Tecnologias Utilizadas
- **Python** (Asyncio, Aiohttp, JSON)
- **Gradio** (Interface gráfica interativa)
- **OpenRouter API** (Para gerar textos com IA)
- **SERPAPI** (Para buscar informações no Google)
- **Jina AI** (Para extrair texto das páginas web)
- **Google Colab** (Para rodar o código de forma prática e gratuita)

## 📥 Como Instalar e Executar
### 1️⃣ Clone o Repositório
```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO
```

### 2️⃣ Instale as Dependências
```bash
pip install nest_asyncio gradio aiohttp python-dotenv
```

### 3️⃣ Configure as Chaves de API
Crie um arquivo **`.env`** e adicione suas chaves de API:
```env
OPENROUTER_API_KEY=SUA_CHAVE_AQUI
SERPAPI_API_KEY=SUA_CHAVE_AQUI
JINA_API_KEY=SUA_CHAVE_AQUI
```

### 4️⃣ Execute o Código
```bash
python pesquisa_inteligente.py
```
Ou, se estiver no **Google Colab**, basta executar as células do notebook.

## 🎮 Como Usar a Interface Gradio
1. **Abra o link gerado pelo Gradio**
2. **Digite o tópico que deseja pesquisar**
3. **Escolha o número máximo de iterações**
4. **Clique em "Executar" e aguarde a IA gerar o relatório!**

🎓 Guia Passo a Passo para Configurar as Credenciais

1️⃣ Criando a Chave da OpenRouter API

Acesse OpenRouter e faça login.

Vá até Dashboard > API Keys.

Gere uma nova chave e copie o código.

Cole no arquivo .env como:

OPENROUTER_API_KEY=SUA_CHAVE_AQUI

2️⃣ Criando a Chave da SERPAPI

Acesse SERPAPI e crie uma conta gratuita.

No painel, vá até API Keys e copie sua chave.

Cole no arquivo .env como:

SERPAPI_API_KEY=SUA_CHAVE_AQUI

3️⃣ Criando a Chave da Jina AI API

Acesse Jina AI e cadastre-se.

Vá até API Keys e gere uma nova chave.

Copie e cole no .env:

JINA_API_KEY=SUA_CHAVE_AQUI

Agora seu ambiente está pronto para rodar o código! 🚀



## 📌 Exemplo de Uso
Se você deseja pesquisar sobre "O impacto da IA na Medicina", o sistema irá:
1. Criar **consultas otimizadas** para encontrar boas fontes.
2. Buscar **os melhores resultados no Google**.
3. **Ler e extrair** as informações mais relevantes dos sites encontrados.
4. **Gerar um relatório detalhado** baseado nos dados coletados.

## 💡 Funcionalidades Futuras
- [ ] Melhorar a extração de dados com NLP
- [ ] Implementar visualização gráfica dos resultados
- [ ] Adicionar suporte a múltiplas línguas

## 📄 Licença
Este projeto está sob a licença **MIT** – sinta-se livre para contribuir e compartilhar! 😃

---
💻 **Desenvolvido por [Ronebragaglia](https://github.com/Ronbragaglia)** 🚀

