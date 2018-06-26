[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> resp = nsfg.ReadFemResp()  
>> pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')  
>> biased_pmf = BiasPmf(pmf, label='biased')  
>> thinkplot.PrePlot(2)  
>> thinkplot.Pmfs([pmf, biased_pmf])  
>> thinkplot.Show(xlabel='class size', ylabel='PMF')  
>>
>> pmf.Mean()  
>> 1.0242051550438309  
>> biased_pmf.Mean()  
>> 2.4036791006642821
