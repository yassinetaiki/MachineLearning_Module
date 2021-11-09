# MachineLearning_Module
dans cette section j'ai realise un ensemble d'application de machine learning a l'aide de differents packages .

Numpy

Scipy 

Pnadas-Time series

matplotlib

Seaborn 

Sklearn:

Preprocessing(encodage(LabelEncoder,OrdinalEncoder,LabelBinarizier,MultilabelBinarizier,OneHotEncoder) , standarisation(StandardScaler) , Normalisation(MinMaxScaler)  , RobusteScaler , polynomialFeatures), (dataset=Titanic)


model_selection(partionnement de données(train_test_split) , CrossValidation , ValidationCurve, Grid searchCV, learningCurve,) avec une classification basée sur l'analyse discriminante lineaire et KNeighborsClassifier (dataset=iris)
 
metrics (MSE,MAE,RMSE,R^2) avec une application de regression basée sur la regression lineaire afin de predire le prix d'un bien imobilier dans la region de lille (dataset =Ventes

aprentissage non supervise(Clusturing(KMeans , AffinityPropagation,DBSCAN)(Dataset=iris)

Detection d'anomalie(IsolationForest, dataset=iris) (EllipticEnvelope,LocalOutlierFactor,dataset=digits)

ensemble methode(Voting (VotingClassifier), Bagging(BaggingClassifier),RandomForestClassifier) , Boosting(AdaBoostClassifier,GradientBoostingClassifier),Stacking(Stacking Classifier)) (Dataset=Iris)

Pipeline(avec et sans CrossValidation, PipelineComposée, PipelineSelector) avec une application de classification des données iris et Titanic

Imputer_FeatureSelection((SimpleImputer),(VarianeTheshold,SelectKbest,SelectFromModel)) avec une application de regression pour prediction sur données de ventes immobilier

