# 🦸 API de Filmes da Marvel

API REST dedicada ao Universo Cinematográfico Marvel (MCU). Permite consultar filmes organizados por fase, buscar personagens, heróis e vilões, e cadastrar novos títulos ao catálogo. Dados incluem bilheteria, nota no IMDb, diretor, sinopse e muito mais sobre os filmes que definiram uma geração.

## 📋 Endpoints disponíveis

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| `GET` | `/filmes` | Lista todos os filmes do MCU (filtrável por fase e ano) |
| `POST` | `/filmes` | Cadastra um novo filme no catálogo |
| `GET` | `/filmes/{id}` | Busca os detalhes de um filme pelo ID |
| `GET` | `/filmes/{id}/personagens` | Lista os personagens que aparecem em um filme |
| `GET` | `/personagens` | Lista todos os personagens (filtrável por herói/vilão e time) |
| `GET` | `/personagens/{id}` | Busca os detalhes de um personagem pelo ID |

## 📄 Documentação

Acesse a documentação interativa completa em:

🔗 **[https://SEU_USUARIO.github.io/filmes-marvel](https://SEU_USUARIO.github.io/filmes-marvel)**

## 🚀 Pipeline CI/CD

O repositório conta com pipeline automatizado via GitHub Actions que:

1. **Valida** o contrato OpenAPI com o Spectral (garante qualidade da especificação)
2. **Publica** a documentação HTML gerada com Redoc no GitHub Pages

[![CI/CD Status](https://github.com/SEU_USUARIO/filmes-marvel/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/SEU_USUARIO/filmes-marvel/actions/workflows/ci-cd.yml)

## 🛠️ Tecnologias

- **Especificação**: OpenAPI 3.0.3
- **Validação**: Spectral CLI
- **Documentação**: Redoc
- **Deploy**: GitHub Pages
- **CI/CD**: GitHub Actions
