## pnpm使用

> ##### 官网： `https://pnpm.js.org/installation/`

### 全局安装

```
npm install pnpm -g
```

### 设置源

```arduino
//查看源
pnpm config get registry 
//切换淘宝源
pnpm config set registry http://registry.npm.taobao.org 
```

### 使用

```csharp
pnpm install 包  // 
pnpm i 包
pnpm add 包    // -S  默认写入dependencies
pnpm add -D    // -D devDependencies
pnpm add -g    // 全局安装
```

### 移除

```csharp
pnpm remove 包                            //移除包
pnpm remove 包 --global                   //移除全局包
```

### 更新

```csharp
pnpm up                //更新所有依赖项
pnpm upgrade 包        //更新包
pnpm upgrade 包 --global   //更新全局包
```

### 设置存储路径

```arduino
pnpm config set store-dir /path/to/.pnpm-store
```

作者：Mr焦
链接：https://juejin.cn/post/7037480024106074148
来源：稀土掘金
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。