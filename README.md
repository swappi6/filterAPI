# filterAPI

App.getFilterResult(category, searchQuery, [sortQuery])

## SAMPLE INPUT
===============================================
category = Mobile Phone (required)
// search Query (optional)
{
	"Price" : {               // range of values
		"gte" = 10000,
		"lte" = 50000
	},"Brand" : ["Samsung", "One Plus", "Motorolla"],      // Can in be in any of those
	"Screen size" : 5.5
}
 //sort Query (optional)
{
	"Price" : "desc",
	"RAM" : "desc"
}

