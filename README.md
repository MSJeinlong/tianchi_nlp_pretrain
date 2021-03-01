# tianchi_nlp_pretrain
阿里天池竞赛-全球人工智能技术创新大赛 热身赛二: 中文预训练模型泛化能力挑战
这个是使用BERT模型的改进版ROBERT做的fine tune模型，基于pytorch框架，直接对标天池赛的热身赛2
本模型需要用到较大的GPU算力，CPU也可跑，可会比GPU慢很多。建议把本模型放在Google Colab（翻墙后登录Colab，可免费使用平台提供的GPU资源）上跑
因为整个模型包括robert.tar.gz（300多MB），无法直接上传到github，于是我把模型的压缩包放在百度网盘里再上传

## step1：点击以下百度网盘链接下载模型代码的压缩包
链接：https://pan.baidu.com/s/1EFSl5Zble9j3dRQtuVcfWg 
提取码：vu78 

## step2：解压压缩包，得到相关文件

## step3： 安装相关依赖库
确保电脑安装好pytorch环境
打开命令行，执行下面命令安装相关依赖库
### pip install zipFile36
### pip install pytorch_pretrained_bert
### pip install transformers

## step4：开始模型训练
### python main.py
