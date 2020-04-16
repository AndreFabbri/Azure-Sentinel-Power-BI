##  5) Conectando o Power BI no Azure Sentinel
Depois de sua Kudo query pronta, clique em **Export** e faça o download da **M query**. Em seguida copie o conteúdo do arquivo de texto.

![](https://media3.giphy.com/media/IcdDrJg6UvwcaFtj35/giphy.gif?cid=ecf05e4758bed1f699b753bbdd7d3a65608fa2a93ccf933f&rid=giphy.gif)

Com o Power BI aberto, clique em **Obter dados**, seleciona **Consulta em branco**. No Ribbon superior clique em **Editor Avançado** e cole o conteúdo do arquivo texto que acabamos de baixar. Clique em **concluído**. Se for requisitado, entre com as credenciais do tipo organizacional para um usuário que tenha acesso ao Azure Sentinel.

GIF2

Faça as modificações necessárias e clique em **Fechar e aplicar**.

Para mais detalhes de como transformar o seu dado, [veja esse material de referencia](http://https://docs.microsoft.com/en-us/power-bi/desktop-query-overview "veja esse material de referencia")

GIF3

## 6) Criação/Customização do Report no Power BI Desktop e Publicação no Power BI Service

Nesse momento, estamos prontos para construir o **Report**. Para mais detalhes em como construir um Relatório no Power, [consulte esse material de referência](http://https://powerbi.microsoft.com/en-us/blog/create-a-power-bi-desktop-report-in-minutes/ "consulte esse material de referência")

No exemplo abaixo, criei 3 visões: Número de Sign-in ao longo do tempo; Número de Sign-in por Cliente; Número de Sign-in por aplicação.

Fiquem a vontade para exercer sua criativade e criar visões que fazem sentido para você.

Quando finalizar, clique em **Publicar**. Salve o arquivo onde desejar. Faça o login caso necessário, escolha uma **workspace do Power BI** para publicar seu relatorio Então seu Report será publicado no Power BI Service.

GIF4

## 7) Configuração de Refreshs automáticos no Power BI Service

- Depois de publicado clique em **Abrir 'nome do seu report.pbix' no Power BI**. 
- No canto inferior esquerdo na blade **Datasets** clique no 3 pontinhos do seu respectivo dataset. Escolha a opção **Schedule Refreshs**.
- Caso necessário clique em **Edit Credentials** e faça o login com um conta que tenha acesso ao Sentinel
- Finalmente, habilite a opção **Schedule Refresh** e adicione o horário das atualizações programadas desejas. Lembrando que utilizando o Power BI PRO pode-se atualizar até 8 vezes ao dia com a frequência máxima de 1 hora. Utilizando o Power BI Premium, esse limite aumenta para 48 vezes ao dia.

GIF 5


## 8) Criação de Dashboards e Compartilhamento da Solução

Facultativamente, pode-se criar Dashboards utilizando os principais visões do Report que criamos. Para isso, basta pinar os gráficos em um novo ou existente dashboard.
Uma vez o dashboard criado, pode-se também compartilhar a solução com aqueles que você achar necessário. Para isso, basta clicar no botão **Share** no canto superior direito e selecionar as pessoas desejadas. Para mais detalhes, use [esse artigo como referência](http://https://docs.microsoft.com/en-us/power-bi/service-share-dashboards "esse artigo como referência"). Para distribuição em larga escala é altamente recomendável utilizar [os apps do Power BI.](http://https://docs.microsoft.com/en-us/power-bi/service-create-distribute-apps "os apps do Power BI.")

GIF6
