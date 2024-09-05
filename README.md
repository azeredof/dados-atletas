# dados-atletas
## Resumo do projeto

Crie uma aplicação capaz de receber informações de um atleta, bem como calcular parâmetros e exibi-los para o usuário.

## Introdução

Os organizadores da competição realizada durante o projeto anterior gostaram muito da sua solução proposta e do seu perfil de desenvolvimento. Com isso, eles resolveram fazer uma nova encomenda utilizando a linguagem JavaScript, onde você deverá criar um software capaz de receber informações dos atletas e exibir a categoria, IMC, média calculada e demais informações capturadas.

## Especificações

Você deverá criar uma classe Atleta para concentrar os atributos e métodos dos atletas.

 A classe deverá receber os seguintes atributos:

<ul>
        <li><strong>Nome:</strong></li>
        <li><strong>Idade:</strong></li>
        <li><strong>Peso:</strong></li>
        <li><strong>Altura:</strong></li>
        <li><strong>Notas:</strong></li>
    </ul>

   A classe deverá possuir os seguintes métodos:
   
 <ul>
        <li><strong>calculaCategoria()</strong>: Calcula a categoria do atleta com base na idade.</li>
        <li><strong>calculaIMC()</strong>: Calcula o IMC (Índice de Massa Corporal) do atleta.</li>
        <li><strong>calculaMediaValida()</strong>: Calcula a média válida das notas do atleta, desconsiderando a maior e a menor nota.</li>
        <li><strong>obtemNomeAtleta()</strong>: Retorna o nome do atleta.</li>
        <li><strong>obtemIdadeAtleta()</strong>: Retorna a idade do atleta.</li>
        <li><strong>obtemPesoAtleta()</strong>: Retorna o peso do atleta.</li>
        <li><strong>obtemNotasAtleta()</strong>: Retorna as notas atribuídas ao atleta.</li>
        <li><strong>obtemCategoria()</strong>: Retorna a categoria do atleta calculada pelo método <code>calculaCategoria()</code>.</li>
        <li><strong>obtemIMC()</strong>: Retorna o IMC do atleta calculado pelo método <code>calculaIMC()</code>.</li>
        <li><strong>obtemMediaValida()</strong>: Retorna a média válida calculada pelo método <code>calculaMediaValida()</code>.</li>
    </ul>
    
Utilize as seguintes regras:

<ol>
        <li>
            <strong>Para calcular a categoria:</strong>
            <ul>
                <li><strong>Infantil:</strong> 9 a 11 anos</li>
                <li><strong>Juvenil:</strong> 12 e 13 anos</li>
                <li><strong>Intermediário:</strong> 14 e 15 anos</li>
                <li><strong>Adulto:</strong> 16 a 30 anos</li>
                <li><strong>Sem categoria:</strong> demais idades</li>
            </ul>
        </li>
        <li>
            <strong>Para calcular o IMC:</strong>
          <ul>
            <p>Fórmula: <code>IMC = peso / (altura * altura)</code></p>
            </ul>
        </li>
        <li>
            <strong>Para calcular a média válida:</strong>
            <p>Utilize a metodologia abordada no Projeto de Certificação 1.</p>
        </li>
    </ol>
