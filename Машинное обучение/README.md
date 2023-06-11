# Проект для «Викишоп»
# Описание проектов
Обучите модель классифицировать комментарии на позитивные и негативные.
# Библиотеки и инструменты
* numpy
* pandas as pd
* matplotlib
* re
* nltk
* io
* torch
* time 
* warnings

* sklearn.model_selection.train_test_split
* sklearn.model_selection.GridSearchCV
* sklearn.ensemble.RandomForestClassifier
* sklearn.model_selection.cross_val_score
* sklearn.metrics.f1_score,make_scorer,accuracy_score,roc_auc_score,roc_curve
* sklearn.utils.class_weight.compute_class_weight

* sklearn.linear_model.LogisticRegression
* sklearn.tree.DecisionTreeClassifier 
* sklearn.ensemble.RandomForestClassifier

* sklearn.svm import SVC, LinearSVC
* catboost import Pool, CatBoostClassifier
* tqdm.notebook,tqdm, trange

* nltk.corpus.stopwords
* nltk.corpus.wordnet
* nltk.stem.WordNetLemmatizer

* sklearn.feature_extraction.text.TfidfVectorizer,CountVectorizer
* sklearn.dummy.DummyClassifier

* sklearn.base.BaseEstimator, TransformerMixin
* gensim.models.Word2Vec
* pytorch_transformers.BertTokenizer, BertConfig,AdamW, BertForSequenceClassification
* IPython.display.clear_output

* torch.utils.data.TensorDataset, DataLoader, RandomSampler, SequentialSampler
* keras.preprocessing.sequenc.pad_sequences
# Вывод
Лучший результат показала модель Логистическая регрессия.

По качеству лучшая модель достигла необходимый по условию проекта уровень метрики f1 не ниже 0,75 на валидационной и на тестовой выборках.

f1 лучшей модели на валидационной выборкес 0.77

f1 лучшей модели на тестовой выборке 0.765
