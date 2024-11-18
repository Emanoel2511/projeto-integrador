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




<h5><em><strong>AGRADECIMENTOS</strong></em></h5>

        Agradecemos em primeiro lugar, a Deus, por iluminar nossos passos, e nos dar a certeza de que os 
		desafios estão presentes em nossas vidas para serem superados.
        Agradecemos ao nosso orientador e professor, por aceitar e compartilhar conosco o desafio que é 
		executar um trabalho de conclusão de curso e a todos professores envolvidos que nos proporcionaram
		e contribuíram no desenvolvimento deste trabalho, e com certeza estarão presentes nas próximas etapas.
		
        Com certeza as críticas e sugestões que todos fizeram, tornou este trabalho o que ele é hoje.



<h5><em><strong>RESUMO</strong></em></h5>


        AMORIN, C. VIDAL, E. CARVALHO, G, CREMM, L. CECILIA, M. MONTEIRO, R. LEONARDO, S. ALVES, V. Implementação
		de processo de modelagem de um sistema Orientado a Objetos, voltado a gestão de dados do Centro Universitário
		SENAC, São Paulo, 2024.
        Este trabalho foi elaborado a partir da solicitação do Centro Universitário SENAC, com objetivo de desenvolver
		de um software com a Linguagem Unificada de Modelagem (UML). No qual possibilitara descrever, visualizar e 
		comunicar o design de um sistema de software de forma clara e concisa. Ela fornece um conjunto de diagramas 
		e notações para modelar diferentes aspectos de um sistema, como a estrutura, o comportamento e a interação 
		entre os componentes.
        Em outras palavras, o software tem como objetivo gerenciar e organizar informações sobre as pessoas que 
		fazem parte da universidade, como estudantes, professores, funcionários, etc.
		
        Palavras-chave: Programação orientada a objetos, linguagem unificada de modelagem (UML), diagrama
		de caso, cenários dos casos de uso, diagrama de classe.






<h5><em><strong>ABSTRACT</strong></em></h5>


        AMORIN, C. VIDAL, E. CARVALHO, G, CREMM, L. CECILIA, M. MONTEIRO, R. LEONARDO, S. ALVES, V. 
		Implementação de processo de modelagem de um sistema Orientado a Objetos, voltado a gestão de dados
		do Centro Universitário SENAC, São Paulo, 2024.
        This work was prepared at the request of the Centro Universitário SENAC, with the objective
		of developing software using the Unified Modeling Language (UML). This would allow the description,
		visualization and communication of the design of a software system in a clear and concise manner.
		It provides a set of diagrams and notations to model different aspects of a system, such as the 
		structure, behavior and interaction between components. In other words, the software aims to manage
		and organize information about the people who are part of the university, such as students, professors,
		employees, etc.
        Keywords: Object-oriented programming, Unified Modeling Language (UML), case diagram, use case scenarios,
		class diagram.






<h5><em><strong>SUMÁRIO</strong></em></h5>
 
		**INTRODUÇÃO*
        1. Desenvolvimento de sistemas;
        1.1. Sistemas de software: definição;
        1.2 Paradigmas de desenvolvimento: estruturado e orientado a objeto;
        2. Ferramentas de desenvolvimento – diagrama de caso de uso;
        2.1 Diagrama de caso de uso;
        2.2 Descrição de caso de uso;
        3.0 Diagrama de classes: conceito;
        3.1 Diagrama de classes;
		CONSIDERAÇÕES FINAIS;
		REFERÊNCIA BIBLIOGRÁFICA.
		
		
		



<h5><em><strong>INTRODUÇÃO</strong></em></h5>
		

		**Desenvolvimento de Sistemas*
		
		A informação é algo tão valioso para as instituições quanto o produto e o serviço que oferecem e,
		com o avanço das tecnologias e a facilidade ao seu acesso, as empresas passaram a depender cada vez 
		mais desses dados e dos sistemas computacionais disponíveis para acompanhar suas atividades.
		Os sistemas e softwares exercem um papel muito importante nesta era tecnológica, nos dias atuais as
		empresas, indivíduos, governo e população em geram tem total dependência dessa tecnologia.
				O Surgimento dos primeiros sistemas de software ocorreu na década de 1950; sua evolução foi
			densa e rápida e, desde então, seu progresso é constante, continuando a ser a tecnologia mais
			importante no contexto mundial (PRESSMAN, 1995; PRESSMAN, 2016).

		Desde o surgimento dos primeiros sistemas de software sua evolução não parou.




