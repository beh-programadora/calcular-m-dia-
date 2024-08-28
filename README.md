# Calculador de Média com Função

Este projeto é um script em Python que define uma função para calcular a média de três notas fornecidas pelo usuário e exibe o resultado.

## Objetivo

O objetivo deste projeto é criar uma função que:
1. Receba três notas como argumentos.
2. Calcule a média dessas notas.
3. Exiba a média formatada com duas casas decimais.

O script principal solicita ao usuário que insira três notas, utiliza a função para calcular a média e exibe o resultado.

## Código

O código consiste em uma função chamada `calcular_media` que calcula a média de três notas e um trecho de código que lê as notas do usuário, chama a função e exibe a média.

```python
def calcular_media(nota1, nota2, nota3):
    return (nota1 + nota2 + nota3) / 3

# Leitura das notas 
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))
nota3 = float(input("Digite a terceira nota: "))

# Chamada da função 
media = calcular_media(nota1, nota2, nota3)

# Exibição da média
print(f"A média das notas é: {media:.2f}")
Como Executar
1. Certifique-se de ter o Python instalado em seu sistema.

2. Salve o código acima em um arquivo chamado calcular_media.py.

3. Execute o código usando o seguinte comando:
python calcular_media.py
4. Insira três notas quando solicitado e veja a média calculada.

Contribuição
Sinta-se à vontade para fazer sugestões ou melhorias. Se encontrar um problema ou tiver uma ideia para aprimorar o projeto, por favor, abra uma issue ou envie um pull request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
