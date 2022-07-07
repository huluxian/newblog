 博客论坛

对git有一定的学习


# 7.7 restful风格的增加

- 在tagControllrt,tagService中增加了测试
理解了restful风格在springboot目录中的应用
即一个相同的接口，对应不同的get,put,post,delete就可以使用不同的方法

- 增加了前后的可分离性

# postman端口的使用

- 前后端分离的体现，利用springboot提供的@RestController 注解，可以直接返回json数据格式
在postman里面直接测得接口返回的类型（已转换为json格式）

- 这是为了接口的测试，弥补@test的不足