# Full-Text Search Using Docker, Elastic Search, NodeJS, ViewJS
Implements full-text search  books from http://www.gutenberg.org/. Currently only 100 books are indexed in the ES.
1. run git clone https://github.com/maaz92/FullTextSearch.git
2. cd FullTextSearch
3. docker-compose up -d --build (shorthand to docker-compose build  and docker-compose up -d)
4. docker exec gs-api "node" "server/load_data.js" (to load data from book files to elasticsearch. This may take a while.)
5. Hit localhost:8080 in your browser

## Todo
Implement Front End With ReactJS
