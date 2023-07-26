# TestLibAndroid


```xml
install: 
  - FILE="-Dfile=gesturedeck.aar" 
  - mvn install:install-file $FILE -Dpackaging=aar -DpomFile=pom.xml
```


```xml
install: 
  - FILE="-Dfile=gesturedeck.aar" 
  - mvn install:install-file $FILE -DgroupId=com.github.Navideck -DartifactId=AndroidTestLibrary -Dversion=1.27 -Dpackaging=aar -DgeneratePom=true
```

  