FIGURA
Fonte: adaptado de Pressman (1995), Albertin (2009), Guerra e Colombo (2009).




		
<h5><em><strong>1.1 Sistemas de software: Definição</strong></em></h5>

        Podemos definir um sistema de software como um conjunto de programas e dados que trabalham juntos para
		realizar uma função específica ou conjunto de funções. Instruções estas que são executadas por um
		computador para realizar uma tarefa ou conjunto de tarefas.
		
				Segundo LEITE, São programas de computadores, em suas diversas formas, e a documentação associada.
			Um programa é um conjunto de soluçõesalgorítmicas, codificadas numa linguagem de programação,
			executado numa máquina real. Software é um produto conceitual e lógico.(LEITE, 2006).
    


<h5><em><strong>1.2 Paradigma de desenvolvimento estruturado</strong></em></h5>

					Antes de 1975, a maior parte das empresas de software não utilizava nenhuma técnica específica;
				cada indivíduo trabalhava do seu próprio jeito. Grandes avanços foram feitos aproximadamente
				entre 1975 e 1985, com o desenvolvimento do assim chamado paradigma clássico ou estruturado (SCHACH, 2010).

		A programação estruturada é uma abordagem para desenvolver software que se baseia em estruturas
		de controle e fluxo de dados. 	


		A programação estruturada tem como base três principais conceitos:

			**1.	Modularidade: o software é dividido em módulos independentes que podem ser facilmente modificados
			**e reutilizados.
			**2.	Estruturas de controle: o fluxo de dados é controlado por estruturas de controle como laços,
			**condições e funções.
			**3.	Abstração: o software é projetado para ser fácil de entender e manter, com abstrações que escondem
			**detalhes técnicos.





<h5><em><strong>2. Ferramentas de desenvolvimento – diagrama de caso de uso</strong></em></h5>

		Um diagrama de caso de uso é uma ferramenta de desenvolvimento de software que ajuda a modelar e a
		documentar os casos de uso de um sistema. Ele é uma representação gráfica que descreve como os usuários
		interagem com o sistema e quais são as necessidades e objetivos que eles buscam atingir.
		
		Um diagrama de caso de uso típico inclui os seguintes elementos:
			**Ator: um usuário ou grupo de usuários que interagem com o sistema.




			**Casos de uso: as ações que os atores realizam para atingir seus objetivos.
			**Requisitos: as necessidades e objetivos dos atores que o sistema deve atender.
			**Restrições: as limitações e restrições que o sistema deve considerar.
		
		Os diagramas de caso de uso são úteis para:
        Entender os requisitos dos usuários: ajudam a identificar as necessidades e objetivos dos atores e
		a priorizar os requisitos do sistema.
		Modelar o comportamento do sistema: ajudam a descrever como o sistema se comporta em diferentes situações
		e como os atores interagem com ele.
		Comunicar os requisitos do sistema: ajudam a documentar e a comunicar os requisitos do sistema para os
		desenvolvedores, gerentes e outros stakeholders.


<h5><em><strong>2.1 Diagrama de caso de uso</strong></em></h5>

		Um diagrama de caso de uso é uma representação gráfica que descreve como os usuários interagem
		com um sistema. Ele é uma ferramenta importante para modelar e documentar a lógica do sistema e
		como os usuários o utilizam.
		
					Os diagramas de caso de uso são utilizados para obter requisitos funcionais do sistema.
				Descrevem as interações entre o sistema e os usuários. Em outras palavras, descrevem graficamente
				quem usará o sistema e de que maneira o usuário espera interagir com o sistema (MARTINS, 2002).
		
					Segundo Bentley e Whitten (2000), o diagrama de caso de uso retrata graficamente o sistema como
				uma coleção de casos de uso,atores (usuários) e suas relações. O diagrama comunica, em um alto nível,
				o escopo dos eventos de negócios que devem ser processados pelo sistema.







