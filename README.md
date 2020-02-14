# MyBatis 插件开发
```
    MyBatis在四大对象的创建过程中，都会有插件进行介入。插件可以利用动态代理机制一层层的包装目标对象，而实现在目标对象执行目标方法之前进行拦截的效果。
    MyBatis允许在已映射语句执行过程中的某一点进行拦截调用。默认情况下，MyBatis允许使用插件来拦截的方法调用包括：
        Executor（update，query，flushStatements，commit，rollback，getTransaction，close，isClosed）
        ParameterHandler（getParameterObject，setParameters）
        ResultHandler（handleResultSets，HandleOutputParameters）
        StatementHandler（prepare，parameterize，bathc，update，query）
```
