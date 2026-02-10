🚀 NOC Master Automation
📌 Objetivo da Aplicação
Esta ferramenta foi desenvolvida para otimizar o fluxo de trabalho dos analistas do NOC, reduzindo o tempo de registro de incidentes e automatizando tarefas repetitivas de telefonia (Genesys). A automação elimina o erro humano na transcrição de dados e garante a padronização do Banco de Dados (Excel/BI).

🛠️ Funcionalidades Principais
- Visão Computacional (CV2): Identifica e interage automaticamente com botões do sistema Genesys (Atender/Desligar/Teclado).
- Captura Inteligente: Workflow semi-automático (F9/F10) que captura dados do clipboard e preenche o formulário instantaneamente.
- Persistência de Dados: Gravação direta em Excel respeitando a formatação e estilos das linhas anteriores.
- Interface Custom: UI moderna em modo Dark feita com customtkinter.

🚀 Como Instalar e Usar:
1. Clone o repositório ou baixe o ZIP.
2. Configuração Inicial: Abra o arquivo config.ini e altere o campo nome_analista para o seu nome.
3. Instalação: Execute o arquivo setup.bat. Ele instalará todas as bibliotecas necessárias automaticamente.
4. Imagens: Certifique-se de que os prints dos botões (botao_responder.png, etc.) estão na pasta assets.
5. Execução: Rode o comando python main.py.

⌨️ Atalhos de Operação
F9: Inicia novo registro (limpa campos).
F10: Repete dados fixos (Equipe/Crit/Orig) para alertas em massa.
CTRL + S: Salva no Excel da operação.
ESC: Desliga a chamada ativa no Genesys.
