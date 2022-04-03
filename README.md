用 << 算2的n次方
int main()
{
	int n = 0;
	while (scanf("%d", &n) != EOF)
	{
		printf("%d", 1 << n);
	}
	return 0;
}
