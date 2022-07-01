programa
{
	funcao inicio() 
	{
	    
	   inteiro valorDiaria, diasHospedagem
	   
	   escreva("digite o valor da diaria do hotel:")
	   leia(valorDiaria)
	   escreva("digite a quantidade de dias da hospedagem:")
	   leia(diasHospedagem)
	   
	   enquanto(diasHospedagem < 0 ou diasHospedagem > 30 ou valorDiaria < 0){
	       escreva("valor inválido, digite novamente: \n")
	       escreva("diaria:")
	       leia(valorDiaria)
	       escreva("hospedagem:")
	       leia(diasHospedagem)
	       
	   }
	escreva("Fim do Programa!")
	
	}
}

