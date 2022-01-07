# WeirdConsole
This allows you to do some weird and useless in the browser's devtools

# Installation
#### Simply load it from a CDN:
```html5
<script src="https://unpkg.com/weirdconsole"></script>
```

#### use npm:
```
npm i weirdconsole
```

# Usage

```javascript
import 'weirdconsole'
```

### consoele.npm

```javascript
consoel.npm('module_name',{
  type?: 'module'
})
```


#### Import specific version:
```javascript
consoel.npm('loadsh@0.0.4')
```
#### use URL:
```javascript
consoel.npm('https://unpkg.com/loadsh@0.0.4/lodash.js')
```
#### 🌰 example：
```javascript
(async function () {
  await console.npm("loadsh")
  console.log(_.random(5)) //2
})()
```

### console.edit
```javascript
console.edit()
```

```javascript
console.edit('#app')
```

### console.color()

```javascript
console.color([
  {
    color: string,
    content: string
  }
])
```

#### 🌰 example：
```javascript
console.color([
  {
    color: 'red',
    content: 'red'
  },
  {
    color: 'rgb(0, 255, 0)',
    content: 'green'
  },
  {
    color: '#000FFF',
    content: 'blue'
  }
])
```

### console.img

```javascript
console.img(url, {
  width?: number,
  height?: number
})
```
### console.loading
```javascript
console.loading('loading...')
```

### console.video
```javascript
console.video(url, {
  width?: number,
  height?: number,
  loop?: boolean
})
```

