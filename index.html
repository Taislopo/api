<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rick and morty</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-LN+7fdVzj6u52u30Kp6M/trliBMCMKTyK833zpbD+pXdCLuTusPj697FH4R/5mcr" crossorigin="anonymous">
    <link rel="stylesheet" href="./css/style.css">
</head>

<body class="bg-light">
    <div class="container my-5">
        <h1 class="text-center mb-4">Rick and Morty</h1>
        <div id="rick-container" class="row row-cols-1 row-cols-sm-2 row-cols-3-md-3">

        </div>
    </div>

    <script>





        
        const container = document.getElementById('rick-container')
        function procurarrickmothy(id){
            return fetch("https://rickandmortyapi.com/api/character/" + id)
            
            .then(function(resposta){
                return resposta.json() //.json = especie de banco de dados web     
            })
        }
        async function carregarrickmothy(){   //async = da um tempo de espera
            for(let i = 1; i <= 9; i++){    //laço de repetição(ate o 6)
                const rickmothyAtual = await procurarrickmothy(i)   //Se uma Promise é passada para uma expressão await, ele espera pela sefinalização da Promise e retorna seu valor final
                let nome = rickmothyAtual.name
                let idrickmothy = rickmothyAtual.id
                let imagem = rickmothyAtual.image
                

                const coluna = document.createElement('div')    //criando uma classe no html
                coluna.className = 'col';    //dando uma classe na div
                coluna.innerHTML = `
                    <div class="card h-100 shadow-sm"> 
                    <div class="card-body text-center">
                        <img src="${imagem}" alt="${nome}">
                        <h5 class="card-title">${nome}</h5>
                        <p class="card-text text-muted">#${idrickmothy}</p>
                    </div>
                    </div>
                `
                    //cards onde cada {} recebe um endereço que se pega do api e se trasfoma em cads com nomes e fotos automaticamente
                container.appendChild(coluna)
            }
        }
    </script>
</body>
</html>