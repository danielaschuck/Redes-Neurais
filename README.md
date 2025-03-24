# Regressão Linear Simples com Backpropagation

Este projeto demonstra a implementação de um modelo de regressão linear simples usando o algoritmo de backpropagation para treinamento.

## Descrição

O objetivo deste projeto é fornecer um exemplo prático de como construir e treinar um modelo de regressão linear do zero, sem usar bibliotecas de aprendizado de máquina prontas. O projeto inclui:

* Geração de dados de treinamento simulados.
* Implementação das funções de forward e backpropagation.
* Cálculo do erro quadrático médio (MSE) e do coeficiente de determinação (R²).
* Visualização dos dados e da linha de regressão ajustada.

## Como Usar

1.  **Clone o repositório:**

    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://www.google.com/search?q=https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```

2.  **Execute o notebook Jupyter:**

    Certifique-se de ter o Jupyter Notebook instalado. Em seguida, execute o notebook `regressao_linear.ipynb`.

    ```bash
    jupyter notebook regressao_linear.ipynb
    ```

3.  **Explore o código:**

    O notebook contém explicações passo a passo de cada parte do código, permitindo que você entenda como o modelo funciona.

## Requisitos

* Python 3.x
* NumPy
* Matplotlib

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está sob a licença [MIT](LICENSE).

## Autor

[Seu Nome]

[Seu GitHub]

## Exemplo de uso

### Geração de dados de treinamento

```python
x = np.arange(-10, 38, 1)
Y = get_linear_curve(x, 1.8, 30, noise_scale=5)
