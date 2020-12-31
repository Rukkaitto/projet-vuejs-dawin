FROM mongo

COPY init.json /init.json
CMD mongoimport --host mongo --db movies --collection movies --type json --file /init.json --jsonArray
