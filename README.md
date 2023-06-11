# Web-Layout-using-GridBOX
## AIM:
To ceate a web-layout using gridbox

## SOFTWARE:
Visual Studio Code
 
## ALGORITHM:
Start by creating the basic HTML structure for your web page
Create a CSS file (e.g., styles.css) and link it to your HTML file. Then, define the styles for the grid layout using the grid-template-areas, grid-template-columns, and grid-template-rows properties.
Feel free to customize the grid layout by adjusting the grid areas, columns, and rows to match your specific design requirements. You can add more elements or modify the existing ones.
Open the HTML file in a web browser to see the web layout created using the CSS Grid. You should have a header at the top, a sidebar on the left, content in the center, and a footer at the bottom.
Run the program.
## PROGRAM:
~~~
java <!doctype html>

<title>Example</title>
<style> body { display: grid; grid-template-areas: "header header header" "nav article ads" "footer footer footer";
grid-template-rows: 60px 1fr 60px;
grid-template-columns: 20% 1fr 15%;
grid-gap: 10px; height: 100vh; margin: 0; }
header, footer, arti![image](https://github.com/SdMdZahi7/Web-Layout-using-GridBOX/assets/94187572/096c2941-71fb-40bc-bf4a-37227eed9ab9)cle, nav, div { padding: 20px; background: rgb(63, 97, 102); } #pageHeader { grid-area: header; }
#pageFooter { grid-area: footer; } #mainArticle { grid-area: article; } #mainNav { grid-area: nav; } #siteAds { grid-area: ads; } </style> Header Article Nav
Ads
Footer
~~~
## OUTPUT:
![image](https://github.com/SdMdZahi7/Web-Layout-using-GridBOX/assets/94187572/90c21b67-22bf-4481-a1f6-8addef16a83a)

## RESULT:
Thus the web-layout using gridbos is created.

