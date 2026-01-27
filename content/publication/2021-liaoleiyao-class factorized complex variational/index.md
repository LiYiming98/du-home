---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Class factorized complex variational auto-encoder for HRR radar target recognition

# 作者信息
authors:
  - Leiyao Liao
  - Lan Du
  - Jian Chen



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-05-01T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Signal Processing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'In the field of radar automatic target recognition (RATR), the high-resolution range profile (HRRP) has received intensive attention. Bar a few exceptions, almost all HRRP-based ATR classification systems ignore the phase of the HRRP when the data is input to the classifier, relying instead only on the magnitude of the complex HRRP samples. This approach ignores the phase of the complex HRRPs, which reduces the information in the signal. In this paper, we develop a novel class factorized complex variational auto-encoder (CFCVAE) to utilize the phase of the high range resolution (HRR) radar echo for recognition. The CFCVAE is a complex-valued neural network (CV-NN) consisting of the encoding and decoding modules. In CFCVAE, the encoding module projects the observed data into the latent space, and then the latent features are fed to the decoding module, which further maps the latent features to data. In particular, the decoding module introduces the class labels to partition the whole observations into some parts, each of which is depicted by a specific class-decoder. Compared with the traditional variational auto-encoder (VAE) containing a single decoder, the CFCVAE can give a more accurate description to the whole dataset via multiple class-decoders, thus improving the characterization ability of features. In addition, based on the class labels, the CFCVAE employs the conditional prior on the latent variable to enhance the discrimination of features. Moreover, a complex backpropagation algorithm is derived for CFCVAE training, and a sample is classified to the class corresponding to the class-decoder with the minimum reconstruction error in the test stage. Experimental evaluations on the measured data indicate that the proposed method indeed achieves very promising target recognition performance.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.sciencedirect.com/science/article/pii/S016516842030476X
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-liaoleiyao-class factorized complex variational.pdf'
# 都留空
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


image:
  caption: 
  focal_point: ''
  preview_only: false

projects: []
slides:
---
