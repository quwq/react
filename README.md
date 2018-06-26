react 学习笔记 react.js 0.13.2

1. hello,world - 创建第一个页面

2. jsx - 学习文件夹
    一种定义代属性树的结够的语法
    特点
        类xml语法容易接受
        增强js语义
        结构清晰
        抽象程度高
        代码模块化

3. react-init
    组件生命周期， 初始化。 有5个方法， getDefaultProps,getInitialState,componentWillMount
    ,render,componentIdMount

4.react-truning
    组件运行中，有5个方法 componentWillReceiveProps,shouldComponentUpdate,componentWillUpdate,render,
    componentDidUpdate,
    
5 react-destroy
    组件销毁
    有一个方法 componentWillUnmount
    
6 react-state
   状态， 是有事物自行处理、不断变化的 
   用法： getInitialState 初始化每个实例特有的状态
          setState: 更新组件状态
   
   setState -》 diff算法 - 有变化-》 更新DOM
   
   状态 只在自己的组件中有关， 属性 不能在组件内部修改
   
          

``