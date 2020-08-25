# Intro-to-R

# Intro to RStudio
makeData.R output

> var1 <- 1:5
> var2 <- (5:1)*20
> var3 <- c("Sakshi", "Aastha", "Sukriti", "Sanjana", "Souyma")
> df1 <- data.frame(var1, var2, var3)
> names(df1) <- c("VarInt", "VarReal", "VarChar")
> #save to a csv file
> write.csv(df1, "./dataforR1.csv", row.names = FALSE)
> #read from a csv file
> df2 <- read.csv("./dataforR1.csv")
> print(df2)
  VarInt VarReal VarChar
1      1     100  Sakshi
2      2      80  Aastha
3      3      60 Sukriti
4      4      40 Sanjana
5      5      20  Souyma

# -----------   OR( other data sets ) --------
  VarInt VarReal      VarChar
1      1     0.1            R
2      2     0.2          and
3      3     0.3  Data Mining
4      4     0.4     Examples
5      5     0.5 Case Studies
