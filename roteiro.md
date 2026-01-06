# Roteiro do Portfólio — marcelomess

## TL;DR
Criar um portfólio público que destaque 5 projetos (fastapi_zero, goexpert, goexpert-client-server-api, freelancer-management-system, marcelomess), com READMEs ricos, assets, CI simples e deploy via GitHub Pages.

## Passos (ordem e estimativa)

1. **Escrever README raiz com banner, resumo e contatos** (3-4h)
   - Adicionar seção "Sobre" com título profissional e stack
   - Listar 5 projetos destacados com links
   - Incluir contatos (LinkedIn, e-mail, GitHub)
   - Adicionar comandos básicos de execução

2. **Criar pasta `assets/` e adicionar banner + screenshots** (1-2h)
   - Banner principal (1200x400px)
   - Screenshots de cada projeto (fastapi_zero, goexpert, client-server)
   - Diagramas de arquitetura (opcional)

3. **Atualizar README de fastapi_zero** (2-3h)
   - Descrição clara do projeto
   - Comandos Docker para executar
   - Screenshot da API/Swagger
   - Adicionar topics: `python`, `fastapi`, `api`, `rest`, `pytest`

4. **Atualizar README de goexpert** (2-3h)
   - Descrição do curso Full Cycle
   - Comandos de build/run
   - Diagrama ou snippet de código
   - Adicionar topics: `go`, `golang`, `fullcycle`, `backend`

5. **Atualizar README de goexpert-client-server-api** (2-3h)
   - Explicar arquitetura cliente/servidor
   - Exemplos de uso e testes
   - GIF demonstrando comunicação
   - Adicionar topics: `go`, `client-server`, `api`, `distributed-systems`

6. **Atualizar README de freelancer-management-system** (2-3h)
   - Descrição do sistema de gerenciamento de freelancers
   - Comandos Docker para executar
   - Screenshots da aplicação
   - Adicionar topics: `freelancer`, `management`, `system`, `backend`, `api`

7. **Atualizar README do repositório do portfólio (`marcelomess`)** (1-2h)
   - Expandir seção "Sobre"
   - Adicionar badges (build, license)
   - Incluir chamada para ação (CTA)

8. **Configurar GitHub Pages** (3-6h)
   - Escolher gerador: Jekyll (rápido) ou Astro/Next.js (flexível)
   - Criar `index.html` ou configurar Jekyll
   - Adicionar `homepage` no settings do repo
   - Configurar domínio customizado (opcional)

9. **Configurar CI básico (GitHub Actions)** (4-8h)
   - Criar `.github/workflows/ci.yml` para 2 repositórios
   - Lint + test + build para Python (fastapi_zero)
   - Lint + test + build para Go (goexpert projetos)
   - Adicionar badges de status nos READMEs

10. **Varredura por segredos no histórico** (1-3h)
   - Instalar e rodar `git-secrets` ou `gitleaks`
   - Verificar histórico de commits
   - Remover/rotacionar credenciais se encontradas (usar BFG Repo-Cleaner)

11. **Publicar e validar SEO** (1-2h)
    - Adicionar descrições nos repositórios
    - Configurar topics em todos os repos
    - Adicionar badges (build, coverage, license)
    - Testar links e navegação

## Checklist técnico (execução)

- [ ] Criar/editar `README.md` raiz
- [ ] Criar `assets/` com: `banner.png`, `screenshot-fastapi.png`, `screenshot-go.png`, `screenshot-freelancer.png`
- [ ] Atualizar READMEs dos 5 repositórios destacados (descrição, run, screenshot)
- [ ] Adicionar `topics` via GitHub UI (ex: go, python, fastapi, api)
- [ ] Configurar GH Pages e adicionar sitemap/robots
- [ ] Adicionar badges (build, coverage, license) nos READMEs
- [ ] Rodar `git-secrets`/`gitleaks` para checar credenciais no histórico
- [ ] Fazer commit e push das mudanças
- [ ] Validar site publicado em `https://marcelomess.github.io/marcelomess/`

## Conteúdo recomendado para READMEs de projeto

Cada README de projeto deve conter:

1. **Título + resumo de 1 linha**
2. **Badges** (build | coverage | license)
3. **Stack / Tecnologias** usadas
4. **Como rodar** (Docker / Make / comandos diretos)
5. **Screenshot / GIF** demonstrativo
6. **Status** do projeto e link para demo/docs

### Exemplo de estrutura:

```markdown
# Nome do Projeto

Descrição curta do que o projeto faz e por que é útil.

![Build](badge) ![Coverage](badge) ![License](badge)

## Stack
- Python 3.11 / Go 1.21
- FastAPI / Gin
- PostgreSQL / SQLite
- Docker

## Como rodar

```bash
docker build -t projeto .
docker run -p 8000:8000 projeto
```

## Screenshots

![Screenshot](assets/screenshot.png)

## Status
Projeto ativo | Em desenvolvimento | Completo
```

## Privacidade e segurança

⚠️ **Atenção:**
- **NÃO** publicar telefones/endereço pessoal
- Usar e-mail profissional ou formulário de contato
- Verificar commits por chaves/API tokens antes de publicar
- Remover histórico de credenciais se encontradas

## Próximos passos imediatos (hoje)

1. Preencher `README.md` raiz e criar `assets/` (3–4h)
2. Atualizar 1 README prioritário (fastapi_zero) e subir commit de teste (2–3h)
3. Adicionar topics aos repositórios via GitHub UI (15min)

## Recursos úteis

- **GitHub Pages**: https://pages.github.com/
- **Jekyll temas**: https://jekyll-themes.com/
- **Shields.io** (badges): https://shields.io/
- **Git-secrets**: https://github.com/awslabs/git-secrets
- **Gitleaks**: https://github.com/gitleaks/gitleaks
- **BFG Repo-Cleaner**: https://rtyley.github.io/bfg-repo-cleaner/

---

**Estimativa total**: 22–46 horas (dividir em sprints de 4–8h)

**Prioridade alta**: Passos 1, 2, 3 (README raiz + assets + 1 projeto)

**Prioridade média**: Passos 4, 5, 6, 10 (outros projetos + SEO)

**Prioridade baixa**: Passos 7, 8, 9 (GH Pages + CI + segurança)

---

Fim do roteiro.
