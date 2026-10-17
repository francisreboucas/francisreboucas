## Francis Rebouças

Desenvolvedor de software em Belo Horizonte (MG). Trabalho com **backend, integração de sistemas e arquitetura**: ERP e SaaS, refatoração de sistemas legados, APIs transacionais e, cada vez mais, ferramentas de engenharia (CAD/BIM) e camadas de IA via **Model Context Protocol (MCP)**.

```text
backend     Go · PHP (Laravel) · Python · Node.js / TypeScript
dados       PostgreSQL · modelagem relacional · otimização de consultas
integração  REST · webhooks · sincronização transacional com ERP · MCP
desktop     Python + Qt (PySide6) · OpenGL (moderngl) · Rust (FFI/CLI)
infra       Docker · GCP (Artifact Registry) · GitLab CI/CD · Nx Cloud
baixo nível C++ · firmware / sistemas embarcados
domínio     ERP · SaaS · CAD/paisagismo · Revit/BIM · QGIS
```

### Em destaque

**[LeafDraw](https://github.com/francisreboucas/leafdraw)** — CAD para projeto de paisagismo, em beta (`v0.1.0-beta.3`).

- Núcleo de modelo separado da interface e testado com `pytest`: entidades imutáveis (linha, polilinha, arco, cota, hachura, planta), unidades em metros, pilha de undo e sinais
- Geometria com transformações afins, interseções e tesselação; offset e contorno de hachura com Shapely
- Viewport 2D + vista 3D em OpenGL 3.3 (moderngl) sobre PySide6
- Importação/exportação DXF com ezdxf e conversor DWG próprio em **Rust**
- Folhas de impressão com escala, carimbo e exportação para PDF
- Empacotamento Windows: PyInstaller (modo pasta, DLLs do Qt substituíveis conforme a LGPL) + Inno Setup, com `--smoke-test` automatizado do pacote

`Python` `PySide6` `moderngl` `Shapely` `ezdxf` `Rust` `pytest` `PyInstaller`

**[filter-sort-ux](https://github.com/francisreboucas/filter-sort-ux)** — skill para agentes de IA com um playbook de filtros e ordenação em listas corporativas (chips, cabeçalhos ordenáveis, padrões enterprise), com fontes rastreáveis.

**[Cidades-e-Estados](https://github.com/francisreboucas/Cidades-e-Estados)** — base de cidades e estados do Brasil em UTF-8.

### Atualmente

- **Gestão de projetos:** refatorando a arquitetura, as métricas de time-tracking e construindo uma camada MCP para expor o domínio a agentes de IA
- **ERP e legado:** arquitetura de APIs, validação de regras de negócio e sincronização de dados transacionais com plataformas ERP (ex.: integrações Asaas e ArchiSnapper)
- **Pesquisa:** QGIS + Mapflow AI, pipelines com Nx Cloud e GCP Artifact Registry

### Contato

[francisreboucas.com.br](https://francisreboucas.com.br)

<details>
<summary><b>English</b></summary>

<br>

Software developer based in Belo Horizonte, Brazil. I work on **backend, systems integration and architecture**: ERP and SaaS, legacy refactoring, transactional APIs, and increasingly engineering tools (CAD/BIM) and AI layers built on the **Model Context Protocol (MCP)**.

**Featured — [LeafDraw](https://github.com/francisreboucas/leafdraw):** a landscape-design CAD app (beta). UI-independent, pytest-covered model core with immutable entities and an undo stack; affine geometry, intersections and hatch boundaries (Shapely); 2D drafting plus a 3D OpenGL 3.3 view (moderngl) on PySide6; DXF I/O via ezdxf and a custom DWG converter written in Rust; print sheets to PDF; Windows packaging with PyInstaller + Inno Setup and an automated smoke test.

**Currently:** refactoring a project-management platform (architecture, time-tracking metrics, MCP layer for AI agents); API architecture and transactional data sync with ERP platforms; researching QGIS + Mapflow AI and cloud pipelines with Nx Cloud and GCP Artifact Registry.

**Stack:** Go, PHP/Laravel, Python, Node.js/TypeScript, PostgreSQL, Qt/PySide6, OpenGL, Rust, C++/embedded, Docker, GCP, GitLab CI/CD.

</details>
