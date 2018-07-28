## real-ip
一个可以获取到用户真实ip地址的包
## install
```bash
npm install real-ip

```
## usage
import {getIPs} from 'real-ip'
注意：需要在dom加载完的时候使用，否则会找不到window
```js
 getIPs(ip=>{
      console.log('真实ip地址',ip)
    })
```



