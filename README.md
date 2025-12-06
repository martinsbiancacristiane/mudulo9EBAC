# mudulo9EBAC
📊 Análise de Dados de Nascimentos (SINASC - RO 2019)
📝 Descrição do ProjetoEste projeto consiste em uma análise exploratória e estatística do conjunto de dados do Sistema de Informações sobre Nascidos Vivos (SINASC), com foco nos registros do estado de Rondônia (RO) referentes ao ano de 2019.
O objetivo principal foi aplicar técnicas de manipulação e agregação de dados utilizando a biblioteca Pandas para responder a questões específicas sobre as características dos nascimentos, como idade de pais e mães, peso dos bebês e distribuição geográfica dos partos.

🛠️ Tecnologias Utilizadas
Linguagem: Python
Biblioteca Principal: Pandas (para manipulação e agregação de dados)
Bibliotecas de Visualização: Matplotlib e Seaborn (para gerar o gráfico de insights)
Ambiente: Jupyter Notebook (Mod9Tarefa1.ipynb)💾 
Conjunto de DadosO dataset utilizado é o SINASC_RO_2019.csv, contendo informações detalhadas sobre os nascimentos, incluindo:
DTNASC: Data de Nascimento
munResNome: Município de Residência da Mãe
IDADEMAE, IDADEPAI: Idade da Mãe e do Pai
PESO: Peso do Recém-Nascido
ESCMAE: Escolaridade da Mãe
QTDFILVIVO: Quantidade de Filhos Vivos (Informada pela Mãe)

🎯 Tarefas de Análise
Métodos como groupby(), mean(), value_counts() e filtros condicionais:Idade Média por Município: Cálculo da idade média das mães e dos pais, agrupada por município de residência (munResNome).
Peso Médio Detalhado: Determinação do peso médio dos bebês nascidos em uma data específica (06 de Agosto), segmentado pela Escolaridade da Mãe (ESCMAE) e pelo Sexo do Recém-Nascido.
Análise do Mínimo: Identificação do município com o menor número de nascimentos em 2019 e cálculo das estatísticas (média, máxima, mínima) de idade das mães e dos pais nesse município.
Análise do Máximo: Identificação do município com o maior número de nascimentos no mês de Março e cálculo das estatísticas de quantidade de filhos vivos e idade dos pais nesse município.

📈 Insight Principal Extraído
Correlação Forte e Direta: Existe uma correlação muito clara entre o aumento da escolaridade da mãe e o adiamento da maternidade em Rondônia.

