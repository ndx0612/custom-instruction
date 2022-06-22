## 自定义指令

从vue2升级到vue3，自定义指令的声明周期函数发生了变化
- bind 函数被替换成了beforeMounted。
- update 被移除。
- componentUpdated 被替换成了updated。
- unbind 被替换成了 unmounted。
- inserted 被移除。