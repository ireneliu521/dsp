[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> diff = firsts.totalwgt_lb.mean() - others.totalwgt_lb.mean()  
>> var1 = firsts.totalwgt_lb.var()  
>> var2 = others.totalwgt_lb.var()  
>> n1, n2 = len(firsts.totalwgt_lb), len(others.totalwgt_lb)   
>> pooled_var = (n1 * var1 + n2 * var2) / (n1 + n2)  
>> d = diff / np.sqrt(pooled_var)  
>> d = -0.088672927072602  
>>
>> The difference in birth weight is 0.089 standard deviation. Different from the difference in pregnancy length, the effect size of birth weight is negative, which indicates the mean of non-first-babies is larger than the mean of first babies.
