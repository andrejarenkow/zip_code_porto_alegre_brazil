# ZIP Code with BeautifulSoup4 in Python

## Introduction

ZIP Code, or CEP in portuguese, is a code that helps locate a adress in a city. Recently I had to compare the zip code number with a neighboorhood in my home town (Porto alegre, Brazil).

## Methods

It was used Python with the library Beautiful Soup 4 to webscrap the website https://cep.guiamais.com.br/busca/porto+alegre-rs and transform the table that was in each page to a dataframe.

## Results

It was necessary to split in 4 blocks the number of pages (1-99; 100-199; 200-299; 300-392), due to a error that I didn't found out wat it was. Also, half of the table had one conformation and the other half had another. A FOR loop was used to transform the data, creating two new columns in the dataframe with the right results.

## Conclusion

Now, the internet has a csv file with this information.

