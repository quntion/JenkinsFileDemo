pipeline {
 agent any  //环境maven、jdk等

 stages {  			//项目构建
  stage('pull code') { 	//拉取代码 
   steps {    	//具体实施步骤
    echo 'pull code' 	// 拉取代码命令
    echo "哈喽，你好啊，大家。。。"
   }
  }
  stage('build project') {		// 编译打包 
   steps {   		 	//具体实施步骤
    echo 'build project' 	 	// 打包命令
    echo "执行构建中..."
   }
  }
  stage('publish project') { 		// 部署上线 
   steps {    		//具体实施步骤
    echo 'publish project' 	// 部署命令
    echo "发布成功"
   }
  }
 }
}
