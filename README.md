> data <- c( 2, 3, 4, 5, 6,7)
> 
> barplot(data)
> 
> barplot(data, col="Red")
> 
> barplot(data, horiz=T)
> 
> barplot(data, col= "orange", horiz=T)
> 
> group <- letters [1:6]
> 
> barplot(data, names.arg=group)
> 
> barplot(data, col= "orange", horiz=T, names.arg=group)
