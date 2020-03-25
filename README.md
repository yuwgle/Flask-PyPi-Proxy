# flask_pypi_proxy 修复版本

这个是https://github.com/tzulberti/Flask-PyPi-Proxy.git的修复版本

- 校验算法从md5更改为sha256以适应当前的需要
- 适配python3
- 更改了web请求的User-Agent header用来规避镜像站点的检测