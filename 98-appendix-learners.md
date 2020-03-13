## Integrated Learners {#list-learners}


\begin{tabular}{l|l|l|l|l}
\hline
Id & Packages & Feature Types & Properties & Predict Types\\
\hline
[`classif.debug`](https://mlr3.mlr-org.com/reference/mlr\_learners\_classif.debug.html) &  & lgl, int, dbl, chr, fct, ord & missings, multiclass, twoclass & response, prob\\
\hline
[`classif.featureless`](https://mlr3.mlr-org.com/reference/mlr\_learners\_classif.featureless.html) &  & lgl, int, dbl, chr, fct, ord & importance, missings, multiclass, selected\_features, twoclass & response, prob\\
\hline
[`classif.glmnet`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.glmnet.html) & [glmnet](https://cran.r-project.org/package=glmnet) & lgl, int, dbl & multiclass, twoclass, weights & response, prob\\
\hline
[`classif.kknn`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.kknn.html) & [kknn](https://cran.r-project.org/package=kknn) & lgl, int, dbl, fct, ord & multiclass, twoclass & response, prob\\
\hline
[`classif.lda`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.lda.html) & [MASS](https://cran.r-project.org/package=MASS) & lgl, int, dbl, fct, ord & multiclass, twoclass, weights & response, prob\\
\hline
[`classif.log\_reg`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.log\_reg.html) & [stats](https://cran.r-project.org/package=stats) & lgl, int, dbl, chr, fct, ord & twoclass, weights & response, prob\\
\hline
[`classif.naive\_bayes`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.naive\_bayes.html) & [e1071](https://cran.r-project.org/package=e1071) & lgl, int, dbl, fct & multiclass, twoclass & response, prob\\
\hline
[`classif.qda`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.qda.html) & [MASS](https://cran.r-project.org/package=MASS) & lgl, int, dbl, fct, ord & multiclass, twoclass, weights & response, prob\\
\hline
[`classif.ranger`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.ranger.html) & [ranger](https://cran.r-project.org/package=ranger) & lgl, int, dbl, chr, fct, ord & importance, multiclass, oob\_error, twoclass, weights & response, prob\\
\hline
[`classif.rpart`](https://mlr3.mlr-org.com/reference/mlr\_learners\_classif.rpart.html) & [rpart](https://cran.r-project.org/package=rpart) & lgl, int, dbl, fct, ord & importance, missings, multiclass, selected\_features, twoclass, weights & response, prob\\
\hline
[`classif.svm`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.svm.html) & [e1071](https://cran.r-project.org/package=e1071) & lgl, int, dbl & multiclass, twoclass & response, prob\\
\hline
[`classif.xgboost`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_classif.xgboost.html) & [xgboost](https://cran.r-project.org/package=xgboost) & lgl, int, dbl & importance, missings, multiclass, twoclass, weights & response, prob\\
\hline
[`regr.featureless`](https://mlr3.mlr-org.com/reference/mlr\_learners\_regr.featureless.html) & [stats](https://cran.r-project.org/package=stats) & lgl, int, dbl, chr, fct, ord & importance, missings, selected\_features & response, se\\
\hline
[`regr.glmnet`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_regr.glmnet.html) & [glmnet](https://cran.r-project.org/package=glmnet) & lgl, int, dbl & weights & response\\
\hline
[`regr.kknn`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_regr.kknn.html) & [kknn](https://cran.r-project.org/package=kknn) & lgl, int, dbl, fct, ord &  & response\\
\hline
[`regr.km`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_regr.km.html) & [DiceKriging](https://cran.r-project.org/package=DiceKriging) & lgl, int, dbl &  & response, se\\
\hline
[`regr.lm`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_regr.lm.html) & [stats](https://cran.r-project.org/package=stats) & lgl, int, dbl, fct & weights & response, se\\
\hline
[`regr.ranger`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_regr.ranger.html) & [ranger](https://cran.r-project.org/package=ranger) & lgl, int, dbl, chr, fct, ord & importance, oob\_error, weights & response, se\\
\hline
[`regr.rpart`](https://mlr3.mlr-org.com/reference/mlr\_learners\_regr.rpart.html) & [rpart](https://cran.r-project.org/package=rpart) & lgl, int, dbl, fct, ord & importance, missings, selected\_features, weights & response\\
\hline
[`regr.svm`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_regr.svm.html) & [e1071](https://cran.r-project.org/package=e1071) & lgl, int, dbl &  & response\\
\hline
[`regr.xgboost`](https://mlr3learners.mlr-org.com/reference/mlr\_learners\_regr.xgboost.html) & [xgboost](https://cran.r-project.org/package=xgboost) & lgl, int, dbl & importance, missings, weights & response\\
\hline
[`surv.blackboost`](https://mlr3proba.mlr-org.com/reference/LearnerSurvBlackboost.html) & [distr6](https://cran.r-project.org/package=distr6), [mboost](https://cran.r-project.org/package=mboost), [mvtnorm](https://cran.r-project.org/package=mvtnorm), [partykit](https://cran.r-project.org/package=partykit), [survival](https://cran.r-project.org/package=survival) & int, dbl, fct &  & distr, crank, lp\\
\hline
[`surv.coxph`](https://mlr3proba.mlr-org.com/reference/LearnerSurvCoxPH.html) & [distr6](https://cran.r-project.org/package=distr6), [survival](https://cran.r-project.org/package=survival) & lgl, int, dbl, fct & importance & distr, crank, lp\\
\hline
[`surv.cvglmnet`](https://mlr3proba.mlr-org.com/reference/LearnerSurvCVGlmnet.html) & [glmnet](https://cran.r-project.org/package=glmnet), [survival](https://cran.r-project.org/package=survival) & int, dbl, fct & weights & crank, lp\\
\hline
[`surv.flexible`](https://mlr3proba.mlr-org.com/reference/LearnerSurvFlexible.html) & [distr6](https://cran.r-project.org/package=distr6), [flexsurv](https://cran.r-project.org/package=flexsurv), [set6](https://cran.r-project.org/package=set6), [survival](https://cran.r-project.org/package=survival) & lgl, int, fct, dbl & weights & distr, lp, crank\\
\hline
[`surv.gamboost`](https://mlr3proba.mlr-org.com/reference/LearnerSurvGamboost.html) & [distr6](https://cran.r-project.org/package=distr6), [mboost](https://cran.r-project.org/package=mboost), [survival](https://cran.r-project.org/package=survival) & int, dbl, fct, lgl &  & distr, crank, lp\\
\hline
[`surv.gbm`](https://mlr3proba.mlr-org.com/reference/LearnerSurvGBM.html) & [gbm](https://cran.r-project.org/package=gbm) & int, dbl, fct, ord & importance, missings, weights & crank, lp\\
\hline
[`surv.glmboost`](https://mlr3proba.mlr-org.com/reference/LearnerSurvGlmboost.html) & [distr6](https://cran.r-project.org/package=distr6), [mboost](https://cran.r-project.org/package=mboost), [survival](https://cran.r-project.org/package=survival) & int, dbl, fct, lgl &  & distr, crank, lp\\
\hline
[`surv.glmnet`](https://mlr3proba.mlr-org.com/reference/LearnerSurvGlmnet.html) & [glmnet](https://cran.r-project.org/package=glmnet), [survival](https://cran.r-project.org/package=survival) & int, dbl, fct & weights & crank, lp\\
\hline
[`surv.kaplan`](https://mlr3proba.mlr-org.com/reference/LearnerSurvKaplan.html) & [distr6](https://cran.r-project.org/package=distr6), [survival](https://cran.r-project.org/package=survival) & lgl, int, dbl, chr, fct, ord & missings & crank, distr\\
\hline
[`surv.mboost`](https://mlr3proba.mlr-org.com/reference/LearnerSurvMboost.html) & [distr6](https://cran.r-project.org/package=distr6), [mboost](https://cran.r-project.org/package=mboost), [survival](https://cran.r-project.org/package=survival) & int, dbl, fct, lgl &  & distr, crank, lp\\
\hline
[`surv.nelson`](https://mlr3proba.mlr-org.com/reference/LearnerSurvNelson.html) & [distr6](https://cran.r-project.org/package=distr6), [survival](https://cran.r-project.org/package=survival) & lgl, int, dbl, chr, fct, ord & missings & crank, distr\\
\hline
[`surv.obliqueRSF`](https://mlr3proba.mlr-org.com/reference/LearnerSurvObliqueRSF.html) & [distr6](https://cran.r-project.org/package=distr6), [obliqueRSF](https://cran.r-project.org/package=obliqueRSF) & int, dbl, fct, ord & missings & crank, distr\\
\hline
[`surv.parametric`](https://mlr3proba.mlr-org.com/reference/LearnerSurvParametric.html) & [distr6](https://cran.r-project.org/package=distr6), [set6](https://cran.r-project.org/package=set6), [survival](https://cran.r-project.org/package=survival) & lgl, int, dbl, fct & weights & distr, lp, crank\\
\hline
[`surv.penalized`](https://mlr3proba.mlr-org.com/reference/LearnerSurvPenalized.html) & [distr6](https://cran.r-project.org/package=distr6), [penalized](https://cran.r-project.org/package=penalized) & int, dbl, fct, ord & importance & distr, crank\\
\hline
[`surv.randomForestSRC`](https://mlr3proba.mlr-org.com/reference/LearnerSurvRandomForestSRC.html) & [distr6](https://cran.r-project.org/package=distr6), [randomForestSRC](https://cran.r-project.org/package=randomForestSRC) & lgl, int, dbl, fct, ord & importance, missings, weights & crank, distr\\
\hline
[`surv.ranger`](https://mlr3proba.mlr-org.com/reference/LearnerSurvRanger.html) & [distr6](https://cran.r-project.org/package=distr6), [ranger](https://cran.r-project.org/package=ranger) & lgl, int, dbl, chr, fct, ord & importance, oob\_error, weights & distr, crank\\
\hline
[`surv.rpart`](https://mlr3proba.mlr-org.com/reference/LearnerSurvRpart.html) & [distr6](https://cran.r-project.org/package=distr6), [rpart](https://cran.r-project.org/package=rpart), [survival](https://cran.r-project.org/package=survival) & lgl, int, dbl, chr, fct, ord & importance, missings, selected\_features, weights & crank, distr\\
\hline
[`surv.svm`](https://mlr3proba.mlr-org.com/reference/LearnerSurvSVM.html) & [survivalsvm](https://cran.r-project.org/package=survivalsvm) & int, dbl &  & crank\\
\hline
\end{tabular}
