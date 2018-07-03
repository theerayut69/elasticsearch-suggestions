# Search Suggestion  

**Run Docker**
```
$ docker-compose up  
```  
**Indexing**  
```
$ cd elasticsearchtutorial-master/  
$ curl -H "content-type: application/json" -XPOST "http://localhost:9200/product/default/_bulk?pretty" --data-binary "@test-data.json"  
```
**Search**
```
$ curl "http://localhost:9200/product/default/_search?q=basil&pretty"  
```
