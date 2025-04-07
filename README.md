### XMLSet
XMLSet is a dataset we provide to train and evaluate models that are based on deep learning and that deal with XPath prediction.

Please if you use this dataset, make sure you evaluate your model on the test only once.

This repository in still in development and part of the project XPathia.

### XPathia
XPathia is model that we propose as a solution to the task of translation natural language sentence inot XPath queries that can retrieve XML content from databases.
If you have any question please contact us. 
Thank you


### Databases sources used in XMLSet

- The dataset contains a diversified list of domains. 
- All xml document are collected from existing sources
- Non of the documents have been created by us.
- Few xml databases have been converted from xml sheets in order to leverage our dataset with data from real word.
- Some xml databases contain more than one root
- In our model XPathia not all queries return results as we want to create an independent querstion answer generator.

| Index | Name | Source |
| :---: | :---: | :---: |
|1  |  books  |  https://docs.microsoft.com/en-us/previous-versions/windows/desktop/ms762271(v=vs.85)|
|2  |  ads  |  https://www.cs.utexas.edu/~mitra/csFall2010/cs329/lectures/xml.html|
|3  |  customers  |  https://docs.microsoft.com/en-us/dotnet/standard/linq/sample-xml-file-customers-orders-namespace|
|4  |  purchases  |  https://docs.microsoft.com/en-us/dotnet/standard/linq/sample-xml-file-multiple-purchase-orders|
|5  |  numerical  data  |  https://docs.microsoft.com/en-us/dotnet/standard/linq/sample-xml-file-numerical-data|
|6  |  food   |  https://www.w3schools.com/xml/simple.xml|
|7  |  plants  |  https://www.w3schools.com/xml/plant\_catalog.xml|
|8  |  cds catalog  |  https://www.w3schools.com/xml/cd\_catalog.xml|
|9  |  museums  |  https://data.world/city-of-ny/kcrm-j9hh|
|10  |  employees  |  https://www.appsloveworld.com/download-free-sample-xml-file-with-multiple-records|
|11  |  orders  |  https://www.appsloveworld.com/download-free-sample-xml-file-with-multiple-records|
|12  |  products   |  https://gist.github.com/kinlane/4abec529e89e4b87a558a6e15986d8a3|
|13  |  friends  |  https://docs.microsoft.com/en-us/office/client-developer/outlook/social-connector/friends-xml-example|
|14  |  people   |  https://github.com/vaticle/typedb-examples/blob/master/datasets|
|15  |  calls  |  https://github.com/vaticle/typedb-examples/blob/master/datasets|
|16  |  companies  |  https://github.com/vaticle/typedb-examples/blob/master/datasets|
|17    |  students    |  https://beginnersbook.com/2018/10/xml-example/|
|18    |  records  |  http://www2.hawaii.edu/~takebaya/cent110/xml/xml.html|
|19    |  interactions    |  https://www.kaggle.com/datasets/jordanrich/german-emails-in-xml|
|20    |  workers  |  https://generatedata.com|
|21    |  news    |  http://site.api.espn.com/apis/site/v2/sports/football/college-football/news|
|22    |  scoreboard    |  http://site.api.espn.com/apis/site/v2/sports/football/college-football/scoreboard|
|23    |  journals    |  https://www.researchgate.net/publication/331938969\_List\_of\_Science\_Citation\_Index\_Expanded\_journals\_2022\_Update\_this\_month (converted)|
|24    |  movies    |  https://www.kaggle.com/datasets/stefanoleone992/filmtv-movies-dataset  (coverted)|
|25    |  players 2021    |  https://www.kaggle.com/datasets/stefanoleone992/fifa-21-complete-player-dataset?select=players\_21.csv (converted)|
|26    |  cars    |  https://www.kaggle.com/datasets/mrushan3/cars-information?select=File+CARS\_1993.xlsx (converted)|
|27    |  sevilla housing  |  https://www.kaggle.com/datasets/javieradvani/sevilla-housing?select=Sevilla\_housing.xlsx (converted)|
|28    |  ranking of universities  |  https://www.kaggle.com/datasets/shivan118/world-university-rankings-analytics?select=nineteen\_twenty\_university\_datasets.xlsx  (converted)|
|29    |  songs  |  https://www.kaggle.com/datasets/muhmores/spotify-top-100-songs-of-20152019?select=Spotify+2010+-+2019+Top+100+Songs.xlsx (converted)|
