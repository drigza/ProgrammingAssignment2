##### Results of running the inverse of matrix in cacheSolve.
<!-- --> 

   > q <- matrix(3:6, nrow=2, ncol=2)
   > a <- makeCacheMatrix(q) 
   > b<- cacheSolve(a)
   > b<- cacheSolve(a)
   getting cached data.
   > q%*%b
        [,1] [,2]
   [1,]    1    0
   [2,]    0    1
