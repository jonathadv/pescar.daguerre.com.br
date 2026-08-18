---
title: "Exercícios de Aula"
date: 2023-09-12T16:25:00-03:00
draft: false
---



<a href="/" title="Voltar para Home Pescar"><i class="fa fa-arrow-circle-o-left"></i><b>Voltar para Home Pescar</b></a>


<details>
<summary>Exercícios de interface gráfica (GUI)</summary>

## 1 - Cinnamon, janelas e arquivos

Siga os passos abaixo no seu computador:

1. **Crie a estrutura do exercício**:
   Dentro da pasta `Documentos`, crie uma pasta chamada `Exercicio 01` e, dentro dela, crie as pastas:

   * `Textos`
   * `Imagens`
   * `Backup`

2. **Crie um arquivo de texto**:
   Dentro da pasta `Textos`, crie o arquivo `aluno.txt` contendo:

   * Seu nome completo
   * A data de hoje
   * Uma frase sobre o que você aprendeu no Linux Mint

3. **Copie e renomeie um arquivo**:
   Copie `aluno.txt` para a pasta `Backup` e renomeie a cópia para `aluno-backup.txt`.

4. **Exclua e restaure um arquivo**:
   Exclua `aluno-backup.txt` e, utilizando a Lixeira, restaure o arquivo para seu local original.

5. **Organize as janelas**:
   Abra a pasta `Textos` em uma janela e a pasta `Backup` em outra. Organize as duas janelas para que cada uma ocupe metade da tela.

6. **Registre o resultado**:
   Tire um screenshot mostrando as duas janelas lado a lado e salve-o dentro da pasta `Imagens`.

7. **Compacte o exercício**:
   Compacte toda a pasta `Exercicio 01` em um arquivo chamado `exercicio01.zip`.

8. **Envie o exercício**:
   Envie `exercicio01.zip` para `jonatha@daguerre.com.br` com o assunto:

   `NOME DO ALUNO - Exercício 01 - Cinnamon`

   Substitua `NOME DO ALUNO` pelo seu nome completo.


---

## 2 - Configurando o computador

Siga os passos abaixo no seu computador:

1. **Crie a pasta do exercício**:
   Dentro de `Documentos`, crie uma pasta chamada `Exercicio 02`.

2. **Personalize a área de trabalho**:
   Altere o plano de fundo para uma paisagem natural e configure a área de trabalho para exibir apenas:

   * Computador
   * Pasta Pessoal
   * Lixeira

3. **Altere as configurações do mouse**:
   Aumente a velocidade do ponteiro do mouse e teste a nova configuração.

4. **Altere as configurações de energia**:
   Configure o computador para desligar a tela após **15 minutos** de inatividade.

5. **Registre informações do computador**:
   Crie o arquivo `sistema.txt` dentro de `Exercicio 02` e registre:

   * Resolução atual da tela
   * Quantidade de discos
   * Capacidade do disco principal
   * Nome do usuário atual

6. **Crie um usuário**:
   Crie um novo usuário chamado `aluno`, utilizando a senha indicada pelo professor.

7. **Registre o resultado e compacte**:
   Tire um screenshot da área de trabalho após as alterações e salve-o em `Exercicio 02`. Depois, compacte toda a pasta em `exercicio02.zip`.

8. **Envie o exercício**:
   Envie `exercicio02.zip` para `jonatha@daguerre.com.br` com o assunto:

   `NOME DO ALUNO - Exercício 02 - Configurações`

   Substitua `NOME DO ALUNO` pelo seu nome completo.

---

## 3 - Gerenciador de aplicativos

Siga os passos abaixo no seu computador:

1. **Crie a pasta do exercício**:
   Dentro de `Documentos`, crie uma pasta chamada `Exercicio 03`.

2. **Instale o Audacity**:
   Utilize o Gerenciador de Aplicativos do Linux Mint para pesquisar e instalar o `Audacity`.

3. **Execute o Audacity**:
   Localize o Audacity no menu de aplicativos e execute o programa.

4. **Registre a instalação**:
   Tire um screenshot mostrando o Audacity em execução e salve-o dentro de `Exercicio 03`.

5. **Registre as informações**:
   Crie um arquivo chamado `audacity.txt` dentro de `Exercicio 03` contendo:

   * Seu nome completo
   * A versão instalada do Audacity
   * Uma frase explicando para que serve o programa

6. **Compacte o exercício**:
   Compacte toda a pasta `Exercicio 03` em um arquivo chamado `exercicio03.zip`.

