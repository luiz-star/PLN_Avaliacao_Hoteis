# PLN_Avaliacao_Hoteis
Collocations e Processamento de Comentários de Avaliações de Hotéis

Collocations são duas ou mais palavras que tendem a aparecer frequentemente juntas, como "Estados Unidos", "Rio Grande do Sul" ou "Machine Learning". Essas palavras podem gerar diversas combinações e por isso o contexto também é importante no processamento de linguagem natural.

Os dois tipos mais comuns de Collocations são bigramas e trigramas. Bigramas são duas palavras adjacentes, como "tomografia computadorizada", "aprendizado de máquina" ou "mídia social". Trigramas são três palavras adjacentes, como "fora do negócio" ou "Proctor and Gamble".

Bigramas: (Nome, Nome), (Adjetivo, Nome)
Trigramas: (Adjetivo/Nome, Qualquer_Item, Adjetivo/Nome)
Mas se escolhermos palavras adjacentes como bigrama ou trigramas, não obteremos frases significativas. Por exemplo, a frase 'Ele usa mídias sociais' contém bigramas: 'Ele usa', 'usa mídias', 'mídias sociais'. "Ele usa" e "usa mídias" não significa nada, enquanto "mídias sociais" é um bigrama significativo.

Como fazemos boas seleções para Collocations? As co-ocorrências podem não ser suficientes, pois frases como 'assim como' podem co-ocorrer com frequência, mas não são significativas. Vamos explorar vários métodos para filtrar as Collocations mais significativas: contagem de frequências, informação mútua pontual (PMI) e teste de hipóteses (teste t e qui-quadrado).
