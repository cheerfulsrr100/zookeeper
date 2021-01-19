# idea-import
1. `ant eclipse`
2. 复制`conf/log4j.properties`至`zookeeper-server`模块的`resource`下
3. 右键`resources`文件夹, 选择`mark directory as` - `resources root`   
3. 复制`zoo_sample.cfg`为`zoo.cfg`
4. 新建`Application`
    * `main-class`: `org.apache.zookeeper.server.ZooKeeperServerMain`
    * `agrement`: `C:\Users\Greekn\IdeaProjects\zookeeper\conf\zoo.cfg`