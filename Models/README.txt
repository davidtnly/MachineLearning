### Models exported from notebooks are stored here

### Various Models

* RF, SVC, XGB, LR

_____________________________________________________________________________________________

```
# Save model
from sklearn.externals import joblib

joblib.dump(svc, '../Models/breast_cancer_svc.pkl')
joblib.dump(lr, '../Models/breast_cancer_lr.pkl')
joblib.dump(xgb, '../Models/breast_cancer_xgb.pkl')
joblib.dump(rf, '../Models/breast_cancer_rf.pkl')

```