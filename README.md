# 配置说明

1. Modify the build.gradle file
<pre>
    repositories {
        flatDir {
            dirs 'libs'
        }
    }

    dependencies {
        implementation (name: 'lib-interface', ext: 'aar')
    }
</pre>

2. copy file to "app\libs"
