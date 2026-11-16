# Prova Didática - Aprendizado de Máquina (UEM)

Este repositório contém os códigos em Python e os materiais de apoio para a prova didática gravada do concurso público para o cargo de Professor Assistente da **Universidade Estadual de Maringá (UEM)** - Edital nº 372/2026-PRH.

**Departamento:** Departamento de Informática (DIN) / Centro de Tecnologia (CTC)
**Área:** Ciência da Computação / Aprendizado de Máquina
**Candidato:** Rafael de Lima Aguiar

## Tema da Aula

**Tópico 7:** Balanceamento e aumento de dados: estratégias de subamostragem; estratégias de sobre amostragem; aumento de dados.

## Estrutura do Repositório

Os exemplos práticos apresentados nos slides para a demonstração visual das fronteiras de decisão estão organizados nos seguintes Jupyter Notebooks:

* `01_undersampling.ipynb`: Demonstração de redução da classe majoritária utilizando Random Undersampling e métodos informados (Tomek Links).
* `02_oversampling.ipynb`: Demonstração de aumento da classe minoritária através de interpolação no espaço de características com o algoritmo SMOTE.
* `03_data_augmentation.ipynb`: Exemplificação de técnicas de aumento de dados em visão computacional (transformações geométricas e injeção de ruído).

## Configuração do Ambiente

Os códigos foram desenvolvidos utilizando Python e gerenciados via Miniconda. Para executar os notebooks localmente, certifique-se de ter as seguintes bibliotecas instaladas no seu ambiente:

* `scikit-learn`
* `imbalanced-learn`
* `matplotlib`
* `jupyter`

Caso precise instalar as dependências no seu ambiente Conda, utilize o terminal:

```bash
conda install scikit-learn imbalanced-learn matplotlib jupyter

Licença
Este material está licenciado sob a Licença MIT - permitindo o uso, cópia, modificação e distribuição de forma livre.