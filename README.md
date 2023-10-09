publicclass Fibonaccinumbers {
publicstaticvoid main(String[] args) {
int elementPosition=1,count=10, firstFibonacciNum=0,nextFibonacciNum=1;
System.out.print(firstFibonacciNum+&quot;&quot;+nextFibonacciNum);
for(elementPosition=2;elementPosition&lt;count;++elementPosition)
{
int sumofPrev2=firstFibonacciNum+nextFibonacciNum;
firstFibonacciNum=nextFibonacciNum;
System.out.print(&quot;&quot;+sumofPrev2);
nextFibonacciNum=sumofPrev2;
elementPosition++;
}
}
}
