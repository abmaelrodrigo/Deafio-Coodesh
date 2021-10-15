# Desafio-Coodesh



## Q.A Challenge 20200715 – Testes da Página https://beta.coodesh.com/

**Tester:** Abmael Souza
**Ambiente:** Google Chrome 93 – Desktop 
**Sistema operacional:** Windows 10 Pro 
**Data de execução dos testes:** 14 e 15/10/2021

### A . Objetivo
**Validar a página https://beta.coodesh.com/ nos seguintes aspectos:**

1- Se a página está carregando corretamente a home page;
2- Navegar pela página e ir ao sistema de vagas no menu superior;
3- Um vez na tela de vagas, nosso sistema de teste automatizado terá que buscar por uma empresa onde terá um ou mais resultados de vagas;
4- Depois obter o resultado, deveremos abrir a vaga e revisar se o carregamento é realizado com sucesso ou não;
5- Por último, precisamos saber se o sistema de candidatar está funcionando e para isso é necessário clicar no botão Candidatar-se e revisar se abriu o modal corretamente.


### B. Framework utilizado
    • Ghost Inpector (https://app.ghostinspector.com/)
    • Razões: rápido aprendizado, fácil manipulação de dados, geração de relatórios, foco em UI, não precisa ter conhecimento avançado em programação, documentação detalhada.
    • Pontos negativos: software pago, execução de testes lenta em relação ao Cucumber e Selenium, dificuldades com assertividades de pop ups. 

### C. Ciclos, Cenários e Casos de Teste

**Ciclo 1 – Validar se a página está carregando corretamente a home page**

Cenário 1.1 – Validar o HEADER
    • Validar a visualização dos elementos do Header
    • Validar o funcionamento dos elementos do Header

Cenário 1.2 – Validar a seção “Atinja suas metas...”
    • Validar a visualização da seção “Atinja suas metas”
    • Validar o funcionamento do botão “Quero Contratar”

Cenário 1.3 – Validar a seção “Empresas que contratam pela Coodesh”
    • Validar a visualização da seção, 
    • Validar a presença do carrossel de empresas 
    • Validar o clique em uma das empresas no carrossel
    • Validar o clique no botão “Veja mais empresas”

Cenário 1.4 – Validar a seção “Oportunidades de Trabalho Remoto”
    • Validar a visualização da seção
    • Validar a presença de, pelo menos, uma oportunidade de emprego 
    • Validar o clique em uma das oportunidades de emprego 
    • Validar o clique no botão “Quero novos desafios”

Cenário 1.5 – Validar a seção “Procurando talentos tech?”
    • Validar a visualização da seção
    • Validar a presença dos banners
    • Validar o clique no botão “Saiba mais” 
    • Validar o clique no botão “Começar Grátis”

Cenário 1.6 – Validar a seção “Leia nossas últimas novidades”
    • Validar a visualização da seção
    • Validar a presença de, pelo menos, um artigo
    • Validar a visualização e o clique no ícone de transição de notícias 
    • Validar a visualização o clique na seta à direita de transição de notícias 
    • Validar a visualização o clique na seta à esquerda de transição de notícias 
    • Validar o clique em uma das notícias

Cenário 1.7 – Validar o Footer
    • Validar a visualização da seção
    • Validar o clique nas redes sociais 
    • Validar o clique em uma das subseções das áreas “Coodesh”, “Para empresas”, “Para Developers” e “Links Úteis”
    • Validar a visualização dos selos 
    • Validar o clique no botão “Go to top”


**Ciclo 2 – Validar o login, busca e exibição de vagas**
Cenário 2.1 – Validar o cadastro de novo usuário
    • Validar a criação de usuário do Login com dados inválidos
    • Validar a criação de usuário do Login com dados válidos

Cenário 2.2 – Validar o Login
    • Validar a realização do Login com dados inválidos
    • Validar a realização do Login com dados válidos

Cenário 2.2 – Validar a pesquisa por vagas
    • Validar a busca com dados inválidos (Categoria e Onde)
    • Validar a busca com dados válidos (Categoria e Onde)
    • Validar os filtros Categoria e Nível 

Cenário 2.3 – Validar o conteúdo da vaga e candidatura 
    • Validar a exibição dos campos da vaga
    • Validar a exibição dos botões de Candidatura
    • Validar a modal de candidatura 

### D.Resultados

	Como os testes foram feitos em um ambiente onde não houve mudanças de escopo do site, como novos artigos, novas vagas de trabalho, mudança de layout, etc., obtivemos resultados positivos para todos os casos de testes implementados. 
	O tempo de implementação de tais testes foi menor caso utilizássemos utilizando Cumcumber ou Selenium, porém, o tempo de execução é relativamente maior que seus concorrentes, uma vez que é tudo é processado no servidor remoto da empresa administradora da Ghost Inspector, incluindo os vídeos.
	Conclui-se que a utilização dessa ferramenta para o teste de interface e usabilidade do site em questão é o que melhor supre as necessidades, tendo em vista que não foram necessários testes mais robustos ou que envolvessem back-end.
	Por fim, em relação aos testes não funcionais, percebe-se que o site beta da Coodesh possui uma interface simples e intuitiva, que ajuda o usuário a entender o objetivo do site e como interagir com o mesmo. Isso acaba sendo refletido na facilidade que encontrei para testá-lo.


Todos os resultados e vídeos podem ser encontrados neste repositório. O Ghost Inspector permitiu a exportação dos casos de teste em formato JSON. Para que o time tenha acesso ao ambiente de eecução de testes seria necessário ter o e-mail de cada membro da equipe. 
