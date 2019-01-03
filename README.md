1. 增加对CSS文件的支持，提取出Chunk中的CSS代码到单独的文件中，压缩CSS文件；
2. 定义NODE_ENV环境变量为production，以去除源码中只有开发时才需要的部分；
3. 给输出的文件添加Hash值；
4. 压缩输出的JavaScript代码。