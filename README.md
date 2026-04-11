   #include <stdio.h>
    int main() 
  {
    char str1[100], str2[100];
    int i = 0, j = 0;
    printf("Enter first string: ");
    fgets(str1,sizeof(str1),stdin);
    printf("Enter second string: ");
    fgets(str2,sizeof(str2),stdin);
    while (str1[i] != '\0') {
        i++;
    }
    (str2[j] != '\0') {
        str1[i] = str2[j];
        i++;
        j++;
    }
    str1[i] = '\0';
    printf("Concatenated string: %s", str1);
    printf("\n25331A05I6");
    return 0;
}
