# Projeto Integrador


<h5>CENTRO UNIVERSITÁRIO SENAC</h5>



<h3>PROJETO INTEGRADOR I: PROCESSO DE MODELAGEM DE UM SISTEMA ORIENTADO A OJETOS DE UMA GRANDE UNIVERSIDADE</h3>



<h5><em><strong> SISTEMA DE GESTÃO DE DADOS DA UNIVERDADE SENAC</strong></em></h5>



  
        CESAR AMORIM DE SOUSA
        EMANOEL VIDAL CERQUEIRA DE MIRANDA
        GABRIELLE DE CARVALHO DA MOTA SILVEIRA
        LARISSA CREMM LEMES
        MARIA CECILIA BENTO GONCALVES
        RODRIGO MONTEIRO DE OLIVEIRA
        SERGIO LEONARDO SOUZA TAVARES
        VITOR ALVES BERNADINO


    <div class="center location-date">São Paulo<br>2024</div>

<head>
	<title>Projeto Integrador I - Centro Universitário SENAC</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			text-align: center;
		}
		h1 {
			font-size: 36px;
			margin-bottom: 10px;
		}
		p {
			margin-bottom: 20px;
		}
		.center {
			text-align: center;
		}
	</style>
</head>
<body>
	<div class="center">
		<h3>PROJETO INTEGRADOR I: PROCESSO DE MODELAGEM DE UM SISTEMA ORIENTADO A OBJETOS DE UMA GRANDE UNIVERSIDADE</h3>
		<p>SISTEMA DE GESTÃO DE DADOS DA UNIVERSIDADE SENAC</p>
		<p>Trabalho de Projeto Integrador I desenvolvido como exigência para obtenção de nota parcial para 1º semestre do Curso Análise e Desenvolvimento de Sistemas – Centro Universitário SENAC, sob orientação do Professor Enoque Leal.</p>
		<p>São Paulo, 2024</p>
	</div>



    <div class="center title">AGRADECIMENTOS</div>
    <div class="content">
        Agradecemos em primeiro lugar, a Deus, por iluminar nossos passos, e nos dar a certeza de que os desafios estão presentes em nossas vidas para serem superados.<br>
        Agradecemos ao nosso orientador e professor, por aceitar e compartilhar conosco o desafio que é executar um trabalho de conclusão de curso e a todos professores envolvidos que nos proporcionaram e contribuíram no desenvolvimento deste trabalho, e com certeza estarão presentes nas próximas etapas.<br>
        Com certeza as críticas e sugestões que todos fizeram, tornou este trabalho o que ele é hoje.
    </div>

    <div class="center title">RESUMO</div>
    <div class="content">
        AMORIN, C. VIDAL, E. CARVALHO, G, CREMM, L. CECILIA, M. MONTEIRO, R. LEONARDO, S. ALVES, V. Implementação de processo de modelagem de um sistema Orientado a Objetos, voltado a gestão de dados do Centro Universitário SENAC, São Paulo, 2024.<br><br>
        Este trabalho foi elaborado a partir da solicitação do Centro Universitário SENAC, com objetivo de desenvolver de um software com a Linguagem Unificada de Modelagem (UML). No qual possibilitara descrever, visualizar e comunicar o design de um sistema de software de forma clara e concisa. Ela fornece um conjunto de diagramas e notações para modelar diferentes aspectos de um sistema, como a estrutura, o comportamento e a interação entre os componentes.<br><br>
        Em outras palavras, o software tem como objetivo gerenciar e organizar informações sobre as pessoas que fazem parte da universidade, como estudantes, professores, funcionários, etc.<br><br>
        Palavras-chave: Programação orientada a objetos, linguagem unificada de modelagem (UML), diagrama de caso, cenários dos casos de uso, diagrama de classe.
    </div>

    <div class="center title">ABSTRACT</div>
    <div class="content">
        AMORIN, C. VIDAL, E. CARVALHO, G, CREMM, L. CECILIA, M. MONTEIRO, R. LEONARDO, S. ALVES, V. Implementação de processo de modelagem de um sistema Orientado a Objetos, voltado a gestão de dados do Centro Universitário SENAC, São Paulo, 2024.<br><br>
        This work was prepared at the request of the Centro Universitário SENAC, with the objective of developing software using the Unified Modeling Language (UML). This would allow the description, visualization and communication of the design of a software system in a clear and concise manner. It provides a set of diagrams and notations to model different aspects of a system, such as the structure, behavior and interaction between components. In other words, the software aims to manage and organize information about the people who are part of the university, such as students, professors, employees, etc.<br><br>
        Keywords: Object-oriented programming, Unified Modeling Language (UML), case diagram, use case scenarios, class diagram.
    </div>

    <div class="center title">SUMÁRIO</div>
    <div class="content">
        INTRODUÇÃO...............................................................................................................7<br>
        1. Desenvolvimento de sistemas......................................................................................7<br>
        1.1. Sistemas de software: definição.................................................................................8<br>
        1.2 Paradigmas de desenvolvimento: estruturado e orientado a objeto............................9<br>
        2. Ferramentas de desenvolvimento – diagrama de caso de uso.................................9<br>
        2.1 Diagrama de caso de uso............................................................................................11<br>
        2.2 Descrição de caso de uso...........................................................................................12<br>
        3.0 Diagrama de classes: conceito.................................................................................16<br>
        3.1 Diagrama de classes...................................................................................................17<br>
        CONSIDERAÇÕES FINAIS........................................................................................18<br>
        REFERÊNCIA BIBLIOGRÁFICA.............................................................................19
    </div>

    <div class="section-title">INTRODUÇÃO</div>
    <div class="subsection-title">Capítulo 1 Desenvolvimento de Sistemas</div>
    <div class="content">
        A informação é algo tão valioso para as instituições quanto o produto e o serviço que oferecem e, com o avanço das tecnologias e a facilidade ao seu acesso, as empresas passaram a depender cada vez mais desses dados e dos sistemas computacionais disponíveis para acompanhar suas atividades.<br>
        Os sistemas e softwares exercem um papel muito importante nesta era tecnológica, nos dias atuais as empresas, indivíduos, governo e população em geral tem total dependência dessa tecnologia.<br>
        O Surgimento dos primeiros sistemas de software ocorreu na década de 1950; sua evolução foi densa e rápida e, desde então, seu progresso é constante, continuando a ser a tecnologia mais importante no contexto mundial (PRESSMAN, 1995; PRESSMAN, 2016).<br><br>
        Desde o surgimento dos primeiros sistemas de software sua evolução não parou.<br><br>
        Fonte: adaptado de Pressman (1995), Albertin (2009), Guerra e Colombo (2009).
    </div>

    <div class="subsection-title">1.1 Sistemas de software: Definição</div>
    <div class="content">
        Podemos definir um sistema de software como um conjunto de programas e dados que trabalham juntos para realizar uma função específica ou conjunto de funções. Instruções estas que são executadas por um computador para realizar uma tarefa ou conjunto de tarefas.<br><br>
        Segundo LEITE, São programas de computadores, em suas diversas formas, e a documentação associada. Um programa é um conjunto de soluções algorítmicas, codificadas numa linguagem de programação, executado numa máquina real. Software é um produto conceitual e lógico. (LEITE, 2006).
    </div>





