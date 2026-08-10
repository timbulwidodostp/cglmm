# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit cosinor model with Generalized Linear Mixed Models Template Model Builder (glmmTMB) Use cglmm With (In) R Software
install.packages("GLMMcosinor")

library("GLMMcosinor")
# Estimation Fit cosinor model with Generalized Linear Mixed Models Template Model Builder (glmmTMB) Use cglmm With (In) R Software
cglmm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/cglmm/main/cglmm/cglmm.csv",sep = ";")
cglmm <-  cglmm(vit_d ~ amp_acro(time_col = time, group = "X", period = 12), data = cglmm)
summary(cglmm)
# Fit cosinor model with Generalized Linear Mixed Models Template Model Builder (glmmTMB) Use cglmm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished