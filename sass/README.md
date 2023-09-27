
Para usar o sass você precisa ter instalado o nodeJS em sua maquina.
feito isso vamos instala-lo globalmente:
~ npm install -g sass


Podemos usar 2 tipos de sintaxes usando extensões diferentes:
sass >> nessa não usamos as chaves nem o ponto e virgula
scss >> nessa forma podemos usar igual ao css padrão

Vamos criar um projeto nodeJS
~ npm init

Adicione o sass ao projeto
~ npm i --save-dev sass

No package-json adicione o comando sass dentro tag scripts:
 "sass": "sass",

 Agora vamos executar o comando informando o arquivo de entrada e de saída:
 ~ npm run sass main.sass main.css

 