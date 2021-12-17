[![Deploy](https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png)](https://dashboard.heroku.com/new?template=https://github.com/euueeuue/euueeuue.git)
```
const SingleDay = 'helloworld.herokuapp.com'
const DoubleDay = 'helloworld.herokuapp.com'
addEventListener(
    "fetch",event => {
    
        let nd = new Date();
        if (nd.getDate()%2) {
            host = SingleDay
        } else {
            host = DoubleDay
        }
        
        let url=new URL(event.request.url);
        url.hostname="helloworld.herokuapp.com";
        let request=new Request(url,event.request);
        event. respondWith(
            fetch(request)
        )
    }
)
```
