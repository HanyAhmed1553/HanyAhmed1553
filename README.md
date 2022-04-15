library (readr)

urlfile="https://raw.githubusercontent.com/SatadruMukherjee/Dataset/main/global_heat_index.csv"

mydata<-read_csv(url(urlfile))
