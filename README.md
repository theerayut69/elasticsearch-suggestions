# Search Suggestion  
```
docker-compose up  
cd elasticsearchtutorial-master/  
curl -H "content-type: application/json" -XPOST "http://localhost:9200/product/default/_bulk?pretty" --data-binary "@test-data.json"  
curl "http://localhost:9200/product/default/_search?q=basil&pretty"  
```
