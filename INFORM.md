## Organização do projeto

```
├── .env               <- Arquivo de variáveis de ambiente (não versionar)
├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- MIT
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto
|
├── notebooks          <- Cadernos Jupyter
|   └──src             <- Código-fonte para uso neste projeto
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      ├── config.py    <- Configurações básicas do projeto
|      └── estatisticas.py  <- Funções criadas especificamente para esse projeto
|
├── referencias        <- Dicionários de dados, manuais e todos os outros materiais explicativos.
|
├── relatorios         <- Análises geradas em HTML, PDF, LaTeX, etc.
│   └── imagens        <- Imagens utilizadas no projeto
```

## Configuração do ambiente

1. Faça o clone do repositório.

    ```bash
    git clone git@github.com:Guitis/projeto_teste.git
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o `conda`.

3. 
      ```bash
      conda env create -f ambiente.yml --name estatistica
      ```

## Um pouco mais sobre a base
[Clique aqui](referencias/01_dicionario_de_dados.md) para ver o dicionário de dados da base utilizada.

## Resumo dos principais resultados
TO BUILD
