#### creating a vite project 

```npx create-vite@latest```
#### In index.html modify title and logo 

Title - ```<title>MaterialUI</title>```

Logo -  ``` <link rel="icon"  href="/icon.jpg" />```

For icons download images from google and save them in public folder so that you can directly refer it on index.html

#### Installation

```npm install @mui/material @emotion/react @emotion/styled```

```npm install @mui/icons-material```

#### Modify font 
First embed code in head tag which you copied from google fonts

Then add below code in index.css
```body {
  font-family: "Winky Sans", sans-serif;
}```