<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paradigma de Desenvolvimento Estruturado</title>

</head>
<body>
    <div class="title">1.2 Paradigma de Desenvolvimento Estruturado</div>
    <div class="content">
        <p>
            Antes de 1975, a maior parte das empresas de software não utilizava nenhuma técnica específica; cada indivíduo trabalhava do seu próprio jeito. Grandes avanços foram feitos aproximadamente entre 1975 e 1985, com o desenvolvimento do assim chamado paradigma clássico ou estruturado (SCHACH, 2010).
        </p>
        <p>
            A programação estruturada é uma abordagem para desenvolver software que se baseia em estruturas de controle e fluxo de dados.
        </p>
        <p>
            A programação estruturada tem como base três principais conceitos:
        </p>
        <ul>
            <li>Modularidade: o software é dividido em módulos independentes que podem ser facilmente modificados e reutilizados.</li>
            <li>Estruturas de controle: o fluxo de dados é controlado por estruturas de controle como laços, condições e funções.</li>
            <li>Abstração: o software é projetado para ser fácil de entender e manter, com abstrações que escondem detalhes técnicos.</li>
        </ul>
    </div>

    <div class="subtitle">2. Ferramentas de Desenvolvimento – Diagrama de Caso de Uso</div>
    <div class="content">
        <p>
            Um diagrama de caso de uso é uma ferramenta de desenvolvimento de software que ajuda a modelar e a documentar os casos de uso de um sistema. Ele é uma representação gráfica que descreve como os usuários interagem com o sistema e quais são as necessidades e objetivos que eles buscam atingir.
        </p>
        <p>
            Um diagrama de caso de uso típico inclui os seguintes elementos:
        </p>
        <ul>
            <li>Ator: um usuário ou grupo de usuários que interagem com o sistema.</li>
            <li>Casos de uso: as ações que os atores realizam para atingir seus objetivos.</li>
            <li>Requisitos: as necessidades e objetivos dos atores que o sistema deve atender.</li>
            <li>Restrições: as limitações e restrições que o sistema deve considerar.</li>
        </ul>
        <p>
            Os diagramas de caso de uso são úteis para:
        </p>
        <ul>
            <li>Entender os requisitos dos usuários: ajudam a identificar as necessidades e objetivos dos atores e a priorizar os requisitos do sistema.</li>
            <li>Modelar o comportamento do sistema: ajudam a descrever como o sistema se comporta em diferentes situações e como os atores interagem com ele.</li>
            <li>Comunicar os requisitos do sistema: ajudam a documentar e a comunicar os requisitos do sistema para os desenvolvedores, gerentes e outros stakeholders.</li>
        </ul>
    </div>

    <div class="subtitle">2.1 Diagrama de Caso de Uso</div>
    <div class="content">
        <p>
            Um diagrama de caso de uso é uma representação gráfica que descreve como os usuários interagem com um sistema. Ele é uma ferramenta importante para modelar e documentar a lógica do sistema e como os usuários o utilizam.
        </p>
        <p>
            Os diagramas de caso de uso são utilizados para obter requisitos funcionais do sistema. Descrevem as interações entre o sistema e os usuários. Em outras palavras, descrevem graficamente quem usará o sistema e de que maneira o usuário espera interagir com o sistema (MARTINS, 2002).
        </p>
        <p>
            Segundo Bentley e Whitten (2000), o diagrama de caso de uso retrata graficamente o sistema como uma coleção de casos de uso, atores (usuários) e suas relações. O diagrama comunica, em um alto nível, o escopo dos eventos de negócios que devem ser processados pelo sistema.
        </p>
    </div>

    <div class="content center">
        <p><strong>Diagrama de caso de uso – Centro Universitário SENAC</strong></p>
        <p><em>Fonte: Elaborado pelo autor.</em></p>
    </div>
