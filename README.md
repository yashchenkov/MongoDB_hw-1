db.books.insertMany([
	{
  		title: "string",
  		description: "string",
  		authors: "string"
	},
	{
  		title: "string",
		  description: "string",
		  authors: "string"
	}
])

db.books.find({ "title": "String"});

db.boks.updateMany(
	{ $set: { description: "new string" } },
	{ $set: { authors: "new string" } }
)