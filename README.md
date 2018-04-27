# 配置说明

1. build.gradle


    repositories {
        flatDir {
            dirs 'libs'
        }
    }

    dependencies {
        implementation (name: 'lib-interface', ext: 'aar')
    }

2. 添加包支持
