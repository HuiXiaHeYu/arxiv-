### arxiv网站关键词论文下载脚本
> arxiv官网：https://arxiv.org/search/

**参数**
- keywords: 关键词【可修改】
- searchtype: 搜索模式`[all/title/author/abstract/comments/journal_ref/acm_class/msc_class/report_num/paper_id/doi/orcid/license/author_id/help/full_text]`[可修改]
- page_size: 爬取速率`[25/50/100/200]`【可修改】
- path_of_csv: 总论文信息csv文件路径【默认不需要修改】
- proxies_port: 使用代理端口，不填则使用临时本地端口【网速慢可挂VPN后修改为对应端口】
- max_workers: 线程池中的线程数【与本地网速有关，默认为3】

**开始使用**
```python
python __init__.py
```

**未来**
- [x]  加入多线程  
- [x]  进度条
- [x]  关键词匹配模式选择
- [ ]  断点重爬
- [ ]  与已下载的文献进行对比输出结果