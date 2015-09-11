//First Program

#include <iostream>

using namespace std;
char nome[50];
int idade;
char email[50];


//Função para exibir os dados
void exibe(char x,int y,char z) {
    cout << "Nome: " << x << endl;
    cout << "Idade: " << y << endl;
    cout << "Email: " << z << endl;
}
//Registro
struct cadastro (){

};
//Programa Central
int main(void)
{
    cout << "Cadastro Pessoal \n\n";
    cout << "Digite o seu nome: ";
    cin >> nome;
    cout << "Digite a sua idade: ";
    cin >> idade;
    cout << "Digite o seu email: ";
    cin >> email;

    exibe(nome, idade, email);
    return 0;
}

