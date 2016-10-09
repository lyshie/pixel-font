# pixel-font
Show font in pixel-level

## Live demo
  * [Click here to show live demo](https://lyshie.github.io/pixel-font/index.html)
  * ![screenshot.png](screenshot.png)
  
## Performance issue
To get better rendering performance! We should avoid using **ctx.putImageData()** and try to use **ctx.fillRect()**.
