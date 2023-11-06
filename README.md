# API_Testing
API testing with the help of CURL (GET and POST request) 
<<<<<<< HEAD
<<<<<<< HEAD
# Script 
#!/bin/bash
## API end piont
=======
=======

# Script 
#!/bin/bash
## API end piont

>>>>>>> a7ceca5f932ff93fdb9089bac6985a4dd69b4a71

# Script
#!/bin/bash
# API end piont
<<<<<<< HEAD
>>>>>>> 64c55f577fc2e27b558bb7ac16725ab9878bbcee
=======

>>>>>>> a7ceca5f932ff93fdb9089bac6985a4dd69b4a71
GET_URL="https://newsapi.org/v2/everything?q=tesla&from=2023-11-04to=2023-11-05&sortBy=publishedAt&apiKey=e782b949696948f28fca32a65958eb78"

POST_URL="https://newsapi.org/v2/everything?q=tesla&from=2023-11-04to=2023-11-04&sortBy=publishedAt&apiKey=e782b949696948f28fca32a65958eb78"

<<<<<<< HEAD
<<<<<<< HEAD
=======
>>>>>>> a7ceca5f932ff93fdb9089bac6985a4dd69b4a71
## Make GET request and save response in GET_RESP.txt file
curl -X GET $GET_URL -o GET_RESP.txt
echo "GET Response:"
cat GET_RESP.txt $/n
## Make POST request and save response in POST_RESP
<<<<<<< HEAD
=======
=======

>>>>>>> a7ceca5f932ff93fdb9089bac6985a4dd69b4a71
curl -X GET $GET_URL -o GET_RESP.txt
echo "GET Response:"
cat GET_RESP.txt $/n
# Make POST request and save response in POST_RESP
<<<<<<< HEAD
>>>>>>> 64c55f577fc2e27b558bb7ac16725ab9878bbcee
=======

>>>>>>> a7ceca5f932ff93fdb9089bac6985a4dd69b4a71
RESP=$(curl -X POST -H "Content type:Application/json" -d '{"name": "abc", "email":"abc@gmail.com"}' $POST_URL -o POST_RESP.txt)
echo "POST Response:"
cat POST_RESP.txt
