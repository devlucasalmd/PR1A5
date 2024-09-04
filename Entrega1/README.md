# Entrega 1

Visão geral  
      - Introdução;   
      - Objetivos   
      - Justificativa   
      - Problema   
    - Tecnologias utilizadas (Linguagem de programação, banco de dados, etc);   
    - Usuários (Mínimo 3);
      - Quais tipos de usuarios você tem?       
    - Requisitos Funcionais (Mínimo 30) e Não Funcionais (Mínimo 10);   
    - Casos de uso (Apenas o título - Mínimo 20);   
    - Definição dos casos de uso que serão desenvolvidos na disciplina PR1A5 (no mínimo 12 casos de uso).   
   
   
1. Introdução   
   Obs.: Fazer introdução, lojas de roupas, pesquisa sobre roupas, marketplace   
   
1.1 Objetivos   

O objetivo do projeto é criar um site onde lojas/vendedores poderão ter sua conta e colocar seus produtos com foto, preço, tamanho, descrição e etc. Tendo também um espaço com dashboard com algumas informações referentes às vendas.  Na visão do cliente, será possivel criar conta para poder fazer compras, participar de promoções, descontos e etc.   

1.2 Justificativa - Obs.: Responder o Problema   

Visando a possibilidade de lojas "pequenas" aumentarem suas vendas sem precisar ter um site proprio, podendo colocar de forma simples seus produtos e informações sobre eles.

1.3 Problema   

Colocar produtos em sites já estabelecidos,  muita vezes aumenta a concorrencia por já ter lojas estabelecidas e taxas altas cobradas, não tendo um retorno esperado. Limitando o espaço de venda para apenas o espaço fisico, não explorando os meios possiveis para que possa aumentar suas vendas e lucros.   


1. Tecnologias Usadas - Obs.: Colocar em forma de Texto   
- JavaScript, React, NodeJS, SQL Server, Docker

2. Usuários - Obs.: Tabela   
- Usuário 1 - Perfil do vendedor/loja: Terá acesso a toda parte de colocar informações sobre os produtos, fotos e etc. Também irá ter acesso ao dashboard.   
- Usuário 2 - Perfil do cliente: Terá acesso a sua conta, podendo editar informações e também acesso ao catalogo dos produtos oferecidos pelas lojas.   
- Usuário 3 - Admnistrador do site   


1. Requisitos - Obs.: Colocar Texto sobre o que é requisito, citar autor.   

4.1 Requisitos Funcionais: - Texto sobre requisito funcional / Fazer Tabela   
REQUISITOS FUNCIONAIS	   
Usuario 1	   
RF001 - Manter Usuario 	O sistema deve permitir realizar as 4 operações do CRUD no perfil do Usuário   
RF002 - Manter Produtos	O sistema deve permitir realizar as 4 operações do CRUD nos produtos   
RF003 - Dashboard	O sistema deve fornecer um dashboard com informações das vendas    
RF004 - Comentarios	O sistema deve permitir que seja possivel responder comentarios    
RF005 - Promoções	O sistema deve permitir o usuario colocar produtos na aba promoções   
RF006 - Historico	O sistema deve mostrar o historico de vendas   
RF007 - Avaliações	O sistema deve mostrar as avaliações recebidas dos clientes

   
Usuario 2	   
RF008 - Manter Usuario	O sistema deve permitir realizar as 4 operações do CRUD no perfil do Usuário   
RF009 - Historico	O sistema deve mostrar o historico de compras do cliente   
RF010 - Salvar Produto	O sistema deve permitir salvar produtos que o usuario tem interesse   
RF011 - Acompanhar	O sistema deve permitir o rastreio do produto comprado   
RF012 - Lista de Presente O sistema deve permitir a criação de lista de presente   
   
      

Usuario 3   
RF013 - Catalogo O sistema deve permitir a atualizacao do catalogo   
   
    
Sistema	   
RF014 - Catalogo	O sistema deve fornecer o catalogo com os produtos cadastrados   
RF015 - Login	O sistema deve permitir a realização de login   
RF016 - Senha	O sistema deve permitir a recuperação da senha   
RF017 - Frete	O sistema deve permitir o calculo do frete   
RF018 - Pesquisa	O sistema deve permitir a pesquisa do produto através do nome   
RF019 - Carrinho	O sistema deve permitir listar os produtos inseridos pelo o cliente   
RF020 - Pagamento	O sistema deve permitir os principais meios de pagamento   
RF021 - Filtros	O sistema deve fornecer filtros para pesquisa dos produtos   
RF022 - Contato	O sistema deve fornecer as opções para entrar em contato    
RF023 - Abas	O sistema deve fornecer abas exclusivas Ex: Promoção, Destaques, etc.   
RF024 - Avaliação	O sistema deve mostrar avaliação do produto    
RF025 - Comentarios	O sistema deve mostrar comentarios sobre o produto   
RF026 - Recomendações	O sistema deve mostrar recomendações de produtos similares   
RF027 - Produtos	O sistema deve mostrar informações dos produtos   
RF028 - Notificações O sistema deve notificar os usuarios sobre qualquer movimentação    
RF029 - Logs O sistema deve conter logs    
RF030 - Boleto O sistema deve fornecer o boleto para o cliente   

4.2 Requisitos não funcionais: - Texto sobre requisito funcional / Fazer Tabela    
RNF01 - O sistema deve conter uma interface intuitiva    
RNF02 - O sistema deve permitir a melhor experiencia no momento de colocar os produtos para venda    
RNF03 - O sistema deve ter autenticação em duas etapas    
RNF04 - O sistema deve criptografar as senhas dos usuarios    
RNF05 - O sistema deve conter menu   
RNF06 - O sistema deve ser responsivo     
RNF07 - O sistema deve responder as requisições dos usuarios    
RNF08 - O sistema deve gerar relatorios em pdf sobre as vendas    
RNF09 - O sistema deve enviar para o email do cliente informações sobre a compra    
RNF10 - O sistema deve enviar para o email do vendedor informações sobre a venda    
RNF11 - O sistema deve conter backup semanalmente do banco de dados   

1. Casos de Uso   
UC01 - Realizar compra    
UC02 - Verificar informações da venda    
UC03 - Atualizar o catalogo    
UC04 - Login   
UC05 - Visualizar dashboard   
UC06 - Carrinho   
UC07 - Pagamento   
UC08 - Filtrar Catalogo   
UC09 - Busca por produto   
UC10 - Cadastro   
UC11 - Visualizar produto   
UC12 - Visualizar historico   
UC13 - Visualizar avaliações   
UC14 - Visualizar Boleto    
UC15 - Redefinir senha    
UC16 - Calcular Frete    
UC17 - Lista de Presente    
UC18 - Cancelamento de Compra   
UC19 - Devolução do Produto   
UC20 - Checkout   

1. Definição dos casos de uso    
UC01 - Cadastro    
UC02 - Login   
UC03 - Verificar informações da venda   
UC04 - Filtrar Catalogo    
UC05 - Busca por produto   
UC06 - Carrinho    
UC07 - Atualizar o catalogo   
UC08 - Visualizar produto   
UC09 - Redefinir senha   
UC10 - Lista de Presente   
UC11 - Realizar compra  
UC12 - Checkout   

