# Stock Analysis

## Overview of Project

### Purpose
Steve’s parents are passionate about green energy and want to invest in DQ. Steve is concerned about diversification. We have evaluated the returns of many green energy stocks to help Steve inform his parents about which stocks would be the most profitable to invest in.

## Results

### Stock Performance between 2017 and 2018
Overall, 2017 was a better year for these green stocks. Except for TERP all the stocks analyzed had a positive return. As shown by the image below:


![2017Results](https://user-images.githubusercontent.com/90511014/139557533-d30634dd-a0ae-411d-b6b6-c554b6c19bc0.png)

 In 2018, only two stocks, ENPH and RUN, had a positive return. As shown below:
 
![2018Results](https://user-images.githubusercontent.com/90511014/139557538-f8aac058-f7a3-4b6c-b921-c2eac18f45ee.png)

Based on the high return for two years in a row, I would recommend investing in ENPH and RUN. To diversify further both SEDG and VSLR had small 2018 losses and large 2017 gains. These may also be strong stocks to invest in. 
 
 
### Execution times of Original Script
The original script had similar times for each year, each about .6 seconds. As shown below:

![2017Initial](https://user-images.githubusercontent.com/90511014/139557542-19ff0011-8827-4f0d-99f5-2ccb9a53351e.png)![2018Initial](https://user-images.githubusercontent.com/90511014/139557543-ae8c3993-f4a3-40bd-8a85-20276376273c.png)

However, the refactored code had significantly faster times for each year each about .15 seconds. As shown below:


![2017Refactored](https://user-images.githubusercontent.com/90511014/139557545-745a1474-0d93-4915-8f68-7a2ddd53affd.png)![2018Refactored](https://user-images.githubusercontent.com/90511014/139557547-b754b49b-c64d-4892-86f2-11d66380dffe.png)

 
## Summary

### Advantages or Disadvantages
Refactoring code allows it to be quicker and more efficient. It also makes it so the code is more understandable and can be changed easier as updates need to be made. This matters significantly in high volume or time sensitive situations. Having an inefficent code will require more resources from the computer. If there is situation where there are hundreds of thousands of data points being analyzed the inefficiency could be a difference of several minutes rather than a fraction of a second. In stock trading this could make a difference in being able to make a transaction now that it would be the most profitable. 
However, anytime new code is introduced, or current code is changed, it increases the opportunity to introduce human error. Some errors may cause the code to stop working completely. Other errors may be harder to identify as the code continues to work however it is not resulting in the desired outcome.


### How do these apply
Writing a more efficient code was 80% faster for 2017 and 74% faster for 2018. This is a very significant difference. However, because the size of our data this difference is not perceptible as it is still a fraction of a second. If we had a larger data set this would be more valuable. In refactoring, I did understand the code better and knew exactly what each part of the code was for. In making the script more efficient, I made many errors. At times the code stopped working completely. Efficiency is great but a working code is better than a not working code. Once I completely understood what the code was doing the code the debugging was much easier. However, I think refactoring without a specific purpose is not a good idea.

