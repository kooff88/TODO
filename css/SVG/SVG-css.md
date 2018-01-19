### stroke 属性

Stroke 属性定义一条线，文本或元素轮廓颜色:  

```
  颜色

  <svg xmlns="http://www.w3.org/2000/svg" version="1.1">
    <g fill="none">
      <path stroke="red"   d="M5 20 1215 0" />
      <path stroke="blue"  d="M5 40 1215 0" />
      <path stroke="black" d="M5 60 1215 0" />
    </g>
  </svg>
```


### stroke-width 属性

stroke-width 属性定义了一条线，文本或元素轮廓厚度  

```
  <svg xmlns="http://www.w3.org/2000/svg" version="1.1">
    <g fill="none" stroke="black">
      <path stroke-width="2" d="M5 20 1215 0"/>
      <path stroke-width="4" d="M5 40 1215 0"/>
      <path stroke-width="6" d="M5 60 1215 0"/>
    </g>
  </svg>
```

### stroke-linecap

stroke-linecap 属性定义不同类型的开放路径的终结  

```
  <svg xmlns="http://www.w3.org/2000/svg" version="1.1">
    <g fill="none" stroke="black" stroke-width="6">
      <path stroke-linecap="butt" d="M5 20 1215 0"/>
      <path stroke-linecap="round" d="M5 40 1215 0"/>
      <path stroke-linecap="square" d="M5 60 1215 0"/>
    </g>
  </svg>
```

### stroke-dasharray

stroke-dasharray属性用于创建虚线  

```
  <svg xmlns="http://www.w3.org/2000/svg" version="1.1">
    <g fill="none" stroke="black" stroke-width="4">
      <path stroke-dasharray="5,5" d="M5 20 1215 0"/>
      <path stroke-dasharray="10,10" d="M5 40 1215 0"/>
      <path stroke-dasharray="20,10,5,5,5,10" d="M5 60 1215 0"/>
    </g>
  </svg>
```

