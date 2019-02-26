# hulk

#### 项目介绍
hulk-bom



#### 使用说明

1. maven项目使用

        <parent>
            <groupId>com.hulk</groupId>
            <artifactId>hulk-bom</artifactId>
            <version>${latest.version}</version>
        </parent>

2. gradle项目使用

        dependencyManagement {
            imports {
                mavenBom 'com.hulk:hulk-bom:${latest.version}'
            }
        }

