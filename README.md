#include <iostream>
#include <vector>
using namespace std;

int main() {
    int N;
    
    cout << "Jumlah angka: ";
    cin >> N;
    
    vector<int> angka(N);
    
    cout << "Masukkan angka satu per satu:\n";
    for (int i = 0; i < N; i++) {
        cout << "Angka ke-" << i + 1 << ": ";
        cin >> angka[i];
    }
    
    cout << "\nMenampilkan angka dalam urutan terbalik:\n";
    for (int i = N - 1; i >= 0; i--) {
        cout << angka[i] << " ";
    }
    cout << endl;

    return 0;
}
