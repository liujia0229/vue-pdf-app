# 发布备忘

    node版本使用12.22.10
    发布顺序：  
    0. 修改package.json版本号
    1. npm install
    2. npm run build:lib
    3. npm run build:icons
    4. npm login   -- 使用npm账号登录
    5. npm publish --access public

## 备忘
    检查远程地址是否正确
    npm config get registry
    
    修改远程地址
    npm config set registry https://registry.npmjs.org/
    