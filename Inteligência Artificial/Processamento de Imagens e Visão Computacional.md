<!-- Cabeçalho ITEC -->
<div align="center">
  <img src="../img/logo_itec.png"
       alt="Logo ITEC"
       width="300"/>

  <h3>Instituto de Tecnologia e Computação</h3>
  
  ---
</div>

# Processamento de Imagens e Visão Computacional

## Ementa

Percepção visual humana; amostragem, quantização e resolução de imagens; modelos de cores RGB, HSV, CMYK e CIE Lab; representação digital de imagens, incluindo pixels, canais e profundidade de bits; formatos JPEG, PNG e TIFF; transformações de intensidade, abrangendo ajuste de contraste e correção gama; cálculo e equalização de histogramas; convolução e correlação; filtros lineares para suavização e realce; filtros não lineares, incluindo filtros mediano e bilateral; modelos de ruído gaussiano, impulsivo (*salt-and-pepper*) e *speckle*; remoção de ruído por filtros de média, gaussiano e mediano; restauração de imagens; detecção de bordas, cantos e pontos de interesse; técnicas de segmentação; modelos de câmera, calibração e correção de distorções; visualização tridimensional; métodos clássicos de reconhecimento de objetos, incluindo correspondência de modelos (*template matching*), descritores de características e modelos de palavras visuais (*bag of visual words*); visão computacional moderna baseada em aprendizagem profunda; e aplicações.

## Bibliografia Básica

1. BARELLI, Felipe. **Introdução à visão computacional**: uma abordagem prática com Python e OpenCV. São Paulo: Casa do Código, 2018.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/212701](https://plataforma.bvirtual.com.br/Acervo/Publicacao/212701)
   - **Justificativa:** apresenta os fundamentos da visão computacional por meio de uma abordagem prática, com exemplos em Python e OpenCV envolvendo manipulação de imagens, filtragem, segmentação, detecção e reconhecimento.

2. GONZALEZ, Rafael C.; WOODS, Richard E. **Processamento digital de imagens**. 3. ed. São Paulo: Pearson, 2009.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/2608](https://plataforma.bvirtual.com.br/Acervo/Publicacao/2608)
   - **Justificativa:** constitui uma referência fundamental para o estudo da representação digital de imagens, transformações de intensidade, histogramas, filtragem, restauração, segmentação e extração de características.

3. SILVA, Luiz Ricardo Mantovani da. **Processamento de sinais e imagens**. Rio de Janeiro: Freitas Bastos, 2026.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/230056](https://plataforma.bvirtual.com.br/Acervo/Publicacao/230056)
   - **Justificativa:** apresenta fundamentos contemporâneos de processamento de sinais e imagens, apoiando a compreensão das operações matemáticas, dos filtros e das técnicas utilizadas na análise de dados visuais.

## Bibliografia Complementar

1. LUGER, George F. **Inteligência artificial**. 6. ed. São Paulo: Pearson, 2013.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/180430](https://plataforma.bvirtual.com.br/Acervo/Publicacao/180430)
   - **Justificativa:** contextualiza os métodos de visão computacional no campo da Inteligência Artificial, oferecendo fundamentos sobre reconhecimento de padrões, aprendizagem e construção de sistemas inteligentes.

2. OPPENHEIM, Alan V.; WILLSKY, Alan S.; EISENCRAFT, Marcio. **Sinais e sistemas**. 2. ed. São Paulo: Pearson, 2010.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/2352](https://plataforma.bvirtual.com.br/Acervo/Publicacao/2352)
   - **Justificativa:** fornece a base matemática para a análise de sinais e sistemas, incluindo convolução, transformações e filtragem, conceitos essenciais ao processamento digital de imagens.

3. PINHEIRO, C. A. M. **Sistemas de controles digitais e processamento de sinais**. 1. ed. Rio de Janeiro: Interciência, 2017.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/124114](https://plataforma.bvirtual.com.br/Acervo/Publicacao/124114)
   - **Justificativa:** complementa a formação em processamento digital de sinais, auxiliando na compreensão de técnicas de filtragem, análise e tratamento computacional aplicáveis às imagens.

4. PRINCE, Simon J. D. **Computer Vision**: models, learning, and inference. Cambridge: Cambridge University Press, 2012. PDF de acesso livre no site oficial. 

   - 🔗 [http://www.computervisionmodels.com/](http://www.computervisionmodels.com/)
   - **Justificativa:** apresenta modelos probabilísticos, métodos de aprendizagem e técnicas de inferência aplicados à visão computacional, abrangendo calibração, segmentação, reconhecimento e análise tridimensional.

5. PRINCE, Simon J. D. **Understanding Deep Learning**. Cambridge: MIT Press, 2023. PDF de acesso livre no site do autor. 

   - 🔗 [https://udlbook.github.io/udlbook/](https://udlbook.github.io/udlbook/)
   - **Justificativa:** oferece fundamentos matemáticos e computacionais da aprendizagem profunda, apoiando o estudo das técnicas modernas empregadas em classificação, detecção, segmentação e reconhecimento de imagens.

## Bibliografia Suplementar

1. DIAMOND, Steven; SITZMANN, Vincent; JULCA-AGUILAR, Frank; BOYD, Stephen; WETZSTEIN, Gordon; HEIDE, Felix. Dirty Pixels: Towards End-to-end Image Processing and Perception. **ACM Transactions on Graphics**, v. 40, n. 3, art. 23, 15 p., jun. 2021.

   - 🔗 [https://doi.org/10.1145/3446918](https://doi.org/10.1145/3446918)
   - **Justificativa:** investiga a integração entre processamento de imagens e percepção computacional em modelos treinados de ponta a ponta, aproximando as etapas de aquisição, restauração e interpretação visual.

2. KHAN, Salman; NASEER, Muzammal; HAYAT, Munawar; ZAMIR, Syed Waqas; KHAN, Fahad Shahbaz; SHAH, Mubarak. Transformers in Vision: A Survey. **ACM Computing Surveys**, v. 54, n. 10s, art. 200, 41 p., jan. 2022.

   - 🔗 [https://doi.org/10.1145/3505244](https://doi.org/10.1145/3505244)
   - **Justificativa:** apresenta uma revisão das arquiteturas baseadas em *transformers* aplicadas à visão computacional, abrangendo classificação, detecção, segmentação e outras tarefas contemporâneas.

3. NEGRI, Rogério Galante. **Reconhecimento de padrões**. 1. ed. São Paulo: Blucher, 2021.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/229650](https://plataforma.bvirtual.com.br/Acervo/Publicacao/229650)
   - **Justificativa:** aborda fundamentos e técnicas de reconhecimento de padrões, complementando o estudo da extração de características, classificação e interpretação automática de imagens.