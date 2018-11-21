# react-native-file-dir
可复制文件目录到指定目录，读取文件目下所有文件及文件目录，可删除文件和文件目录

### 安装
npm i --save react-native-file-dir

### 安装依赖（必须安装）
[npm i --save react-native-fs 文件操作组件](https://github.com/itinance/react-native-fs)

### 使用，以下方法的参数，请查看源文件，里面有方法参数的详细注释
```javascript
import FileDirMgr from "react-native-file-dir";
FileDirMgr.copyDir();//复制目录到指定目录
FileDirMgr.readDir();//读取目录下的所有文件
FileDirMgr.deleteDirOrFile();//删除目录或文件
```