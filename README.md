# Seção de Recursos · Quatro Cartões

Estudo de layout em CSS para apresentar quatro cartões de funcionalidades com ícones.

## O que o projeto apresenta

- Cartões Supervisor, Calculadora, Equipe e Karma no markup original.
- Arquivo de estilos e ícones SVG.
- Organização visual de blocos horizontais e verticais.

## Tecnologias

HTML · CSS

## Executar localmente

Consulte o HTML original ao final deste README. O repositório não possui atualmente uma página HTML executável na raiz.

## Estrutura

- `README.md`
- `favicon-32x32.png`
- `icon-calculator.svg`
- `icon-karma.svg`
- `icon-supervisor.svg`
- `icon-team-builder.svg`
- `style.css`

## Estado atual

O HTML original foi armazenado no próprio README, sem arquivo `index.html`. Ele é preservado abaixo para consulta. Para uma página executável, salve o trecho em um arquivo HTML e ajuste os caminhos de imagens para os arquivos existentes.

## Autoria

[Weldon Carlos](https://github.com/WeldonCarlos) · [LinkedIn](https://www.linkedin.com/in/weldon-carlos-41b488231/)

<details>
<summary>HTML original preservado</summary>

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seção de recursos de quatro cartões</title>
    <link rel="shortcut icon" href="../four-card-feature-section-master/images/favicon-32x32.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="cabeca"> 
        <h2 class="texto-um-cabeca" >
            Entrega, confiável e eficiente
        </h2>
        <h2 class="texto-dois-cabeca"  >  
            Alimentado por Tecnologia
        </h2>

        <h3 class="texto-tres-cabeca" > 
            Nossos pedágios alimentados por inteligência artificial usam milhões de dados  
        </h3>
        <h3 class="texto-quatro-cabeca" >
            do projeto pontos para garantir que seu projeto seja bem-sucedido
        </h3>
    </header>

        <main id="corpo">
           
            <section id="blocos-horizontais" >
            
            <div class="bloco-um">
                <h2 class="titulo-bloco-um" >
                    Supervisor
                    
                </h2>
                    <h3 class="subtitulo-um" >
                        Monitorar as atividades para identificar os 
                    </h3>
                    <h3 class="subrtitulo-dois" >
                        bloqueios do projeto 
                    </h3> 
                            <img class="ico-bloco-um" src="../four-card-feature-section-master/images/icon-supervisor.svg" alt="">

            </div>
            
            <div class="bloco-tres">
                <h2 class="titulo-bloco-tres" >
                    Calculadora
                </h2>
                    <h3 class="subtitulo-bloco-tres" >
                        Usa dados de projetos anteriores para fornecer 
                    </h3>
                    <h3 class="subtitulo3">
                        estimativas de entrega líquidas
                    </h3>
                       <img class="ico-bloco-tres" src="../four-card-feature-section-master/images/icon-calculator.svg" alt="">
            </div>

        </section>

        <section id="blocos-verticais">
        
       
            <div class="bloco-dois">
                <h2 class="titulo-bloco-dois" >
                    Formador de equipe
                </h2>
                    <h3 class="subtitulo-bloco-dois" >
                        Analisa nossa rede de talentos para  criar a 
                    </h3>

                    <h3 class="subtitulos2-bloco-dois" >
                         equipe ideal para o seu projeto
                    </h3>
                        <img class="ico-bloco-dois" src="../four-card-feature-section-master/images/icon-team-builder.svg" alt="">
            </div>
      
               
                        
                        <div class="bloco-quatro" >
                            <h2 class="titulo-bloco-quatro">
                                Karma
                            </h2>
                                <h3 class="subtitulo-b-4" >
                                    Avalia regularmente nosso talento para 
                                </h3>
                                <h3 class="sub-sub">
                                    garantir a qualidade 
                                </h3>
                                    <img class="ico-bloco-quatro" src="../four-card-feature-section-master/images/icon-karma.svg" alt="">
                        </div>
        </section>

        </main>
    
</body>
</html>

```

</details>
