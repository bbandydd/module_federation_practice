# Module Federation Practice

- 使用Webpack5 Module Federation動態載入另一個JS應用的Component範例
  - Main: remote使用App1的Button Component，顯示於應用中
  - App1: 提供Button Component供Main使用

`npm run install` 安裝Main及App1 node_modules

`npm run start` 執行Main及App1