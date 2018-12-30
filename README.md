    # Algo-5.1
Biner

    #include <iostream>
    #include <conio.h>
    using namespace std;
    unsigned int bil2,bit2;
    void konversi(unsigned int bil2){
    if (bil2>1){
        konversi(bil2/2);}
        bit2=bil2%2;
        cout<<bit2<<"";
    }
    int main  (){
    cout<<"masukan bilangan :";
    cin>>bil2;
    konversi(bil2);
    cout<<endl<<endl;
    getch();

    }
    
  Aplikasi
  
  ![img](https://github.com/muhammadyusufalfaqih/Algo-5.1/blob/master/biner%20img.png)
