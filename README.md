# Como rodar

1.Bibliotecas utilizadas: pandas, scikit-learn, numpy, jupyter.

2.Baixe o dataset (OnlineRetail.csv, ele se encontra na pasta archive do repositorio).

3.Execute o Jupyter Notebook.

4.Abra e rode todas as células do arquivo SistemaDeRecomendações.ipynb.



# SistemaRecomendacaoSimples Resultados

 Nesse projeto, é possivel observar dois métodos de filtragem para um sistema de recomendação de produtos: Colaborativa e Baseada em Conteúdo
 
 Comparando esses dois métodos é possivel dizer que o de filtragem por conteúdo obteve um resultado melhor, visto que o histórico de compras por cliente é limitado, o que reduz a eficácia da filtragem colaborativa. Além de que, os produtos possuem descrições detalhados permitindo extrair features significativas via TF-IDF. E a filtragem por conteúdo não depende de histórico prévio, melhor para novos produtos/clientes.

 Então para o sistema de recomedação de produtos o método de filtragem por conteúdo recomendaria itens tematicamente relacionados, enquanto a colaborativa poderia sugerir itens não relacionados, mas comprados pelo mesmo cliente.


# Videos Referencia

https://youtu.be/ijtxuF_5kEU?si=wSG7p0vV023gk1w9

https://youtu.be/G4MBc40rQ2k?si=VzvSV-Yo4HduHHpw

https://youtu.be/IPMwdk8qHMI?si=_RT4nmNvA5A15aHX

https://youtu.be/XwTvjHsmkdw?si=NMcIjy5RQ659SWDh

https://youtu.be/6jesOOhbCaQ?si=29lYydipqC7Wb2Vk

https://youtu.be/u8c7CgZAQDs?si=qvu9CBlPragicRKa
