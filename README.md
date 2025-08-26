# AI Search API 🔍✨

Bring **AI-powered web search** into your apps with just a few lines of code.  
AI Search API is built for developers who want reliable, real-time search results directly from the web — without dealing with scraping, parsing, or heavy integrations.  

👉 [aisearchapi.io](https://aisearchapi.io/)

---

## 🌟 Why AI Search API?

- ⚡ **Fast & Easy** — start searching the web with only a few lines of code.  
- 🧑‍💻 **Developer-friendly** — simple SDKs for JavaScript, Python, and LangChain.  
- 🔍 **Real-time Web Search** — fresh results from the internet.  
- 🤖 **LLM-Ready** — seamlessly integrates with your AI applications.  
- 🔒 **Secure** — authenticated API calls with your API key.  

AI Search API is designed for developers, freelancers, and teams who want to integrate **powerful search** into their applications without the extra complexity.

---

## 🚀 Quickstart

### JavaScript / TypeScript
```bash
npm install aisearchapi-client
```
```ts
import { AISearchAPI } from "aisearchapi-client";

const client = new AISearchAPI("YOUR_API_KEY");

(async () => {
  const results = await client.search("latest AI news");
  console.log(results);
})();
```

### Python
```bash
pip install aisearchapi-client
```
```python
from aisearchapi import AISearchAPI

client = AISearchAPI("YOUR_API_KEY")
results = client.search("latest AI news")
print(results)
```

### LangChain
Easily integrate with **LangChain** to power your LLM apps:
```python
from langchain_community.tools import AISearchAPITool

tool = AISearchAPITool(api_key="YOUR_API_KEY")
result = tool.run("latest AI research papers")
print(result)
```

---

## 💡 Example Use Cases

- **Chatbots** that answer questions with fresh, real-world data.  
- **Research tools** that fetch the latest articles, news, or blog posts.  
- **AI assistants** that enrich responses with up-to-date knowledge.  
- **Data pipelines** that pull web information for analysis.  

Wherever you need **up-to-date search results**, AI Search API can help.

---

## 📚 SDKs

Choose your favorite language and start building:  

- [aisearchapi-js](https://github.com/aisearchapi/aisearchapi-js)  
- [aisearchapi-python](https://github.com/aisearchapi/aisearchapi-python)  
- [aisearchapi-langchain](https://github.com/aisearchapi/aisearchapi-langchain)  

---

## 🌍 Website

👉 Try it live: [aisearchapi.io](https://aisearchapi.io/)

---

## 🤝 Contributing

We love contributions from the community ❤️  

Here’s how you can help:
1. **Star this repo** ⭐️ to support the project.  
2. **Open issues** for bugs, ideas, or feature requests.  
3. **Submit pull requests** with improvements.  

Whether it’s code, documentation, or examples — every contribution counts!  

---

## 📜 License

MIT — free to use, share, and improve.  
