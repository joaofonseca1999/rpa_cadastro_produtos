# 🐍 Automação de Cadastro de Produtos com Python

## 📌 Descrição do Projeto
Este projeto demonstra como utilizar **Python** para automatizar tarefas repetitivas de cadastro de produtos em um sistema web.  
A automação é feita com a biblioteca **PyAutoGUI**, que controla o mouse e o teclado simulando ações humanas.  
A base de dados utilizada é um arquivo CSV contendo informações de diversos produtos, que são inseridos automaticamente no sistema.

---

## 🚀 Funcionalidades
- 🌐 Abertura automática do navegador e acesso ao sistema de login  
- 🔑 Realização de login com credenciais fornecidas  
- 📂 Leitura da base de dados `produtos.csv`  
- 📝 Preenchimento automático dos campos do formulário:  
  - Código do produto  
  - Marca  
  - Tipo  
  - Categoria  
  - Preço unitário  
  - Custo  
  - Observações (quando disponíveis)  
- 📤 Envio das informações ao sistema  
- 🔄 Repetição do processo até cadastrar todos os produtos  

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**  
- **Pandas** → leitura e manipulação da base de dados  
- **PyAutoGUI** → controle do mouse e teclado  
- **Time** → gerenciamento de pausas e sincronização  

---

## ⚙️ Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-automacao.git
   cd projeto-automacao
2. Instale as dependências:
    pip install pandas pyautogui
3. Certifique-se de que o arquivo  está na mesma pasta do script.
4. Execute o script:
   python automacao.py

---

⚠️ Observações Importantes
- 🖱️ As coordenadas de clique (x, y) variam conforme o monitor(conforme resolução de sua tela).
Utilize o script pegar_posicao.py para capturar as posições corretas antes de rodar a automação.
- 🔍 Recomenda-se testar com uma base reduzida (5–10 produtos) antes de executar com a lista completa.
- ⏱️ O tempo de execução depende da quantidade de produtos e do tempo de pausa configurado no PyAutoGUI

