# UAS-Dasprog
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Pemrograman
<br> Nama		      : Muhammad Agits Fathul Ma'asyi
<br>NIM		        : 1227050082	
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

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
