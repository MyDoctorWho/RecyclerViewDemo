# RecyclerViewDemo
recyclerview的使用详细

recyclerview item 的decoration问题，自定义decoration样式，以及宽高；
多行多列等情况，需要自定义manager计算宽高；
item最外层viewgroup的宽高与recyclerview方向相同的一方设置为wrap_content;
嵌套使用时，被嵌套的recyclerview添加decoration的时候需要先调用removeItemDecoration()方法，然后再调用addItemDecoration才不会出错。