<!-- Cabeçalho ITEC -->
<div align="center">
  <img src="../img/logo_itec.png"
       alt="Logo ITEC"
       width="300"/>

  <h3>Instituto de Tecnologia e Computação</h3>
  
  ---
</div>

# Computação Gráfica

## Ementa

Gráficos vetoriais e imagens matriciais (*bitmaps*); renderização em CPU e GPU; *framebuffers*, resolução e profundidade de cor; sistemas de coordenadas e transformações geométricas; operações matriciais de rotação, translação e escala; coordenadas homogêneas; transformações bidimensionais e tridimensionais; primitivas gráficas 2D, incluindo desenho de linhas e círculos, recorte e preenchimento de polígonos; modelagem tridimensional; sistemas de coordenadas de modelo, mundo, visão e tela; transformações de visualização; projeções de câmera em perspectiva e ortogonal; matrizes de projeção; recorte e volumes de visualização em 3D; modelos de iluminação ambiente, difusa e especular; técnicas de sombreamento de Gouraud e Phong; modelos de reflexão de superfícies; geração de sombras; modelos de cores RGB, HSV e CMYK; interpolação; mapeamento e filtragem de texturas; composição alfa e transparência; técnicas de antisserrilhamento; e introdução à OpenGL.

## Bibliografia Básica

1. CARDOSO, Leandro da Conceição. **Introdução ao processo de renderização**. 1. ed. Curitiba: InterSaberes, 2023.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/214432](https://plataforma.bvirtual.com.br/Acervo/Publicacao/214432)
   - **Justificativa:** apresenta os fundamentos do processo de renderização, contribuindo para a compreensão das etapas de geração de imagens, modelagem, iluminação, materiais, texturas e visualização de cenas.

2. GONZALEZ, Rafael C.; WOODS, Richard E. **Processamento digital de imagens**. 3. ed. São Paulo: Pearson, 2009.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/2608](https://plataforma.bvirtual.com.br/Acervo/Publicacao/2608)
   - **Justificativa:** fornece fundamentos sobre representação digital de imagens, modelos de cores, resolução, profundidade, interpolação, filtragem e transformações, complementando os conteúdos de computação gráfica.

3. SHIRLEY, Peter; BLACK, Trevor David; HOLLASCH, Steve. **Ray Tracing in One Weekend**. [S. l.: s. n.], 2024. Licença CC0. 

   - 🔗 [https://raytracing.github.io/](https://raytracing.github.io/)
   - **Justificativa:** apresenta uma implementação didática de um renderizador baseado em traçado de raios, integrando conceitos de câmera, geometria, interseção, materiais, iluminação, reflexão e geração de imagens.

## Bibliografia Complementar

1. DE VRIES, Joey. **Learn OpenGL**: learn modern OpenGL graphics programming in a step-by-step fashion. [S. l.: s. n.], 2020. PDF de acesso livre no site oficial. 

   - 🔗 [https://learnopengl.com/book/book_pdf.pdf](https://learnopengl.com/book/book_pdf.pdf)
   - **Justificativa:** oferece uma abordagem prática e progressiva da programação gráfica com OpenGL, abrangendo transformações, câmeras, iluminação, texturas, modelos, *shaders* e técnicas modernas de renderização.

2. GALLOTTI, Giocondo Marino Antonio (org.). **Sistemas multimídia**. 1. ed. São Paulo: Pearson, 2017.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/152024](https://plataforma.bvirtual.com.br/Acervo/Publicacao/152024)
   - **Justificativa:** contextualiza imagens, gráficos, animações, áudio e vídeo em sistemas multimídia, contribuindo para a compreensão de formatos, representação, processamento e integração de conteúdo visual.

3. GAMBETTA, Gabriel. **Computer Graphics from Scratch**: a programmer’s introduction to 3D rendering. San Francisco: No Starch Press, 2021. Hospedagem livre autorizada pela editora.

   - 🔗 [https://gabrielgambetta.com/computer-graphics-from-scratch/](https://gabrielgambetta.com/computer-graphics-from-scratch/)
   - **Justificativa:** desenvolve os fundamentos da renderização tridimensional por meio da implementação de algoritmos, incluindo projeção, rasterização, recorte, iluminação, sombreamento e traçado de raios.

4. OPPENHEIM, Alan V.; WILLSKY, Alan S.; EISENCRAFT, Marcio. **Sinais e sistemas**. 2. ed. São Paulo: Pearson, 2010.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/2352](https://plataforma.bvirtual.com.br/Acervo/Publicacao/2352)
   - **Justificativa:** apresenta fundamentos matemáticos de sinais, amostragem, convolução e filtragem aplicáveis ao processamento de imagens, ao mapeamento de texturas e às técnicas de antisserrilhamento.

5. **Produção gráfica**: arte e técnica na direção de arte. São Paulo: Pearson, [s. d.]. 

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/3102](https://plataforma.bvirtual.com.br/Acervo/Publicacao/3102)
   - **Justificativa:** apresenta princípios visuais, cromáticos e técnicos da produção gráfica, complementando o estudo de modelos de cores, composição, resolução, formatos e preparação de imagens.

## Bibliografia Suplementar

1. COGALAN, Ugur et al. MILO: A Lightweight Perceptual Quality Metric for Image and Latent-Space Optimization. **ACM Transactions on Graphics**, v. 44, n. 6, 2025.

   - 🔗 [https://doi.org/10.1145/3763340](https://doi.org/10.1145/3763340)
   - **Justificativa:** apresenta uma métrica perceptual para avaliação e otimização da qualidade de imagens, ampliando a discussão sobre percepção visual, comparação de resultados e qualidade de renderização.

2. JIANG, Yuheng et al. Robust Dual Gaussian Splatting for Immersive Human-centric Volumetric Videos. **ACM Transactions on Graphics**, v. 43, n. 6, 2024.

   - 🔗 [https://doi.org/10.1145/3687926](https://doi.org/10.1145/3687926)
   - **Justificativa:** explora uma técnica contemporânea de representação e renderização volumétrica baseada em *Gaussian splatting*, aplicada à geração de vídeos imersivos centrados em pessoas.

3. SMERF: Streamable Memory Efficient Radiance Fields for Real-Time Large-Scene Exploration. **ACM Transactions on Graphics**, v. 43, 2024.

   - 🔗 [https://dl.acm.org/doi/abs/10.1145/3658193](https://dl.acm.org/doi/abs/10.1145/3658193)
   - **Justificativa:** apresenta uma abordagem eficiente para representação e renderização em tempo real de grandes cenas por campos de radiância, relacionando qualidade visual, desempenho e uso de memória.