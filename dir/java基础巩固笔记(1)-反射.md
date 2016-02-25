aaaaaaa

asdas 


- SqlSessionFactory

通过SqlSessionFactory创建SqlSession，使用单例模式管理sqlSessionFactory（工厂一旦创建，使用一个实例）。将来mybatis和spring整合后，使用单例模式管理sqlSessionFactory。

- SqlSessionFactory（不空，不换）
通过SqlSessionFactory创建SqlSession，使用单例模式管理sqlSessionFactory（工厂一旦创建，使用一个实例）。将来mybatis和spring整合后，使用单例模式管理sqlSessionFactory。

- SqlSessionFactory(不空，换行)
通过SqlSessionFactory创建SqlSession，使用单例模式管理sqlSessionFactory（工厂一旦创建，使用一个实例）。
将来mybatis和spring整合后，使用单例模式管理sqlSessionFactory。

- SqlSessionFactory（空，换）

通过SqlSessionFactory创建SqlSession，使用单例模式管理sqlSessionFactory（工厂一旦创建，使用一个实例）。
将来mybatis和spring整合后，使用单例模式管理sqlSessionFactory。

- SqlSessionFactory（空，不换）

通过SqlSessionFactory创建SqlSession，使用单例模式管理sqlSessionFactory（工厂一旦创建，使用一个实例）。将来mybatis和spring整合后，使用单例模式管理sqlSessionFactory。


- 输出映射：
	- resultType：
		查询到的列名和resultType指定的pojo的属性名一致，才能映射成功。
	- reusltMap：
		可以通过resultMap 完成一些高级映射。
		如果查询到的列名和映射的pojo的属性名不一致时，通过resultMap设置列名和属性名之间的对应关系（映射关系）。可以完成映射。
		高级映射：
			将关联查询的列映射到一个pojo属性中。（一对一）
			将关联查询的列映射到一个List<pojo>中。（一对多）
