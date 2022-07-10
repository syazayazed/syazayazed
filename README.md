> library(readxl)
Warning message:
package ‘readxl’ was built under R version 4.1.3 
> W_H <- read_excel("syaza/studies/sem 4/statistics II/ASSIGNMENT/W&H.xlsx")
> View(W_H)
> data.frame(W_H)
     id age Race Marital Education Employment Credit Saving   weight height
1  a001  22    1       1         6          2      1      0 68.00000   1.66
2  a002  21    1       1         4          1      0      1 45.00000   1.66
3  a003  15    1       1         2          2      0      1 38.00000   1.55
4  a004  23    1       1         6          2      0      1 90.00000   1.60
5  a005  19    1       1         5          2      0      1 69.00000   1.60
6  a006  21    1       1         5          1      0      1 80.00000   1.65
7  a007  23    1       1         6          2      0      1 46.00000   1.53
8  a008  23    1       1         6          2      0      1 50.00000   1.60
9  a009  23    1       1         6          2      0      1 58.00000   1.68
10 a010  24    1       1         6          1      0      1 52.00000   1.65
11 a011  21    1       1         6          2      1      1 58.00000   1.68
12 a012  19    1       1         9          2      0      1 77.00000   1.66
13 a013  17    1       1         2          1      0      1 48.00000   1.52
14 a014  23    1       1         6          1      0      1 45.00000   1.54
15 a015  24    1       1         7          1      1      1 60.00000   1.56
16 a016  23    1       1         6          1      0      1 47.00000   1.66
17 a017  16    1       1         3          2      0      1 48.00000   1.58
18 a018  22    1       1         3          2      0      1 82.00000   1.63
19 a019  23    1       1         6          2      0      1 59.09091   1.60
20 a020  20    1       1         5          2      0      1 65.00000   1.65
21 a021  18    1       1         3          2      0      1 45.00000   1.44
22 a022  22    1       1         6          2      0      1 58.00000   1.51
23 a023  24    2       1         6          1      1      1 45.00000   1.57
24 a024  24    1       1         7          1      0      1 65.00000   1.72
25 a025  24    1       1         6          1      1      1 80.00000   1.65
26 a026  24    1       1         7          2      0      1 42.00000   1.54
27 a027  24    1       1         7          2      0      1 42.00000   1.50
   Exercise Ofen Long medical Religious1 Religous2 Religous3 Religous4
1         1    5    2       2          5         5         5         5
2         1    2    3       2          4         4         4         4
3         1    5    3       1          4         5         5         5
4         1    2    4       1          4         4         4         4
5         1    3    4       2          2         3         4         4
6         0    0    0       0          3         3         4         3
7         0    0    0       0          3         3         4         3
8         0    0    0       0          3         3         4         5
9         1    4    4       0          4         5         5         4
10        1    5    2       3          4         5         5         5
11        1    3    3       1          3         5         5         5
12        0    0    0       2          3         4         5         3
13        0    0    0       0          4         5         5         4
14        1    2    2       1          4         5         5         5
15        1    5    4       3          5         5         5         4
16        0    1    2       1          3         4         4         3
17        0    3    4       3          4         4         4         3
18        1    5    2       1          4         3         4         4
19        1    4    4       1          4         5         5         5
20        0    1    2       1          5         5         5         5
21        0    1    3       3          3         3         4         2
22        1    5    3       1          5         5         5         5
23        1    4    4       0          4         4         4         4
24        0    1    2       1          5         5         5         5
25        1    4    3       1          4         4         5         4
26        1    2    3       2          3         3         5         4
27        1    5    1       1          5         5         5         4
   Religous5 GHQ1 GHQ2 GHQ3 GHQ4 GHQ5 GHQ6 GHQ7 GHQ8 GHQ9 GHQ10 GHQ11 GHQ12
