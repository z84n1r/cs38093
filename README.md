java c
PM 510 Homework #02
1.   For nominal, ordinal, interval, and ratio measurements, indicate which of the following can be calculated.
Measurement type
Can you calculate?
Nominal
Ordinal
Interval
Ratio
Frequency  distribution




Values which are larger than others




Addition and subtraction




Values which are
twice as large as
others




2.   Use Table 1 from the Shikuma article to answer the following questions.
(a) List up to 3 of each of the types of variables discussed in class: nominal, ordinal, discrete numeric, and continuous.   (Note: If there aren’t three of one of the types, list all that you can find.)
(b) For the categorical variables you chose in part (a), list the possible values or levels of those variables.
(c) For the numeric variables you chose in part (a), state whether they are interval or ratio measurements.
(d) Pick one of the continuous variables you chose in part (a) and convert it to a categorical variable with at least three categories.
(e) Pick one of the continuous variables you chose in part (a) and explain a way it could be considered as a discrete numeric variable.
3.   [SPSS] The data set lowbwt .sav contains information for the sample of 100 low birth weight infants born in Boston, Massachusetts. This data set contains information on the systolic blood pressure (SBP) of the infants measured in millimeters of mercury (mm Hg). Categorize SBP into 5 categories (<20, 20–39, 40–59, 60–79, ≥80) and name it SBP_cat.
(a) Make a histogram with SBP. Comment about the graph. Make sure you comment about the shape, symmetry, skewness and the modality of the graph
(b) Make a stem and leaf plot with SBP. Comment about the graph. What are the extremes of the observation?
(c) Make a pie chart with SBP_cat. What proportion of children have systolic blood pressure between 40–59 mmHg?
(d) Make a bar chart with SBP_cat.
BEYOND THE BASICSThese are the problems included to clarify concepts beyond basic statistical skill required for the class.  You will not be penalized for not attempting these.  However, you are encouraged to do them.
4.   [SPSS]  Suppose you want to test  a six-sided die to see if it’s fair. You  decide to roll it repeatedly, construct a histogram, and see if the histogram “looks OK.” In ord代 写PM 510 Biostatistics Homework #02Matlab
代做程序编程语言er to do that, you need to know what “looks OK” means, and how far off it could be even if it really were a fair die.  This problem will let you explore that.
(a) Use SPSS to simulate rolling a fair six-sided die 60 times. Do this twice more so you have three sets of 60 simulated rolls.  (Instructions for how to do this are below.) Construct a histogram for each set of simulated rolls and describe how they compare to each other and to what they “should be.”
(b) Repeat part (a) but do 600 simulated rolls each time.
One way to simulate rolling a fair die in SPSS:
1.   Open SPSS and get an empty data set.
2.   Scroll down until youreach the 60th  row and put any number you want in the first column of that row.  (All of the rows above it should now have dots in the first column.)
3.   Choose the Transform. menu.
4.   In the Target Variable box, write down a name for a new variable, for example Rand1.
5.   In the Function group box, scroll down and choose Random Numbers.
6.   In the Functions and Special Variables box, scroll down and choose Rv .Uniform.
7.   In the Numeric Expression box, replace the question marks with 0 and 1.
8.   Select OK.  There should now be a set of numbers between 0 and 1 in the column Rand1. Next, we transform. them to be the numbers 1 through 6.
9.   Choose the Transform. menu.
10. In the Target Variable box, write down a name for a new variable, for example Roll1.
11. In the Numeric Expression box, type the following: 1 + TRUNC(6 * Rand1)
12. Select OK.  There should now be the numbers 1 through 6 (they will probably look like 1.00, 2.00, etc.) in the column Roll1.  This represents your random sample.
13. Repeat Steps 4–12 using Rand2/Roll2 and Rand3/Roll3 in place of Rand1/Roll1. You now have 3 simulated sets of 60 rolls of a fair six-sided die (Roll1, Roll2, and Roll3).To do the sets of 600 rolls, you first need to get something in the 600th row of the first column. In my version of SPSS, you can only scroll down so far with an empty data set (unlike in Excel, for example). So probably the easiest way to get down to 600 is to select the first 60 rows in the first column (with the number in the 60throw that you put there before), then Copy-Paste that repeatedly to get to 600 rows. Then repeat the above instructions.





         
加QQ：99515681  WX：codinghelp