7. **Envie o exercício**:
   Envie `exercicio03.zip` para `jonatha@daguerre.com.br` com o assunto:

   `NOME DO ALUNO - Exercício 03 - Aplicativos`

   Substitua `NOME DO ALUNO` pelo seu nome completo.
</details>




<details>
<summary>Exercícios de interface de linha de comando (CLI)</summary>

## Exercício 1 — Entendendo o terminal

1. Descubra e exiba no terminal:
   * Seu nome de usuário;
   * O diretório em que você está;
   * A data e hora atuais.

2. Exiba o calendário correspondente ao **mês e ano do seu nascimento**.

3. Liste o conteúdo da sua pasta pessoal exibindo também os **arquivos ocultos**.

4. Acesse o diretório `Documentos` utilizando um **caminho relativo** e confirme em qual diretório você está.

5. Sem sair de `Documentos`, liste detalhadamente o conteúdo do diretório `/tmp` utilizando um **caminho absoluto**.

6. Execute, em sequência:

   * Vá para o diretório pai utilizando `..`;
   * Vá para sua pasta pessoal utilizando `~`;
   * Vá para o diretório raiz utilizando `/`;
   * Retorne para sua pasta pessoal.

7. Utilize o comando `ls` para listar o conteúdo da sua pasta pessoa, e mostrar o tamanho dos arquivos de forma humanizada (KB, MB, GB).

8. Limpe o terminal e mostre novamente apenas:

   * Seu usuário;
   * Seu diretório atual.

---

## Exercício 2 — Conhecendo o sistema

1. Exiba as informações do kernel Linux utilizado pelo computador, incluindo sua versão.

2. Descubra quanto espaço está:

   * Disponível;
   * Utilizado;

   no sistema de arquivos principal do computador.

3. Descubra:

   * A quantidade total de memória RAM;
   * A quantidade atualmente disponível (livre).

4. Abra a **Calculadora** pelo menu do Cinnamon. Depois, utilize o terminal para localizar o processo correspondente na lista de processos em execução.

5. Utilizando o PID encontrado, encerre o processo da Calculadora através do terminal com `kill`.

6. Abra o comando `htop` e localize alguns dos processos que estão consumindo mais CPU ou memória. Depois, saia do `htop` sem fechar o terminal.


---

## Exercício 3 — Criando e manipulando arquivos

1. Dentro de `Documentos`, crie através do terminal a seguinte estrutura de diretórios:

```text
Exercicio03/
├── trabalhos/
│   ├── linux/
│   └── outros/
└── backup/
```

2. Copie o arquivo `/etc/os-release` para o diretório `trabalhos/linux`.

3. Faça uma segunda cópia de `os-release` dentro do diretório `backup`.

4. Renomeie o arquivo existente em `trabalhos/linux` de `os-release` para:

```text
sistema.txt
```

5. Mova `sistema.txt` de `trabalhos/linux` para `trabalhos`.

6. Exclua o diretório `linux`, que agora está vazio, utilizando um comando apropriado para remover **diretórios vazios**.

7. Exclua o diretório `outros` e, em seguida, crie dentro de `trabalhos`:

```text
arquivos/
├── documentos/
└── temporarios/
```

Faça isso utilizando **um único comando**.

8. Ao terminar, a estrutura deverá ser:

```text
Exercicio03/
├── backup/
│   └── os-release
└── trabalhos/
    ├── sistema.txt
    └── arquivos/
        ├── documentos/
        └── temporarios/

```

---

## Exercício 4 — Trabalhando com informações


1. Exiba no terminal o conteúdo completo do arquivo:

```text
/etc/passwd
```

2. Abra `/etc/passwd` de forma que seja possível **navegar pelo conteúdo usando o teclado**, sem despejar todo o arquivo de uma vez no terminal.

3. Descubra:

   * Quantas linhas existem em `/etc/passwd`;
   * Quantas palavras existem no arquivo.

4. Procure dentro de `/etc/passwd` todas as linhas que contêm:

```text
/bin/bash
```

Exiba também o **número das linhas** encontradas.

5. Utilize `find` para localizar dentro de `/etc` todos os arquivos que possuem exatamente o nome:

```text
hosts
```

Ignore eventuais mensagens de `Permission denied`.

6. Utilize um **pipe (`|`)** para descobrir quantos usuários de `/etc/passwd` possuem `/bin/bash` configurado.

7. Utilize `ps` combinado com `grep` através de um **pipe** para procurar os processos relacionados ao Cinnamon que estão em execução.


</details>