<h5><em><strong>Diagrama de caso de uso – Centro Universitário SENAC</strong></em></h5>
print


		Fonte: Elaborado pelo autor.



		**A seguir são exibidos os principais casos de uso do sistema, assim como a descrição dos casos de uso.
		
		
<body>
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
</body>

<body>
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
</body>


<body>
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
</body>


<body>
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
                1. No passo 5, se não visualizar pessoa professor cadastrado, o sistema exibe mensagem deprofessor não localizado;<br>
                2. Encerra-se o caso de uso e volta a opção 1.
            </td>
        </tr>
    </table>
</body>



<body>
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
            </
</body>



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








<h5><em><strong>3.0 Diagrama de classes.</strong></em></h5>


		Uma forma simples para representarmos classes é o uso de diagrama, ou seja, representação gráfica que
		descreve classes, objetos e relações entre eles em um sistema. Por isso é uma ferramenta importante
		para modelar e documentar todo estrutura do sistema.

			> Guedes (2018) acrescenta que o diagrama de classes é um dos diagramas mais importantes como
			ferramenta de desenvolvimento. Seu principal objetivo está em permitir as visualizações das classes
			que constituem o software com seus respectivos atributos e métodos, bem como demonstrar como
			as classes do diagrama se relacionam, complementam e transmitem informações entre si


		**Diagrama de classes – Centro Universitário SENAC*
		FIGURA

		**Fonte: Elaborado pelo autor**


<h5><em><strong>CONSIDERAÇÕES FINAIS</strong></em></h5>


		Ao realizar este projeto, concluímos que ele é um elemento fundamental na análise e desenvolvimento
		de sistemas, pois ele define a melhor direção e o escopo do trabalho a ser realizado. 
		
		O diagrama de caso de uso, nos permitiu através da representação gráfica descrever como os usuários
		interagem com um sistema. Ele foi uma ferramenta importante para modelarmos e documentarmos a lógica
		do sistema e como os usuários o utilizam. A utilização da descrição dos casos de uso que é uma parte
		importante do processo de análise de requisitos e modelagem de sistemas, nos permitiu entender melhor
		como os usuários interagem com o sistema e quais são suas necessidades e objetivos no projeto.


<h5><em><strong>REFERÊNCIAS</strong></em></h5>


		PRESSMAN, S. Roger. Engenharia de software. 3. ed. São Paulo: McGraw-Hill, 1995.

		LEITE, Jair C. Engenharia de software: ciclos de vida. Universidade do Rio Grande do Norte, 2006.
		
		SOMMERVILLE, Ian. Engenharia de software. 8. ed. São Paulo: Pearson Addison-Wesley, 2007.
		
		ALBERTIN, Alberto L. Administração de informática: funções e fatores críticos de sucesso. 6. ed. São Paulo: Atlas, 2009.
		
		SCHACH, Stephen R. Engenharia de software: os paradigmas clássicos e orientado a objetos. 7. ed. Porto Alegre: AMGH, 2010.
		
		ENTLEY, Lonnie; WHITTEN, Jeffrey. L. Systems analysis and design methods. 7. ed. New York: Irwin/McGraw Hill, 2000.
		
		GUEDES, Gilleanes T. A.  UML 2: uma abordagem prática. 3. ed. São Paulo: 
		Novatec, 2018.
		










<h5><em><strong>3.0 Diagrama de classes.</strong></em></h5>


	Uma forma simples para representarmos classes é o uso de diagrama, ou seja, representação gráfica que descreve classes, objetos e relações entre eles em um sistema. Por isso é uma ferramenta importante para modelar e documentar todo estrutura do sistema.

Guedes (2018) acrescenta que o diagrama de classes é um dos diagramas mais importantes como ferramenta de desenvolvimento. Seu principal objetivo está em permitir as visualizações das classes que constituem o software com seus respectivos atributos e métodos, bem como demonstrar como as classes do diagrama se relacionam, complementam e transmitem informações entre si


		**Diagrama de classes – Centro Universitário SENAC*
		FIGURA

		**Fonte: Elaborado pelo autor**


