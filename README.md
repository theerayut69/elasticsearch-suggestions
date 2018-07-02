# Search Suggestion  

**Run Docker**
```
$ docker-compose up  
```  
**นำเข้าข้อมูล**  
```
$ cd elasticsearchtutorial-master/  
$ curl -H "content-type: application/json" -XPOST "http://localhost:9200/product/default/_bulk?pretty" --data-binary "@test-data.json"  
```
**ทดสอบค้นหาข้อมูล**
```
$ curl "http://localhost:9200/product/default/_search?q=basil&pretty"  
```
