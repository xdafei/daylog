 ##岁月残片
- 对方答复
- 对方答复
- 对方答复
[简书](http://www.jianshu.com)
###以下是代码展示
```
let data = {
  memberId: window.BL.uid,
  code: this.yourTick,
  timestamp: timer,
  sign: window.BL.cer,
  cer: window.BL.cer
}
this.$http.post(url, data).then(res => {
  console.log(res.data)
})
```