<h5><em><strong>CONSIDERAÇÕES FINAIS</strong></em></h5>


	Ao realizar este projeto, concluímos que ele é um elemento fundamental na análise e desenvolvimento de sistemas, pois ele define a melhor direção e o escopo do trabalho a ser realizado. 
		
	O diagrama de caso de uso, nos permitiu através da representação gráfica descrever como os usuários interagem com um sistema. Ele foi uma ferramenta importante para modelarmos e documentarmos a lógica do sistema e como os usuários o utilizam. A utilização da descrição dos casos de uso que é uma parte importante do processo de análise de requisitos e modelagem de sistemas, nos permitiu entender melhor como os usuários interagem com o sistema e quais são suas necessidades e objetivos no projeto.


<h5><em><strong>REFERÊNCIAS</strong></em></h5>


	PRESSMAN, S. Roger. Engenharia de software. 3. ed. São Paulo: McGraw-Hill, 1995.

LEITE, Jair C. Engenharia de software: ciclos de vida. Universidade do Rio Grande do Norte, 2006.
		
	SOMMERVILLE, Ian. Engenharia de software. 8. ed. São Paulo: Pearson Addison-Wesley, 2007.
		
	ALBERTIN, Alberto L. Administração de informática: funções e fatores críticos de sucesso. 6. ed. São Paulo: Atlas, 2009.
		
	SCHACH, Stephen R. Engenharia de software: os paradigmas clássicos e orientado a objetos. 7. ed. Porto Alegre: AMGH, 2010.
		
	ENTLEY, Lonnie; WHITTEN, Jeffrey. L. Systems analysis and design methods. 7. ed. New York: Irwin/McGraw Hill, 2000.
		
	GUEDES, Gilleanes T. A.  UML 2: uma abordagem prática. 3. ed. São Paulo: Novatec, 2018.
		














<h5><em><strong>3.0 Diagrama de classes.</strong></em></h5>


		Uma forma simples para representarmos classes é o uso de diagrama, ou seja, representação gráfica que descreve classes, objetos e relações entre eles em um sistema. Por isso é uma ferramenta importante para modelar e documentar todo estrutura do sistema.

			> Guedes (2018) acrescenta que o diagrama de classes é um dos diagramas mais importantes como ferramenta de desenvolvimento. Seu principal objetivo está em permitir as visualizações das classes que constituem o software com seus respectivos atributos e métodos, bem como demonstrar como as classes do diagrama se relacionam, complementam e transmitem informações entre si


		***Diagrama de classes – Centro Universitário SENAC***
		FIGURA

		***Fonte: Elaborado pelo autor***


<h5><em><strong>CONSIDERAÇÕES FINAIS</strong></em></h5>


		Ao realizar este projeto, concluímos que ele é um elemento fundamental na análise e desenvolvimento de sistemas, pois ele define a melhor direção e o escopo do trabalho a ser realizado. 
		
		O diagrama de caso de uso, nos permitiu através da representação gráfica descrever como os usuários interagem com um sistema. Ele foi uma ferramenta importante para modelarmos e documentarmos a lógica do sistema e como os usuários o utilizam. A utilização da descrição dos casos de uso que é uma parte importante do processo de análise de requisitos e modelagem de sistemas, nos permitiu entender melhor como os usuários interagem com o sistema e quais são suas necessidades e objetivos no projeto.


<h5><em><strong>REFERÊNCIAS</strong></em></h5>


		PRESSMAN, S. Roger. Engenharia de software. 3. ed. São Paulo: McGraw-Hill, 1995.

		LEITE, Jair C. Engenharia de software: ciclos de vida. Universidade do Rio Grande do Norte, 2006.
		
		SOMMERVILLE, Ian. Engenharia de software. 8. ed. São Paulo: Pearson Addison-Wesley, 2007.
		
		ALBERTIN, Alberto L. Administração de informática: funções e fatores críticos de sucesso. 6. ed. São Paulo: Atlas, 2009.
		
		SCHACH, Stephen R. Engenharia de software: os paradigmas clássicos e orientado a objetos. 7. ed. Porto Alegre: AMGH, 2010.
		
		ENTLEY, Lonnie; WHITTEN, Jeffrey. L. Systems analysis and design methods. 7. ed. New York: Irwin/McGraw Hill, 2000.
		
		GUEDES, Gilleanes T. A.  UML 2: uma abordagem prática. 3. ed. São Paulo: 
		Novatec, 2018.
		


