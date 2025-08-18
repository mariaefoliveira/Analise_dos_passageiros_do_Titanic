# **Análise de sobrevivência dos passageiros do Titanic**
#### Observação:
_A intenção deste projeto é analisar a base de dados existente sobre o titanic e aprofundar os conhecimentos sobre análise de dados._

_Os dados utilizados serão do arquivo "treino" (titanic_train.csv). Que foram tirados do Kaggle._
_Link: https://www.kaggle.com/competitions/titanic

> Caso tenham interesse em visualizar a análise, podem baixar o arquivo Power BI:
> - **Relatório de sobreviventes do Titanic.pbix**

## **Resumo**:
> As questões trabalhadas foram focadas nas **classes** dos sobreviventes, **taxa** paga, e a **média** da idade dos passageiros, fazendo uma divisão entre os sexos para entender se houve alguma ligação real na sobrevivência dos passageiros do **Titanic**.

---

# Análise e Visualização

A partir de agora, a análise realizada foi feita com o auxílio do Power BI, então o que eu deixarei em seguida, serão os prints das análises.

> Obs: Você também pode estar visualizando através do arquivo powerBI disponível no github

O arquivo pode ser encontrado com o nome "Relatório de sobreviventes do Titanic.pbix" na página principal (main)

---

Deixo claro que o número de passageiros registrados na planilha é de: `891`.
Podendo haver ou não mais passageiros.

#Número de Passageiros
<div align="center">
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/Num%20de%20passageiros%20por%20Sexo.png?raw=true" alt="Número de passageiros por Sexo">
</div>

Houveram mais passageiros abordo do sexo masculino do que feminino. Ocupando cerca de `64,76%` da tabela.

#Número de passageiros por Classe
<div align="center">
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/Num%20de%20passageiros%20por%20tipo%20Classe.png?raw=true">
</div>

Foram identificados um maior número de pessoas da **primeira** e **terceira** classe, mas isso pode estar intrísecamente relacionado a idade. Mas analisando superficialmente, **491** dos passageiros eram da 3ª classe e **216* da 1ª classe, sendo a **2ª classe** a de menor registro.

#Taxa de Sobrevivência Total em %
<div align="center">
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/Porc_Sobreviventes_Sexo_e_Idade.png?raw=true">
</div>

#Taxa de Sobrevivência por Classe
<div align="center">
  <table>
    <tr>
      <td align="center">
        <h4>1ª Classe</h4>
        <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/Taxa_sobrev_1_classe.png?raw=true" alt="Taxa de sobrevivência na 1ª Classe" width="300"/>
      </td>
      <td align="center">
        <h4>2ª Classe</h4>
        <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/Taxa_sobrev_2_classe.png?raw=true" alt="Taxa de sobrevivência na 2ª Classe" width="300"/>
      </td>
      <td align="center">
        <h4>3ª Classe</h4>
        <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/Taxa_sobrev_3_classe.png?raw=true" alt="Taxa de sobrevivência na 3ª Classe" width="300"/>
      </td>
    </tr>
  </table>
</div>

Como podemos analisar das imagens, na **terceira** classe, homens e mulheres tiveram uma taxa de óbito maior, e comparando o grupo das mulheres com a dos homens, as mulheres tiveram uma sobrevivência maior em cada uma das classes.

# Taxa de Sobrevivência por Idade
<div align="center">
  <table>
    <tr>
      <td align="center">
        <h4>1ª Classe</h4>
        <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/taxa_sobrev_idade_1.png?raw=true" alt="Taxa de sobrevivência por idade - Grupo 1" width="300"/>
      </td>
      <td align="center">
        <h4>2ª Classe</h4>
        <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/taxa_sobrev_idade_2.png?raw=true" alt="Taxa de sobrevivência por idade - Grupo 2" width="300"/>
      </td>
      <td align="center">
        <h4>3ª Classe</h4>
        <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Passageiros/taxa_sobrev_idade_3.png?raw=true" alt="Taxa de sobrevivência por idade - Grupo 3" width="300"/>
      </td>
    </tr>
  </table>
