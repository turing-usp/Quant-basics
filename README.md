# Quant basics

Notebook com estudo guiado de finanças quantitativas, contendo os seguinte tópicos

- Importação de dataset de preço históricos
- Retornos e Risco (Volatilidade)
- Lidando com portfolios
- Predição de Series Temporais

## Instalação

Crie um ambiente virtual
```
$ virtualenv .quantenv
```

Instale os requirements

```
$ pip install -r requirements.txt
```

Adicione o ambiente virtual a sua base de kernels do jupyter notebook

```
$ python -m ipykernel install --user --name=.quantenv
```

Após executar esse comando espera-se um resultado como o seguinte:

```
Installed kernelspec .quantenv in /home/user/.local/share/jupyter/kernels/.quantenv
```

Ative o ambiente virtual

```
$ source .quantenv/bin/activate
```

Inicie o Jupyter Notebook

```
$ jupyter notebook
```

**Obs:** Não esqueça de alterar o kernel para .quan
