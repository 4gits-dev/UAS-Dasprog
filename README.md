# UAS-Dasprog
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Pemrograman
<br> Nama		      : Muhammad Agits Fathul Ma'asyi
<br>NIM		        : 1227050082	
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Array dua dimensi adalah sebutan untuk array yang penomoran index-nya menggunakan 2 buah angka. Analogi lain adalah matriks. Matrixs Merupakan kumpulan-kumpulan bilangan yang disusun secara baris (vertikal) dan kolom (horizontal) bisa disebut juga array dua dimensi (multi-dimensional). Transpose Matriks adalah memperoleh sebuah matriks dengan cara menukar baris menjadi kolom dan kolom menjadi baris dari sebuah matriks. Dalam matematika, matriks terdiri dari kolom dan baris. Kembali, untuk menentukan nilai dari sebuah matriks, kita harus sebut secara berpasangan seperti baris 1 kolom 1, atau baris 2 kolom 3, dst. Konsep seperti inilah yang menjadi dasar dari array 2 dimensi. Untuk membuat array 2 dimensi di dalam bahasa C++, caranya tulis 2 kali tanda kurung siku setelah nama variabel, seperti contoh berikut:
int arr[2][2];
Untuk UAS kali ini kami diminta membuat 2 buah program yaitu program pertama adalah membuat array 2 dimensi dengan baris , kolom dan nilai nya di input lalu ditukarkan antara kolom dan baris sedangkan program ke dua digunakan untuk mencari nilai yang dapat di bagi 3, 7, dan 5.
## Source Code
cout<<"==========================================================================================="<<endl;
cout <<" Input banyaknya baris dan kolom, kemudian tukar kolom jadi baris dan sebaliknya"<<endl;
cout <<"==========================================================================================="<<endl<<endl;

 int nilai[100][100];
  int baris, kolom, a, j;
 
  cout << "Input jumlah baris matriks: ";
  cin >> baris;
 
  cout << "Input jumlah kolom matriks: ";
  cin >> kolom;
  cout << endl;
 
  // proses input array
  for(a = 0; a < baris ; a++){
    for(j = 0; j < kolom; j++){
      cout << "Baris " <<a+1<<", kolom "<<j+1<< " = ";
      cin >> nilai[a][j];
    }
    cout << endl;
  }
 
  cout << "Hasil matriks normal " << endl<<endl;
 
  // menampilkan array
  for(a = 0; a < baris ; a++){
    for(j = 0; j < kolom; j++){
      cout  << nilai[a][j] << " ";
    }
    cout <<endl;
  }
   cout <<endl<< "Hasil matriks yang ditukar"<<endl<<endl;
   for(a = 0; a < kolom ; a++){
    for(j = 0; j < baris; j++){
      cout  << nilai[j][a] << " ";
    }
    cout << endl;
  }
}

## Output

<img src="output soal no 1.png">
