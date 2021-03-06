![Bluestorm Software](https://media-exp1.licdn.com/dms/image/C4E0BAQElDZKhzHntvg/company-logo_200_200/0?e=2159024400&v=beta&t=JgA2xy_CRrCu-B-_NxCglbSxKezsc1IxRNyZp_sizoM)

Desafio técnico `Devops`
========================

# Parte 1

## Sobre o 'desafio'

Esse é um teste feito para conhecer um  pouco mais de cada candidato a vaga de DevOps na Bluestorm. Não se trata de um teste objetivo, capaz de gerar uma nota ou uma taxa de acerto, mas sim de um estudo de caso com o propósito de conhecer os conhecimentos, experiências e modo de trabalhar de um cadidato. Sinta-se livre para desenvolver sua solução para o problema proposto e em caso de dúvidas entre em contato no darcy.silva@bluestorm.com.br

## Cenário

Dentro do diretório `app` existe uma aplicação muito simples em Flask. Quando essa aplicação  subir ela irá ler uma variável de ambiente `TOKEN_PASS` que será a senha da api. Ou seja, ao executarmos uma chamada para essa aplicação devemos passar um `Header` de  `Authorization` com o token específico. Por exemplo: `curl -H "Authorization: Token VALOR_DA_VARIAVEL_TOKEN_PASS" http://localhost/`. Você deve nos informar como podemos definir/trocar esse token facilmente.

Seu objetivo é fazer deploy dessa aplicação. Crie um arquivo `part1.md` descrevendo todos os passos para que possamos executar sua infraestrutura em nosso ambiente. Esses são os pontos de atenção:

* A aplicação deverá rodar em containner docker.

Sinta-se livre para mudar o código da aplicação se julgar necessário.

# Entrega

* Você deve clonar esse repositório e commitar todas as modificações, porém, não abra um pull request ou deixe seu código de resposta aberto em um fork, por exemplo.
* Depois que terminar, compacte todo o diretório e nos envie. **Queremos analisar seus commits**.
* Envie para o email darcy.silva@bluestorm.com.br


Boa sorte!
