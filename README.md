# Relatório de Estágio II — Arena90 (Futevôlei Regional)

Documentação do desenvolvimento do **Relatório Final de Estágio II**, elaborado a partir da base construída no Estágio I e expandido com os três eixos temáticos definidos para esta etapa. Este README resume o que foi produzido, as fontes utilizadas e como o trabalho pode ser continuado.

---

## 1. Contexto do projeto

A **Arena90** é um complexo esportivo e de lazer localizado na região do Anália Franco, zona leste de São Paulo, que já realiza um campeonato de futevôlei em sua própria instalação. A proposta do Estágio II consistiu em **ampliar esse campeonato para um evento regional entre escolas**, capaz de gerar demanda turística (visitantes, famílias, equipes de fora), e em estruturar tecnicamente essa expansão sob a ótica do Turismo.

A partir disso, foram definidos **três temas** de desenvolvimento, todos interligados como facetas de uma mesma proposta:

| Item | Tema | Foco |
|---|---|---|
| 4.1 | Planejamento e estruturação do campeonato regional de futevôlei | O campeonato como produto de turismo de eventos |
| 4.2 | Logística turística e hospitalidade das equipes participantes | Recepção, operação e hospitalidade das equipes/visitantes |
| 4.3 | Desenvolvimento de experiências e roteiros de turismo esportivo em São Paulo | Roteiro de visitas a atrativos esportivos (Museu do Futebol, Arenas, Museu do Rei Pelé) |

---

## 2. Arquivo final

**`RELATORIO_ESTAGIO_II_ARENA90.docx`** — versão consolidada, editada diretamente sobre o arquivo-base enviado pelo usuário (`RELATORIO_ESTAGIO_II_BASE.docx`), preservando toda a formatação, estilos e estrutura originais (estilos `Ttulo1`, `Ttulo2`, `MeuEstilo`).

### Estrutura completa do relatório (do que foi preenchido nesta conversa)

```
1  INTRODUÇÃO                                          (já existia)
2  CARACTERIZAÇÃO DA EMPRESA (2.1–2.4)                 (já existia)
3  O ESTÁGIO                                            ✅ preenchido
4  CONHECIMENTO E ADAPTAÇÃO AO CAMPO DE ESTÁGIO          ✅ preenchido
5  RELACIONAMENTO                                        ✅ preenchido
6  ÁREA DE ATUAÇÃO DO ESTAGIÁRIO                         ✅ preenchido
7  ATIVIDADES DESENVOLVIDAS PELO ESTAGIÁRIO
   4.1 Planejamento e Estruturação do Campeonato         ✅ desenvolvido
   4.2 Logística Turística e Hospitalidade                ✅ desenvolvido
   4.3 Experiências e Roteiros de Turismo Esportivo       ✅ desenvolvido (ABNT)
8  CONSIDERAÇÕES FINAIS                                   ✅ preenchido
   REFERÊNCIAS                                            ✅ atualizado (ABNT)
   ANEXOS                                                  (já existia / não alterado)
```

---

## 3. Biblioteca de fontes

A biblioteca teórica usada na fundamentação dos três temas está disponível em dois locais:

- **Google Drive** (22 arquivos `.docx`, usado nesta conversa para leitura): `https://drive.google.com/drive/folders/1BhPKRAZkXTGC9Yl7nBqAZOAqvB86CKGK`
- **GitHub** (22 arquivos `.md` + pasta `imagens/`): `https://github.com/tourguidebrazilian/estagio/tree/main/docs`

> **Atenção ao caminho no GitHub:** a pasta agora se chama `docs` (minúsculas). O endereço anterior, com `DOCS` (maiúsculas), retorna erro 404, pois o GitHub diferencia maiúsculas de minúsculas.

### 3.1 Análise do repositório GitHub (`docs/`)

O repositório foi reestruturado em relação à versão anterior (`DOCS/`, 21 arquivos `.docx`):

- **Formato:** os textos foram convertidos para Markdown (`.md`), com as figuras extraídas para `docs/imagens/` (112 arquivos). Isso torna as fontes legíveis e pesquisáveis, inclusive o livro de Lashley, que no Drive é um `.docx` baseado em imagens e não pôde ser lido.
- **Numeração:** os prefixos foram padronizados (`01`–`08` com zero à esquerda).
- **Duplicatas removidas:** `00 - Introducao...BOOK` (cópia de Getz), `12 - HATHER` (cópia de Gibson, com erro de digitação) e `99 - A_Experiencia_do_Turismo_Ecologico...` (cópia de Ruschmann).
- **Fontes novas:**
  - `94` e `95 - LASHLEY - Perspectiva para uma Mundo Globalizado BOOK` — *Em busca da hospitalidade* (Manole, 2004); os dois arquivos são **idênticos** (mesmo hash MD5).
  - `96 - Hospitalidade e Hospitabilidade_Conrad LASHLEY` — artigo de Lashley.
  - `95 - TRIGO e PANOSSO - Cenarios do Turismo Brasileiro_2009` — Aleph, 2009.
  - `97 - Turismo Contemporaneo Luiz Godoi TRIGO` — Cooper, Hall e Trigo (Elsevier/Campus).
- **Pontos de atenção no repositório:**
  - existem dois arquivos com o prefixo `95` (Lashley e Trigo/Panosso);
  - os arquivos `94` e `95 - LASHLEY` são duplicatas exatas;
  - o arquivo `10 - HALL, COOPER, THIMOTHY - Sport Tourism - Development` é, na verdade, o livro de **Higham e Hinch** (Hall, Cooper e Timothy são apenas os editores da série), o que é coerente com a referência ABNT usada no relatório.

### 3.2 Comparação Drive × GitHub

O GitHub **deixou de ser um espelho exato** do Drive:

| Situação | Arquivos |
|---|---|
| **Nos dois** (mesma obra) | Beni (3 obras), Santos, Marcellino, Weed, Ruschmann (2), Higham e Hinch (livro), Gibson (2), Hinch e Higham (2001), Getz (2), Boullón, Duxbury, Trigo (*Lazer e Educação*), Lashley (livro *Em busca da hospitalidade*) |
| **Só no GitHub** | Lashley — *Hospitalidade e Hospitabilidade* (`96`); Trigo e Panosso — *Cenários do Turismo Brasileiro* (`95`); *Turismo Contemporâneo* (`97`); pasta `imagens/` |
| **Só no Drive** (duplicatas) | `00 - Introducao...BOOK` (Getz), `12 - HATHER...Ativo` (Gibson), `99 - A_Experiencia...` (Ruschmann), `A Natureza do Espaco BOOK_Milton DANTOS` (Santos, com erro de digitação) |

**Conclusão:** nenhuma obra citada no relatório depende dos arquivos divergentes. Todas estão nos dois locais. O GitHub é hoje a versão mais completa e legível, com 3 fontes adicionais e o livro de Lashley acessível em texto.

### 3.3 Verificação das referências do relatório

Com o texto de Lashley agora legível no GitHub, foi possível conferir os dados que antes constavam apenas de memória:

- **Lashley e Morrison (2004):** confirmados editora (Manole, Barueri), 1ª edição brasileira de 2004, tradução de *In search of hospitality* e ISBN 978-85-204-4333-0. O sumário confirma a estrutura dos três domínios (social, privado e comercial), usada no item 4.2. Esses domínios estão no capítulo 1, de Lashley (p. 1–23).
- **Gibson (1998)** (*Sport Management Review*, v. 1, p. 45–76) e **Weed (2006)** (idrottsforum.org, 13/12/2006): confirmados nos próprios arquivos.
- **Duxbury:** o arquivo não traz o ano de publicação. O texto cita obras de 2021 e trata da pandemia de 2020, o que é compatível com 2021, mas convém conferir a ficha catalográfica do livro.
- **Getz:** os arquivos não trazem ano nem edição, e por isso a referência no relatório está sem esses dados. Convém completá-la com a edição usada.

