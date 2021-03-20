# mini-redux
mini redux deeply fullfilled understand confusion of reudx


参考redux简易版mini-redux
createStore <br>
创建 store 对象，包含 getState, dispatch, subscribe, replaceReducer

reducer <br>
reducer 是一个计划函数，接收旧的 state 和 action，生成新的 state

action <br>
action 是一个对象，必须包含 type 字段

dispatch <br>
dispatch( action ) 触发 action，生成新的 state

subscribe <br>
实现订阅功能，每次触发 dispatch 的时候，会执行订阅函数

combineReducers <br>
多 reducer 合并成一个 reducer

replaceReducer <br>
替换 reducer 函数, reducer 热更新时会用到

middleware <br>
扩展 dispatch 函数！

