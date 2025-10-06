# Desafio de Criptografia

Este projeto foi criado como parte de um desafio do curso 
O objetivo é demonstrar o funcionamento básico de criptografia e descriptografia de arquivos usando Python e a biblioteca `pyaes`.

---

## ⚙️ Como funciona

- O arquivo **`encrypter.py`** lê o conteúdo de `Arquivo.txt`, criptografa os dados usando o algoritmo **AES (modo CTR)** com uma chave fixa (`testeransomwares`) e salva o resultado em um novo arquivo chamado **`Arquivo.txt.lock`**.  
  Em seguida, o arquivo original (`Arquivo.txt`) é removido.

- O arquivo **`decrypter.py`** faz o processo inverso:  
  lê `Arquivo.txt.lock`, descriptografa o conteúdo com a mesma chave e recria o arquivo original `Arquivo.txt`.

---

## ▶️ Como usar

### 1. Criptografar
Execute o comando abaixo no terminal:
```bash
python encrypter.py
```

### 2. Descriptografar
Execute o comando abaixo no terminal:
```bash
python decrypter.py
```
