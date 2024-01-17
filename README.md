# blog만들기

## 설치과정
`npx create-next-app --example blog-starter blog-starter-app`

```js
/**
 * @type {import('next').NextConfig}
 */
const nextConfig = {
    output: 'export',
    distDir: 'dist',
    images: {
        unoptimized: true,
    }
}

module.exports = nextConfig
```

`npm run build`