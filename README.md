# result-rank

This is the result ranker for the search engine project. This recieves queries from [user-interface](https://github.com/systemsdevelopmentclub/user-interface) and asks the [database wrapper](https://github.com/systemsdevelopmentclub/database) to get all the matching results. Based on the results returned by the database, the result ranker will sort the pages and send them in JSON back to the UI.
