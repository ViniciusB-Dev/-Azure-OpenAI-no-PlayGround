
# Entendendo o Desafio: Usando o Playground do Azure OpenAI

## 📌 Objetivo

O objetivo deste desafio é utilizar o **Playground do Azure OpenAI** para gerar conteúdos com base em dados próprios e compreender as diferentes **configurações e parâmetros** disponíveis, explorando suas funcionalidades para personalização de respostas da IA.

---

## 🧠 Compreendendo o Playground

O **Playground do Azure OpenAI** oferece uma interface interativa para testar e ajustar modelos de linguagem. Com ele, é possível:

- Definir instruções e contextos para a IA;
- Adicionar fontes de dados personalizadas;
- Controlar o comportamento da IA com parâmetros ajustáveis.

### 🖼️ Interface do Playground

![Chat Playground](assets/chat-playground-new.png)

Na tela acima, podemos ver:

- Um campo para inserir instruções para o modelo;
- A opção **Add your data**, que permite carregar arquivos ou conectar fontes externas;
- Seções de prompts e parâmetros ajustáveis;
- Histórico de mensagens para melhor acompanhamento da conversa.

---

## 📂 Adicionando Dados Personalizados

Ao clicar em **"Add a data source"**, é possível incluir documentos que serão usados como referência para o modelo responder.

### ⚙️ Configurações Avançadas

![Configurações Avançadas](assets/studio-advanced-settings.png)

Após adicionar os dados, é possível ajustar:

- **Limit responses to your data content**: Restringe as respostas somente aos conteúdos carregados;
- **Strictness (1-5)**: Define o quão rigorosa será a correspondência com os dados (quanto maior, mais exato precisa ser);
- **Retrieved documents (3-20)**: Define quantos documentos o modelo pode buscar por vez para formar a resposta.

Essas opções ajudam a refinar os resultados e garantir que o conteúdo retornado esteja de acordo com o que foi carregado.

---

## 🧪 Testando no Playground

Você pode realizar testes diretamente no painel, fazendo perguntas com base nos dados inseridos. Exemplo:

```
Qual é o conteúdo do arquivo que acabei de carregar?
```

Com a opção de limitar às suas fontes marcada, a IA só responderá com base no conteúdo dos arquivos carregados, respeitando o nível de **strictness** e a quantidade de documentos recuperados.

---

## ✅ Conclusão

Este desafio permite explorar a integração de dados próprios com modelos de linguagem no **Azure OpenAI**, utilizando o Playground para:

- Compreender como a IA lida com fontes externas;
- Ajustar parâmetros para melhores resultados;
- Criar uma experiência de geração de conteúdo mais controlada e personalizada.
