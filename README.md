### demonstrate that bundler needs all `require()`'s to resolve

* do `npm run build` (will fail)


### demonstrate that bundler would include everything if all `require()`s resolve

* do `npm install xmldom xpath`
* do `npm run build`
* inspect bundled file in /build/bundle.js and see how huge it is because XMLDom and XPath are included.