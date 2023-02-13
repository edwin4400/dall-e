const withCSS = require('@zeit/next-css')
const withImages = require('next-images')

module.exports = withCSS(withImages({
  webpack: (config) => {
    // Add any custom webpack config here
    return config
  },
  target: 'serverless',
  env: {
    // Add any environment variables here
  }
}))
