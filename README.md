# code-mixed-tweets
These files contain the ids of code-mixed tweets harvested through the Twitter API.

## Russian-German Code-Mixed Tweets
The tweets were harvested using the following query:
```
(ратхаус OR праксисы OR шпаркасса OR шпаркассе OR хаусарцт\
      OR нотфаль OR бератер OR кауцион OR киндергельд OR титель OR анмелдунг OR анмельдунг OR гевербе\
      OR фермитер OR фермитера OR абрехнунг OR паушаль OR финанцамт OR бетройер \
      OR хоумофис OR хоум-офис OR хоумофиса\
      OR хохшуле OR ангебот OR аусбильдунг OR аусбильдунга OR ангеботы OR вонхайм\
      OR "взять термин" OR "взял термин" OR "взяла термин" OR "сделать термин"\
      OR арбайтсамт OR бюргерамт) lang:ru -is:retweet
 ```
      
 The dataset contains 688 tweets spanning the time period from July 18, 2022 to January 16, 2023. The total number of tokens in the
preprocessed dataset is 15,309, and the number of types is 5,583.
  
  ## Russian-Hebrew Code-Mixed Tweets
The tweets were harvested using the following query:
 ```
 (машканта OR машканту OR мисрад OR теудат OR мазган OR мерказит OR хавер OR хавера \
      OR хашмаль OR рамзор OR шутафа OR мивца OR ханут OR хеврат OR геверет OR мотек OR ракевет\
      OR анахну OR слиха OR битахон OR (купат холим) OR тахане OR багрут OR мивхан\
      OR асаот OR шиур OR тиуль OR пкида OR пкиде) lang:ru -is:retweet
  ```
      
 The dataset contains 853 tweets spanning the time period from July 17, 2022 to January 16, 2023. The total number of
tokens in the preprocessed dataset is 16,302, and the number of types is 6,342.
