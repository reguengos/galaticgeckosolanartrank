# galaticgeckosolanartrank

this works with Chrome extension:
Javascript Injector

# How to use:
1- activate extension:
https://chrome.google.com/webstore/detail/javascript-injector/ejnccfcackblkelbafbolcpjfpcmbplg

2- Navigate to Solanart galatic gecko 
https://solanart.io/collections/galacticgeckospacegarage

3- activate extension


Paste the following code:
```
fetch('https://assets.galacticgeckos.app/assets/t2r.json')
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
