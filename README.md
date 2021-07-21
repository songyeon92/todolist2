# todolist2
upgrade version 

# mongoDB start && stop 
brew services start mongodb-community@5.0
brew services stop mongodb-community@5.0

# mongoDB server start 
brew services list

#명령어
help 입력시 collection, document 등 접근 방법 확인가능함.

Creat : 
  db.collection.insertOne({filed:value});
  db.collection.insertMany({document1}, {document2});

Read :
  db.collection.find( {filed: { $gt: 18 }} ); (query filter)
  
Update :
  db.collection.updateOne({filed:value});
  db.collection.updateMany({document1}, {document2});
  
Delete :
  db.collection.deleteOne({filed:value});
  db.collection.deleteMany({document1}, {document2});
  
  

