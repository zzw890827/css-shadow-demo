## CSS3 Shadow Demo
A Shadow style demo.

### Properties
- inset: 默认阴影在边框外。使用 inset 后，阴影在边框内（即使是透明边框），背景之上内容之下。也有些人喜欢把这个值放在最后，浏览器也支持。
- offset-x offset-y: 这是头两个 <length>值，用来设置阴影偏移量。<offset-x> 设置水平偏移量，如果是负值则阴影位于元素左边。
<offset-y> 设置垂直偏移量，如果是负值则阴影位于元素上面。可用单位请查看 <length>。如果两者都是0，那么阴影位于元素后面。这时如果设置了 <blur-radius> 或 <spread-radius> 则有模糊效果。
- blur-radius: 这是第三个 <length> 值。值越大，模糊面积越大，阴影就越大越淡。 不能为负值。默认为0，此时阴影边缘锐利。
- spread-radius: 这是第四个 <length> 值。取正值时，阴影扩大；取负值时，阴影收缩。默认为0，此时阴影与元素同样大。
- color: 相关事项查看 <color> 。如果没有指定，则由浏览器决定——通常是color的值，不过目前Safari取透明。

### Set up
```npm install```

### Develop
```npm run start```

### Build
```npm run build```

