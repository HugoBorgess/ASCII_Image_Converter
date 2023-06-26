# ASCII Image Converter

Este é um programa simples em Python que converte imagens em ASCII art. O programa utiliza a biblioteca OpenCV para ler a imagem de entrada, realiza um redimensionamento da imagem e, em seguida, converte os pixels em uma representação ASCII.

## Requisitos

Certifique-se de ter os seguintes requisitos instalados:

- Python 3.x
- Biblioteca OpenCV (cv2)
- Biblioteca NumPy

## Instalação

1. Clone o repositório do projeto ou faça o download dos arquivos para o seu computador.
2. Certifique-se de ter as dependências necessárias instaladas. Caso contrário, você pode instalá-las usando o pip:

   ```bash
   pip install opencv-python numpy
   ```

## Como usar

1. Execute o programa através do comando:

   ```bash
   python ascii_converter.py [caminho_da_imagem]
   ```

   Se você não especificar o caminho da imagem, o programa usará "sample_image.png" como imagem de entrada.

2. O programa irá redimensionar a imagem e converter os pixels em uma representação ASCII.
3. O resultado será exibido no terminal e também será exportado para um arquivo de texto chamado "output.txt" no diretório atual.

   **Nota:** Você pode ajustar os parâmetros de redimensionamento no código para obter o resultado desejado.

## Exemplos

Aqui estão alguns exemplos de uso:

```bash
python ascii_converter.py
```

Neste exemplo, o programa usará a imagem "sample_image.png" como entrada e gerará a representação ASCII correspondente.

```bash
python ascii_converter.py my_image.jpg
```

Neste exemplo, o programa usará a imagem "my_image.jpg" como entrada e gerará a representação ASCII correspondente.

## Limitações e melhorias futuras

- O programa suporta apenas imagens no formato PNG e JPG. Outros formatos podem ser adicionados no futuro.
- A seleção de símbolos ASCII é limitada a um conjunto pré-definido. Pode ser interessante permitir que o usuário personalize essa seleção no futuro.
- A interface do programa é baseada em linha de comando. Uma possível melhoria seria criar uma interface gráfica para uma experiência mais amigável.

Sinta-se à vontade para contribuir para o projeto, fornecer feedback ou sugerir melhorias!
 
