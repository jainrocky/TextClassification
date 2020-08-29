# TextClassification

## Dataset Used
[20newsgroup](http://qwone.com/~jason/20Newsgroups/)

## Methodology

<p>
  Text classification using sklearn `MultinomialNB` classifier and `MultinomialNaiveBayes` classifier written from scratch.
</p>

### NaiveBayes Probability Formula
![wo_correction](L_corr.png)


### After Laplace correction
![w_correction](L_corr1.png)

## Results

Classifier |Features|Train Accuracy (%) | Test Accuracy(%)
---|:---:|:---:|:---:
MultinomialNB|1791|85.44|81.84
**MultinomialNaiveBayes**|1791|87.94|85.46

