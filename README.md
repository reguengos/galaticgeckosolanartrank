# Galactic Geckos Solanart Rank â
![Logo](https://github.com/reguengos/galaticgeckosolanartrank/blob/main/logoggs.PNG)

Disclaimer: i am not affiliate with solanart nor GGSCâ
            Built with love for the community.â¤ð 

# My geckos :D
![Logo](https://github.com/reguengos/galaticgeckosolanartrank/blob/main/gg.PNG)

# How to use:
this works with Chrome extension:
Javascript Injector

1- activate extension:

https://chrome.google.com/webstore/detail/javascript-injector/ejnccfcackblkelbafbolcpjfpcmbplg
Kudos to the creator ð¥ : 
https://github.com/hex0cter/js-injector

2- Navigate to Solanart galatic gecko ð±âð

https://solanart.io/collections/galacticgeckospacegarage

3- activate and use extension!

Paste the following code:â¡
```
fetch('https://raw.githubusercontent.com/reguengos/galaticgeckosolanartrank/main/t2r.json')
.then(res => res.json())
.then((out) => {
  console.log('Checkout this JSON! ', out);
var els = document.getElementsByClassName("card-title h5");

Array.prototype.forEach.call(els, function(el) {

replaced = el.textContent.replace("Galactic Gecko #","")
idx = replaced
token = out[idx];
rank = token["rank"];
el.textContent = "ID:"+replaced+"|rank:"+rank


});
})
.catch(err => { throw err });


```

![Instructions](https://github.com/reguengos/galaticgeckosolanartrank/blob/main/instructions.PNG)

# Done! Start buying with confidence! â¨â¨â¨â¨âð

# pay me a cofee if you feel it deserves :
AJpuaH2Ke13VoMrk8MRCE693yMWMLyTBf2e2J48Pzz7j



