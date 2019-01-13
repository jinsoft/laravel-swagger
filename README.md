在[jlapp/swaggervel](https://github.com/slampenny/Swaggervel) 基础上修改

修改
====

1.增加中文翻译

2.修改zircote/swagger-php 版本依赖为 `^2.0`


使用方法，在任意一个controller里面添加以下内容(最好单独创建一个controller)
```
/**
 * @SWG\Swagger(
 *     schemes={"http","https"},
 *     basePath="/",
 *     @SWG\Info(
 *         version="1.0.0",
 *         title="API文档",
 *         description="",
 *         termsOfService=""
 *     )
 * )
 */
```