Fontes efetivamente lidas e utilizadas na fundamentação:

| Autor(es) | Obra | Arquivo no GitHub (`docs/`) | Drive | GitHub | Usado em |
|---|---|---|:---:|:---:|---|
| GETZ, Donald | Estudos de eventos, gestão de eventos e turismo de eventos | `15 - GETZ - Introducao...BOOK.md` | ✅ | ✅ | 4.1, 4.2 |
| GETZ, Donald | Turismo de Eventos | `14 - GETZ - Turismo de Eventos_Donald.md` | ✅ | ✅ | catalogado |
| BENI, Mário Carlos | Sistema de Turismo – SISTUR | `01 - BENI - Sistema_do_Turismo_SISTUR...md` | ✅ | ✅ | 4.1 |
| BENI, Mário Carlos | Relações Públicas e Desenvolvimento Sustentável do Turismo | `02 - BENI - Relacoes Publicas...md` | ✅ | ✅ | 4.2 |
| BENI, Mário Carlos | Política e Planejamento Estratégico do Turismo | `03 - BENI - Politica e Planejamento...BOOK.md` | ✅ | ✅ | catalogado |
| HIGHAM, James; HINCH, Tom | Sport Tourism Development (3. ed., 2018) | `10 - HALL, COOPER, THIMOTHY - Sport Tourism - Development.md` | ✅ | ✅ | 4.1, 4.3 |
| HINCH, Thomas D.; HIGHAM, James E. S. | Turismo Esportivo: uma estrutura para pesquisa (2001) | `13 - HINCH & HIGHAM...md` | ✅ | ✅ | 4.3 |
| GIBSON, Heather J. | Turismo esportivo: uma análise crítica da pesquisa (1998) | `12 - HEATHER - ...Analise Critica_Gibson.md` | ✅ | ✅ | 4.3 |
| GIBSON, Heather J. | Turismo esportivo ativo: quem participa? | `11 - HEATHER - ...Ativo_Gibson.md` | ✅ | ✅ | catalogado |
| BOULLÓN, Roberto C. | Planejamento do Espaço Turístico (4. ed., 2006) | `16 - BOULLON - Planejamento de Espaco Turistico Urbano.md` | ✅ | ✅ | 4.2, 4.3 |
| LASHLEY, Conrad; MORRISON, Alison (org.) | Em busca da hospitalidade (2004) | `94` / `95 - LASHLEY - ...BOOK.md` | ⚠️ ilegível | ✅ | 4.2 |
| LASHLEY, Conrad | Hospitalidade e hospitabilidade | `96 - Hospitalidade e Hospitabilidade_Conrad LASHLEY.md` | ❌ | ✅ | disponível |
| WEED, Mike | Turismo esportivo e o desenvolvimento de eventos esportivos (2006) | `06 - WEED - Turismo Esportivo_Mike.md` | ✅ | ✅ | 4.3 |
| DUXBURY, Nancy (ed.) | Sustentabilidade cultural, turismo e desenvolvimento | `17 - DUXBURY - ...Nancy.md` | ✅ | ✅ | 4.3 |
| TRIGO, Luiz Gonzaga Godoi | Considerações sobre lazer e educação em sociedades pós-industriais | `18 - TRIGO - Consideracoes sobre Lazer e Educacao_LGG.md` | ✅ | ✅ | consultado |
| TRIGO, L. G. G.; PANOSSO NETTO, A. | Cenários do Turismo Brasileiro (2009) | `95 - TRIGO e PANOSSO...md` | ❌ | ✅ | disponível |
| COOPER, C.; HALL, C. M.; TRIGO, L. G. G. | Turismo Contemporâneo | `97 - Turismo Contemporaneo Luiz Godoi TRIGO.md` | ❌ | ✅ | disponível |
| MARCELLINO, Nelson Carvalho | Lazer e Sociedade | `05 - MARCELLINO - Lazer e Sociedade.md` | ✅ | ✅ | catalogado |
| RUSCHMANN, Doris | Impactos ambientais / A experiência do turismo ecológico | `07` e `08 - RUSCHMANN...md` | ✅ | ✅ | catalogado |
| SANTOS, Milton | A Natureza do Espaço | `04 - SANTOS - A Natureza do Espaco BOOK_Milton.md` | ✅ | ✅ | catalogado |

