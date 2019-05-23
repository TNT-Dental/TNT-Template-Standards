# TNT-Template
Coding Standards for TNT Websites

### HEAD HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0" />				
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta content="$var(metaDescription)$" name="Description" />		
	<title>$var(pageTitle)$</title>
	<link rel="canonical" href="http://www.$var(siteURL)$/$var(pageURL)$.html" />	
	<link href="styles.css" type="text/css" rel="stylesheet">	
	<link href="https://tnt-dental.github.io/tnt-extra-icons/css/fontello.css" type="text/css" rel="stylesheet">
	<link href="https://tntwebsites.com/tnticons/css/fontello.css" type="text/css" rel="stylesheet">		
	<!--[if lt IE 9]><script src="assets/js/html5shiv.min.js"></script><![endif]-->		
	<link rel="apple-touch-icon" alt="Favicon 144x144" sizes="144x144" href="assets/images/apple-touch-icon-144.png"/>
	<link rel="apple-touch-icon" alt="Favicon 114x114" sizes="114x114" href="assets/images/apple-touch-icon-114.png"/>
	<link rel="apple-touch-icon" alt="Favicon 72x72" sizes="72x72" href="assets/images/apple-touch-icon-72.png"/>
	<link rel="apple-touch-icon" alt="Favicon 57x57" href="assets/images/apple-touch-icon-57.png"/>
	<link rel="icon" alt="Favicon" href="assets/images/favicon.png"/>			
	<meta name="apple-mobile-web-app-title" content="" />
</head>
```
### Fixed Tabs
| ID or Class | Description                    |
| ------------- | ------------------------------ |
| `#fixed-tabs` | Scrolling side buttons |
| `.ra`   | For Request Appointment button |
| `.fm`   | For Patient Forms button |

### Header
| ID or Class | Description                    |
| ------------- | ------------------------------ |
| `#hd-contents` | Header container |
| `#hd-info`   | Header address, phone, etc |

### Footer IDs & Classes
| ID or Class | Description                    |
| ------------- | ------------------------------ |
| `#fo-contents` | Footer container |
| `#fo-info`   | Footer address, phone, etc |
