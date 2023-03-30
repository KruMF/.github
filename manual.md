# KruMF - Manual

## JitPack use

### Using Maven

Illustrating the use of [KruMF/ConsoleUtils](https://github.com/KruMF/ConsoleUtils) in [KruMF/DelayCalculator](https://github.com/KruMF/DelayCalculator) (see full pom [here](https://github.com/KruMF/DelayCalculator/blob/master/pom.xml)).
Replace values as needed.

1. Add the JitPack repository to your build file (pom.xml):
```markup
<repositories>
	<repository>
		<id>jitpack.io</id>
		<url>https://jitpack.io</url>
	</repository>
</repositories>
```

2. Add the desired dependency:
```markup
<dependencies>
	<dependency>
		<groupId>com.github.KruMF</groupId>
		<artifactId>ConsoleUtils</artifactId>
		<version>0.3</version>
	</dependency>
</dependencies>
```


### Using Gradle or other

It probably also works with Gradle, but I haven't tested it, nor specifically looked into it, as I mainly use Maven.

They have some instructions on their own website [here](https://jitpack.io/#gradle). Also includes instructions for [sbt](https://jitpack.io/#sbt) and [leiningen](https://jitpack.io/#lein).


## Testing

*More info coming soon...*

Here's a test image:

![image](images/image.png)
