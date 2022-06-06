# AppHelpers
A couple of ui helper modules for my apps

# First you need to add jitpack.io to your repositories in the root `build.grade` file:
```
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
Or in the new way, to `settings.gradle` :
```
dependencyResolutionManagement {
	repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```

# Add all modules:
```implementation "com.github.user5234:AppHelpers:1.0.1"```

# Add specific ones:
```implementation "com.github.user5234.AppHelpers:module-name:1.0.1"```
