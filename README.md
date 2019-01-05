# contoh-1-array-2-manipulasi

    #include<stdio.h>
    #include<conio.h>

    int main()
    {
        int bil[7],i;
        printf("elemen 1 ? ") ; scanf("%d",&bil[0]);
        bil[1] = 5;
        bil[2] = bil[1] + 20;
        for(i=4;i<7;i++) bil[i] = i*10;
        bil[3] = bil[bil[1]];
        for(i=0;i<7;i++) printf("bil[%d] %d dan alamatnya: %x\n",i,bil[i],&bil[i]);
        getch();
        return 0;
    }
    
    
    
    
hasil
![img](https://github.com/septianaana/contoh-1-array-2-manipulasi/blob/master/contoh%20array%202%20manipulasi%201.png?raw=true)
