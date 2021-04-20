Siloed web

A protocol for dynamic communication between websites

### Siloed component is a glorified iframe with dynamic properties

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

### Ads
`Company A` has an ad that it wants to share with `company B`

### UI Design Systems
`Tailwind CSS` being used on your site with no local install, but just reference to server-side CSS code.

