# Competition Standards

Este projeto é um estudo sobre padrões de concorrência em Go (Golang). Ele contém exemplos práticos e implementações de diferentes abordagens para lidar com concorrência, como multiplexação, geração de dados e pools de workers.

## Estrutura do Projeto

- **Generators**: Contém o exemplo de geração de dados concorrente.
  - Arquivo: `Generators/generator.go`
  - Demonstra como criar uma função que gera dados continuamente em um canal.

- **Multiplexador**: Contém o exemplo de multiplexação de canais.
  - Arquivo: `Multiplexador/multiplexador.go`
  - Mostra como combinar múltiplos canais de entrada em um único canal de saída.

- **Worker Pools**: Contém o exemplo de pools de workers para processamento paralelo.
  - Arquivo: `Worker Pools/worker-pools.go`
  - Implementa um pool de workers para calcular números da sequência de Fibonacci.

## Como Executar

1. Certifique-se de ter o Go instalado em sua máquina. Você pode baixá-lo em [golang.org](https://golang.org/).
2. Clone este repositório:
   ```bash
   git clone https://github.com/gilberto-dev-silva/competition-standards
	```
3. Navegue até o diretório do projeto:
	```bash
	cd competition-standards
	```
4. Execute os exemplos disponíveis:

    - Generators: Para executar o exemplo de geração de dados concorrente:
    ```bash
    go run Generators/generator.go
    ```

    - Multiplexador: Para executar o exemplo de multiplexação de canais:
    ```bash
    go run Multiplexador/multiplexador.go
    ```

    - Worker Pools: Para executar o exemplo de pools de workers:
    ```bash
    go run Worker\ Pools/worker-pools.go
    ```
## Obrigado

Obrigado por conferir este projeto! Esperamos que os exemplos e instruções tenham sido úteis. Se quiser colaborar, será muito bem-vindo(a)!

