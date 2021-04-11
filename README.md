# siloed web

A protocol for dynamic communication between websites

```bash
 npm install siloed 

 sockets 
 api 
	website A <- api -> website B
server-side 
	web A <- server -> web B
```

## React

suppose you have `component A` in web A and `component B` in web B. 
If both sites have `siloed` installed, they can interchange `components A -> B` 

## Use-case

`Company A` has an ad that it wants to share with `company B`
