# Introdução a computação quântica

Nesse minicurso, tentarei passar conceitos básicos de computação quântica para leigos.\ 
Esse curso tem como objetivo instigar as pessoas à testarem mais e se engajarem nessa área.\
Sinta-se a vontade para fazer um fork do projeto e modifcar os códigos.\
Para mais detalhes de como prosseguir com o curso, veja as seçoẽs abaixo.

## Requisitos

No curso será usado o `python 3.8.15` junto com o `pip`, garanta que eles estão instalados corretamente. Usar `anaconda` é opcional, mas recomendado!.

- [python 3.8.15](https://www.python.org/downloads/release/python-3815/)
- [anaconda](https://www.anaconda.com/)

## Ambiente

Para configurar seu ambiente execute:

```bash
##anaconda (opcional)
conda env create -f environment.yml
conda activate quantum

pip install -r requirements.txt
```

Após terminar os trabalhos, caso estiver usando anaconda rode:

```bash
conda deactivate
```

para sair do ambiente virtual.


## Executando

Para executar os códigos rode:

```bash
jupyter lab code.ipynb
```
