### Create the necessary folders

`mkdir myFirstWebsite`

`cd myFirstWebsite`

`mkdir assets`

`mv background.jpeg ./assets/`

https://www.shell-tips.com/bash/download-files-from-shell/
`curl -o logo.svg https://github.com/green-fox-academy/teaching-materials/blob/master/workshop/first-website/aperture.svg`

`mv logo.jpg ./assets`

`touch index.html`

`touch style.css`

Ouch... Let's rename because I so st*pid

`mv style.css styles.css` 

`cd ..`

`mv myFirstWebsite myFirstFoxSite`

`touch example.txt`

`echo 'Hello' >> example.txt`  Valamiért csinált egy sortörést is... ez így jó? Vagy keressek más megoldást?

`mv example.txt ./myFirstFoxSite/assets/`

`rm -i ./myFirstFoxSite/assets/example.txt`  enter `y`

`mv myFirstFoxSite myFirstWebsite`
