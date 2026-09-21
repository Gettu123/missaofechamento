# 🎯 Missão: Fecho de Rubricas

Um minijogo interativo desenvolvido em HTML, CSS e JavaScript desenhado para testar conhecimentos sobre auditoria, fecho de folha e conciliação. O projeto destaca-se pela utilização de um avatar animado em vídeo, com remoção de fundo verde (Chroma Key) em tempo real através da API Canvas, que reage dinâmica e emocionalmente às respostas do utilizador.

## ✨ Funcionalidades
* **Sistema de Quiz de Auditoria:** Cenários práticos sobre conciliação, regras de negócio e rastreabilidade de dados.
* **Gamificação Integrada:** Contagem de pontos, bónus de sequência (streak), sistema de vidas finitas e penalizações por dicas.
* **Avatar Interativo (Máquina de Estados):** O vídeo do personagem transita de forma fluida entre diferentes segmentos (Espera/Ocioso, Sucesso, Erro) consoante a ação do jogador.
* **Chroma Key via JS:** Processamento de pixéis em tempo real no *frontend* para tornar o fundo verde do vídeo transparente, sobrepondo-o à interface.
* **Totalmente Client-Side:** Não requer servidor backend ou base de dados para a jogabilidade principal.

## 📁 Estrutura de Ficheiros
Para que a aplicação funcione corretamente, a estrutura do repositório deve ser a seguinte:

```text
missao-fechamento/
├── index.html
└── assets/
    ├── 1000910734.mp4 (Vídeo da animação com fundo verde)
    └── marcelo_avatar.png (Imagem de fallback)
