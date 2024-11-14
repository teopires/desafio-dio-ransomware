# 🔒 Projeto de Criptografia de Arquivos

Este projeto Python demonstra como criptografar e descriptografar arquivos de maneira eficiente. Ideal para quem deseja aprender conceitos de criptografia simétrica e aplicá-los para proteger arquivos pessoais de forma segura.

## 🗂 Estrutura do Projeto

- `encrypter.py`: Script para criptografar arquivos.
- `decrypter.py`: Script para descriptografar arquivos previamente criptografados.
- `README.md`: Instruções e detalhes do projeto.

## 🎯 Objetivo

Este projeto foi desenvolvido para oferecer uma solução de criptografia básica, onde você pode criptografar arquivos com uma chave secreta e posteriormente restaurá-los. A ideia é compreender o funcionamento básico da criptografia simétrica.

## 🚀 Passo a Passo de Uso

### 1. Clone o Repositório

Primeiro, faça o clone do projeto para sua máquina local:

bash
git clone https://github.com/seu-usuario/nome-do-projeto.git
cd nome-do-projeto

2. Instale Dependências
Este projeto utiliza a biblioteca cryptography. Instale-a com:

bash
Copiar código
pip install cryptography
3. Geração de Chave de Criptografia 🔑
Para iniciar, gere uma chave de criptografia. Esta chave será usada para proteger seus arquivos.

bash
Copiar código
python encrypter.py --generate-key
4. Criptografando um Arquivo 🔐
Escolha o arquivo que deseja criptografar e execute o comando abaixo. Certifique-se de que a chave foi gerada e está acessível.

bash
Copiar código
python encrypter.py --encrypt arquivo.txt
💡 Dica: Use uma senha ou frase secreta forte para proteger a chave.

5. Descriptografando o Arquivo 🔓
Para restaurar o arquivo criptografado, use o seguinte comando. Certifique-se de ter a chave gerada disponível.

bash
Copiar código
python decrypter.py --decrypt arquivo.txt.enc



