# todo

- Is there any difference among formats of css transform property: 'translate(0px, -1000px) translateZ(0px)', 'translateY(-1000px)' and 'translate3d(0px, -1000px, 0px)'?
- If the list is longer, the maxSpeed should be higher, shouldn't it?

# contrast

- 模拟滚动不同隐藏方式间对比（display none、visibility hidden、无）：`scroll.js.html?size=1000&content=1` vs `scroll.js.html?size=1000&content=1#1` vs `scroll.js.html?size=1000&content=1&hide=false`
- 不同滚动对比（高度固定自动隐藏模拟滚动、高度固定不隐藏模拟滚动、iscroll、原生）：`scroll.js.html?size=10000&content=0&height=true` vs `scroll.js.html?size=10000&content=0&height=true#1` vs `scroll.js.html?size=10000&content=0&height=true&hide=false` vs `scroll.js.iscroll.html?size=10000&content=0&method=iscroll` vs `scroll.js.native.html?size=10000&content=0&method=native`
