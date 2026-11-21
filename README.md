<p align="center">
  <img src="https://raw.githubusercontent.com/ProjectNox-org/.github/main/assets/brand/nox-emblem.webp" alt="Emblema oficial do Project Nox" width="96" />
</p>

<h1 align="center">Project Nox · Extensões de Mangá</h1>

<p align="center">
  Catálogo oficial de extensões de mangá para <strong>Mihon e aplicativos compatíveis</strong>.
</p>

<p align="center">
  <strong>Distribuição oficial 100% gratuita</strong> · Não pague por instalações ou atualizações oferecidas como serviço oficial do projeto.
</p>

## Como instalar

### Opção 1: Instalação automática (Android)

O GitHub bloqueia links que abrem aplicativos diretamente a partir do README. Para adicionar o catálogo com um toque pelo navegador do seu celular Android, acesse a página oficial de instalação:

[**Adicionar catálogo ao Mihon pelo portal oficial**](https://projectnox-org.github.io/extensoes/#mihon)

Se o aplicativo não abrir automaticamente ou o seu fork não reconhecer o link, use a instalação manual abaixo.

### Opção 2: Instalação manual (copiar e colar)

1. Abra o **Mihon** (ou fork compatível) e vá em **Mais** → **Configurações** → **Navegar** → **Repositórios de extensões** *(em alguns forks, acesse **Configurações → Navegar**)*.
2. Toque em **Adicionar** (`+`).
3. Copie e cole o endereço abaixo:

```text
https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/index.pb
```

4. Confirme e volte à aba **Navegar** → **Extensões** para instalar as fontes desejadas.

<details>
<summary>Meu aplicativo deu erro ao importar <code>index.pb</code> (formatos JSON para clientes antigos ou forks)</summary>

O arquivo `index.pb` (Protobuf) é o padrão atual. Caso seu aplicativo seja antigo ou exija JSON, use uma das URLs abaixo (mantidas atualizadas automaticamente):

- **JSON compacto** *(também usado no link automático `tachiyomi://`)*:
  ```text
  https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/index.min.json
  ```
- **JSON completo**:
  ```text
  https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/index.json
  ```

</details>

<details>
<summary>Alternativa: baixar o APK de uma extensão individual</summary>

Um `.apk` de extensão adiciona apenas uma fonte específica sem precisar registrar o catálogo inteiro. Para utilizá-lo, já é necessário ter o **Mihon** (ou aplicativo compatível) instalado no Android — instalar apenas a extensão não cria um leitor independente.

- Baixe somente pelos canais oficiais em [**Releases**](https://github.com/ProjectNox-org/manga-extensoes/releases) (os hashes SHA-256 dos pacotes estão disponíveis em [`release-assets.json`](release-assets.json)).

</details>

## O que são as extensões?

- **O catálogo é apenas a lista de fontes:** adicionar o repositório permite que o aplicativo encontre as extensões do Project Nox, mas não instala nenhuma fonte automaticamente.
- **Você escolhe o que instalar:** após adicionar o catálogo, abra a aba **Extensões** no aplicativo, procure as fontes desejadas e toque em instalar.
- **Conteúdo de terceiros:** cada extensão conecta o aplicativo diretamente a sites públicos de mangás, manhwas e quadrinhos.

## Atualizações e migração

Novas versões das extensões e adições ao catálogo aparecem diretamente na aba **Extensões** do aplicativo sempre que você atualizar a lista.

<details>
<summary>Já utilizava o repositório antigo (<code>Awerkori</code>)?</summary>

Os endereços antigos sob `Awerkori/manga-extensoes` continuam ativos via redirecionamento do GitHub e as assinaturas dos APKs não foram alteradas.

Para migrar para a URL oficial da organização:

1. **Adicione o repositório `ProjectNox-org` antes de remover o antigo.**
2. Caso utilize um fork afetado e alguma extensão apareça como *Obsoleta*, reinicie o aplicativo para recarregar a lista.

</details>

## Suporte

Encontrou uma fonte que parou de carregar capítulos ou quer pedir uma nova extensão?

- **Central de Pedidos ([`project-nox-requests`](https://github.com/ProjectNox-org/project-nox-requests)):** abrir pedidos de novas extensões e relatar problemas.
- **Tracker ([Project Nox Tracker](https://projectnox-org.github.io/project-nox-tracker/)):** consultar e acompanhar o status das solicitações.

## Informações técnicas

- **Código-fonte e compilação:** os pacotes desta branch (`repo`) são compilados, assinados digitalmente com chaves consistentes e publicados automaticamente a partir de [`manga-fonte-extensoes`](https://github.com/ProjectNox-org/manga-fonte-extensoes).
- **Arquivos publicados:** [`index.pb`](https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/index.pb) (Protobuf v2 principal), [`index.json`](https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/index.json), [`index.min.json`](https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/index.min.json), [`repo.json`](https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/repo.json) e [`release-assets.json`](https://raw.githubusercontent.com/ProjectNox-org/manga-extensoes/repo/release-assets.json) (verificação SHA-256 dos APKs nas Releases).

## Projetos relacionados

- [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/ProjectNox-org/manga-fonte-extensoes) — Código em Kotlin, automação de build e desenvolvimento.
- [**Project Nox · Extensões de Anime**](https://github.com/ProjectNox-org/anime-extensoes) — Catálogo oficial de extensões de anime para Aniyomi e forks.
- [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/ProjectNox-org/anime-fonte-extensoes) — Código-fonte e extractors das extensões de anime.

## Créditos

- **Felipe GFA** ([@FelipeGFA](https://github.com/FelipeGFA)): estruturação do ecossistema de compilação, engenharia dos scripts de catalogação em Protobuf v2 e suporte às fontes brasileiras.
- **Keiyoushi** ([@keiyoushi](https://github.com/keiyoushi)): especificação da arquitetura de catálogos v2 e ecossistema upstream de referência.
- **Javier Tomás / Tachiyomi** e demais colaboradores históricos do ecossistema open-source e do Project Nox.

## Licenciamento e informações legais

- **Código-fonte correspondente (AGPLv3, Seção 6):** o código-fonte, receitas Gradle e workflows dos APKs distribuídos aqui estão disponíveis em [`ProjectNox-org/manga-fonte-extensoes`](https://github.com/ProjectNox-org/manga-fonte-extensoes). Extensões mantidas ativamente pelo Project Nox possuem rastreabilidade entre código, scripts e binários; pacotes históricos incorporados do ecossistema Keiyoushi mantêm rastreabilidade por pacote, versão e árvore upstream, sem declarar rastreabilidade universal a commits individuais para binários legados sem evidência direta.
- **Licença dos pacotes e do catálogo:** contribuições originais do Project Nox e a organização do catálogo combinado seguem a **GNU Affero General Public License v3.0** (`AGPL-3.0-only`, [`LICENSE`](LICENSE)). Componentes herdados de Keiyoushi, Tachiyomi, Felipe GFA e demais autores mantêm integralmente seus copyrights e licenças originais (notadamente **Apache License 2.0**), sem reivindicação de exclusividade pelo Project Nox sobre código de terceiros. O regime jurídico de cada APK observa os componentes efetivamente incorporados.
- **Gratuidade e redistribuição:** o Project Nox distribui oficialmente seus catálogos e APKs de forma gratuita, preservando as liberdades de redistribuição previstas na GNU AGPLv3 e na Apache 2.0.
- **Rede, marca e isenção de responsabilidade:** nos termos da Seção 13 da AGPLv3, quem operar versão modificada com interação remota de rede deve disponibilizar o Código-Fonte Correspondente; conforme a Seção 7(e) da AGPLv3, a licença de software não autoriza usar os nomes ou marcas "Project Nox", "Awerkori" ou de terceiros para sugerir endosso oficial. O Project Nox fornece apenas software livre de integração e não hospeda nem distribui conteúdos de terceiros.

Consulte [`LICENSE`](LICENSE) e [`NOTICE`](NOTICE) para o texto integral da licença e o inventário completo de atribuições.

```text
Copyright (C) Felipe GFA
Copyright (C) Keiyoushi Contributors
Copyright (C) 2026 Project Nox Contributors & Awerkori
```