</body>
</html>


<body>
    <div class="title">Casos de Uso do Sistema</div>

    <div class="case">
        <h2>Nome do cenário: [UC001] Cadastro de Pessoa Física</h2>
        <div class="subsection">
            <p><strong>Atores:</strong> Administrador, Funcionário, Aluno, Fornecedor, Professor.</p>
            <p><strong>Pré-condições:</strong> Funcionário tem permissão para cadastrar pessoas físicas, os dados da pessoa física são válidos</p>
            <p><strong>Pós-condições:</strong> A pessoa física está cadastrada no sistema e os dados são válidos.</p>
        </div>
        <div class="subsection">
            <p><strong>Fluxo Básico / Principal:</strong></p>
            <ol class="list">
                <li>O Funcionário acessa a tela de cadastro de pessoa física;</li>
                <li>O Funcionário preenche os campos com os dados da pessoa física;</li>
                <li>O sistema verifica se os dados são válidos;</li>
                <li>Se os dados forem válidos, o sistema cadastra a pessoa física;</li>
                <li>O Funcionário pode visualizar a pessoa física cadastrada.</li>
            </ol>
        </div>
        <div class="subsection">
            <p><strong>Fluxo Alternativo 1:</strong></p>
            <ol class="list">
                <li>No passo 5, se não visualizar pessoa cadastrada, o sistema exibe mensagem de pessoa não localizada;</li>
                <li>Encerra-se o caso de uso e volta a opção 1.</li>
            </ol>
        </div>
    </div>

    <div class="case">
        <h2>Nome do cenário: [UC002] Cadastro de Pessoa Jurídica</h2>
        <div class="subsection">
            <p><strong>Atores:</strong> Funcionário, pessoa jurídica</p>
            <p><strong>Pré-condições:</strong> Funcionário tem permissão para cadastrar pessoas físicas, os dados da pessoa Jurídica são válidos.</p>
            <p><strong>Pós-condições:</strong> A pessoa jurídica está cadastrada no sistema e os dados são válidos.</p>
        </div>
        <div class="subsection">
            <p><strong>Fluxo Básico:</strong></p>
            <ol class="list">
                <li>O Funcionário acessa a tela de cadastro de pessoa jurídica;</li>
                <li>O Funcionário preenche os campos com os dados da pessoa jurídica;</li>
                <li>O sistema verifica se os dados são válidos;</li>
                <li>Se os dados forem válidos, o sistema cadastra a jurídica;</li>
                <li>O Funcionário pode visualizar a pessoa jurídica cadastrada.</li>
            </ol>
        </div>
        <div class="subsection">
            <p><strong>Fluxo Alternativo 1:</strong></p>
            <ol class="list">
                <li>No passo 5, se não visualizar Pessoa Jurídica cadastrada, o sistema exibe mensagem de Pessoa Jurídica não localizada;</li>
                <li>Encerra-se o caso de uso e volta a opção 1.</li>
            </ol>
        </div>
    </div>

    <div class="case">
        <h2>Nome do cenário: [UC003] Cadastro de Fornecedor</h2>
        <div class="subsection">
            <p><strong>Atores:</strong> Funcionário/Fornecedor</p>
            <p><strong>Pré-condições:</strong> Funcionário tem permissão para cadastrar Fornecedor, os dados do Fornecedor são válidos.</p>
            <p><strong>Pós-condições:</strong> A pessoa jurídica/Fornecedor está cadastrada no sistema e os dados são válidos.</p>
        </div>
        <div class="subsection">
            <p><strong>Fluxo Básico:</strong></p>
            <ol class="list">
                <li>O sistema solicita o cadastro Fornecedor; (fluxo alternativo 1 cadastro representante empresa);</li>
                <li>O funcionário digita o nome da empresa;</li>
                <li>O funcionário digita o nome e sobrenome do representante;</li>
                <li>O funcionário digita o CNPJ;</li>
                <li>O funcionário digita o email;</li>
                <li>O funcionário confirma o email;</li>
                <li>O funcionário digita uma senha;</li>
                <li>O funcionário confirma os dados.</li>
                <li>O Funcionário pode visualizar fornecedor cadastrado.</li>
            </ol>
        </div>
        <div class="subsection">
            <p><strong>Fluxo Alternativo 1 – Dados incompletos:</strong></p>
            <ol class="list">
                <li>No passo 3, se o funcionário não criar cadastro de representante ele não acessará universidade;</li>
                <li>O sistema envia
				
				
				
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casos de Uso do Sistema</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #000;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Casos de Uso do Sistema</h1>

    <table>
        <tr>
            <th>Nome do cenário</th>
            <td>[UC001] Cadastro de Pessoa Física</td>
        </tr>
        <tr>
            <th>Atores</th>
            <td>Administrador, Funcionário, Aluno, Fornecedor, Professor</td>
        </tr>
        <tr>
            <th>Pré-condições</th>
            <td>Funcionário tem permissão para cadastrar pessoas físicas, os dados da pessoa física são válidos</td>
        </tr>
        <tr>
            <th>Pós-condições</th>
            <td>A pessoa física está cadastrada no sistema e os dados são válidos.</td>
        </tr>
        <tr>
            <th>Fluxo Básico / Principal</th>
            <td>
                1. O Funcionário acessa a tela de cadastro de pessoa física;<br>
                2. O Funcionário preenche os campos com os dados da pessoa física;<br>
                3. O sistema verifica se os dados são válidos;<br>
                4. Se os dados forem válidos, o sistema cadastra a pessoa física;<br>
                5. O Funcionário pode visualizar a pessoa física cadastrada.
            </td>
        </tr>
        <tr>
            <th>Fluxo Alternativo 1</th>
            <td>
                1. No passo 5, se não visualizar pessoa cadastrada, o sistema exibe mensagem de pessoa não localizada;<br>
                2. Encerra-se o caso de uso e volta a opção 1.
            </td>
        </tr>
    </table>

    <table>
        <tr>
            <th>Nome do cenário</th>
            <td>[UC002] Cadastro de Pessoa Jurídica</td>
        </tr>
        <tr>
            <th>Atores</th>
            <td>Funcionário, pessoa jurídica</td>
        </tr>
        <tr>
            <th>Pré-condições</th>
            <td>Funcionário tem permissão para cadastrar pessoas físicas, os dados da pessoa Jurídica são válidos.</td>
        </tr>
        <tr>
            <th>Pós-condições</th>
            <td>A pessoa jurídica está cadastrada no sistema e os dados são válidos.</td>
        </tr>
        <tr>
            <th>Fluxo Básico</th>
            <td>
                1. O Funcionário acessa a tela de cadastro de pessoa jurídica;<br>
                2. O Funcionário preenche os campos com os dados da pessoa jurídica;<br>
                3. O sistema verifica se os dados são válidos;<br>
                4. Se os dados forem válidos, o sistema cadastra a jurídica;<br>
                5. O Funcionário pode visualizar a pessoa jurídica cadastrada.
            </td>
        </tr>
        <tr>
            <th>Fluxo Alternativo 1</th>
            <td>
                1. No passo 5, se não visualizar Pessoa Jurídica cadastrada, o sistema exibe mensagem de Pessoa Jurídica não localizada;<br>
                2. Encerra-se o caso de uso e volta a opção 1.
            </td>
        </tr>
    </table>

    <table>
        <tr>
            <th>Nome do cenário</th>
            <td>[UC003] Cadastro de Fornecedor</td>
        </tr>
        <tr>
            <th>Atores</th>
            <td>Funcionário/Fornecedor</td>
        </tr>
        <tr>
            <th>Pré-condições</th>
            <td>Funcionário tem permissão para cadastrar Fornecedor, os dados do Fornecedor são válidos.</td>
        </tr>
        <tr>
            <th>Pós-condições</th>
            <td>A pessoa jurídica/Fornecedor está cadastrada no sistema e os dados são válidos.</td>
        </tr>
        <tr>
            <th>Fluxo Básico</th>
            <td>
                1. O sistema solicita o cadastro Fornecedor; (fluxo alternativo 1 cadastro representante empresa);<br>
                2. O funcionário digita o nome da empresa;<br>
                3. O funcionário digita o nome e sobrenome do representante;<br>
                4. O funcionário digita o CNPJ;<br>
                5. O funcionário digita o email;<br>
                6. O funcionário confirma o email;<br>
                7. O funcionário digita uma senha;<br>
                8. O funcionário confirma os dados.<br>
                9. O Funcionário pode visualizar fornecedor cadastrado.
            </td>
        </tr>
        <tr>
            <th>Fluxo Alternativo 1 – Dados incompletos</th>
            <td>
                1. No passo 3, se o funcionário não criar cadastro de representante ele não acessará universidade;<br>
                2. O sistema envia uma mensagem da necessidade de cadastro do representante fluxo alternativo 1;<br>
                3. No passo 9, se não visualizar fornecedor cadastrado, o sistema exibe mensagem de fornecedor não localizada;<br>
                4. Encerra-se o caso de uso e volta a opção 1.
            </td>
        </tr>
    </table>

    <table>
        <tr>
            <th>Nome do cenário</th>
            <td>[UC004] Cadastro de Professores</td>
        </tr>
        <tr>
            <th>Atores</th>
            <td>Funcionário, Professor</td>
        </tr>
        <tr>
            <th>Pré-condições</th>
            <td>Funcionário tem permissão para cadastrar Professor, os dados do Professor são válidos.</td>
        </tr>
        <tr>
            <th>Pós-condições</th>
            <td>O professor está cadastrada no sistema e os dados são válidos.</td>
        </tr>
        <tr>
            <th>Fluxo Básico</th>
            <td>
                1. O Funcionário acessa a tela de cadastro de professor;<br>
                2. O Funcionário preenche os campos com os dados do professor;<br>
                3. O sistema verifica se os dados são válidos;<br>
                4. Se os dados forem válidos, o sistema cadastra o professor;<br>
                5. O Funcionário pode visualizar o professor cadastrado.
            </td>
        </tr>
        <tr>
            <th>Fluxo Alternativo 1</th>
            <td>
                1. No passo 5, se não visualizar pessoa professor cadastrado, o sistema exibe mensagem de professor não localizado;<br>
                2. Encerra-se o caso de uso e volta a opção 1.
            </td>
        </tr>
    </table>

    <table>
        <tr>
            <th>Nome do cenário</th>
            <td>[UC005] - Cadastro de Aluno</td>
        </tr>
        <tr>
            <th>Atores</th>
            <td>Funcionário, Aluno</td>
        </tr>
        <tr>
            <th>Pré-condições</th>
            <td>Funcionário tem permissão para cadastrar Aluno, os dados do aluno são válidos e aprovado em curso.</td>
        </tr>
        <tr>
            <th>Pós-condições</th>
            <td>Aluno está cadastrada no sistema e os dados são válidos.</td>
        </tr>
        <tr>
            <th>Fluxo Básico</th>
            <td>
                1. O Funcionário acessa a tela de cadastro de aluno;<br>
                2. O Funcionário preenche os campos com os dados do aluno;<br>
                3. O sistema verifica se os dados são válidos;<br>
                4. Se os dados forem válidos, o sistema cadastra o aluno;<br>
                5. O Funcionário pode visualizar o aluno cadastrado.
            </td>
        </tr>
        <tr>
            <th>Fluxo Alternativo 1</th>
            <td>
                1. No passo 5, se não visualizar aluno cadastrado, o sistema exibe mensagem de aluno não localizada;<br>
                2. Encerra-se o caso de uso e volta a opção 1.
            </td>
        </tr>
    </table>

