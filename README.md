# Quiz de Curiosidades em Python

Um jogo de perguntas e respostas interativo desenvolvido em Python, utilizando princípios de Programação Orientada a Objetos para testar seus conhecimentos sobre curiosidades do mundo.

## Arquitetura do Projeto

**Componentes Principais**
- `main.py`: Controlador principal que orquestra o fluxo do jogo
- `question_model.py`: Classe modelo para estruturação das questões
- `quiz_brain.py`: Gerenciador do quiz com lógica de pontuação e validação
- `data.py`: Banco de dados com questões predefinidas

## Características Técnicas

**Padrões de Projeto**
- Implementação do padrão MVC (Model-View-Controller)
- Encapsulamento de dados com classes Python
- Sistema modular para fácil expansão

**Funcionalidades Avançadas**
- Sistema de pontuação em tempo real
- Validação case-insensitive das respostas
- Feedback detalhado após cada resposta
- Gerenciamento automático de progresso

## Banco de Questões

O projeto inclui 12 questões curiosas e interessantes sobre diversos temas:
- Biologia e anatomia humana
- Curiosidades sobre animais
- Fatos históricos
- Leis inusitadas
- Tecnologia e empresas famosas

## Instruções de Instalação

1. Requisitos do Sistema:
```bash
python >= 3.6
git
```

2. Configuração do Ambiente:
```bash
git clone https://github.com/Brassolotto/quiz-game.git
cd quiz-game
python main.py
```

## Guia de Desenvolvimento

**Para Adicionar Novas Questões**
```python
# Formato em data.py
question_data.append({
    "text": "Sua nova pergunta aqui",
    "answer": "True/False"
})
```

## Recursos Técnicos

**Classes e Métodos Principais**
- `QuizBrain`: Gerencia a lógica do quiz
  - `still_has_questions()`: Controle de fluxo
  - `next_question()`: Gerenciamento de questões
  - `check_answer()`: Validação de respostas

## Planos Futuros

- Implementação de categorias de perguntas
- Sistema de ranking
- Interface gráfica com Tkinter
- Modo multiplayer
- Banco de dados expansível via API

## Licença e Contribuições

Este projeto está sob licença MIT e aceita contribuições via Pull Requests para:
- Novas funcionalidades
- Correções de bugs
- Melhorias de documentação
- Adição de novas questões
