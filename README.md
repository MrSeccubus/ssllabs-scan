你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
ssllabs-scan
============

This tool is a command-line client for the SSL Labs APIs, designed for
automated and/or bulk testing. Both the tool and the APIs are still in development,
and should be considered alpha quality.

If you'd like to contribute, please have a look at the TODO file. For larger work,
please get in touch first. For smaller work (there are some TODO comments in the
source code), feel free to submit pull requests.

To report a problem, please create a new issue on GitHub: https://github.com/ssllabs/ssllabs-scan/issues
Please don't send bug reports to the mailing list.

To discuss the API and the development of the reference client implementation, please
join the ssllabs-devel mailing list: https://sourceforge.net/p/ssllabs/mailman/ssllabs-devel/

Before you use this tool please review the terms and conditions, which are included
with the API documentation.


##Requirements

* Go >= 1.3

##Usage 

SYNOPSIS
```
    ssllabs-scan [options] hostname
    ssllabs-scan [options] --hostfile file
```

OPTIONS

| Option      | Default value | Description |
| ----------- | ------------- | ----------- |
| --api       | BUILTIN       | API entry point, for example https://www.example.com/api/ |
| --verbosity | info          | Configure log verbosity: error, info, debug, or trace. |
| --quiet     | false         | Disable status messages (logging) |
| --json-flat | false         | Output results in flattened JSON format |
| --hostfile  | none          | File containing hosts to scan (one per line) |
| --usecache  | false         | If true, accept cached results (if available), else force live scan. |
| --grade     | false         | Output only the hostname: grade |
| --hostcheck | false         | If true, host resolution failure will result in a fatal error. |
