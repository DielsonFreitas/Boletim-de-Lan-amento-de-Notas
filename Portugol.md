

programa {
  funcao inicio() {
    
    cadeia nome
    cadeia curso
    cadeia disciplina
    inteiro nota
    inteiro valor

    escreva("\n=====BOLETIM DE LANÇAMENTO DE NOTAS=====")
    
    escreva("\nInforme o nome do(a) aluno(a): ")
    leia(nome)
    escreva("\nInforme o curso: ")
    leia(curso)
    escreva("\nInforme a disciplina: ")
    leia(disciplina)
    escreva("\nInforme a nota: ")
    leia(nota)

    se ( nota >= 60 e nota <= 100 ) 
    {
      escreva("Está APROVADO!")
    }
    senao 
      se ( nota <= 19)
    {
      escreva("Está de EXAME!")
    }
    senao
    {
      escreva("Está de RECUPERAÇÃO!")
    }
    
      
  }
}
