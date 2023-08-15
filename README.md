# metis-maintenance
Configuration to alert users about maintenance on metis servers.

Entries in `maintenance.json` specify a message and an optional period when it will show:

```	"sandbox-ui-test": {
		"maintenanceMessage": "The site (sandbox test) is down",
		"period": {
			"from": "8/15/2023, 9:43:03 AM",
			"to": "8/15/2023, 9:44:13 AM"
		}
	},```


(the js function `new Date().toLocalString()` yields the correct format)
