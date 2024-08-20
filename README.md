# MKSF-Shader
来源 基于[Open4es](https://github.com/Open4Es/Open4Es-Shader-Android)
由于pojavlauncher的最新测版移除了vgpu，virgl，并且一些设备不支持zink，angle暂时不支持光影，因此制作了这款着色器

特点 Open4ES最新的Beta7版本添加了一些效果，此光影特点已无，待后续更新

要求 渲染器：gl4es1.1.4，暂不支持iris，和Open4es一样，除骁龙和部分较早联发科机型外会出现渲染Bug

已知问题 1.17后的OptiFine上不会正常工作(树叶抽搐及矮草不晃已修复但暂未发布)

未来的更新 景深，动态模糊，云，矿物发光，水下阴影

其它 [Open4ES Renewed](https://modrinth.com/shader/open4es-renewed)这款光影效果更好但优化较差