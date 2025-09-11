# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Multiple Correspondence Analysis (MCA) Use MCA (FactoMineR) With (In) R Software
install.packages("FactoMineR")
library("FactoMineR")
MCA = read.csv("https://raw.githubusercontent.com/timbulwidodostp/MCA/main/MCA/MCA.csv",sep = ";")
# Estimation Multiple Correspondence Analysis (MCA) Use MCA (FactoMineR) With (In) R Software
MCA <- MCA(MCA, quanti.sup = 19, quali.sup = 20:36)
summary(MCA)
# Multiple Correspondence Analysis (MCA) Use MCA (FactoMineR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished