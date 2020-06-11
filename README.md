# A Deep Learning Approach for Automatic Detection of Fake News
Research Paper Published at ICON 2019, indexed in ACL Anthology by **Tanik Saikh**, **Arkadipta De**, **Asif Ekbal**, **Pushpak Bhattacharyya**

# Introduction
Fake news detection is a very prominent and
essential task in the field of journalism. This
challenging problem is seen so far in the field
of politics, but it could be even more challenging when it is to be determined in the
multi-domain platform. In this paper, we
propose two effective models based on deep
learning for solving fake news detection problem in online news contents of multiple domains. We evaluate our techniques on the
two recently released datasets, namely FakeNews AMT and Celebrity for fake news detection. The proposed systems yield encouraging
performance, outperforming the current handcrafted feature engineering based state-of-theart system with a significant margin of 3.08%
and 9.3% by the two models, respectively. In
order to exploit the datasets, available for the
related tasks, we perform cross-domain analysis (i.e. model trained on FakeNews AMT and
tested on Celebrity and vice versa) to explore
the applicability of our systems across the domains.

# Result
|Dataset|System Model|Test Accuracy(%)|
|---|---|---|
|FakeNews AMT|Proposed Model1|77.08|
|FakeNews AMT|Proposed Model2|83.33|
|FakeNews AMT|(Perez-Rosas et al. 2018) Linear SVM|74|
|Celebrity|Proposed Model1|76.53|
|Celebrity|Proposed Model2|79|
|Celebrity|(Perez-Rosas et al. 2018) Linear SVM|76|

# Citation
For Research Puropose cite the following:
```
@article{Saikh2020ADL,
  title={A Deep Learning Approach for Automatic Detection of Fake News},
  author={Tanik Saikh and Arkadipta De and Asif Ekbal and Pushpak Bhattacharyya},
  journal={ArXiv},
  year={2020},
  volume={abs/2005.04938}
}
```
