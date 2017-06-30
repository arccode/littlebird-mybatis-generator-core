## littlebird-mybatis-generator-core文档

该项目基于`mybatis-generator-core`进行修改, 定制一些更人性化的功能; 

修改的功能如下: 

1. 数据库中的字段写有注释, 希望注释能自动生成在对应的领域模型中
2. 删除领域模型中setter和getter方法的注释
3. XXMapper.xml空格改为四个
4. XXMapper.java修改为XXDao.java
5. 修改XXDao.java注释
6. 删除直接插入和更新方法, 保留动态插入和动态更新

### 环境依赖

JDK >= 1.6

### 如何引入项目

### Demo

搭建中

### License

[Apache](http://www.apache.org/licenses/LICENSE-2.0)

Copyright (c) 2016 arccode or original author or authors .

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
