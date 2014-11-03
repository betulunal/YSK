YSK
===

YSK (Yuksek Secim Kurulu) 2014 Yerel secim sonuclarini indiren, duzenleyen, analiz edn script'ler ve de sonuc dosyalari.

Scripts to scrape ballot-box level official vote counts, to clean/reformat/combine resulting files, and to recalculate GPD weighted votes for Turkey's 2014 local election.
Codes are commented, short deescriptions of the files are as follows:

- **scrape.py**: the script that I used to scrape the Turkish local elections, 2014.
- **merge.py**: to clean the collected data and combine them into a single CSV file.
- **plaka.tsv**: a helper file to map the cities to their traffic codes
- **GSKD.csv**: extracted from [TUIK April 2014 report](http://www.tuik.gov.tr/jsp/duyuru/upload/yayinrapor/GSKD_Bolgesel_2004-2011.pdf) to get regional GDPs for analysis.
- **kd_oylar.py**: to get GDP per region weighted votes.
- **kd_oylar.csv**: GDP per region weighted votes resulting file
- **yerel2014.csv**: Official ballot-box level results of the top ten parties' in Turkish local elections, 2014.
- **Yerel-GSKD-TR.png**: Pie chart of recalculated vote shares of parties if GDP voted not people. Replicated what [the Guardian](http://www.economist.com/blogs/graphicdetail/2015/10/daily-chart-18) did for Brazil.
