在数据出现多行的时候，发现重复的记录标签很多
从程序的角度看待，这些标签是从重复的(处于数据和 UI 的渲染的混杂在一起的)，可以从组件的方式考虑替代，正确的做法是数据和逻辑是分离的.
即 通过 props 进行组件替代 代码版本 v0.2.2
状态 state 的改变 参见代码 v0.2.3
有状态组件和无状态组件的区分，区分组件的职能 参见代码 v0.2.4
