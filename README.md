# techniknews
JavaScript library for techniknews.net
# main
```js
async function main(){
    const {techniknews} = require('./techniknews');
    const info= new techniknews();
    let req=await info.ip_info("ip")
    console.log(req)
}
main()
```