<body>
    <table>
        <tr>
            <th>Nome do cenário</th>
            <td>[UC006] – Acessar a Universidade</td>
        </tr>
        <tr>
            <th>Atores</th>
            <td>Pessoa Física, professor, aluno, funcionário</td>
        </tr>
        <tr>
            <th>Pré-condições</th>
            <td>Estar cadastrado no sistema</td>
        </tr>
        <tr>
            <th>Pós-condições</th>
            <td>Acesso a Universidade liberado</td>
        </tr>
        <tr>
            <th>Fluxo Básico</th>
            <td>
                1. O sistema solicita digital ou código de acesso;<br>
                2. O interessado atende requisição e insere código;<br>
                3. O sistema valida dados;<br>
                4. O sistema autentica o interessado e emite mensagem de acesso liberado.
            </td>
        </tr>
        <tr>
            <th>Fluxo Alternativo – Não cadastrado</th>
            <td>
                1. O sistema solicita que procure funcionário;<br>
                2. O sistema retorna ao passo 1 do fluxo principal.
            </td>
        </tr>
        <tr>
            <th>Fluxo Alternativo – Dados Inválidos</th>
            <td>
                1. O sistema exibe uma mensagem de falha de login;<br>
                2. O sistema retorna ao passo 1 do fluxo principal.
            </td>
        </tr>
        <tr>
            <th>Fluxo de Exceção – Excesso de tentativas</th>
            <td>
                Após 3 tentativas de login:<br>
                1. O sistema bloqueia o usuário;<br>
                2. Sistema solicita que procure funcionário;<br>
                3. O sistema redireciona o interessado ao passo 1 do fluxo principal.
            </td>
        </tr>
    </table>
