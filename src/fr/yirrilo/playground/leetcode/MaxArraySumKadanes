public class MaxArraySumKadanes {
	public static void kadanes(int arr[])
	{
		int cs=0;
		int ms=Integer.MIN_VALUE;
		for(int i=0;i<arr.length;i++)
		{
			cs=cs+arr[i];
			if(cs<0)
			{
				cs=0;
			}
			else
			{
				ms=Math.max(ms, cs);
			}
			
		}System.out.println(ms);
	}
	public static void main(String[] args) {
		// TODO Auto-generated method stub
    int arr[]= {-2,-3,4,-1,-2,1,5,-3};
    kadanes(arr);
    }

}
