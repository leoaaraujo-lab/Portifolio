# Pagina Pessoal no GitHub Pages

Projeto de pagina pessoal estatica (HTML, CSS e JS) pronta para publicar no GitHub Pages.

## 1) Personalize os dados
Edite o arquivo `index.html` e troque:
- Nome
- Bio
- Projetos
- Links de email, GitHub e LinkedIn

## 2) Inicialize o Git e suba para o GitHub
No terminal, dentro desta pasta:

```bash
git init
git add .
git commit -m "feat: pagina pessoal inicial"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
```

## 3) Ative o GitHub Pages
No repositório no GitHub:
1. Entre em `Settings`
2. Clique em `Pages`
3. Em `Build and deployment`, selecione:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` e pasta `/ (root)`
4. Salve

Seu site ficará em:

```text
https://SEU_USUARIO.github.io/SEU_REPOSITORIO/
```

## 4) Recomendação de nome do repo
Se quiser URL curta, crie o repositório com nome:

```text
SEU_USUARIO.github.io
```

Nesse caso, a URL fica:

```text
https://SEU_USUARIO.github.io/
```
