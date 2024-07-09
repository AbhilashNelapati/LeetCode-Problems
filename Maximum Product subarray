class sample:
    def product_maximum(self , num: list[int])->int:
        
        if not num:
            return 0
            
        prod=num[0]
        maxprod=num[0]
        minprod=num[0]
       
            
        for i in range(1,len(num)):
            temp = maxprod
            maxprod = max( num[i] , maxprod * num[i] , minprod * num[i] )
            minprod = max( num[i] , temp * num[i] , minprod * num[i] )
            
            prod = max(prod,maxprod)
            
        return prod

solution = sample()

result = solution.product_maximum([2, 3, -2, 4])
print("Maximum product subarray:", result)


