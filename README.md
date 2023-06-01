to reproduce:

-   `pnpm i`
-   `pnpm dev`
-   open browser

stack trace is wrong on node

```
error Error: ho
    at error (webpack-internal:///./pages/index.tsx:10:11)
    at Home (webpack-internal:///./pages/index.tsx:6:5)
    at renderWithHooks (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5658:16)
    at renderIndeterminateComponent (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5731:15)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5946:7)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderIndeterminateComponent (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5785:7)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5946:7)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderNode (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6259:12)
    at renderChildrenArray (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6211:7)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6141:7)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5971:9)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderNode (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6259:12)
    at renderChildrenArray (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6211:7)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6141:7)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5971:9)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderContextProvider (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5920:3)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6017:11)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderContextProvider (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5920:3)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6017:11)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderIndeterminateComponent (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5785:7)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5946:7)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderContextProvider (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5920:3)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6017:11)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderContextProvider (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5920:3)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6017:11)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderContextProvider (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5920:3)
    at renderElement (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6017:11)
    at renderNodeDestructiveImpl (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6104:11)
    at renderNodeDestructive (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:6076:14)
    at renderContextProvider (/Users/morse/Documents/GitHub/does-next-use-sourcemaps/node_modules/.pnpm/react-dom@18.2.0_react@18.2.0/node_modules/react-dom/cjs/react-dom-server.browser.development.js:5920:3) {
  digest: undefined
}
```
