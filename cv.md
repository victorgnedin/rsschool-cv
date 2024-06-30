![Photo of Victor Gnedin](/images/photo.jpg)

# Victor Gnedin
Senior+ Product Designer & Mentor

## Contact me
**Email:** victor@gned.in  
**Phone:** +44 7904 875186 🇬🇧  
**Telegram:** [victorgnedin](https://t.me/victorgnedin)  
**Discord username:** Victor Gnedin (@victorgnedin)  
**Github:** [victorgnedin](https://github.com/victorgnedin)

## About
Based in London 🇬🇧, Global Talent visa.  

Senior+ Product Designer with 8 years of experience in delivering products cherished by up to 90 million people.  

Proven in B2C and B2B products across diverse fields: FinTech, EdTech, Search Engines, and Classifieds.  

Experienced with two of Russia's top three Big Tech firms, akin to FAANG.  

Committed to mentoring and teaching, graduating over 100 designers and delivering 150+ hours of live webinars.  

## Skills 
- Product, Experience (UX), Interaction, Interface (UI), Graphic & Motion Design.
- Art Direction, Information Architecture, Wireframing, Prototyping, Animation.
- Figma, Sketch, Adobe CC, Spline, Rive, HTML, CSS, JS, ThreeJS, GSAP, Swift.
- Business Models, Product-Market Fit, Qualitative and Quantitative Research, Data Analysis, CJM, A/B Testing.
- Management, Negotiation, Facilitation, Presentation, Communication.

## Code example
This fucnction sets weather info on my personal websiite [gned.in](https://gned.in)

```js
function setWeather() {

    fetch("https://2qtt2ujcsk.execute-api.eu-north-1.amazonaws.com/prod/weather")
        .then(response => response.json())
        .then(data => {
            // Set temperature data
            const spanTemperature = document.querySelector("span.temperature")
            spanTemperature.textContent = data.current.tempFormatted
        })
        .catch(error => {
            // Hide container if no temperature data has returned
            const divWeather = document.querySelector("div.weather")
            divWeather.style.display = "none"
        })
}
```

## Languages
- English — Advanced
-  Russian — Native