Antes de rodar, crie primeiro um ambiente virtual isolado
--

Execute o comando:

```bash
python3 -m venv meu_ambiente
```

Após execute o seguinte comando:

```bash
source meu_ambiente/bin/activate
```

Instalar o Jupyter dentro do ambiente virtual:

```bash
pip install --upgrade pip
pip install jupyter jupyterlab
```

Executar o Jupyter Notebook:

```bash
jupyter notebook
```


Para instalar o Java, execute o seguinte comando para baixar o ijava:

```bash
curl -L -o ijava.zip https://github.com/SpencerPark/IJava/releases/download/v1.3.0/ijava-1.3.0.zip

```

e agora para instalar, após tirar o conteúdo do zip:

```bash
python3 ijava/install.py --sys-prefix


```