</div>

A preferência foi dada para 1ª e 2ª classe, onde na primeira foi até equilibrada o número de óbitos, mas quando olhamos com mais cuidado, vemos que na 2ª classe há uma ligeira crescente de óbitos, divergindo na segurança das crianças, chegando a 27%. Por último a **terceira** classe que teve uma perda acentuada de vidas, principalmente para crianças, com apenas cerca de 30% delas sendo salvas, o que me leva a crer uma possível desvantagem por conta da classe.

#Análise Demográfica
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Demografico/Sozinho-em-familia-Geral.png?raw=true" alt="Porto de Embarque" width="600"/>
      </td>
    </tr>
  </table>
</div>

Apesar das implicações vistas nos gráficos anteriores, sobre o impacto da terceira classe, em relação as crianças, vemos que foi dado a preferência para aqueles que estavam viajando em família e que mesmo estando sozinho, os passageiros desacompanhados no titanic tiveram essa desvantagem por conta da ordem estabelecida.
> "Mulheres e crianças primeiro".

# Análise Familiar

## Grupo Feminino
<div align="center">
  <h4>1ª Classe</h4>
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Familia/Feminino/Geral-1.png?raw=true" alt="Primeira Imagem" width="500"/>
</div>
<br>
<div align="center">
  <h4>2ª Classe</h4>
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Familia/Feminino/Geral-2.png?raw=true" alt="Segunda Imagem" width="500"/>
</div>
<br>
<div align="center">
  <h4>3ª Classe</h4>
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Familia/Feminino/Geral-3.png?raw=true" alt="Terceira Imagem" width="500"/>
</div>

## Grupo Masculino

<div align="center">
  <h4>1ª Classe</h4>
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Familia/Masculino/Geral-1.png?raw=true" alt="Primeira Imagem" width="500"/>
</div>
<br>
<div align="center">
  <h4>2ª Classe</h4>
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Familia/Masculino/Geral-2.png?raw=true" alt="Segunda Imagem" width="500"/>
</div>
<br>
<div align="center">
  <h4>3ª Classe</h4>
  <img src="https://github.com/mariaefoliveira/Analise_Titanic/blob/main/Imagem-Print/Familia/Masculino/Geral-3.png?raw=true" alt="Terceira Imagem" width="500"/>
</div>

### Resumo
A maioria das mulheres eram jovens, chegando a 28 anos, e todas elas tiveram uma taxa de sobrevivência alta, menos a da terceira classe, o que leva a crer que priorizaram realmente mulheres e crianças, mas principalmente **primeira** e **segunda** classe.
Já entre os homens, um número alto não conseguiram sobreviver, as classes que se destacaram foi novamente, **primeira** e **segunda** classe, indicando a prioridade usada, assim como foi para as mulheres

# Considerações Finais

Dos 891 passageiros que foram analisados, 314 era do sexo feminino e 577 do masculino.

Durante a análise, foi reforçado bastante que enquanto o navio afundava, foi priorizado crianças e mulheres primeiro e em seguida os homens, mas com uma regra igual para ambos que era priorização da **1ª e 2ª classe**. Esta questão foi percebida, pelo número de falecidos da 3ª classe que para ambos os sexos aumenta consideravelmente, se comparado as outras duas classes, principalmente quando nos referimos as crianças que também foi um fator que aumentou consideravelmente.

A maioria que escolheram a terceira classe, era em parte jovens com uma média de 25 anos, me levando a considerar a possibilidade de serem pessoas que estavam alí que queriam viajar e ainda não chegaram ao auge financeiro em suas carreiras.

## Possíveis questão a ser trabalhada:

Haveria alguma relação da sobrevivência e o número da cabine do passageiro?

Neste caso é considerando a distância para chegar até a saída. Então para chegar a resposta, seria necessário informações complementares algumas informações.
