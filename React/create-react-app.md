1.create-react-app  
2.npm start  
3.报错如下  
![Image text](http://www.unuseshare.cn/static/createReactApp/img01.png)
4.解决：新增 .env 文件，SKIP_PREFLIGHT_CHECK=true  

5.在创建 React 项目之后，使用 npm run eject 命令报错：This git repository has untracked files or uncommitted changes  

6.解决方法：git init     git add .   git commit -m '初始化项目'  

7.create-react-app 下使用装饰器  
![Image text](http://www.unuseshare.cn/static/createReactApp/img02.png)
{
    "presets": ["react-native-stage-0/decorator-support"]
}

8.报错  
Error: Multiple configuration files found. Please remove one:
 - package.json#babel
 - .babelrc

解决：删除 .babelrc   npm install @babel/  plugin-proposal-decorators     package.json里面加
![Image text](http://www.unuseshare.cn/static/createReactApp/img03.png)
