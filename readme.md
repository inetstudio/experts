# Elasticsearch

````
PUT app_index
PUT app_index/_mapping/persons
{
  "properties": {
    "id": {
      "type": "integer"
  	},
    "name": {
  	  "type": "string"
    },
    "post": {
  	  "type": "string"
    },    
	  "description": {
  	  "type": "text"
  	},  
	 "content": {
  	  "type": "text"
  	 }
  }
}
````
