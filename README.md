# 7
int main()
{
	int i = 0;
	int n = 0;
	int ret = 1;
	int d = 0;
	int c = 0;
	scanf("%d", &n);
	for (i = 1; i <= n; i++)
	{
		ret = ret * i;
		d = ret;
		c = c + d;
		
	}
	printf("c = %d\n", c);



}
