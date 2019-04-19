## hibernate validator

### 注解使用方式
#### 可供使用的注解
* javax.validation.constraints 包下面的内置注解
* org.hibernate.validator.constraints 包下面 hibernate 新增的注解
#### 使用步骤
* 引入 hibernate 相关依赖
```
Group ID: org.hibernate Artifact ID: hibernate-validator Version: 5.2.5.Final
```
* 接口参数打上 @Valid 即可
