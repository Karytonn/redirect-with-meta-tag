# Redirect with Meta Tag

Redirect to outher URL

## Use cases

- Website migration
- URL Update
- Redirect a page that no longer exists
- Multiple domains
- Fix 404 error


## Whol implements

1) Create an ```index.html``` file and set a meta tag whit ```http-equiv="refresh"``` property

```html
<!-- In content define after how long the new url will be loaded and then the destination -->
<meta http-equiv="refresh" content="0, url=https://www.newwebsite.com" />
```

2) Create a rollback if it doesn't work


```html
<p>
    If your browser supports meta tag redirect, you will be redirected
	to our <a href="https://www.newwebsite.com">new site</a>
	in 5 seconds, otherwise select the link manually.
</p>
```
## Demo

(Click here to demo)[]


## NOTE

_We know it's good practice to do this from the server side, but we don't always have access to it, or most of the time, we wouldn't have the time for this implementation._

