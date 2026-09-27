# 🪽 Hermes Agent + Claude Code: meus projetos

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Hermes Agent](https://img.shields.io/badge/Hermes_Agent-111111?style=flat-square&logo=github&logoColor=white)

Aqui eu mostro os projetos que eu construí usando dois agentes de IA no dia a dia: o **Hermes Agent** e o **Claude Code**.

## 🧭 Quer usar o Hermes?

O Hermes Agent é um agente de IA **open source** da Nous Research. Ele roda no seu computador, tem memória, aprende skills novas e conversa com você por vários canais.

👉 **Repositório oficial:** [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

Pra instalar e configurar, siga o README oficial. Dicas de quem já apanhou um pouco:

1. Comece com poucas skills e vá ligando só as que você usa. Cada skill a mais deixa ele mais lento.
2. Escreva as regras e os fatos importantes no arquivo de personalidade dele. Modelo pequeno inventa o que não está escrito.
3. Antes de trocar de modelo, confira o limite de uso do plano grátis. Ele muda de um modelo pro outro.
4. Depois de atualizar, teste de novo tudo que você tinha configurado.

## 🤖 E o Claude Code?

O [Claude Code](https://claude.com/claude-code) é o agente de programação da Anthropic que roda no terminal. Eu uso ele como **par de programação**: eu decido o que fazer, reviso e testo, e ele acelera a escrita.

Os dois conversam: quando a tarefa é pesada (ler um PDF grande, escrever código), o Hermes passa pro Claude Code pelo terminal e só me entrega o resultado.

## 🛠️ Projetos

| Projeto | O que faz | Stack |
|---|---|---|
| 📄 Gerador de documentos | Preenche modelos `.docx` com os dados certos e mantém a formatação original | Python, python-docx |
| 📡 Monitor diário | Consulta APIs públicas todo dia e me manda só o que mudou, resumido | Python, APIs REST |
| 🧠 Busca nas anotações | Índice de busca full-text das minhas anotações: achar algo caiu de minutos pra 0,3 s | Python, SQLite FTS5 |
| 🎙️ Transcrição local | Transcreve áudio e aula na GPU, 100% offline | Whisper, CUDA |
| 🔍 Triagem de PDF | OCR + modelo de IA local pra ler e separar documentos escaneados | Tesseract, Ollama |
| 🗂️ Diagramas ER por código | Gera modelos do brModelo direto por script pra faculdade | Java |
| 📚 Revisões em PDF | Monta material de revisão das matérias a partir das minhas anotações | Python, HTML → PDF |
| 🔗 Ponte Hermes → Claude Code | O Hermes delega tarefa pesada pro Claude Code e devolve a resposta | Hermes Agent, Claude Code |

> O código desses projetos fica privado porque roda com dados do meu trabalho. Aqui eu mostro o que cada um faz e com o que foi feito.

## 💡 O que eu aprendi

- Agente de IA bom é agente com **regra escrita**, não só com prompt.
- **Rodar local** é o caminho quando o dado é sensível.
- Automatizar o repetitivo primeiro e deixar a IA só pra parte que precisa pensar.

---

📌 Mais projetos no meu [perfil](https://github.com/gabrielvictoraraujodacruz-create).
