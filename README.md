# Dacon-korean-NLI

 데이콘 한국어 문장 분류 경진대회에서 PRIVATE Score 0.88415로 23위 (상위 4.9%)를 달성하였습니다.
#### https://dacon.io/competitions/official/235875/overview/description

* Task : NLI (Natural Language Inference)  
* Model : klue/roberta-large 30개 앙상블 (hard voting)
* Data : klue - nli dataset ( https://klue-benchmark.com/tasks/68/data/download )
* GPU : A6000 x 2 (96GB), A5000 x 2 (48GB)


+ code
  + data
    + data_aug.tsv
    + train_data.tsv
    + test_data.tsv
  + train.py
  + classify.py
  + utils.py
  + bert_dataset.py
     
 
 
학습 방법

 ```
 $ python train.py 
 ```
 
 
