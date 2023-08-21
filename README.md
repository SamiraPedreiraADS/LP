#include <iostream>

using namespace std;

int main() {
  string alunos[10] = {"Mateus", "Melissa", "Pedro", "Sofia", "Esther", "Gustavo", "Fernanda", "Victoria", "Olivia", "Renato"};
  string nomes[10] = {"Mateus", "Melissa", "Pedro", "Sofia", "Esther", "Gustavo", "Fernanda", "Victoria", "Olivia", "Renato"};
  int notas1, notas2, media, i;


    cout << "---BOLETIM ESCOLAR 2023---\n";
    cout << "Por favor, informe o nome do aluno: ";
    cin >> alunos[i];
  
    cout << "Agora insira a nota do primeiro bimestre de " << alunos[i] << ": ";
    cin >> notas1;

    cout << "Para fecharmos a média desse aluno, informe a segunda nota: ";
    cin >> notas2;
    
  

    media = (notas1 + notas2) / 2;

    if (media < 5){
     cout << "O aluno(a) " << alunos[i] << " está de recuperação ";
    }
    if (media == 5) {
     cout << "O aluno(a) " << alunos[i] << " passou na média";
    }
   if (media > 5) {
     cout << "O aluno(a) " << alunos[i] << " passou acima da média, Parabéns!" ;
    }


}
