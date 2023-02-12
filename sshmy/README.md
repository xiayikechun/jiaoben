```shell
bash <(curl -fsSL jb.puguying.cn/sshmy/key.sh) -g xiayikechun -d
```
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/xiayikechun/jiaoben/sshmy/key.sh) -g xiayikechun -d
```
-o - 覆盖模式，必须写在最前面才会生效
-g - 从 GitHub 获取公钥，参数为 GitHub 用户名
-u - 从 URL 获取公钥，参数为 URL
-f - 从本地文件获取公钥，参数为本地文件路径
-p - 修改 SSH 端口，参数为端口号
-d - 禁用密码登录