# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Spatial Gini coefficient Use spGini (lctools) With (In) R Software
install.packages("lctools")
install.packages("backports")
install.packages("minqa")
library("lctools")
spGini = read.csv("https://raw.githubusercontent.com/timbulwidodostp/spGini/main/spGini/spGini.csv",sep = ";")
# Estimation Spatial Gini coefficient Use spGini (lctools) With (In) R Software
Coords1<-cbind(spGini$X, spGini$Y)
Bandwidth1<-12
x1<-spGini$Income01
WType1<-'Binary'
Gini <- spGini(Coords1,Bandwidth1,x1,WType1)
Gini
# Spatial Gini coefficient Use spGini (lctools) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished