# EcoDrive Database Project 📊

---
## Integrantes do Projeto 👥

- **Luis Henrique Oliveira da Silva** - RM 552692  
- **Matheus Duarte Oliveira** - RM 554199  
- **Sabrina da Motta Café** - RM 553568
---

## Descrição do Projeto

O projeto EcoDrive tem como objetivo desenvolver uma solução para facilitar o uso de veículos elétricos na cidade de São Paulo, promovendo a conscientização ambiental e melhorando a experiência dos usuários em relação à recarga desses veículos. A solução é composta por uma plataforma mobile integrada com serviços de geolocalização, agendamento, histórico de carregamento e análise de impacto ambiental, além de destacar a utilização de energias renováveis.

### Funcionalidades principais:

- **Conscientização Ambiental**: Apresentar informações sobre os benefícios dos veículos elétricos em comparação com os de combustão, enfatizando eficiência energética, custo-benefício e impacto ambiental.
- **Localização de Estações de Carregamento**: Permitir que os usuários localizem estações próximas, utilizando APIs de mapas, e obtenham detalhes como disponibilidade, tipos de carregadores e preços.
- **Reserva de Pontos de Carregamento**: Implementar uma funcionalidade que permita aos usuários agendar e reservar pontos de recarga, com notificações sobre status e lembretes.
- **Histórico de Carregamento e Gastos**: Oferecer relatórios detalhados sobre sessões de carregamento, incluindo custos, tempos e locais, e ferramentas de análise de uso.
- **Integração com Energias Renováveis**: Identificar e promover estações que utilizam fontes de energia sustentáveis, destacando a redução de emissões de carbono.

---

## Links
- **Modelo Conceitual**: [Diagrama ER no Figma](https://www.figma.com/design/Ir8V7KPSws9gH2ncECyi20/Global-Solution-FIGMA?node-id=0-1&t=lP467r4AvsqUzDdJ-1)
- **Documentação do Projeto**: [Miro Board](https://miro.com/welcomeonboard/V2NOUThhVkZWb3F5YVhPcHlKZ1lEYjMxdVF6bzBFbDJDL21wdE5OcFAzb1M4SSt1cm5uNTFldGI2SE1tZGo2ZFNMbTZIcUx0ZzBwdGlWemtQSjNVamVTblNRd0hWWWw2clpGd0Rwd0JXMmQ0S1RHelhxMHZ2VUZwdHFUWWJuTGwhZQ==?share_link_id=468499909302)
- **Vídeo Pitch**: [Vídeo no YouTube](https://www.youtube.com/watch?v=8bzh6oU2oPI)
- **Demonstração da Aplicação**: [Vídeo de Demonstração](https://www.youtube.com/watch?v=UyvLvyCwWyY)

---

## Configuração do Projeto ⚙️

Para rodar o projeto, siga as etapas abaixo:

1. **Configuração do Banco de Dados**:
   - Crie o banco de dados OracleSQL utilizando o script `create_db.sql` fornecido.
   - Execute os scripts de criação de tabelas e inserção de dados iniciais.

2. **Configuração da Aplicação Java**:
   - Certifique-se de ter o JDK instalado.
   - Configure a conexão com o banco de dados no arquivo `dbconfig.properties`:
     ```properties
     db.url=jdbc:oracle:thin:@localhost:1521:xe
     db.username=seu_usuario
     db.password=sua_senha
     ```
   - Compile e execute a aplicação Java.

---

## Estrutura do Projeto 📁

- **src**: Código-fonte Java.
- **sql**: Scripts SQL para criação e manipulação do banco de dados.
- **docs**: Documentação do projeto, incluindo diagramas e especificações técnicas.
- **resources**: Arquivos de configuração e outros recursos necessários para a execução do projeto.

---

## Arquitetura do Projeto 🏗️

O projeto EcoDrive utiliza uma arquitetura composta por dois ambientes de máquina virtual (VM):

1. **VM com Sistema Operacional Windows**:
   - **API Backend**: Implementada em Java, responsável por gerenciar as funcionalidades de reserva e notificações.
   - **Requisitos de Software**: Java 8u311 ou superior, IntelliJ IDEA 2024.3, Postman 11.19.0.
   - **Requisitos de Hardware**: RAM: 8 GB, CPU: Processador moderno multi-core, Disco: SSD.

2. **VM com Sistema Operacional Linux**:
   - **Banco de Dados Oracle**: Hospeda o banco de dados Oracle, armazenando informações relacionadas às estações, reservas, histórico e usuários.
   - **Requisitos de Software**: Oracle SQL Developer, JDK 17.
   - **Requisitos de Hardware**: RAM: 8 GB, CPU: Processador moderno multi-core, Disco: 2 GB livres.

---

## Escolhas das IDEs

- **IntelliJ IDEA**: Escolhido por suas funcionalidades avançadas, suporte ao Spring Boot, inteligência de código, facilidade de configuração, análise de dependências, e gerenciamento com Maven.
- **Oracle SQL Developer**: Utilizado durante o curso de Análise e Desenvolvimento de Sistemas na disciplina de Banco de Dados, proporcionando um ambiente robusto para desenvolvimento SQL.

---

Este projeto foi desenvolvido como parte do curso de DevOps Tools & Cloud Computing, visando a aplicação prática dos conceitos aprendidos e a integração de tecnologias modernas para a solução de problemas reais.
