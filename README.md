# Project Nox · Extensões de Mangá

Repositório oficial de distribuição e catálogo compilado de extensões de mangá do **Project Nox** para **Mihon e forks**.

---

> [!TIP]
> **Distribuição oficial 100% gratuita**
>
> O Project Nox não cobra pelo download, instalação ou atualização das suas extensões de mangá e anime.
>
> Caso alguém solicite pagamento alegando representar o Project Nox ou afirmando que o acesso às extensões oficiais exige uma taxa, desconfie e consulte nossos repositórios oficiais.
>
> Distribuições independentes podem exercer os direitos previstos nas licenças de software livre aplicáveis, inclusive redistribuição comercial legítima, desde que cumpram suas obrigações e não se apresentem falsamente como canais oficiais.

---

## 🎯 Para quem é este repositório?

Este repositório é voltado para **leitores e usuários finais** que desejam instalar, explorar e manter atualizadas as extensões de leitura de mangás, manhwas, manhuas e quadrinhos diretamente em seus aplicativos móveis compatíveis com o ecossistema **Mihon e forks**.

> [!NOTE]
> Se você é desenvolvedor e procura o **código-fonte em Kotlin** das extensões ou deseja contribuir tecnicamente com correções, acesse o repositório irmão de desenvolvimento:  
> ➡️ [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/Awerkori/manga-fonte-extensoes)

---

## 📲 Como Adicionar ao Mihon e forks

### Método 1: Instalação Automática (Recomendado)
Toque no link abaixo diretamente pelo navegador do seu celular Android para registrar o repositório de forma automática no aplicativo:

👉 [**Adicionar Repositório Automaticamente**](tachiyomi://add-repo?url=https%3A%2F%2Fraw.githubusercontent.com%2FAwerkori%2Fmanga-extensoes%2Frepo%2Findex.min.json)

---

### Método 2: Instalação Manual

1. No seu aplicativo (**Mihon e forks**), acesse **Mais** (ou Configurações) → **Configurações** → **Navegar** → **Repositórios de extensões**.
2. Toque no botão de adicionar (`+`).
3. Insira a URL do catálogo moderno de alta performance (Protobuf):

```
https://raw.githubusercontent.com/Awerkori/manga-extensoes/repo/index.pb
```

*(Opcional: para versões antigas de leitores ou compatibilidade legada com JSON puro, você também pode utilizar `https://raw.githubusercontent.com/Awerkori/manga-extensoes/repo/index.min.json`).*

---

### Método 3: Download Direto de APKs
Caso prefira instalar uma extensão específica manualmente:
- Acesse as [Releases](https://github.com/Awerkori/manga-extensoes/releases) deste repositório para baixar o arquivo `.apk` desejado e instalá-lo no Android (a integridade criptográfica dos pacotes pode ser conferida no manifesto `release-assets.json`).

---

## ⚙️ Como Funciona este Repositório

- **Automação Completa:** Os arquivos desta branch (`repo`) são gerados e mantidos por pipelines automatizados acionados a partir de [`manga-fonte-extensoes`](https://github.com/Awerkori/manga-fonte-extensoes).
- **Catálogo Otimizado (Protobuf v2):** O arquivo binário `index.pb` provê leitura ultrarrápida, serialização compacta e baixo consumo de dados móveis no seu aplicativo.
- **Assinatura e Segurança:** Todos os APKs disponibilizados são assinados digitalmente com chaves criptográficas consistentes, garantindo integridade e atualizações transparentes.

---

## 🛠️ Suporte e Pedidos de Extensões

Encontrou uma fonte de mangá que parou de funcionar ou deseja sugerir uma nova scan/site?

- 🎫 **Abrir solicitação oficial:** [Project Nox · Central de Pedidos](https://github.com/Awerkori/project-nox-requests)
- 📊 **Acompanhar status em tempo real:** [Project Nox · Tracker](https://awerkori.github.io/project-nox-tracker/)
- 🌐 **Ler pelo navegador:** [Project Nox · Site](https://manga.project-nox-awerkori.workers.dev)

---

## 🔗 Projetos Relacionados

- 💻 [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/Awerkori/manga-fonte-extensoes) — Código em Kotlin, automação e desenvolvimento.
- 🎬 [**Project Nox · Extensões de Anime**](https://github.com/Awerkori/anime-extensoes) — Catálogo de extensões de vídeo para Aniyomi e forks.
- 💻 [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/Awerkori/anime-fonte-extensoes) — Código-fonte e extractors de streaming.
- ⚙️ [**Project Nox · Importer**](https://github.com/Awerkori/project-nox-importer) — Ingestão contínua de catálogo para a plataforma web.
- 📊 [**Project Nox · Tracker**](https://awerkori.github.io/project-nox-tracker/) — Dashboard público de status.

---

## 🌟 Créditos e Reconhecimento

- **Felipe GFA** ([@FelipeGFA](https://github.com/FelipeGFA)): Responsável pela estruturação do ecossistema de compilação, engenharia dos scripts de catalogação em Protobuf v2 e suporte primordial às fontes brasileiras.
- **Keiyoushi** ([@keiyoushi](https://github.com/keiyoushi)): Especificação de arquitetura de catálogos v2 e ecossistema upstream de referência.
- Comunidade open-source de leitores e desenvolvedores independentes.

---

## ⚖️ Licença e Copyright

As contribuições originais do Project Nox e a organização do catálogo combinado são disponibilizadas sob os termos da **GNU Affero General Public License versão 3.0** (`AGPL-3.0-only`). Componentes herdados dos projetos Keiyoushi, Tachiyomi, Felipe GFA e demais autores upstream mantêm integralmente seus respectivos direitos autorais e licenças originais (notadamente Apache-2.0). A inclusão de código em um trabalho combinado compatível não transfere a titularidade intelectual ao Project Nox, não cancela as obrigações de atribuição da Apache 2.0, e o Project Nox não declara nem reivindica direitos exclusivos sobre código criado por terceiros. O regime aplicável a cada pacote binário respeita os componentes nele incorporados e as licenças correspondentes. Consulte o arquivo [LICENSE](LICENSE) para obter o texto integral inalterado da licença e o arquivo [NOTICE](NOTICE) para o inventário de autoria e termos legais.

```
Copyright (C) Felipe GFA
Copyright (C) Keiyoushi Contributors
Copyright (C) 2026 Project Nox Contributors & Awerkori
```

### 📦 Código-Fonte Correspondente e Rastreabilidade (AGPLv3 Seção 6)
Em cumprimento à Seção 6 da GNU AGPLv3, o código-fonte correspondente aos APKs distribuídos neste repositório está publicamente disponível em:  
➡️ [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/Awerkori/manga-fonte-extensoes)

- **Instruções e Receitas de Compilação:** Os scripts Gradle, configurações de build e pipelines de CI/CD estão mantidos de forma auditável e transparente no repositório de desenvolvimento irmão.
- **Rastreabilidade e Integridade:** Cada pacote possui identificador único (`pkg`), versão (`version`), código de versão (`code`) e verificação de integridade criptográfica SHA-256 no catálogo `release-assets.json`.
- **Ressalva de Proveniência Forense:** Extensões mantidas ativamente pelo Project Nox contam com rastreabilidade completa entre código-fonte, scripts e binários. Para os pacotes históricos incorporados do ecossistema upstream Keiyoushi, a rastreabilidade é assegurada por pacote, versão e árvore de código upstream, não se declarando rastreabilidade universal a commits individuais para binários pré-existentes sem evidência histórica direta.
- **Componentes de Terceiros, Atribuição e Regime dos APKs:** Os componentes herdados mantêm seus avisos de copyright e obrigações de atribuição sob a Apache License 2.0. As contribuições originais desenvolvidas pelo Project Nox são licenciadas sob a GNU AGPL versão 3.0. O regime de cada pacote binário (.apk) observa as licenças de seus respectivos componentes, sem declaração de exclusividade sobre código de terceiros.

### 🌐 Política Oficial de Distribuição
- **Gratuidade Oficial:** O Project Nox distribui oficialmente todos os seus APKs e catálogos de forma 100% gratuita para a comunidade.
- **Redistribuição Comunitária:** Incentivamos o compartilhamento comunitário e o espelhamento livre dos pacotes, sempre respeitando os créditos de autoria e os termos das licenças.
- **Liberdades sob a AGPL 3.0:** Em estrita conformidade com a GNU AGPLv3 (e Apache 2.0), não é imposta nenhuma cláusula proibindo redistribuição comercial por terceiros. A gratuidade oficial é prática direta do Project Nox, preservando integralmente os direitos legais de redistribuição garantidos pela licença.

### 📌 Interação Remota de Rede (GNU AGPLv3 Seção 13)
O Project Nox adota oficialmente a licença **GNU AGPL versão 3.0**. Em estrita conformidade com a Seção 13 da AGPLv3, caso uma versão modificada deste software seja operada em servidores ou instâncias acessíveis através de uma rede de computadores com interação remota de usuários, o operador deve oferecer a todos esses usuários a oportunidade de obter o Código-Fonte Correspondente (Corresponding Source) da versão modificada em execução, sem custos e através de meio habitual de disponibilização de software em rede.

### 🛡️ Proteção de Identidade e Marca (AGPLv3 Seção 7(e))
A concessão da licença de software livre refere-se estritamente ao código e aos binários. Ela **não concede** autorização ou licença de uso da marca, do nome "Project Nox" ou de logotipos oficiais para insinuar endosso, homologação ou representação oficial do projeto sem consentimento prévio por escrito.

### ⚖️ Isenção de Responsabilidade
O **Project Nox** disponibiliza apenas ferramentas de software livre para integração e leitura. Não controlamos, não hospedamos e não comercializamos arquivos de imagem de terceiros. Todo o conteúdo carregado através das extensões é fornecido diretamente pelas fontes externas públicas.
