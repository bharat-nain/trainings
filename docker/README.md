curl -XPOST 'http://localhost:8086/query' --data-urlencode 'q=CREATE DATABASE telegraf'
curl -G http://localhost:8086/query?pretty=true --data-urlencode "db=glances" --data-urlencode "q=SHOW DATABASES"
