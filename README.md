# covid19-lazio
Dashboard per la visualizzazione di dati relativi al COVID-19 nella Regione Lazio. Dati estratti dalla repository della Protezione Civile. 

**Dashboard**

Questa Dashboard è sviluppata sulla base del template di Rami Krispin ([Coronavirus dashboard:](https://www.antoinesoetewey.com/files/coronavirus-dashboard.html)) e adattato al caso della Regione Lazio. L'intera Dashboard è sviluppata in R utilizzando il framework R Markdown. 

**Codice**

Il codice è disponibile su GitHub al seguente link [GitHub](https://github.com/){target="_blank"}.


**Dati**

I dati mostrati sono estratti da quelli messi a disposizione dalla Protezione Civile Italiana ([Dati Covid-19 Italia](https://github.com/pcm-dpc/COVID-19)) a livello regionale e provinciale. 


**Update**

I dati sono aggiornati al `r format(max(covid_data_lazio$Date), "%d %B, %Y")`.
La dashboard è stata manualmente aggiornata il `r format(Sys.time(), "%d %B, %Y")`.
