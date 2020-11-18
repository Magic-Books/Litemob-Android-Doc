## android开发文档

+ **工具类**

  **App.java**

  ```java
  //初始化工具类，在BaseApplication中调用
  App.init(Application);
  
  
  //获取全局Context
  App.self();
  ```

  **SharedPreferences  取数据**

  ```java
  // 通过strin_def 指定默认值类型
  App.sp().get(String key, String string_def);
  
  // 通过方法名称指定参数类型
  App.sp().getString(String key, String def);
  ```

  **SharedPreferences  存数据**

  ```java
  //值只能传基本数据类型
  // String｜Boolean｜Float｜Integer｜Long
  App.sp().put(String key, Object value);
  ```

  

