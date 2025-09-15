# xianlai-parent

v1.0.0

xianlai-parent 是「闲来 - XianLai」项目群的父构件，为所有子项目定义统一的依赖、插件等元数据，可在任意子项目中通过 \<parent\> 标签引入以使用此父构件。xianlai-parent 统一定义的重要元数据包括：

- Java 版本：17
- Spring Boot 版本：3.2.4
- 私服 Nexus 构件库 releases 仓库上传地址：须修改\<distribution.releases.url\>标签值
- 私服 Nexus 构件库 snapshots 仓库上传地址：须修改\<distribution.snapshots.url\>标签值
