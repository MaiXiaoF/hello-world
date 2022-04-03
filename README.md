打印出生年月
int main()
{
	int year = 0;
	int month = 0;
	int date = 0;
	scanf("%4d%2d%2d", &year, &month, &date);
	printf("year=%4d\n", year);
	printf("month=%02d\n", month);
	printf("date=%02d\n", date);
	return 0;
}
