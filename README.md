#membuat model
model1 = glm(Gender~., DataLogistik, family=binomial(link="logit")) ;model1
#UJI SIGNIFIKANSI SELURUH MODEL
library(pscl)
pR2(model1)
qchisq(0.95,6)
summary(model1)
summary(model2)
summary(model3)
summary(model4)
summary(model5)
summary(model6)
model6 = glm(Gender~`Hand in inches`+`Shoe (US)`, DataLogistik, family=
               binomial(link="logit")) ;model6#membuat model
model1 = glm(Gender~., DataLogistik, family=binomial(link="logit")) ;model1
#UJI SIGNIFIKANSI SELURUH MODEL
library(pscl)
pR2(model1)
qchisq(0.95,6)
summary(model1)
summary(model2)
summary(model3)
summary(model4)
summary(model5)
summary(model6)
model6 = glm(Gender~`Hand in inches`+`Shoe (US)`, DataLogistik, family=
               binomial(link="logit")) ;model6
