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
git clone https://github.com/Ronbragaglia/pesquisa-inteligente.git
cd pesquisa-inteligente
```

### 2️⃣ Instale as Dependências
```bash
pip install nest_asyncio gradio aiohttp python-dotenv
```

### 3️⃣ Configure as Chaves de API
Para que o código funcione corretamente, é necessário obter **três chaves de API**:
- **OpenRouter API** → [Criar chave aqui](https://openrouter.ai/)
- **SERPAPI API** → [Criar chave aqui](https://serpapi.com/)
- **Jina AI API** → [Criar chave aqui](https://jina.ai/)

Após obter as credenciais, crie um arquivo **`.env`** na raiz do projeto e adicione:
```env
OPENROUTER_API_KEY=SUA_CHAVE_AQUI
SERPAPI_API_KEY=SUA_CHAVE_AQUI
JINA_API_KEY=SUA_CHAVE_AQUI
```

### 4️⃣ Execute o Código
```bash
python opendeepresearcher.py
```
Ou, se estiver no **Google Colab**, basta acessar e rodar o notebook:
[🔗 Google Colab](https://colab.research.google.com/drive/1g6sTT6VTmZVypF5VEDsmmAUJkJZcLaOf?usp=sharing)

## 🎮 Como Usar a Interface Gradio
1. **Abra o link gerado pelo Gradio**
2. **Digite o tópico que deseja pesquisar**
3. **Escolha o número máximo de iterações**
4. **Clique em "Executar" e aguarde a IA gerar o relatório!**

## 🎓 Guia Passo a Passo para Configurar as Credenciais

### 1️⃣ Criando a Chave da OpenRouter API
1. Acesse [OpenRouter](https://openrouter.ai/) e faça login.
2. Vá até **Dashboard > API Keys**.
3. Gere uma nova chave e copie o código.
4. Cole no arquivo `.env` como:
   ```env
   OPENROUTER_API_KEY=SUA_CHAVE_AQUI
   ```

### 2️⃣ Criando a Chave da SERPAPI
1. Acesse [SERPAPI](https://serpapi.com/) e crie uma conta gratuita.
2. No painel, vá até **API Keys** e copie sua chave.
3. Cole no arquivo `.env` como:
   ```env
   SERPAPI_API_KEY=SUA_CHAVE_AQUI
   ```

### 3️⃣ Criando a Chave da Jina AI API
1. Acesse [Jina AI](https://jina.ai/) e cadastre-se.
2. Vá até **API Keys** e gere uma nova chave.
3. Copie e cole no `.env`:
   ```env
   JINA_API_KEY=SUA_CHAVE_AQUI
   ```

Agora seu ambiente está pronto para rodar o código! 🚀

## 📌 Exemplo de Uso
Se você deseja pesquisar sobre "O impacto da IA na Medicina", o sistema irá:
1. Criar **consultas otimizadas** para encontrar boas fontes.
2. Buscar **os melhores resultados no Google**.
3. **Ler e extrair** as informações mais relevantes dos sites encontrados.
4. **Gerar um relatório detalhado** baseado nos dados coletados.

## 🔎 OpenDeepResearcher: A Revolução da Pesquisa Automatizada com IA

Imagina ter uma IA open-source que realiza pesquisas extensas, extrai insights valiosos e gera relatórios detalhados automaticamente. Esse é o **OpenDeepResearcher!** 🚀

### 🧠 Como funciona?
✅ Realiza pesquisas com base na sua consulta
✅ Extrai as informações mais relevantes
✅ Aprofunda a busca com base nos primeiros achados
✅ Repete o processo até obter um conjunto robusto de dados
✅ Sintetiza tudo em um relatório completo

O diferencial? Todas as pesquisas são executadas em paralelo, garantindo velocidade e eficiência nos resultados. Embora ainda não seja tão avançada quanto a pesquisa profunda da OpenAI, essa ferramenta já é um marco na evolução dos agentes de busca inteligentes.

🔗 **Código no GitHub:** [OpenDeepResearcher.py](https://github.com/Ronbragaglia/pesquisa-inteligente/blob/main/opendeepresearcher.py)

## 💡 Funcionalidades Futuras
- [ ] Melhorar a extração de dados com NLP
- [ ] Implementar visualização gráfica dos resultados
- [ ] Adicionar suporte a múltiplas línguas

## 📄 Licença
Este projeto está sob a licença **MIT** – sinta-se livre para contribuir e compartilhar! 😃

---
💻 **Desenvolvido por [Rone Bragaglia](https://github.com/Ronbragaglia)** 🚀

#IA #ArtificialIntelligence #IAGenerativa #Inovação #MachineLearning #Chatbot #OpenAI #Anthropic #Claude #Google #Gemini #Meta #Llama #OpenSourceAI #AIagents #AgentesIA #Automation #Automação #DeepSeek #Qwen #Grok



