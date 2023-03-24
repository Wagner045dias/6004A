fun main() {
    
    var pessoal = Pessoa() // Instanciamos um obj derivado da classe da pessoa
    println(pessoal.peso) // Exibr o valor de um parametro de um obj
    pessoal.peso = 55.0 // Edição de valor de um atributo
    println(pessoal.peso)
    pessoal.nome= "Matue"
    println(pessoal.nome) // Orientação de valor de um atributo
    println(pessoal.nome)
    
  
}
// POO = Programação orientada a objetos  
// 
// POO é uma apresentação virtual de atividades baseadas pro mundo real
// 
// Objertos - é tudo que ocupa um determinado espaço e executa uma determinada atividade
// 
//        .Estados - atributos, caracteristicas, propriedade, (nome,idade, altura...)
//        .Comportamento- atividades, tarefas, funções (andar, correr, comer...)
//        
//Classes - Modelos para a construção de obj derivados dele mesmo
//         . heranças - objetos herdam atributos das classes
// 

class Pessoa(){
    
    var nome = ""
    var idade = 0
    var altura = 1.90
    var peso = 30.0 
    var nacionalidade = "Italiano"
    
    
    
}
