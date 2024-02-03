---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.18",
	"elements": [
		{
			"type": "image",
			"version": 93,
			"versionNonce": 1875168361,
			"isDeleted": false,
			"id": "6-PLhlE1SDybOKCyCecjb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -731.3411458333333,
			"y": -718.5338541666666,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1440,
			"height": 1351.234375,
			"seed": 298409639,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706847698328,
			"link": null,
			"locked": false,
			"customData": {
				"mermaidText": "C4Component\n    title Component diagram for Internet Banking System - API Application\n\n    Container(spa, \"Single Page Application\", \"javascript and angular\", \"Provides all the internet banking functionality to customers via their web browser.\")\n    Container(ma, \"Mobile App\", \"Xamarin\", \"Provides a limited subset to the internet banking functionality to customers via their mobile mobile device.\")\n    ContainerDb(db, \"Database\", \"Relational Database Schema\", \"Stores user registration information, hashed authentication credentials, access logs, etc.\")\n    System_Ext(mbs, \"Mainframe Banking System\", \"Stores all of the core banking information about customers, accounts, transactions, etc.\")\n\n    Container_Boundary(api, \"API Application\") {\n        Component(sign, \"Sign In Controller\", \"MVC Rest Controller\", \"Allows users to sign in to the internet banking system\")\n        Component(accounts, \"Accounts Summary Controller\", \"MVC Rest Controller\", \"Provides customers with a summary of their bank accounts\")\n        Component(security, \"Security Component\", \"Spring Bean\", \"Provides functionality related to singing in, changing passwords, etc.\")\n        Component(mbsfacade, \"Mainframe Banking System Facade\", \"Spring Bean\", \"A facade onto the mainframe banking system.\")\n\n        Rel(sign, security, \"Uses\")\n        Rel(accounts, mbsfacade, \"Uses\")\n        Rel(security, db, \"Read & write to\", \"JDBC\")\n        Rel(mbsfacade, mbs, \"Uses\", \"XML/HTTPS\")\n    }\n\n    Rel_Back(spa, sign, \"Uses\", \"JSON/HTTPS\")\n    Rel(spa, accounts, \"Uses\", \"JSON/HTTPS\")\n\n    Rel(ma, sign, \"Uses\", \"JSON/HTTPS\")\n    Rel(ma, accounts, \"Uses\", \"JSON/HTTPS\")\n\n    UpdateRelStyle(spa, sign, $offsetY=\"-40\")\n    UpdateRelStyle(spa, accounts, $offsetX=\"40\", $offsetY=\"40\")\n\n    UpdateRelStyle(ma, sign, $offsetX=\"-90\", $offsetY=\"40\")\n    UpdateRelStyle(ma, accounts, $offsetY=\"-40\")\n\n        UpdateRelStyle(sign, security, $offsetX=\"-160\", $offsetY=\"10\")\n        UpdateRelStyle(accounts, mbsfacade, $offsetX=\"140\", $offsetY=\"10\")\n        UpdateRelStyle(security, db, $offsetY=\"-40\")\n        UpdateRelStyle(mbsfacade, mbs, $offsetY=\"-40\")"
			},
			"status": "saved",
			"fileId": "tJYGyRZWPPBhwu06nN5do",
			"scale": [
				1,
				1
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 981.25,
		"scrollY": 724.7786458333336,
		"zoom": {
			"value": 0.6000000000000001
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%