> Добавил абстрактный класс RepositoryImpl.java, который имплементирует методы интерфейса Repository.java
> Теперь RepositiryFile.java, NewRepositoryFile.java наследуют абстрактный класс RepositoryImpl.java. Это помогло убрать дублирование кода в классах RepositiryFile.java, NewRepositoryFile.java.

> Наследовал NewUserMapper.java от UserMapper.java. Это помогло избежать будлирование кода. 
> также переопределил метод map в классе NewUserMapper.java
