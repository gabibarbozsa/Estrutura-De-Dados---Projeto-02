# Patience Sort – Implementação Completa, Validação e Análise Experimental

Este projeto apresenta uma implementação robusta do algoritmo Patience Sort, incluindo:

✔️ Ordenação crescente e decrescente
✔️ Suporte a keys e objetos personalizados
✔️ Validação rigorosa de corretude
✔️ Medição de desempenho com diferentes tipos de dados
✔️ Geração automática de gráficos
✔️ Testes visuais com objetos
✔️ Código totalmente comentado e organizado

O objetivo principal é demonstrar o funcionamento e o desempenho do Patience Sort em diferentes cenários e tamanhos de entrada.

#Descrição Geral

O Patience Sort é um algoritmo baseado na lógica do jogo "Paciência".
Ele funciona criando "pilhas" de valores e, posteriormente, realizando um merge eficiente utilizando um min-heap.

Este projeto implementa:

🔹 Parte 1 — Implementação do algoritmo

Distribuição em pilhas usando busca binária (bisect_left)

Merge final usando heap mínimo (heapq)

Suporte a key e ordenação reversa (reverse=True)

🔹 Parte 2 — Validação de corretude

Comparação automática com o sorted() para múltiplos cenários

Testes com listas pequenas e grandes, ordenadas, inversas e com valores iguais

🔹 Parte 3 — Medição de desempenho

Geração de listas de inteiros e strings

Medição em milissegundos

Tamanhos: 100, 1000, 10000, 100000

🔹 Parte 4 — Geração de gráficos

São gerados automaticamente:

Tempo em escala linear

Comparativo Inteiros x Strings

Gráfico Log-Log para análise assintótica

Os arquivos gerados são:

grafico_1_linear.png
grafico_2_comparacao.png
grafico_3_log.png

 Como executar
1️ Instale as dependências
pip install matplotlib

 Execute o script principal
python main.py


O programa irá automaticamente:

Validar o algoritmo

Executar testes de desempenho

Gerar gráficos na pasta do projeto

Exibir testes com objetos personalizados

Gráficos Gerados

O código gera automaticamente três gráficos:

Gráfico	Finalidade
grafico_1_linear.png	Comportamento direto do tempo de execução
grafico_2_comparacao.png	Diferença entre ordenar inteiros e strings
grafico_3_log.png	Análise assintótica (log-log)

Exemplo com Objetos (Produtos)

O código inclui um teste visual:

Produto("Café", 15)
Produto("Arroz", 20)
Produto("Balinha", 0.5)


E demonstra ordenação crescente e decrescente por preço.

# Tecnologias Utilizadas

Python 

heapq (Fila de prioridade)

bisect (Busca binária)

Matplotlib (Geração de gráficos)

Random / String (Geração de dados)

Participantes :

Gabriel Loiola

Maria Clara Cruz

Maria Gabriela Barbosa

Thays Gomes

Este projeto é disponibilizado para fins acadêmicos e de estudo.
