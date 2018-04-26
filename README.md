# vue-problem 
class绑定问题
----
owner_process_body 静态网页 （示例页面）

owner_process_body_cope      Vue渲染的页面

希望通过Vue  绑定  Class 从而动态去改变 html的状态，如下：

![enter image description here](https://raw.githubusercontent.com/wfyweb/vue-problem/master/images/demo.png)

通过属性去改变 流程进度

    data: {
        state: 5,
     }
    

 解决

	
先把html 标签静态的样式固定，在通过v-for 循环渲染页面。
确定哪些是动态绑定的class ，在data对象里面写出来。
通过 computed 计算 state 的值，之后返回 页面。
 