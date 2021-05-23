# data-science-practical
Q1. function to compute running total of a list.
soln: total<- function(list) cumsum(list)
         total(c(1,2,3,4,5,6))
         
 Q2. implementation of linear search.
 soln: linSearch <- function(list,element)
       {
         pos=1;
         flag=FALSE;
         for(l in list)
         {
           if(l==element)
           {
             flag=TRUE;
             break;
            }
             pos=pos+1;
           }
           if(flag)
           {
             print(paste("Element found at",pos),quote=FALSE);
            }
            else
            {
             print("Element not found", quote=FALSE);
            }
          }
          
          linSearch(c(45,12,1,63,50,12),63)
          
         Q3. implementation of matrix addition, substraction and multiplication.
           m1= matrix(c(1,2,3,4,5,6), nrow=2)
           print("Matrix-1:")
           print(m1)
           m2=matrix(c(0,1,2,3,0,2),nrow=2)
           print("Matrix-2:")
           print(m2)
           
           result= m1+m2
           print("Result of addition")
           print(result)
           
           result=m1-m2
           print("Result of substraction")
           print(Result)
           
           result=m1*m2
           print("Result of multiplication")
           print(result)
