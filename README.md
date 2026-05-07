# Chat.java

[![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)](https://www.java.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)

Um simples chat básico que guarda as informações por enquanto em um arquivo `.txt`.

## 📋 Descrição

Chat.java é uma aplicação de chat de linha de comando desenvolvida em Java que permite comunicação básica entre usuários. As mensagens são armazenadas em arquivos de texto para persistência de dados.

## 📁 Estrutura do Projeto

```
Chat.java/
├── README.md
├── src/
│   └── [Arquivos Java do projeto]
├── data/
│   └── *.txt (Arquivos de armazenamento de mensagens)
└── [Outros arquivos de configuração]
```

> **⚠️ Nota:** Os arquivos `.txt` na pasta `data/` são gerados automaticamente pela aplicação durante a execução.

## 🚀 Como Compilar e Executar

### Pré-requisitos
- Java 8 ou superior instalado
- Git (opcional, para clonar o repositório)

### Compilação
```bash
# Clone o repositório
git clone https://github.com/Neownkw1/Chat.java.git
cd Chat.java

# Compile o projeto
javac src/*.java -d bin/
```

### Execução
```bash
# Execute a aplicação
java -cp bin/ [MainClassName]
```

## 📖 Guia de Uso

1. **Inicie a aplicação** seguindo as instruções acima
2. **Escolha um nome de usuário** para sua sessão
3. **Digite suas mensagens** e pressione Enter para enviar
4. **Veja o histórico** de mensagens salvas no arquivo `.txt`
5. **Saia da aplicação** com o comando `exit` ou `quit`

### Exemplo de Uso
```
Digite seu nome: João
Bem-vindo, João!
> Olá pessoal!
> Como estão?
> exit

Mensagens salvas em: data/chat_messages.txt
```

## ⚙️ Funcionalidades

- ✅ Chat básico em linha de comando
- ✅ Armazenamento de mensagens em arquivo `.txt`
- ✅ Suporte a múltiplos usuários (sequencial)
- ✅ Histórico de conversas persistente

## ⚠️ Limitações Conhecidas

| Limitação | Descrição | Status |
|-----------|-----------|--------|
| Sem rede | Funciona apenas localmente (não é cliente/servidor) | Em análise |
| Sem criptografia | Mensagens armazenadas em texto puro | ⏳ Planejado |
| Sem autenticação | Qualquer usuário pode acessar o histórico | ⏳ Planejado |
| Sem interface gráfica | Interface apenas de linha de comando | 📋 Backlog |
| Sem timestamp | Mensagens não possuem data/hora | ⏳ Planejado |

## 🔄 Melhorias Futuras

- [ ] Implementar arquitetura cliente/servidor
- [ ] Adicionar timestamps às mensagens
- [ ] Criptografar dados armazenados
- [ ] Criar interface gráfica (Swing/JavaFX)
- [ ] Implementar banco de dados (MySQL/SQLite)
- [ ] Autenticação de usuários
- [ ] Salas de chat separadas
- [ ] Notificações em tempo real

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Descrição |
|-----------|--------|-----------|
| Java | 8+ | Linguagem de programação |
| File I/O | Built-in | Leitura/escrita de arquivos |

## 📝 Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

**Neownkw1** - [Perfil GitHub](https://github.com/Neownkw1)

## 💬 Suporte

Se encontrou problemas ou tem sugestões, abra uma [issue](https://github.com/Neownkw1/Chat.java/issues) no repositório.

---

**Última atualização:** 2026-05-07
