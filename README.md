# 🌈 go-lolcat

[![Go Version](https://img.shields.io/github/go-mod/go-version/seu-usuario/go-lolcat)](https://go.dev/)
[![License](https://img.shields.io/github/license/seu-usuario/go-lolcat)](LICENSE)
[![Go Report Card](https://goreportcard.com/badge/github.com/seu-usuario/go-lolcat)](https://goreportcard.com/report/github.com/seu-usuario/go-lolcat)

Um clone colorido e moderno do clássico lolcat implementado em Go. Transforme sua saída de terminal em um arco-íris vibrante! 🎨

![Demo do go-lolcat](./docs/assets/demo.gif)

## 🚀 Características

- Coloração em arco-íris de texto no terminal
- Suporte a pipe de entrada (STDIN)
- Personalização de cores e animações
- Alta performance e baixo consumo de memória
- Cross-platform (Windows, Linux, macOS)

## 📋 Pré-requisitos

- Go 1.21 ou superior
- Terminal com suporte a cores ANSI

## 🛠️ Instalação

```bash
go install github.com/seu-usuario/go-lolcat@latest
```

## 💡 Uso

Uso básico:
```bash
go-lolcat arquivo.txt
```

Pipe com outros comandos:
```bash
echo "Hello, Rainbow World!" | go-lolcat
```

Opções disponíveis:
```bash
go-lolcat --help
```

## 🧪 Testes

```bash
go test -v ./...
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor, leia nosso [Guia de Contribuição](CONTRIBUTING.md) antes de enviar um Pull Request.

## 📝 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## About

### 💭 Motivação

Este projeto foi criado como parte do meu aprendizado em Go, inspirado pelo [lolcat original](https://github.com/busyloop/lolcat). O objetivo é fornecer uma implementação moderna e eficiente em Go, aproveitando as características da linguagem como concorrência e gestão eficiente de memória.

### 🎯 Objetivos do Projeto

- Aprender e demonstrar boas práticas de programação em Go
- Implementar um CLI moderno e eficiente
- Explorar manipulação de cores em terminal
- Praticar testes e documentação em Go

### 🏗️ Arquitetura

O projeto segue uma arquitetura limpa e modular:

```
go-lolcat/
├── cmd/           # Ponto de entrada do CLI
├── internal/      # Código interno do pacote
│   ├── color/     # Lógica de coloração
│   ├── input/     # Processamento de entrada
│   └── render/    # Renderização do output
├── pkg/           # Pacotes públicos reutilizáveis
├── docs/          # Documentação
└── test/         # Testes de integração
```

### 🛣️ Roadmap

- [x] Implementação básica
- [x] Suporte a pipes
- [ ] Animações personalizáveis
- [ ] Modo interativo
- [ ] Suporte a Unicode
- [ ] Otimizações de performance

## 📚 Recursos Adicionais

- [Documentação da API](docs/API.md)
- [Guia de Desenvolvimento](docs/DEVELOPMENT.md)
- [Notas de Release](CHANGELOG.md)

---
