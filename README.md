# metis-maintenance
Configuration to alert users about maintenance on metis servers.

Entries in `maintenance.json` specify a message and an optional period when it will show:

```	"sandbox-ui-test": {
		"maintenanceMessage": "The site (sandbox test) is temporarily down for maintenance",
		"period": {
			"from": "2023-08-17T09:30:00.000Z",
			"to": "2023-08-17T09:45:00.000Z"
		}
	},```


(the js function `new Date().toISOString()` yields the correct format)