</body>
</html>


<body>
    <div class="title">3.0 Diagrama de Classes</div>

    <div class="content">
        <p>Uma forma simples para representarmos classes é o uso de diagrama, ou seja, representação gráfica que descreve classes, objetos e relações entre eles em um sistema. Por isso é uma ferramenta importante para modelar e documentar toda estrutura do sistema.</p>
        <p>Guedes (2018) acrescenta que o diagrama de classes é um dos diagramas mais importantes como ferramenta de desenvolvimento. Seu principal objetivo está em permitir as visualizações das classes que constituem o software com seus respectivos atributos e métodos, bem como demonstrar como as classes do diagrama se relacionam, complementam e transmitem informações entre si.</p>
    </div>

    <div class="content">
        <p><strong>Diagrama de classes – Centro Universitário SENAC</strong></p>
        <p><em>Fonte: Elaborado pelo autor.</em></p>
    </div>

    <div class="section">
        <h2>CONSIDERAÇÕES FINAIS</h2>
        <div class="content">
            <p>Ao realizar este projeto, concluímos que ele é um elemento fundamental na análise e desenvolvimento de sistemas, pois ele define a melhor direção e o escopo do trabalho a ser realizado.</p>
            <p>O diagrama de caso de uso nos permitiu através da representação gráfica descrever como os usuários interagem com um sistema. Ele foi uma ferramenta importante para modelarmos e documentarmos a lógica do sistema e como os usuários o utilizam. A utilização da descrição dos casos de uso que é uma parte importante do processo de análise de requisitos e modelagem de sistemas, nos permitiu entender melhor como os usuários interagem com o sistema e quais são suas necessidades e objetivos no projeto.</p>
        </div>
    </div>

    <div class="section">
        <h2>REFERÊNCIAS</h2>
        <div class="content">
            <p>PRESSMAN, S. Roger. Engenharia de software. 3. ed. São Paulo: McGraw-Hill, 1995.</p>
            <p>LEITE, Jair C. Engenharia de software: ciclos de vida. Universidade do Rio Grande do Norte, 2006.</p>
            <p>SOMMERVILLE, Ian. Engenharia de software. 8. ed. São Paulo: Pearson Addison-Wesley, 2007.</p>
            <p>ALBERTIN, Alberto L. Administração de informática: funções e fatores críticos de sucesso. 6. ed. São Paulo: Atlas, 2009.</p>
            <p>SCHACH, Stephen R. Engenharia de software: os paradigmas clássicos e orientado a objetos. 7. ed. Porto Alegre: AMGH, 2010.</p>
            <p>ENTLEY, Lonnie; WHITTEN, Jeffrey. L. Systems analysis and design methods. 7. ed. New York: Irwin/McGraw Hill, 2000.</p>
            <p>GUEDES, Gilleanes T. A. UML 2: uma abordagem prática. 3. ed. São Paulo: Novatec, 2018.</p>
        </div>
    </div>
</body>
</html>
