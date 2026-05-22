# TelePronto — IHC & UX

## Nome dos Alunos
- Seu nome
Fernando almeida de oliveira Braga RA :326132695

---

# Sobre o Projeto

O TelePronto é um aplicativo de atendimento médico remoto criado para reduzir filas em pronto-socorros físicos e facilitar consultas rápidas por vídeo para casos leves.

O aplicativo permite:
- Triagem inteligente
- Consulta imediata por vídeo
- Receitas digitais
- Alarmes de medicamentos
- Busca de farmácias próximas

---

# Análise de Acessibilidade

O design foi desenvolvido pensando em usuários debilitados, idosos ou com dificuldades momentâneas devido ao mal-estar.

## Soluções Utilizadas

### Fontes Grandes
Utilizamos textos maiores para facilitar a leitura em situações de visão turva.

### Botões Grandes
Os botões possuem áreas amplas de clique para ajudar usuários com dedos trêmulos ou dificuldade motora.

### Alto Contraste
As cores possuem contraste elevado para melhorar a visualização.

### Interface Simples
A interface possui poucos elementos visuais para evitar distrações e confusão.

### Navegação Clara
As funções principais ficam visíveis logo na tela inicial.

### Emergência Sempre Visível
O botão de emergência permanece acessível em todas as telas do aplicativo.

---

# Fluxo Crítico

## Caminho para iniciar uma consulta de urgência

1. O usuário abre o aplicativo.
2. Seleciona “Consulta Agora”.
3. Realiza a triagem rápida de sintomas.
4. Entra na fila virtual.
5. Aguarda atendimento médico.
6. Inicia a videochamada.
7. Recebe a receita digital após a consulta.

---

# Prevenção de Erros

Para evitar erros durante o atendimento:

- O botão “Encerrar Consulta” possui confirmação antes de fechar a chamada.
- Os botões principais ficam separados para evitar toques acidentais.
- O sistema apresenta feedback visual em todas as ações.
- Alertas aparecem antes de sair da consulta.
- Informações importantes ficam destacadas na tela.

---

# Desafio Extra

## Fluxo de Dependente

O aplicativo possui opção para alternar entre perfis de familiares.

Exemplo:
- Pai/mãe seleciona o perfil da criança.
- O sistema exibe informações pediátricas.
- A consulta infantil é iniciada normalmente.

---

## Modo Baixa Conexão

Quando a internet está instável:

- O aplicativo exibe aviso de conexão fraca.
- O vídeo pode ser desativado automaticamente.
- O áudio continua funcionando para manter o atendimento.
- O usuário recebe mensagem explicando a mudança.

---

# Tempo de Aula

- Mapeamento de Requisitos: 10 minutos
- Prototipagem no Miro: 40 minutos
- Subida no GitHub: 10 minutos

---

# Estrutura do Projeto

```txt
ihcux-tele-pronto/
│
├── prototipo/
│   ├── prototipo.png 

│   └── prototipo.pdf

│
└── README.md
