# Menghitung-total-max-min-rata-rata

    #include<iostream>
    using namespace std;
    int main()
    {
    int i,bil[13],jumlah,tertinggi,terendah;
    float rata;
    for(i=0;i<13;i++)
    {
        cout<<"masukkan data:"<<i+1<<" = ";cin>>bil[i];
    }
    cout<<"seluruh elemen \n";
    jumlah=0;
    terendah=bil[0];
    tertinggi=bil[0];
    for(i=0;i<13;i++)
    {
        cout<<bil[i]<<endl;
        jumlah=jumlah+bil[i];
        if(bil[i]<terendah)
        {
            terendah=bil[i];
        }
        else if(bil[i]>tertinggi);
        {
            tertinggi=bil[i];
        }
    }
    rata=jumlah/13;
    cout<<"total :"<<jumlah<<endl;
    cout<<"max :"<<tertinggi<<endl;
    cout<<"min :"<<terendah<<endl;
    cout<<"rata-rata :"<<rata<<endl;
    return 0;

    }

## Hasilnya

![img](https://github.com/ernico27/Menghitung-total-max-min-rata-rata/blob/master/total%201.png?raw=true)

![img](https://github.com/ernico27/Menghitung-total-max-min-rata-rata/blob/master/total%202.png?raw=true)
