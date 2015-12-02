##  05 - Preprocessor Support

<small>webpack.config.js</small>
```javascript
// Other file contents omitted

{
    test: /\.scss/,
    exclude: /node_modules/,
    loader: 'style-loader!css-loader?modules&importLoaders=1
            &localIdentName=[name]__[local]___[hash:base64:5]
            !sass-loader?outputStyle=expanded'
}
```