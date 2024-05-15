
### BrowserRouter vs HashRouter
- Implementation
	- BR uses H5 history API (this.props.history) -> not integrated with version below IE9
	- HashRouter uses URL hasing
- URL is different
	- BR doesn't have # in the pathname -> localhost:3000/demo/test
	- HR has #: localhost:3000/#/demo/test
- refreshes -> impact on the state
	- BR doesn't have any impact as state is stored in history 
	- HR refresh causes the state lost


## Redux

- 什么是redux？
	- 专门做状态管理的js库
	- 可以用于react，angular，vue中
	- 集中管理react多个组件的共享
- 什么情况下用redux
	- 某个组建的动态需要其他组件随时拿到
	- 一个组件需要另一个组件的状态（通信）

