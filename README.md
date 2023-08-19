# TextCNN_classification

This is a TextCNN classification model based on Pytorch.

## Dependencies

Install with

```bash
pip install torch numpy tqdm zhon sklearn jieba matplotlib
```

## Dataset

The model is trained on [THUCNews dataset](http://thuctc.thunlp.org/).

THUCNews is generated based on the historical data filtered from the Sina News RSS subscription channel between 2005 and 2011. It contains 740,000 news articles (2.19 GB), all in UTF-8 plain text format. Based on the original classification system of Sina News, we have reorganized and divided it into 14 candidate categories: 财经 (Finance), 彩票 (Lottery), 房产 (Real Estate), 股票 (Stocks), 家居 (Home & Living), 教育 (Education), 科技 (Technology), 社会 (Society), 时尚 (Fashion), 时政 (Politics), 体育 (Sports), 星座 (Horoscope), 游戏 (Games), and 娱乐 (Entertainment).

## Acknowledgments

The project uses the Tencent word embedding. [Directional Skip-Gram: Explicitly Distinguishing Left and Right Context for Word Embeddings](https://aclanthology.org/N18-2028) (Song et al., NAACL 2018)

This project was inspired by the [Chinese-Text-Classification-Pytorch](https://github.com/649453932/Chinese-Text-Classification-Pytorch.git) by [huwenxing]((https://github.com/649453932)).
