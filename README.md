# 📄 Cv Sync (Smart ATS Resume Optimizer)

Desafio de projeto da **DIO (Digital Innovation One)** para criação de um aplicativo web de otimização de currículos para sistemas ATS utilizando o conceito de **Vibe Coding** com o auxílio do **Copilot Web** e do **Lovable**.

🔗 **[Acesse a Aplicação Publicada Aqui](https://id-preview--aac0b787-7b45-48c8-9cdf-f5d581c114ed.lovable.app/?__lovable_receipt=mat_3bgs5094kd8mc826c2m7nmg1t3)**

---

## 🎯 1. A Dor Escolhida e Por Que Vale um Negócio

- **A Dor Escolhida:** Milhares de profissionais altamente qualificados perdem oportunidades de emprego diariamente porque seus currículos são sumariamente rejeitados por sistemas automatizados de triagem (ATS — *Applicant Tracking System*) antes mesmo de serem lidos por um recrutador humano, devido à falta de palavras-chave adequadas ou formatação incompatível.
- **Por que vale um negócio:** Otimizar a compatibilidade de currículos de forma inteligente e ágil para qualquer vaga (seja em tecnologia, administração, saúde ou vendas) democratiza o acesso a processos seletivos e aumenta drasticamente as taxas de conversão de entrevistas para os candidatos.

---

## 📊 2. Tamanho de Mercado e Business Model Canvas

### Tamanho de Mercado
- **TAM (Total Addressable Market):** O mercado global e nacional de busca de empregos e transição de carreira (milhões de profissionais ativos anualmente).
- **SAM (Serviceable Available Market):** Candidatos ativos que aplicam para vagas online e enfrentam barreiras de filtragem automatizada em plataformas digitais.
- **SOM (Serviceable Obtainable Market):** Profissionais iniciantes e intermediários que buscam otimizar seus currículos rapidamente de forma orgânica.

### Business Model Canvas (Resumo)
* **Parceiros-Chave:** Plataformas de emprego e criadores de conteúdo de carreira.
* **Atividades-Chave:** Processamento de linguagem natural (análise de compatibilidade) e refinamento de texto.
* **Recursos-Chave:** Aplicação web interativa (Cv Sync) e modelos de IA para análise semântica.
* **Proposta de Valor:** Sincronização rápida entre currículo e descrição de vaga, gerando alta compatibilidade ATS sem inventar dados falsos.
* **Relação com o Cliente:** Automatizada, intuitiva e consultiva via interface web.
* **Canais:** Redes sociais, portais de tecnologia e indicações orgânicas.
* **Segmento de Clientes:** Profissionais de todas as áreas buscando se destacar em processos seletivos.
* **Estrutura de Custos:** Hospedagem da aplicação e infraestrutura de IA.
* **Fontes de Receita:** Modelo freemium ou planos de assinatura para recursos avançados de exportação em massa.

---

## 🧪 3. A Tese do MVP e O Que Ficou Manual

- **A Tese do MVP:** Profissionais preferem colar a descrição da vaga e o seu currículo em uma interface centralizada para visualizar instantaneamente o percentual de match e obter um texto reestruturado e honesto, em vez de reescrever o currículo manualmente para cada vaga.
- **O que ficou manual de propósito:** 
  - **Ajustes Finais de Layout:** O download/cópia do texto otimizado é fornecido de forma limpa para que o usuário faça os retoques finais no seu editor favorito (Word/Google Docs).
  - **Histórico e Persistência de Dados:** No MVP atual, as análises rodam em tempo real na sessão sem a necessidade de banco de dados complexo ou sistema de login obrigatório no primeiro acesso.

---

## 🖼️ 4. Imagens das Telas da Aplicação

| Tela Inicial e Entrada de Dados | Painel de Análise e Match |
| :---: | :---: |
<img width="1907" height="884" alt="image" src="https://github.com/user-attachments/assets/c923b6c5-d141-4586-9296-10cdee11bfd8" />


| Palavras-Chave e Otimização ATS | Currículo Otimizado |
| :---: | :---: |
| <img width="1907" height="639" alt="image" src="https://github.com/user-attachments/assets/858038f1-e574-41a4-86b8-ca66b31f1922" />
<img width="1113" height="322" alt="image" src="https://github.com/user-attachments/assets/fc33dbbc-642e-465c-825e-186955c01cad" />




---

## 📋 5. O Mega Prompt e as Correções Posteriores

<details>
<summary><b>Clique para expandir o Mega Prompt inicial usado no Lovable</b></summary>

```markdown
Crie uma aplicação web moderna, responsiva e de alto padrão em React com Tailwind CSS, shadcn/ui e Lucide Icons chamada "Cv Sync". O objetivo da aplicação é analisar dinamicamente a compatibilidade entre o currículo de um profissional (de qualquer área de atuação) e a descrição de uma vaga de emprego colada pelo usuário, gerando uma versão otimizada e "ATS-friendly" (compatível com sistemas de triagem do RH) sem inventar experiências que o candidato não possui.

A identidade visual deve ser limpa, profissional e inspirada em ferramentas corporativas de alta tecnologia, utilizando uma paleta de cores moderna em tons de azul escuro/indigo, branco e detalhes em verde esmeralda para indicar sucesso e match.

A aplicação deve conter as seguintes telas e fluxos principais em uma experiência de página única (SPA) fluida:

1. Header / Barra de Navegação:
- Logotipo moderno com ícone de documento/IA e o nome "Cv Sync".
- Subtítulo indicando o propósito: "Sincronize seu currículo com qualquer vaga e passe pelos filtros ATS com inteligência".

2. Seção de Entrada de Dados (Dois painéis lado a lado em telas grandes):
- Painel esquerdo: Textarea para colar a Descrição da Vaga (qualquer cargo ou área: tecnologia, saúde, vendas, administração, etc.).
- Painel direito: Textarea para colar o Currículo Atual do candidato.
- Botão de destaque centralizado: "Analisar Compatibilidade e Otimizar" com ícone de IA (Sparkles).

3. Seção de Resultados da Análise:
- Indicador de Match (%): Um cartão em destaque mostrando a porcentagem de compatibilidade com barra de progresso visual.
- Palavras-Chave Encontradas e Faltantes: Listas visuais (badges) diferenciando termos presentes e ausentes.

4. Seção do Currículo Otimizado (ATS-Friendly):
- Painel com o texto revisado incorporando as palavras-chave faltantes de forma honesta.
- Aviso ético em destaque: "Aviso: Otimizamos a apresentação e o vocabulário para sistemas ATS sem inventar experiências."
- Botões de Ação: "Copiar Currículo Otimizado" e "Baixar / Exportar".