> As referências completas em padrão ABNT dos itens efetivamente citados estão na seção **REFERÊNCIAS** do relatório.
> O repositório pode ser citado no relatório como fonte pública de rastreabilidade das obras consultadas, se a banca exigir.

---

## 4. Metodologia de desenvolvimento adotada

1. **Leitura da biblioteca de fontes** no Google Drive indicado pelo usuário, mapeando qual obra fundamenta qual tema.
2. **Redação tema a tema** (4.1 → 4.2 → 4.3), cada um validado pelo usuário antes de seguir ao próximo.
3. **Triangulação teórica no item 4.3**: mais de um autor usado para sustentar a mesma afirmação (ex.: Boullón + Hinch/Higham para a dimensão espacial do roteiro; Weed + Gratton *apud* Higham/Hinch + Duxbury para justificar uma postura realista quanto à escala do evento).
4. **Citações em padrão ABNT** `(AUTOR, ano)` aplicadas de forma completa no item 4.3 e na lista de REFERÊNCIAS.
5. **Preenchimento das seções estruturais em branco** (O Estágio, Conhecimento e Adaptação, Relacionamento, Área de Atuação, Considerações Finais), mantendo coerência narrativa com os três temas e sem aparato teórico pesado (estilo alinhado ao da Introdução já existente no documento).
6. Todas as edições foram feitas **diretamente no XML do `.docx` original**, preservando estilos, numeração e formatação herdados do arquivo-base — sem recriar o documento do zero.
7. Cada etapa foi **validada visualmente** (conversão para PDF e inspeção página a página) antes de ser entregue.

---

## 5. Pendências / próximos passos sugeridos

- [ ] **Retrofit ABNT nos itens 4.1 e 4.2**: atualmente esses dois itens citam os autores (Getz, Beni, Boullón, Lashley etc.) apenas pelo sobrenome, sem `(AUTOR, ano)`, por terem sido escritos antes do pedido explícito de padrão ABNT. Recomenda-se uniformizar com o 4.3.
- [ ] Revisar/ajustar a **numeração automática dos capítulos** gerada pelo Word (ela já atribui números sequenciais únicos a cada `Título 1`, independentemente da subdivisão lógica 3.x) — confirmar com o orientador se esse é o padrão desejado pela banca.
- [ ] Validar com a Arena90 (ou com dados fictícios assumidos) informações operacionais específicas mencionadas no texto (ex.: nomes exatos de parcerias, datas, capacidade de público) antes da entrega final.
- [ ] **Corrigir a referência de Lashley** na seção REFERÊNCIAS: os três domínios da hospitalidade estão no capítulo 1, de Lashley, e podem ser referenciados no nível do capítulo.
- [ ] **Completar a referência de Getz** com ano e edição (os arquivos-fonte não trazem esses dados) e confirmar o ano da obra de Duxbury.
- [ ] **Limpar o repositório GitHub:** remover a duplicata `94`/`95 - LASHLEY` e renumerar um dos dois arquivos `95`.
- [ ] Conferir se a seção **ANEXOS** precisa de algum material de apoio (ex.: regulamento do campeonato, roteiro detalhado dia a dia).

---

## 6. Histórico de versões geradas nesta conversa

| Versão | Conteúdo adicionado |
|---|---|
| v2 | Item 4.1 (Planejamento e Estruturação do Campeonato) |
| v3 | Item 4.2 (Logística Turística e Hospitalidade) |
| v4 | Item 4.3 (Experiências e Roteiros, com ABNT) + lista de Referências |
| v5 | Seções estruturais: O Estágio, Conhecimento e Adaptação, Relacionamento, Área de Atuação, Considerações Finais |
| **Final** | `RELATORIO_ESTAGIO_II_ARENA90.docx` — versão consolidada e entregue |
