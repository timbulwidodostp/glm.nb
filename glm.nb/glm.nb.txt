# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a Negative Binomial Generalized Linear Model Use glm.nb With (In) R Software
install.packages("MASS")
library("MASS")
spml_one = read.csv("https://raw.githubusercontent.com/timbulwidodostp/glm.nb/main/glm.nb/glm.nb.csv",sep = ";")
# Estimation Fit a Negative Binomial Generalized Linear Model Use glm.nb With (In) R Software
glm.nb <- glm.nb(Days ~ Sex/(Age + Eth*Lrn), data = glm.nb)
summary(glm.nb)
# Fit a Negative Binomial Generalized Linear Model Use glm.nb With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished



