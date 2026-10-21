# Agência Pixel · Informática Empresarial · 2º ADM · IEEL

<!-- Se o endereço abaixo não for o do seu site, edite só esta linha. -->
**Site:** https://charltonjulio-sudo.github.io/infoempresarial2ano/

**Formulário de entrega:** (cole aqui o link de edição do Google Forms, se quiser tê-lo à mão; ele só abre para a sua conta)

Site das aulas de design visual, slides institucionais e direitos autorais: guia de estudo, jogo valendo nota, aula no celular e área do professor.

## Para os alunos

As páginas abaixo ficam no endereço do site seguido do nome do arquivo. Exemplo: o jogo é o endereço do site + `jogo.html`.

| Página | Para que serve |
|---|---|
| Início (`index.html`) | Passo a passo, regras do jogo e avisos |
| Guia do Estagiário (`guia.html`) | Material de estudo, uma fase por aula |
| Jogo (`jogo.html`) | Treino valendo nota; no fim gera o placar e envia a nota |
| Aula no celular (`aula-aluno.html`) | Acompanhar a aula no próprio ritmo; cada bloco abre com o código que o professor passa em sala |

Use Chrome ou Firefox atualizados. O progresso do jogo fica salvo no navegador do aparelho.

## Arquivos

| Arquivo | O que é | Quem usa |
|---|---|---|
| `index.html` | Página inicial do site | Alunos |
| `guia.html` | Guia de estudo | Alunos |
| `jogo.html` | Jogo com as perguntas da unidade | Alunos |
| `aula-aluno.html` | Aula no celular | Alunos |
| `config.js` | Link do formulário de entrega usado pelo jogo. Vazio = o jogo pede a imagem do placar no Classroom | Professor (editar só aqui) |
| `professor.html` | Área do professor (conferência de notas, configuração do formulário, links da aula) | Professor |
| `aula-professor.html` | Painel do professor (controla os slides) | Professor |
| `aula-slides.html` | Slides para projetar (abrem pelo painel) | Professor |
| `aula-quadro.html` | Roteiro da aula no celular, para turmas sem TV | Professor |

As páginas do professor pedem senha para abrir. A senha não fica no repositório.

## Como atualizar

1. **Add file → Upload files** e arraste os arquivos novos (substituem os antigos com o mesmo nome).
2. **Commit changes**.
3. O site atualiza em 1 a 2 minutos. Se não mudar, recarregue com `Ctrl + F5`.

Não substitua o `config.js` depois de configurado, a menos que o formulário mude.

## Publicação (só na primeira vez)

**Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save.**
O endereço segue o padrão `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.
