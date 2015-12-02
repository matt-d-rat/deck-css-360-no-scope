## 02 - Webpack Config

The key line in the configuration for CSS Modules is this:

<br />

<small>webpack.config.js</small>
```javascript
// Other file contents omitted

{
    test: /\.css$/,
    exclude: /node_modules/,
    loader: 'style-loader!css-loader?modules&importLoaders=1
            &localIdentName=[name]__[local]___[hash:base64:5]'
}
```
