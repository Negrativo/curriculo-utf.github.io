<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Currículo Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        
        .header {
            text-align: right;
            margin-bottom: 30px;
            font-style: italic;
            color: #666;
        }
        
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        
        h2 {
            color: #2980b9;
            margin-top: 25px;
        }
        
        h3 {
            color: #16a085;
            margin-bottom: 5px;
        }
        
        .job-title {
            font-weight: bold;
            margin-bottom: 0;
        }
        
        .company {
            font-weight: normal;
            display: inline;
        }
        
        .job-period {
            color: #666;
            margin-top: 0;
        }
        
        .job-location {
            font-style: italic;
        }
        
        .profile-img {
            float: right;
            margin: 0 0 20px 20px;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #3498db;
        }
        
        .highlight {
            background-color: #f9f9f9;
            padding: 15px;
            border-left: 4px solid #3498db;
            margin: 20px 0;
            color: #7f8c8d;
        }
        
        .footer {
            margin-top: 40px;
            text-align: right;
        }
        
        .footer a {
            color: #3498db;
            text-decoration: none;
            margin-left: 15px;
        }
        
        .skills {
            margin-top: 10px;
            font-style: italic;
        }
        
        .employment-type {
            display: inline-block;
            margin-left: 10px;
            color: #666;
        }
    </style>
</head>
<body>
    <h1>Meu Currículo Profissional</h1>
    
    <img src="./public/eu.jpg" alt="Minha Foto de Perfil" class="profile-img">
    
    <h2>Informações Pessoais</h2>
    <p>Nome: João Lucas Rodrigues de Souza</p>
    <p>Idade: 24 anos</p>
    <p>E-mail: lucas.rsouza2000@gmail.com</p>
    <p>Telefone: (43) 99806-8333</p>
    <p>Localização: Londrina, Paraná</p>
    
    <h2>Formação Acadêmica</h2>
    <h3>Tecnólogo em Análise e Desenvolvimento de Sistemas</h3>
    <p>Universidade Tecnológica Federal do Paraná - 2019 a 2025</p>
    
    <div class="highlight">
        <p>"Programador de sistemas web Angular e React, como também aplicações mobile com Java, Kotlin e React Native. 
            Sou especializado em Java, JavaScript e Typescript, com pontos fortes em Backend com Spring Boot e Node.js, Front-end em React e React Native seja com JavaScript ou Typescript."</p>
    </div>
    
    <h2>Experiência Profissional</h2>
    
    <h3 class="job-title">Desenvolvedor de sistemas Full-stack/Java <span class="company">- Grupo Muffato</span></h3>
    <p class="job-period">set de 2024 - o momento - 7 meses <span class="employment-type">· Tempo integral · Presencial</span></p>
    <p class="job-location">Londrina, Paraná, Brasil</p>
    <p>Desenvolvimento e manutenção de servidor Java Spring. Manutenção em Banco de dados Oracle e MySQL. Como também sistemas web em React e PHP.</p>
    
    <h3 class="job-title">Desenvolvedor full stack <span class="company">- Integra Tecnologia</span></h3>
    <p class="job-period">set de 2023 - set de 2024 - 1 ano 1 mês <span class="employment-type">· Tempo integral · Remota</span></p>
    <p class="job-location">Londrina, Paraná, Brasil</p>
    <p>Desenvolvimento e manutenção de sistemas web utilizando React com servidor em Java.</p>
    <p>Desenvolvimento de front-end e Desenvolvimento de back-end.</p>
    
    <h3 class="job-title">Desenvolvedor Web/Java <span class="company">- myOrg</span></h3>
    <p class="job-period">ago de 2021 - mar de 2023 - 1 ano 8 meses <span class="employment-type">· Tempo integral</span></p>
    <p class="job-location">Londrina, Paraná, Brasil</p>
    <p>Desenvolvimento web em Angular TypeScript com integração em servidor Java Spring Boot.</p>
    <p>Manutenção e implementação em sistema de gestão e refinamento de metas, direcionado para indústria.</p>
    <p class="skills">Java, Scrum e mais 12 competências</p>
    
    <h3 class="job-title">Analista de sistema <span class="company">- Solus Computação</span></h3>
    <p class="job-period">mar de 2020 - ago de 2021 - 1 ano 6 meses <span class="employment-type">· Tempo integral</span></p>
    <p class="job-location">Londrina, Paraná</p>
    <p>Manutenção e correção em sistema de gestão de plano de saúde, sendo utilizado por operadoras de plano de saúde e hospitais.</p>
    <p>Atendimento ao cliente e suporte, correções em sistema desktop Delphi, servidores.</p>
    <p class="skills">Java, Serviços web e mais 7 competências</p>
    
    <div class="footer">
        <a href="https://www.linkedin.com/in/lucas-souza-negrativo/">Link direto para o meu Linkedin</a>
        <a href="https://github.com/Negrativo">Link direto para o meu GitHub</a>
    </div>
</body>
</html>