1          1    1    0    1    1    1    0    1    1    0     0     0     1
2          1    1    0    0    1    0    0    0    1    0     0     0     0
3          1    1    1    1    1    2    1    2    1    0     0     0     1
4          2    1    1    1    1    1    1    1    1    1     0     0     1
5          1    1    0    1    1    1    0    1    1    1     0     0     0
6          1    1    2    1    1    1    1    1    1    1     1     1     1
7          2    1    1    1    1    1    1    1    1    1     1     1     1
8          1    1    0    1    1    0    0    1    1    0     0     0     1
9          1    1    1    2    2    1    2    1    2    3     2     1     2
10         1    0    1    0    0    0    0    0    0    0     0     0     1
11         1    0    1    1    1    0    0    0    1    0     0     0     1
12         2    1    0    1    1    2    2    1    1    2     0     0     1
13         5    2    1    0    2    2    1    1    1    2     2     1     1
14         2    1    2    1    1    1    0    0    1    1     0     0     1
15         1    1    1    1    1    1    1    1    0    2     1     0     1
16         3    1    0    2    1    1    1    1    1    1     1     1     1
17         3    0    2    1    2    2    1    1    3    1     3     0     2
18         5    2    2    1    1    2    0    2    1    3     1     1     2
19         1    1    0    1    1    0    1    1    2    2     0     0     2
20         3    1    1    1    1    2    1    2    2    2     2     2     2
21         4    1    1    1    1    2    2    1    2    1     1     1     2
22         2    1    1    0    0    2    1    1    0    1     1     0     1
23         4    1    1    1    1    1    1    1    1    1     1     1     1
24         3    1    0    1    1    0    0    1    1    0     0     0     1
25         3    0    0    1    0    0    0    0    0    0     0     0     1
26         1    0    1    0    2    1    1    1    2    1     1     2     1
27         4    0    0    0    0    0    0    0    0    1     0     1     0
   Life1 Life2 Life3 Life4 Life5
1      4     4     4     3     4
2      3     2     2     3     2
3      5     5     5     1     2
4      3     3     4     3     4
5      4     4     3     3     3
6      2     2     3     2     1
7      3     3     3     3     3
8      4     5     5     3     2
9      3     2     4     3     2
10     5     5     3     5     5
11     5     5     4     5     3
12     3     3     4     3     1
13     5     5     5     5     1
14     3     4     4     3     3
15     5     5     5     3     4
16     4     3     4     3     4
17     2     1     2     1     5
18     5     5     5     5     5
19     4     4     1     3     2
20     3     3     3     3     1
21     3     2     2     1     1
22     4     4     4     4     4
23     3     3     3     3     3
24     4     3     3     3     3
25     4     3     2     2     1
26     4     4     4     4     4
27     5     4     5     4     4
 [ reached 'max' / getOption("max.print") -- omitted 173 rows ]
> attach(W_H)
> W_H$Education[W_H$Education == 99] <- NA
> W_H$Employment[W_H$Employment == 99] <- NA
> W_H$Credit[W_H$Credit == 99] <- NA
> W_H$Ofen[W_H$Ofen == 99] <- NA
> W_H$medical[W_H$medical == 99] <- NA
> W_H$GHQ2[W_H$GHQ2 == 9.00] <- NA
> W_H$GHQ3[W_H$GHQ3 == 9.00] <- NA
> W_H$GHQ8[W_H$GHQ8 == 9.00] <- NA
> W_H$weight[W_H$weight == 0.00] <- NA
> W_H$height[W_H$height == 0.00] <- NA
> W_H$Ofen[W_H$Ofen == 0.00] <- NA
> View(W_H)
> summary(W_H)
      id                 age             Race          Marital     
 Length:200         Min.   :15.00   Min.   :1.000   Min.   :1.000  
 Class :character   1st Qu.:19.00   1st Qu.:1.000   1st Qu.:1.000  
 Mode  :character   Median :21.00   Median :1.000   Median :1.000  
                    Mean   :20.94   Mean   :1.525   Mean   :1.035  
                    3rd Qu.:24.00   3rd Qu.:2.000   3rd Qu.:1.000  
                    Max.   :30.00   Max.   :3.000   Max.   :2.000  
                                                                   
   Education       Employment        Credit           Saving     
 Min.   :0.000   Min.   :1.000   Min.   :0.0000   Min.   :0.000  
 1st Qu.:3.000   1st Qu.:1.000   1st Qu.:0.0000   1st Qu.:1.000  
 Median :5.000   Median :2.000   Median :0.0000   Median :1.000  
 Mean   :4.626   Mean   :1.658   Mean   :0.1256   Mean   :0.925  
 3rd Qu.:6.000   3rd Qu.:2.000   3rd Qu.:0.0000   3rd Qu.:1.000  
 Max.   :9.000   Max.   :4.000   Max.   :1.0000   Max.   :1.000  
 NA's   :5       NA's   :1       NA's   :1                       
     weight          height         Exercise          Ofen     
 Min.   :36.00   Min.   :1.295   Min.   :0.000   Min.   :1.00  
 1st Qu.:45.00   1st Qu.:1.540   1st Qu.:1.000   1st Qu.:2.00  
 Median :51.00   Median :1.590   Median :1.000   Median :3.00  
 Mean   :53.54   Mean   :1.590   Mean   :0.755   Mean   :3.06  
 3rd Qu.:59.09   3rd Qu.:1.640   3rd Qu.:1.000   3rd Qu.:4.00  
 Max.   :90.00   Max.   :1.810   Max.   :1.000   Max.   :5.00  
 NA's   :3       NA's   :5                       NA's   :32    
      Long          medical        Religious1      Religous2    
 Min.   :0.000   Min.   :0.000   Min.   :1.000   Min.   :1.000  
 1st Qu.:2.000   1st Qu.:0.000   1st Qu.:3.000   1st Qu.:3.000  
 Median :3.000   Median :1.000   Median :4.000   Median :4.000  
 Mean   :2.415   Mean   :1.061   Mean   :3.665   Mean   :3.845  
 3rd Qu.:4.000   3rd Qu.:2.000   3rd Qu.:4.000   3rd Qu.:5.000  
 Max.   :4.000   Max.   :4.000   Max.   :5.000   Max.   :5.000  
                 NA's   :2                                      
   Religous3      Religous4       Religous5        GHQ1      
 Min.   :1.00   Min.   :1.000   Min.   :1.0   Min.   :0.000  
 1st Qu.:4.00   1st Qu.:3.000   1st Qu.:1.0   1st Qu.:1.000  
 Median :5.00   Median :4.000   Median :3.0   Median :1.000  
 Mean   :4.18   Mean   :3.805   Mean   :2.6   Mean   :1.095  
 3rd Qu.:5.00   3rd Qu.:5.000   3rd Qu.:3.0   3rd Qu.:1.000  
 Max.   :5.00   Max.   :5.000   Max.   :9.0   Max.   :3.000  
                                                             
      GHQ2            GHQ3             GHQ4            GHQ5      
 Min.   :0.000   Min.   :0.0000   Min.   :0.000   Min.   :0.000  
 1st Qu.:0.000   1st Qu.:1.0000   1st Qu.:1.000   1st Qu.:1.000  
 Median :1.000   Median :1.0000   Median :1.000   Median :1.000  
 Mean   :1.005   Mean   :0.9545   Mean   :0.975   Mean   :1.245  
 3rd Qu.:1.000   3rd Qu.:1.0000   3rd Qu.:1.000   3rd Qu.:2.000  
 Max.   :3.000   Max.   :3.0000   Max.   :3.000   Max.   :3.000  
 NA's   :1       NA's   :2                                       
      GHQ6            GHQ7            GHQ8            GHQ9     
 Min.   :0.000   Min.   :0.000   Min.   :0.000   Min.   :0.00  
 1st Qu.:0.000   1st Qu.:1.000   1st Qu.:1.000   1st Qu.:0.00  
 Median :1.000   Median :1.000   Median :1.000   Median :1.00  
 Mean   :0.955   Mean   :1.005   Mean   :1.045   Mean   :1.01  
 3rd Qu.:1.000   3rd Qu.:1.000   3rd Qu.:1.000   3rd Qu.:1.00  
 Max.   :3.000   Max.   :3.000   Max.   :3.000   Max.   :3.00  
                                 NA's   :1                     
     GHQ10           GHQ11          GHQ12          Life1           Life2    
 Min.   :0.000   Min.   :0.00   Min.   :0.00   Min.   :1.000   Min.   :1.0  
 1st Qu.:0.000   1st Qu.:0.00   1st Qu.:1.00   1st Qu.:3.000   1st Qu.:3.0  
 Median :1.000   Median :0.00   Median :1.00   Median :3.000   Median :3.0  
 Mean   :0.845   Mean   :0.66   Mean   :0.96   Mean   :3.375   Mean   :3.4  
 3rd Qu.:1.000   3rd Qu.:1.00   3rd Qu.:1.00   3rd Qu.:4.000   3rd Qu.:4.0  
 Max.   :3.000   Max.   :3.00   Max.   :3.00   Max.   :5.000   Max.   :5.0  
                                                                            
     Life3           Life4           Life5      
 Min.   :1.000   Min.   :1.000   Min.   :1.000  
 1st Qu.:3.000   1st Qu.:2.000   1st Qu.:2.000  
 Median :3.000   Median :3.000   Median :3.000  
 Mean   :3.355   Mean   :2.985   Mean   :2.655  
 3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:4.000  
 Max.   :5.000   Max.   :5.000   Max.   :5.000  
                                                
