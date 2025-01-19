# Dataset
Decidimos treinar uma IA para classificar imagens de construções de pequeno e médio porte entre casas e prédios/edifícios.

Após a decisão de qual classificação iríamos realizar, partimos em busca de datasets contendo imagens dessas 2 categorias de construções que almejamos classificar.
Como não encontramos 1 dataset perfeito, decidimos mesclar diferentes datasets. 
Um dataset contendo imagens de casas e outro contendo pequenos prédios foram utilizados.

Para não extrapolarmos demais o tamanho dos datasets, visto que estamos trabalhando com imagens, decidimos utilizar apenas 100 imagens de cada categoria.
Utilizamos o padrão de divisão 70:20:10 para train, validation e test respectivamente.

### Dataset 1: Prédios
De início, encontramos um dataset com imagens de boas resoluções de prédios de pequeno porte (em geral, até 5 ou 6 andares).
Conferimos que as imagens deste dataset possuiam tamanho fixo de 1024x1024 e que todas as extensões estavam uniformizadas como .jpg, o que facilitou bastante o nosso processo.

Após a escolha randômica das imagens coletadas, dividimos as mesmas nas pastas `/train` `/validation` e `/test`.

Link do dataset 1 original: https://universe.roboflow.com/combined-uav-object-recognition/building-facade-segmentation-original-9p4g8/dataset/1

### Dataset 2: Casas
Em seguida, nos propomos a procurar o dataset com as imagens das casas.

Após a escolha randômica das imagens coletadas, seguimos o processo de separação das mesmas no mesmo esquema de pastas realizado para o dataset 1.

Link do dataset 2 original: https://images.cv/dataset/house-image-classification-dataset
