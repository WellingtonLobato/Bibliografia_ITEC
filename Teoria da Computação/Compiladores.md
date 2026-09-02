<!-- Cabeçalho ITEC -->
<div align="center">
  <img src="../img/logo_itec.png"
       alt="Logo ITEC"
       width="300"/>

  <h3>Instituto de Tecnologia e Computação</h3>
  
  ---
</div>

# Compiladores

## Ementa

Definição, estrutura e aplicações dos compiladores; fases do processo de compilação; análise léxica, incluindo expressões regulares, autômatos finitos, reconhecimento de padrões, tokens e analisadores léxicos; ferramentas Lex e Flex; análise sintática; revisão de gramáticas livres de contexto; árvores sintáticas e árvores de sintaxe abstrata; análise sintática descendente (*top-down*), incluindo descida recursiva e LL(1); análise sintática ascendente (*bottom-up*), incluindo *shift-reduce*, LR(0), SLR e LALR; geradores de analisadores sintáticos Yacc e Bison; análise semântica; tabelas de símbolos; escopo, declarações e vinculação de nomes (*binding*); verificação, sistemas e inferência de tipos, incluindo Hindley–Milner; detecção e tratamento de erros; representações intermediárias; grafos de fluxo de controle; ambientes de execução e passagem de parâmetros por valor e por referência; introdução à geração de código; e técnicas de otimização de código.

## Bibliografia Básica

1. AHO, Alfred V.; LAM, Monica S.; SETHI, Ravi; ULLMAN, Jeffrey D. **Compiladores**: princípios, técnicas e ferramentas. 2. ed. São Paulo: Pearson, 2008.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/280](https://plataforma.bvirtual.com.br/Acervo/Publicacao/280)
   - **Justificativa:** constitui uma referência fundamental sobre todas as fases de compilação, abrangendo análise léxica, análise sintática, tradução dirigida pela sintaxe, análise semântica, representação intermediária, geração e otimização de código.

2. ASCENCIO, Ana Fernanda Gomes; CAMPOS, Edilene Aparecida Veneruchi de. **Fundamentos da programação de computadores**: algoritmos, Pascal, C/C++ (padrão ANSI) e Java. 3. ed. São Paulo: Pearson, 2012.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/417](https://plataforma.bvirtual.com.br/Acervo/Publicacao/417)
   - **Justificativa:** fornece fundamentos sobre linguagens, tipos, variáveis, escopos, funções, parâmetros e estruturas de controle necessários à compreensão da análise e da tradução de programas.

3. DEITEL, Paul J.; DEITEL, Harvey M. **C**: como programar. 6. ed. São Paulo: Pearson, 2011.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/2660](https://plataforma.bvirtual.com.br/Acervo/Publicacao/2660)
   - **Justificativa:** oferece a base de programação em C utilizada na implementação de analisadores, tabelas de símbolos, árvores sintáticas e outros componentes de compiladores.

## Bibliografia Complementar

1. MIZRAHI, Victorine Viviane. **Treinamento em linguagem C**. 2. ed. São Paulo: Pearson, 2008.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/2781](https://plataforma.bvirtual.com.br/Acervo/Publicacao/2781)
   - **Justificativa:** reforça conhecimentos de programação em C, incluindo ponteiros, funções, estruturas e manipulação de arquivos, aplicáveis ao desenvolvimento dos componentes de um compilador.

2. NYSTROM, Robert. **Crafting Interpreters**. [S. l.]: Genever Benning, 2021. Texto integral disponível gratuitamente no site oficial. 

   - 🔗 [https://craftinginterpreters.com/](https://craftinginterpreters.com/)
   - **Justificativa:** apresenta de maneira prática a implementação de linguagens, interpretadores e máquinas virtuais, abrangendo análise léxica, análise sintática, árvores de sintaxe, ambientes, tipos e execução.

3. **Programação de computadores**. São Paulo: Pearson, [s. d.]. 

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/22108](https://plataforma.bvirtual.com.br/Acervo/Publicacao/22108)
   - **Justificativa:** oferece fundamentos de programação, estruturas de controle, tipos de dados e organização de programas que apoiam a compreensão das construções processadas pelos compiladores.

4. STALLINGS, William. **Arquitetura e organização de computadores**. 10. ed. São Paulo: Pearson, 2017.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/1247](https://plataforma.bvirtual.com.br/Acervo/Publicacao/1247)
   - **Justificativa:** apresenta fundamentos da arquitetura de computadores e do conjunto de instruções necessários à compreensão da geração de código, do armazenamento de dados e das otimizações dependentes da máquina.

5. TANENBAUM, Andrew Stuart; BOS, Herbert. **Sistemas operacionais modernos**. 5. ed. Porto Alegre: Bookman, 2024.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/213434](https://plataforma.bvirtual.com.br/Acervo/Publicacao/213434)
   - **Justificativa:** oferece fundamentos sobre processos, memória, arquivos e interfaces do sistema que auxiliam na compreensão dos ambientes de execução e da interação dos programas traduzidos com o sistema operacional.

## Bibliografia Suplementar

1. CATARINO, Marino H. **Teoria da computação**. 1. ed. Rio de Janeiro: Freitas Bastos, 2023.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/211225](https://plataforma.bvirtual.com.br/Acervo/Publicacao/211225)
   - **Justificativa:** apresenta os fundamentos de linguagens formais, gramáticas e autômatos que sustentam teoricamente as etapas de análise léxica e sintática dos compiladores.

2. MUÑOZ, R. C.; BLANCO, B. B.; CAMPO-ÁVILA, J. del; RODRIGUEZ, J. L. T. Teaching Compilers: Automatic Question Generation and Intelligent Assessment of Grammars’ Parsing. **IEEE Transactions on Learning Technologies**, v. 17, p. 1694–1704, 2024.

   - 🔗 [https://doi.org/10.1109/TLT.2024.3405565](https://doi.org/10.1109/TLT.2024.3405565)
   - **Justificativa:** apresenta técnicas para geração automática de questões e avaliação inteligente de análise gramatical, oferecendo recursos contemporâneos para aprendizagem e verificação de conhecimentos sobre *parsing*.

3. ZHONG, Ming; LV, Fang; WANG, Lulin; QIU, Lei; WANG, Yingying; LIU, Ying; CUI, Huimin; FENG, Xiaobing; XUE, Jingling. VEGA: Automatically Generating Compiler Backends Using a Pre-trained Transformer Model. In: ACM/IEEE INTERNATIONAL SYMPOSIUM ON CODE GENERATION AND OPTIMIZATION, 23., 2025, New York. **Proceedings** [...]. New York: Association for Computing Machinery, 2025. p. 90–106.

   - 🔗 [https://doi.org/10.1145/3696443.3708931](https://doi.org/10.1145/3696443.3708931)
   - **Justificativa:** apresenta uma abordagem contemporânea baseada em *transformers* para geração automática de *back-ends* de compiladores, ampliando a discussão sobre geração de código e automação da construção de compiladores.