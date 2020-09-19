# FFmpegSecurity
Multimedia  Communication

# CVE 漏洞复现

## 1. [CVE-2019-12730](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-12730)

### 描述
FFmpeg是FFmpeg团队的一套可录制、转换以及流化音视频的完整解决方案。  
FFmpeg 3.2.14之前版本和4.1.4之前的4.x版本中的libavformat/aadec.c文件的‘aa_read_header’函数存在安全漏洞。攻击者可利用该漏洞绕过安全检查。
