# diffusion 


 ⭐️ 模版  
**Year:** 2022   
**Summary:**  
局部重绘效果     
**Images**  
![]()  
**Link:** XXX  
**Page:** XXX  
**Code:** XXX   
**Ref:** XXX   
#


 ⭐️ Blended Latent Diffusion  
**Year:** 2022   
**Summary:**  
局部重绘效果问题，使用SD在隐空间上进行mask过滤保留背景和修改前景；同时使用mask随着推理步数增加由大变小越来越精细；还尝试微调VAE的解码器权重来重建背景高频细节；尝试多个生成结果与文本引导的CLIP空间向量计算余弦相似度来排名挑选最好的结果；但仍对文本关键词，mask大小和形状等敏感，背景替换有时候不成功。   
**Images**  
![](./image/blended%20latent%20diffusion/1.png)  
![](./image/blended%20latent%20diffusion/2.png)  
![](./image/blended%20latent%20diffusion/3.png)  
![](./image/blended%20latent%20diffusion/4.png)
  
**Link:** https://arxiv.org/pdf/2206.02779.pdf  
**Page:** https://omriavrahami.com/blended-latent-diffusion-page/  
**Code:** https://github.com/omriav/blended-latent-diffusion  
**Ref:** https://zhuanlan.zhihu.com/p/632643263
#