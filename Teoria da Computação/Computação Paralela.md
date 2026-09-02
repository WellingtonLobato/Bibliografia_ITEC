<!-- Cabeçalho ITEC -->
<div align="center">
  <img src="../img/logo_itec.png"
       alt="Logo ITEC"
       width="300"/>

  <h3>Instituto de Tecnologia e Computação</h3>
  
  ---
</div>

# Computação Paralela

## Ementa

Paralelismo e concorrência; métricas de desempenho, aceleração e eficiência; leis de Amdahl e Gustafson; sistemas de memória compartilhada, incluindo *threads*, exclusão mútua e OpenMP; sistemas de memória distribuída e MPI; comunicação ponto a ponto e operações coletivas; arquiteturas híbridas; unidades de processamento gráfico (GPUs); paralelismo de dados com CUDA e OpenCL; paralelismo baseado em tarefas com Cilk e Intel TBB; projeto de algoritmos paralelos; decomposição, particionamento e mapeamento de tarefas; balanceamento de carga; custos de comunicação e sincronização; algoritmos paralelos de ordenação, incluindo *quicksort*; soma de prefixos (*prefix scan*); multiplicação de matrizes; algoritmos paralelos em grafos, incluindo busca em largura e caminhos mínimos; mecanismos de sincronização, incluindo semáforos, barreiras e bloqueios; impasses (*deadlocks*), bloqueios ativos (*livelocks*) e inanição (*starvation*); análise de gargalos; coerência de cache; e técnicas e ferramentas de análise de desempenho, depuração e perfilamento de programas paralelos.

## Bibliografia Básica

1. SILVA, Luiz Ricardo Mantovani da. **Organização e arquitetura de computadores**: uma jornada do fundamental ao inovador. Rio de Janeiro: Freitas Bastos, 2023.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/213436](https://plataforma.bvirtual.com.br/Acervo/Publicacao/213436)
   - **Justificativa:** apresenta fundamentos e tendências da organização de computadores, incluindo processadores multicore, hierarquia de memória, coerência de cache e arquiteturas paralelas.

2. STALLINGS, William. **Arquitetura e organização de computadores**: projetando com foco em desempenho. 11. ed. Porto Alegre: Bookman, 2024.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/213400](https://plataforma.bvirtual.com.br/Acervo/Publicacao/213400)
   - **Justificativa:** oferece fundamentos sobre paralelismo, multiprocessadores, memória compartilhada, coerência de cache, arquiteturas multicore e avaliação de desempenho.

3. TANENBAUM, Andrew Stuart; AUSTIN, Todd. **Organização estruturada de computadores**. 6. ed. São Paulo: Pearson, 2013.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/3825](https://plataforma.bvirtual.com.br/Acervo/Publicacao/3825)
   - **Justificativa:** apresenta a organização dos sistemas computacionais em níveis, contribuindo para a compreensão de processadores, memórias, execução paralela e suporte arquitetural à programação concorrente.

## Bibliografia Complementar

1. CORRÊA, Ana Grasielle Dionísio (org.). **Organização e arquitetura de computadores**. São Paulo: Pearson, 2017.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/124147](https://plataforma.bvirtual.com.br/Acervo/Publicacao/124147)
   - **Justificativa:** aborda os componentes e princípios da organização computacional que sustentam a execução paralela, incluindo processadores, memórias, interconexões e mecanismos de entrada e saída.

2. MATLOFF, Norm. **Programming on Parallel Machines**: GPU, multicore, clusters and more. Davis: University of California, Davis, 2017. Licença Creative Commons. 

   - 🔗 [https://heather.cs.ucdavis.edu/matloff/public_html/158/PLN/ParProcBook.pdf](https://heather.cs.ucdavis.edu/matloff/public_html/158/PLN/ParProcBook.pdf)
   - **Justificativa:** apresenta programação paralela em processadores multicore, GPUs e clusters, abrangendo *threads*, OpenMP, MPI, CUDA, sincronização, desempenho e aplicações.

3. SILVA, G. P.; BIANCHINI, C. P.; COSTA, E. B. **Programação paralela e distribuída**: com MPI, OpenMP e OpenACC para computação de alto desempenho. São Paulo: Casa do Código, 2022.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/212678](https://plataforma.bvirtual.com.br/Acervo/Publicacao/212678)
   - **Justificativa:** oferece uma abordagem prática para o desenvolvimento de programas paralelos em memória compartilhada, memória distribuída e aceleradores, utilizando OpenMP, MPI e OpenACC.

4. TANENBAUM, Andrew Stuart; VAN STEEN, Maarten. **Sistemas distribuídos**: princípios e paradigmas. 2. ed. São Paulo: Pearson, 2007.

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/411](https://plataforma.bvirtual.com.br/Acervo/Publicacao/411)
   - **Justificativa:** apresenta fundamentos de comunicação, processos, sincronização, concorrência, consistência e tolerância a falhas relevantes para sistemas paralelos de memória distribuída.

5. VERAS, Manoel; DIOGENES, Yuri. **Computação em nuvem**: nova arquitetura de TI. 1. ed. Rio de Janeiro: Brasport, 2015. 

   - 🔗 [https://plataforma.bvirtual.com.br/Acervo/Publicacao/160695](https://plataforma.bvirtual.com.br/Acervo/Publicacao/160695)
   - **Justificativa:** contextualiza o uso de infraestruturas virtuais, clusters e serviços de nuvem para execução escalável de aplicações paralelas e distribuídas.

## Bibliografia Suplementar

1. BEZ, Jean Luca; BYNA, Suren; IBRAHIM, Shadi. I/O Access Patterns in HPC Applications: A 360-Degree Survey. **ACM Computing Surveys**, v. 56, n. 2, art. 46, 41 p., fev. 2024.

   - 🔗 [https://doi.org/10.1145/3611007](https://doi.org/10.1145/3611007)
   - **Justificativa:** apresenta uma revisão dos padrões de entrada e saída em aplicações de computação de alto desempenho, ampliando a análise de gargalos, desempenho e escalabilidade.

2. GONNORD, Laure; HENRIO, Ludovic; MOREL, Lionel; RADANNE, Gabriel. A Survey on Parallelism and Determinism. **ACM Computing Surveys**, v. 55, n. 10, art. 210, 28 p., out. 2023.

   - 🔗 [https://doi.org/10.1145/3564529](https://doi.org/10.1145/3564529)
   - **Justificativa:** discute a relação entre paralelismo e determinismo, abordando modelos, linguagens e técnicas para desenvolver programas paralelos previsíveis e corretos.

3. SOZZO, E. D.; CONFICCONI, D.; ZENI, A.; SALARIS, M.; SCIUTO, D.; SANTAMBROGIO, M. D. Pushing the Level of Abstraction of Digital System Design: A Survey on How to Program FPGAs. **ACM Computing Surveys**, v. 55, n. 5, p. 1–48, 2022.

   - 🔗 [https://dl.acm.org/doi/10.1145/3532989](https://dl.acm.org/doi/10.1145/3532989)
   - **Justificativa:** revisa métodos e ferramentas de programação de FPGAs, ampliando o estudo de arquiteturas paralelas, aceleradores de hardware e abstrações para computação de alto desempenho.