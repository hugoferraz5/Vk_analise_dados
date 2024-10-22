<div align='center'>
    <img src="https://github.com/user-attachments/assets/ebf7e7f5-88a7-4a99-ad2a-61cbcd4b2bc3" style="width: 30%; height: auto;"/>
</div>

&nbsp;

Você pode acessar o notebook [aqui](https://github.com/hugoferraz5/Vk_analise_dados/blob/main/analise_vk.ipynb).

## Cenário

O projeto refere-se ao lançamento de um produto, que envolveu a execução de tráfego em diversos canais para atrair potenciais clientes. Foram fornecidos dados para análise descritiva, identificação de insights de negócios e sugestões de otimizações para aprimorar os resultados em futuros lançamentos. O estudo a seguir, desenvolvido para minha equipe de BI fictícia, oferece uma visão clara do lançamento para os stakeholders. Utilizei meus conhecimentos em análise de dados, incluindo o uso de Python e o cuidado na apresentação das informações de forma clara. Além disso, executei o processo de ETL, que inclui a extração dos dados fornecidos, limpeza, tratamento de valores ausentes e tipagem.

## Dados 

A primeira tabela de dados traz dados de leads inscritos em um lançamento, ou seja, dados de quem se inscreveu para participar de um lançamento(quem apenas se inscreveu).
Na tabela há o e-mail do lead e os parâmetros de UTM de entrada desse lead. Dica: UTMs são parâmetros que indicam a origem do lead, nesse caso, Source representa o canal de origem, Medium (para canais de tráfego pago) representa o público e Term (para canais de tráfego pago) o anúncio que trouxe o lead.

A segunda tabela traz dados de compradores do lançamento(quem se inscreveu e comprou).Ela é composta apenas pelo e-mail de quem comprou a oferta realizada no lançamento.

A terceira tabela traz dados de uma pesquisa de persona distribuída durante a captação e que foi respondida por alguns dos leads dando mais informações sobre eles.(informações mais detalhadas dos leads).Ela é composta apenas pelo e-mail do lead que respondeu, idade, renda e há quanto tempo conhece o expert.

A quarta tabela contém o link pra alguns dos anúncios retratados como origem dos leads.
O anúncio em si pode servir para análises mais qualitativas do seu estudo.

## Análises

- Dentre os 5 maiores domínios dos leads, observamos que a grande maioria, representando 73,19%, utiliza o Gmail regularmente em seu dia a dia, o que significa que podemos investir em tráfegos pagos via gmail.com.

<div align='center'>
<img src="https://github.com/user-attachments/assets/3a285291-2162-4c42-a0e4-442603d8fd5d" width="80%"/>
</div>

- O gráfico abaixo mostra que 84.07% do tráfego dos leads vieram do facebookads, ou seja, a grande maioria usa essa plataforma de anúncios.Também, pode ser investido anúncios no facebookads.

<div align='center'>
<img src="https://github.com/user-attachments/assets/f6e7323e-c365-4512-8b20-416d1a8cb3c1" width="80%"/>
</div>

- Nesses valores, representando o anúncio que trouxe o lead, ad17 e ad19 lideram como maiores pontos de tráfego, embora não possua uma disparidade nas frequências.

<div align='center'>
<img src="https://github.com/user-attachments/assets/8a78faaa-4fa9-4cf8-98a3-acc7615d2670" width="50%"/>
</div>

<div align='center'>
<img src="https://github.com/user-attachments/assets/bff9b5ab-4bba-48c0-b778-b7f27b6a1763" width="80%"/>
</div>

- Nessa análise, observamos que o público nos meios de tráfegos possuem um certo equilíbro nas suas frequências, com uma leve maioria no 2.03_lookalike_1_compras_180D_ADS_Campeoes.

<div align='center'>
<img src="https://github.com/user-attachments/assets/8ee0d667-ee01-4d4a-811c-1bf77552a85b" width="80%"/>
</div>

- Dos 9999 leads inscritos no lançamento, 71 executaram a compra, que corresponde a 0.71% do total de leads.
  
- Existem 53 links para alguns dos anúncios retratados como origem dos leads.

- A grande maioria dos leads possuem rendas abaixo de 1500 reais, com uma leve quantidade entre 1500 a 3000 reais.

<div align='center'>
<img src="https://github.com/user-attachments/assets/61742fe3-19f7-4449-aef9-f28ac4f82453" width="60%"/>
</div>

- A grande maioria dos leads conhecem há menos de 1 mês o expert, ou seja, provavelmente ficou conhecido após o lançamento.

<div align='center'>
<img src="https://github.com/user-attachments/assets/b7fa4156-dcfa-41f0-85d7-2d83da554168" width="60%"/>
</div>

- Podemos observar que há um equilíbrio na porcentagem de idades dos leads, com uma leve vantagem para idades entre 31 e 55 anos. Talvez seja interessante focar em anúncios para essa faixa etária.

<div align='center'>
<img src="https://github.com/user-attachments/assets/a03e49b6-3fee-4134-928c-30fa9617a8a8" width="80%"/>
</div>

- A tabela de leads mostra uma ordem específica de frequência para cada utm_source mostrada no gŕafico. Na tabela de compradores, essa ordem se mantém, com destaque para Facebook Ads, seguido por ManyChat, Bio, Google Leads, Stories, Email, Direct, e YouTube. **Podemos direcionar nossos investimentos em anúncios seguindo a ordem de frequência apresentada nos gráficos, com ênfase especial no Facebook Ads, que se destaca com a maior frequência entre todas as plataformas.**

<div align='center'>
<img src="https://github.com/user-attachments/assets/e4b66f3c-52bb-4292-9e8e-f95155916271" width="60%"/>
</div>

<div align='center'>
<img src="https://github.com/user-attachments/assets/388f9e58-d874-46e6-979a-b5160e07841f" width="80%"/>
</div>

- A tabela de leads revela uma ordem específica de frequência para cada faixa de renda apresentada no gráfico. No entanto, na tabela de compradores, essa ordem não é mantida. Apenas a faixa de renda até 1.500 reais segue a mesma ordem, enquanto os clientes com rendas acima de 3.000 reais mostraram uma alta porcentagem de compras. Em contraste, a maioria dos leads tinha renda inferior a 3.000 reais. **Podemos direcionar nossos investimentos em anúncios para pessoas com renda maior que 3000 reais. Podemos realizar algumas promoções para pessoas com renda menor que 3000 reais.**

<div align='center'>
<img src="https://github.com/user-attachments/assets/4652adae-e0e7-415e-900c-e2f7ad123c04" width="60%"/>
</div>

<div align='center'>
<img src="https://github.com/user-attachments/assets/ef156f51-e8c4-454c-8d4e-757a904bca2f" width="80%"/>
</div>
