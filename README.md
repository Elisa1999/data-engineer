# data-engineer


### Install Apache Cassendra on Macbook Pro M1 Pro and connect Apache Cassendra with Jupyter Notebook
1. using homebrew to install following: 

```pip install cql```

```brew install cassandra```

```brew info cassandra``` #check if there are any other packages you need to install 

2. install java8 and switch java version

```brew tap adoptopenjdk/openjdk```

```brew install --cask adoptopenjdk8``` #install java8 

```usr/libexec/java_home -V ```#check the java version you have in you mbp

```export JAVA_HOME='/usr/libexec/java_home -v 1.8'``` #switch the java version

```java -version``` #check java version

3.run cassendra and cqlsh on your terminal to check if it works

```cassendra```

```cqlsh``` 

4. in juypter notebook (either one)

```pip install --pre cassandra-driver``` #only this one works on my notebook

```pip install cassandra-driver```

5. import packages

```import cassandra```


reference: 
https://gist.github.com/hkhamm/a9a2b45dd749e5d3b3ae
https://stackoverflow.com/questions/27004773/cassandra-cqlsh-unable-to-connect-to-any-servers-127-0-0-19160-closed-is-a
https://stackoverflow.com/questions/24342886/how-to-install-java-8-on-mac
