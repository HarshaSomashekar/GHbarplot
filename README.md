> data <- c( 2, 3, 4, 5, 6,7)
> 
> barplot(data)
> 
> barplot(data, col="Red")
> barplot(data, horiz=T)
> barplot(data, col= "orange", horiz=T)
> group <- letters [1:6]
> barplot(data, names.arg=group)
> barplot(data, col= "orange", horiz=T, names.arg=group)
> data <- as.matrix(data.frame(A = c(2, 3), 
                               B = c(4, 5),
                               C = c(6, 7)))
> rownames(data) <- c("Group 1", "Group 2")
> data  or >str(data)  or >head(data)
> barplot(data, col=c("darkgreen", "Grey"))         
> barplot(data, col=c("darkgreen", "Grey"), beside=TRUE) 
> legend("topright", 
       legend = c ("Group1", "Group2"), 
       fill= c ("darkgreen", "Grey"))
> barplot(data, 
        xaxt='n', yaxt="n", beside= TRUE)
> barplot(data, 
         xaxt='n', yaxt="n", beside= TRUE),
         xlab = 'My x-axis label')
> barplot(data, 
         ylim =c(0, 2))
> barplot(data, 
         ylim =c(0, 2), xaxt='n', xlab = 'My x-axis label', beside= TRUE)
