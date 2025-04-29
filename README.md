# Análise de conjuntos de dados sobre câncer

Este projeto analisa conjuntos de dados sobre câncer para explorar diversas hipóteses relacionadas à incidência e às taxas de sobrevivência da doença no Brasil. Ele fornece insights sobre os tipos de câncer, dados demográficos dos pacientes e tendências ao longo do tempo.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Python version](https://img.shields.io/badge/Python-3.13-blue.svg)

## Instalação

Para usar este projeto, você precisará ter as seguintes dependências instaladas:

- Python 3.13
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Você pode instalar estas dependências usando o pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Você pode usar o Google Collab para realizar as análises também.

## Uso/Exemplos

O script principal `datasets_cancer_global.py` executa as seguintes tarefas:

1. Carrega o conjunto de dados `global_cancer_patients_2015_2024.csv`.
2. Explora o conjunto de dados exibindo informações básicas, manipulando valores ausentes e convertendo tipos de dados.
3. Analisa a distribuição dos tipos de câncer, idades dos pacientes e casos de câncer no Brasil.
4. Limpa e codifica os dados para modelos de aprendizado de máquina.
5. Investiga quatro hipóteses relacionadas ao câncer no Brasil:
- **Hipótese 1:** O câncer está aumentando entre jovens adultos de 20 a 30 anos.
- **Hipótese 2:** O câncer de pele é mais comum em homens do que em mulheres.
- **Hipótese 3:** A taxa de sobrevivência para câncer de pulmão é maior do que para câncer de pele.
- **Hipótese 4:** As mulheres apresentam estágios de câncer mais avançados em comparação aos homens.

## Referência de API

Este projeto não fornece uma API pública. Trata-se de um script de análise de dados que pode ser usado como referência ou ponto de partida para futuras pesquisas e análises sobre o câncer.

## Contribuindo

Contribuições para este projeto são bem-vindas. Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma nova issue ou enviar um pull request.

## Executando Testes

Este projeto não inclui testes automatizados. A análise é realizada por meio de visualização exploratória de dados e testes de hipóteses.

## Recursos Relacionados


- [Fontes de Dados Kaggle](https://www.kaggle.com/datasets/)

## Conclusão
- Hipotese 1: Há um crescimento de câncer entre jovens e adultos de 20 a 30 anos;
  ![image](https://github.com/user-attachments/assets/47e0c026-a160-4a60-80d3-26c104d1afd8)

- Hipotese 2: Mostrou-se nula, pois o câncer de pele é mais comum em mulheres;
  ![image](https://github.com/user-attachments/assets/b42789e1-c378-4cbf-bb56-2d0ca29872d0)

- Hipotese 3: O tempo médio de Sobrevivência de câncer de pulmão é menor que de câncer de pele no geral e
em homens e mulheres, o tempo médio de sobrevivência de câncer de pulmao é maior que de câncer de pele;

![image](https://github.com/user-attachments/assets/1726ae70-9aca-49eb-be99-890498073424)

O gráfico acima representa a média geral de homens e mulheres por tipo de câncer (Pulmão e Pele).

![image](https://github.com/user-attachments/assets/8e0f5f4e-b3bb-4370-9f0e-4411bf5cd9d9)

O segundo gráfico representa o tempo médio separado por gênero em cada tipo de câncer analisado.

Hipotese 4: Em relação aos estágios de câncer, nota-se que entre os estágios 0 a III, há mais mulheres que homens. E em relação ao estágio IV, há mais homens que mulheres.

![image](https://github.com/user-attachments/assets/41744a89-de68-4f93-a387-759d4aeb5d3f)



## Lições Aprendidas
Foram realizadas limpezas e exploração dos dados, o uso de bibliotecas para realizar analises estatísticas em Python.

Como resultado foram gerados:
Gráficos:
-  Distribuição entre homens e mulheres de câncer no geral de acordo com a faixa etária no Brasil.
-  Incidência de câncer levando em consideração o gênero.
-  Tempo médio de sobrevivência no geral. Para a análise foi escolhido aleatoriamente o câncer de pele e de pulmão.
-  Estagio de câncer (0 a IV), divididos por gêneros.

## Licença

Este projeto está licenciado sob a Licença MIT.
