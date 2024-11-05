# **APP Calculadora**

> Um aplicativo Android simples para realizar operações matemáticas básicas.

## 📱 Descrição

O **APP Calculadora** permite ao usuário realizar operações de soma, subtração, multiplicaçãoe divisão entre dois valores.
É ideal para cálculos rápidos e possui uma interface simples, intuitiva e com tema verde vibrante.

## 🔧 Funcionalidades

- [x] Entrada de dados (Valor A e Valor B)
- [x] Operações matemáticas:
  - Soma
  - Subtração
  - Multiplicação
  - Divisão (exibindo mensagem de erro para divisão por zero)
- [x] Exibição do resultado diretamente na interface

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para estrutura da interface
- [x] **EditText** para entrada de valores
- [x] **TextView** para exibição de texto e resultado
- [x] **Button** para cada operação matemática

## 🛠️ Como Rodar o Projeto

Para executar este projeto em seu ambiente de desenvolvimento local, siga os passos abaixo:

1. Clone o repositório:

    ```bash
    git clone https://github.com/Cav-lua/calculadora-app.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/calculadora
│   │   │   │   └── MainActivity.java       # Classe principal para as operações matemáticas
│   │   │   └── res
│   │   │       ├── layout
│   │   │       │   └── activity_main.xml   # Layout da tela principal
│   │   │       └── values
│   │   │           ├── strings.xml         # Strings usadas no app
│   │   │           ├── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do Gradle
└── README.md                               # Este arquivo
```
🎨 Design e Prototipagem
A interface do app foi criada usando ConstraintLayout para manter a simplicidade e a clareza em diferentes tamanhos de tela. A cor de fundo é verde (#06F03C), e os botões possuem um design padronizado e bem visível.

🖥️ Telas do Aplicativo
Tela Principal

Na tela principal, o usuário insere os valores desejados, escolhe a operação matemática desejada (SOMA, SUBTRAIR, DIVIDIR, MULTIPLICAR) e vê o resultado exibido logo abaixo.


![CalTela](https://github.com/user-attachments/assets/a528d888-7854-4d6c-ad99-0db2f18b39b0)


👨‍💻 Desenvolvedores
Cav-lua - Desenvolvedor - GitHub

📄 Licença
Este projeto está licenciado sob os termos da licença MIT.
