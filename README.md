```
#   compound init blog --tpl jade --db mysql
    compound init blog
    cd blog
       npm install -l
       npm install jugglingdb-mysql 

```

# part 2 - https://nyukapiszka.wordpress.com/2013/03/01/compound-js-controller-routing-and-simple-ajax-request/
```
    compound init compound-angular-todo —coffee —tpl jade
    cd compound-angular-todo
       npm install —save-dev node-dev
       npm install
       node-dev server.coffee

       compound g controller tasks
       compound g model task description:string completed:boolean created_at:date
 ```
