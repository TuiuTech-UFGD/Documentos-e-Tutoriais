<p align="center">
  <img src="assets/logo-tuiutech.png" alt="Logo TuiuTech" width="220">
</p>

<h1 align="center">TuiuTech · Documentos e Tutoriais</h1>

<p align="center">
  Base de conhecimento do grupo de robótica <strong>TuiuTech</strong> da<br>
  <strong>Universidade Federal da Grande Dourados (UFGD)</strong>
</p>

---

## Sobre este repositório

Este é o espaço compartilhado de **todos os membros da TuiuTech** para publicar e consultar documentos, tutoriais e materiais de referência do grupo.

A ideia é que o conhecimento produzido pela equipe não se perca entre conversas, pastas pessoais e trocas de gestão: aprendeu algo, resolveu um problema ou montou algo novo? Documente aqui para quem vier depois.

## O que você encontra aqui

| Pasta | Conteúdo |
|---|---|
| [`tutoriais/`](tutoriais/) | Passo a passos práticos: montagem, programação, uso de ferramentas e equipamentos |
| [`documentos/`](documentos/) | Regimentos, atas, relatórios, planejamentos e documentos institucionais |
| [`referencias/`](referencias/) | Datasheets, manuais, artigos e links úteis |
| [`projetos/`](projetos/) | Documentação técnica dos projetos e robôs do grupo |
| [`onboarding/`](onboarding/) | Material de boas-vindas para novos membros |
| [`templates/`](templates/) | Modelos para escrever novos tutoriais e documentos |
| [`assets/`](assets/) | Imagens, diagramas e arquivos usados nos documentos |

### Organização sugerida dos tutoriais

```
tutoriais/
├── eletronica/        # Solda, multímetro, circuitos, sensores, atuadores
├── programacao/       # Arduino, ESP32, Python, ROS, controle
├── mecanica/          # Modelagem 3D, impressão 3D, corte, montagem
└── ferramentas/       # Git, GitHub, softwares e ambientes de desenvolvimento
```

## Novo por aqui?

Comece pela pasta [`onboarding/`](onboarding/). Lá estão as primeiras informações sobre o grupo, como funcionam as equipes e por onde começar a estudar.

## Como contribuir

Qualquer membro da organização pode propor conteúdo novo ou correções.

1. **Crie uma branch** a partir da `main` com um nome descritivo:
   ```bash
   git checkout -b tutorial/sensor-ultrassonico
   ```
2. **Escreva seu conteúdo** em Markdown (`.md`), de preferência usando um modelo da pasta [`templates/`](templates/).
3. **Coloque imagens** em `assets/` (ou numa subpasta `img/` ao lado do seu arquivo) e referencie com caminho relativo.
4. **Faça commit e push**:
   ```bash
   git add .
   git commit -m "Adiciona tutorial de sensor ultrassônico HC-SR04"
   git push origin tutorial/sensor-ultrassonico
   ```
5. **Abra um Pull Request** no GitHub descrevendo o que foi adicionado. Outro membro revisa antes de entrar na `main`.

> Não sabe usar Git? Tudo bem! Você também pode criar e editar arquivos direto pelo site do GitHub (botão **Add file** ou ícone de lápis) e abrir o Pull Request por lá.

### Boas práticas

- **Nomes de arquivos** em minúsculas, sem acentos e com hífens: `controle-pid-motor-dc.md`
- **Um assunto por arquivo**: tutoriais curtos e focados são mais fáceis de achar e manter
- **Inclua data e autor** no início do documento
- **Liste materiais e versões** usadas (placa, biblioteca, software), porque elas mudam com o tempo
- **Prefira texto a prints de código**: código em bloco pode ser copiado
- **Cite as fontes** quando usar material de terceiros
- **Nada de senhas, tokens ou dados pessoais** nos arquivos

### Estrutura básica de um tutorial

```markdown
# Título do tutorial

**Autor(a):** Nome · **Data:** AAAA-MM-DD · **Nível:** Iniciante / Intermediário / Avançado

## Objetivo
O que a pessoa vai conseguir fazer ao final.

## Materiais
- Item 1
- Item 2

## Pré-requisitos
Conhecimentos ou tutoriais que convém ver antes.

## Passo a passo
1. ...
2. ...

## Problemas comuns
Erros frequentes e como resolver.

## Referências
- Links e materiais consultados
```

## Dúvidas e sugestões

- Encontrou um erro ou tem uma ideia de tutorial? Abra uma [**issue**](../../issues).
- Para outros assuntos, fale com a coordenação do grupo.

---

<p align="center">
  Feito pela equipe <strong>TuiuTech</strong> · UFGD · Dourados - MS
</p>