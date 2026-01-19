# 🚀 Projeto Flutter

Este é o ponto de partida do seu novo aplicativo incrível desenvolvido com Flutter! Este documento vai te guiar desde a instalação básica até a execução do projeto no VS Code.

---

## ⚠️ Aviso Importante: Instalação do SDK

Antes de rodar qualquer comando, você precisa ter o Flutter instalado na sua máquina.

1. **Baixe o SDK**
   O Flutter geralmente vem em um arquivo `.zip` no site oficial.

2. **Extraia**
   Coloque a pasta extraída em um local seguro, por exemplo:

   ```bash
   C:\src\flutter
   ```

3. **Variáveis de Ambiente**
   Adicione o caminho da pasta `bin` (dentro do Flutter) ao `Path` do seu sistema para que o terminal reconheça o comando `flutter`.

4. **Verificação**
   Abra o terminal e digite:

   ```bash
   flutter doctor
   ```

   Este comando dirá se falta instalar algo (como o Android Studio ou o VS Code).

---

## 🛠️ Comandos Essenciais no VS Code

Para abrir o terminal no VS Code, use o atalho `Ctrl + ``. Siga estes passos na ordem:

### 1. Obter as dependências

Sempre que baixar um projeto novo ou adicionar uma biblioteca, rode:

```bash
flutter pub get
```

### 2. Verificar dispositivos conectados

Para saber onde seu app vai rodar (Emulador ou Celular via USB):

```bash
flutter devices
```

### 3. Executar o projeto

Para compilar e abrir o app no dispositivo selecionado:

```bash
flutter run
```

### 4. Limpar o projeto

Se o projeto começar a dar erros estranhos de compilação, use:

```bash
flutter clean
```

---

## 💡 Atalhos de Ouro (Durante a Execução)

Enquanto o app estiver rodando pelo terminal, você pode usar estas teclas:

```bash
r   # Hot Reload: Atualiza as mudanças no código quase instantaneamente ⚡
R   # Hot Restart: Reinicia o app do zero, limpando o estado 🔄
q   # Para o app e fecha a execução ❌
```

---

## 📚 Recursos para Estudo

* [Escreva seu primeiro app Flutter](https://flutter.dev/docs/get-started/codelab)
* [Cookbook: Exemplos úteis](https://flutter.dev/docs/cookbook)
* [Documentação oficial do Flutter](https://flutter.dev/docs)

**Dica:** No VS Code, instale as extensões **Flutter** e **Dart**. Elas vão colorir seu código e ajudar a encontrar erros mais rápido!
