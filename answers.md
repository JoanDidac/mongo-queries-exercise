# Solutions sheet

Submit your final query after each iteration:

## Iteration 1
db.users.find({}, {name: 1 , _id: 0}).sort({name : 1})
## Iteration 2
db.users.find( {hasInsurance: {$eq:true}})
## Iteration 3
db.users.find( {age: {$gte:18}})
## Iteration 4
