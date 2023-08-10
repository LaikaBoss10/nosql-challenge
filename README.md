# nosql-challenge

### First establishments.json was imported to a mongoDB database by creating a data base called uk_food and a collection called establishments then entering 'mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json' in git bash.

### NoSQL_setup_starter.ipynb firstly updates the database with an additional document. Second it removes documents with LocalAuthorityName equal to "Dover". Lastly it adjusts the data value types of RatingValue and longitude/latitude to integer and double respectively.

### NoSQL_analysis_starter.ipynb analyzes the data base by making some advanced querys including methods and techniques such as conditional queries, sorts, and aggregation piplines. It also converts queries into dataframes for easy access via python and pandas.