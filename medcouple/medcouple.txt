# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# A robust measure of skewness for univariate data Use medcouple (mrfDepth) With (In) R Software
install.packages("mrfDepth")
library("mrfDepth")
medcouple = read.csv("https://raw.githubusercontent.com/timbulwidodostp/medcouple/main/medcouple/medcouple.csv",sep = ";")
# Estimation A robust measure of skewness for univariate data Use medcouple (mrfDepth) With (In) R Software
medcouple_1 <- medcouple(medcouple)
medcouple_data <- medcouple[1:25,]
medcouple_2 <- medcouple(medcouple_data, do.reflect = FALSE)
medcouple_3 <- medcouple(medcouple_data, do.reflect = TRUE)
medcouple_1
medcouple_2
medcouple_3
# A robust measure of skewness for univariate data Use medcouple (mrfDepth) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished