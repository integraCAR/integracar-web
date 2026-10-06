# integracar-web

Site institucional do projeto IntegraCAR, Integração do Cadastro Ambiental
Rural no Estado do Espírito Santo.

Endereço previsto: [integracar.agr.br](https://integracar.agr.br)

> **Estado atual:** planejado. Este repositório ainda não tem código.

---

## Sobre

O site vai reunir as informações sobre o projeto, os parceiros institucionais
e o acesso aos demais módulos do sistema.

Ele será servido no mesmo servidor (VPS) do sistema de gestão
(`integracar-gestao`) e do dashboard (`integracar-dashboard`), com roteamento
pelo nginx.

Hoje existe uma página de apresentação estática dentro do
`integracar-dashboard` (`src/index.html`) que pode servir de ponto de partida.

Documentação: [`integracar-docs/web`](https://github.com/integraCAR/integracar-docs/blob/main/web/README.md).

---

## Estrutura prevista

```
integracar-web/
├── public/
├── src/
└── README.md
```

---

## Repositórios relacionados

| Repositório | Descrição |
|---|---|
| [integracar-gestao](https://github.com/integraCAR/integracar-gestao) | Sistema web de gestão de processos, mesmo servidor (privado) |
| [integracar-dashboard](https://github.com/integraCAR/integracar-dashboard) | Painel Streamlit de análise de processos, mesmo servidor (privado) |
| [integracar-docs](https://github.com/integraCAR/integracar-docs) | Documentação técnica de todos os repositórios |

---

## Equipe Desenvolvedora

- Arthur Gonçalves
- Beatriz Ruela
- Cauã Marvila
- Eduardo Esquincalha
- Gabriela Marques
- Lucas Altoé
- Mikaela Cantalejo
- Murilo Cruz
- Pedro Almeida

---

## Projeto

Parceria: Idaf, Ifes e Seger
Vigência: 2024-2027
Organização: [integraCAR](https://github.com/integraCAR)
