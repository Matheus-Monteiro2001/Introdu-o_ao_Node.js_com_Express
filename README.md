# OBJETIVOS DA AULA

1. Conhecer a origem do Node.js

2. Criar um ambiente de desenvolvimento em Node.js

3. Criar uma API com Express

# REQUISITOS BÁSICOS

1. Conhecer JavaScript e seus fundamentos

2. Familiaridade com comandos no terminal

3. Conhecimento básico sobre protocolos HTTP (GET, POST, PUT, DELETE)

4. Conhecer o conceito de RestAPI

# ORIGEM DO NODE.JS
### **Introdução ao Node.js com Express**

### **Origem do Node.js**

* Criado em 2009 por Ryan Dahl

* Combina a máquina virtual JavaScript V8, Event Loop e a libuv

* Usa a Java Script como linguagem de programação

* É guiado a eventos (Event Driven)

# CARACTERÍSTICAS DO Node.js

* É um ambiente de servidor de código aberto

* Gratuíto para uso

* É executado em várias plataformas (Windows, Linux, Unix, Mac OSX, etc.)

* É JavaScript no servidor

* Event Loop (Loop de Eventos )

* Assincronicidade

* Processos de I/O não bloqueante

* Alta performance (quando bem estruturado)

---
# o que é o express?
### **Introdução ao node.js com express**

* Framework web minimalista e rápido para node.js

* Fornece uma estrura e conjunto de recursos robustos para aplicações web e mobile

* Dispçoe de métodos utilitários HTTP e middlewares para criar uma API rápida e segura

## Instalando o Express  
## no cmd, 
~~~
npm install express --save
~~~
~~~
npm init
~~~
~~~
node-express
~~~

**localhost:3000**

---

# Atividade Prática
## Criar uma endpoint para useres:
* Listar usuários (GET)
* Criar usuários (POST)
* Modificar usuário (PUT)
* Remover usuário (DELETE)

---

**Aula 2**

## Desenvolvimento Ferramentas de Linha de comando em Node.js

# Objetivos

1. Entender o conceito de CLI (Command Line Interface)
2. Exemplos de CLI em Node.js
3. Criar uma ferramenta CLI

# REQUISITOS BÁSICOS

. Conhecer JavaScript e seus fundamentos  
. Familiaridade com comandos no terminal  
. Nodde e NPM instalados na máquina

# O que é uma CLI?
. Ferramenta que disponibiliza uma interface de linha de comando para executar tarefas no terminal  
. Normalmente são criadas através de Shell Script  
. Automatiza uma tarefa através de um arquivo executável  
. Pode ser facilmente distribuído em várias plataformas  

# Por que criar uma CLI em Node.js
. A popularidade do Node.js se dá ao rico ecossistema de pacotes  
. Mais de 900.000 pacotes registrados no NPM  
. CLIs podem ser facilmente distribuídas e consumidas em múlpiplas plataformas  
. Explorar o ecossistema, incluindo sua grande quantidade de pacotes focados em CLI

# Atividade Prática
. Criar uma CLI simples para procurar arquivos em um diretório  
. Instalar local para desenvolvimento e testes  
. Passo a passo para publicar a CLI no NPM  
<https://github.com/hmschreiner/node-cli>

---

# O que é o Commander.js?
. Ferramenta completa para criação de CLIs em Node.js  
. Definição de comandos, parametro de opções e execução de ações  
. Descrição para cada comando e menu de ajuda com exemplos de uso  

# Atividade Prática
. Criar uma CLI usando o Commander.js  
. Criar uma ferramenta que mostra o clima atual de uma cidade pelo nome  
. Usar a API do ClimaTempo  
<https://github.com/hmschreiner/node-clima-cli>

---

# Criação de templates com Pug

## Objetivos da Aula
1. Criar templates em HTML usando o Pug
2. Gerar templates avançados com Pug
3. Integrar o Pug com Express.js

## O que é Pug?
. É um template engine de alta performance  
. Implementado com JavaScript para Node.js e Browsers  
. Conhecido anteriormente como "Jade"  
. Pode ser integrado com Express  

## Pros e Contras
**Pros:**  
. Escrever mais HTML com menos código  
. Código parecido com parágrafos, o que a legibilidade do código e simplifica   projetos com vários desenvolvedores  
. Não há fechamento de tags; É usado indentação para identificar aninhamento de tags  
. É possível escrever JavaScript dentro dos templates  
**Contras:**  
. Espaços em branco importam - e muito! Um mínimo erro de indentação pode trazer grandes problemas para seu código!  
. Não é possível usar código HTML de qualquer lugar; É preciso converter para Pug antes de usar  

# Atividade Prática
<https://github.com/hmschreiner/pug-template>

---

# Integrando Pug com Express
. Um template engine possibilita o uso de arquivos de template estatico na sua aplicação
. Em tempo de execução, variáveis dentro desse template podem ser substituídas por valores reais
. Transforma o template em HTML e manda para o client
. Facilita o desenvolvimento de páginas HTML dinamicas usando conteúdo estático

# Atividade Prática
<https://github.com/hmschreiner/pug-express.git>

