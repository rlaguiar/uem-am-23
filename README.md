# Prova Didática - Aprendizado de Máquina (UEM)

Este repositório contém os códigos em Python e os materiais de apoio para a prova didática do processo seletivo para o cargo de Professor da **Universidade Estadual de Maringá (UEM)** - Edital nº 372/2026-PRH.

**Departamento:** Departamento de Informática (DIN) / Centro de Tecnologia (CTC)  
**Área:** Ciência da Computação / Aprendizado de Máquina  
**Candidato:** Me. Rafael de Lima Aguiar  

## Tema da Aula

**Tópico 7:** Balanceamento e aumento de dados: estratégias de subamostragem; estratégias de sobre amostragem; aumento de dados.

## Estrutura do Repositório

O laboratório de experimentação apresentado na aula foi dividido em três Jupyter Notebooks evolutivos, desenhados para demonstrar a geometria dos algoritmos, o trade-off de métricas operacionais e as boas práticas de prevenção de vazamento de dados:

* **`toyDatabase.ipynb`**: Utiliza uma base de dados didática (2D) para ilustrar o comportamento matemático no espaço de atributos das técnicas de *Random Undersampling*, *Tomek Links* (limpeza de fronteira), *Random Oversampling* e *SMOTE* (interpolação).
* **`digits.ipynb`**: Aplicação das técnicas de reamostragem em uma base real desbalanceada de imagens pixeladas (dataset *Digits* binarizado). Focado na análise do "Paradoxo da Acurácia" e no *trade-off* prático entre Revocação (*Recall*) e Precisão.

## Configuração do Ambiente

Os códigos foram desenvolvidos utilizando Python 3 e gerenciados via Miniconda. Para executar os notebooks localmente e interagir com as esteiras de ML, certifique-se de ter as seguintes bibliotecas instaladas no seu ambiente:

* `scikit-learn`
* `imbalanced-learn`
* `pandas`
* `matplotlib`
* `jupyter`

Caso precise instalar as dependências no seu ambiente Conda, utilize o terminal:

```bash
conda install scikit-learn imbalanced-learn pandas matplotlib jupyter
```

## Licença

Este material está licenciado sob a Licença MIT - permitindo o uso, cópia, modificação e distribuição de forma livre, com a devida atribuição.