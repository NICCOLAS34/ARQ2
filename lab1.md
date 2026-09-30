# LAB1 -    

# modelo do processador
AMD Ryzen 3 PRO 5350GE with Radeon Graphics

# número de núcleos
4

# Númerod e threads
2

# Frequência minima / Máxima
400.0000 / 4267.0000 Mhz

# Tamanho das caches
L1 = 128 Kib
L2 = 2 MiB
L3 = 8 MiB

# 3 Tempo e ciclo

# Primeira simulação ./medir.c

# tempo total
0.120 s
 
# ns/iteração
0.240 

# ciclos/iteração
0.865
 
# frequência do TSC para cada execução.
3.600 GHz

# Segunda simulação 

# tempo total
1.181 s
 
# ns/iteração
0.236

# ciclos/iteração
0.850

# frequência do TSC para cada execução.
3.600 GHz

# Terceira simulação 

# tempo total
0.376 s
 
# ns/iteração
0.752

# ciclos/iteração
2.706

# frequência do TSC para cada execução.
3.600 GHz


# 4 Hierarquia da memória 

|------------------------------|
|tamanho_KB  |  ns_por_acesso  |
|------------------------------|
|         4  |       1.07      |
|         8  |       0.95      |
|        16  |       0.95      |
|       32   |       0.98      |
|        64  |       1.97      |
|      128   |       2.44      |
|       256  |       2.65      |
|       512  |       4.78      |
|      1024  |       8.93      |
|      2048  |      11.29      |
|      4096  |      11.38      |
|      8192  |      17.08      |
|     16384  |      53.95      |
|     32768  |      73.09      |
|     65536  |      82.68      |
|    131072  |      87.44      |
|------------------------------|

# 5 Localidade na matriz


# Matriz 256
- Tempo ijk = 0.036 s
- Gflop ijk = 0.93 s

- Tempo ikj = 0.005
- Gflop ikj = 6.29 s

# Matriz 512
- Tempo ijk = 0.358 s
- Gflop ijk = 0.75 s

- Tempo ikj = 0.039 s
- Gflop ikj = 6.84 s

# Matriz 1024
- Tempo ijk = 5.494 s 
- Gflop ijk = 0.39 s

- Tempo ikj = 0.357 s
- Gflop ikj = 6.02 s 


# 6 - Previsão de desvios

- ns/elemento 
0

- razão
0

# 7 Paralelismo em nível

# Soma1 1 
- ns/elemento
0.702 

- ciclos tsc 
2.527
 
# Soma 2 
- ns/elemento
0.173

- ciclos tsc
0.623
 
# Soma 3 
- ns/elemento
0.094

- ciclos tsc 
0.338


