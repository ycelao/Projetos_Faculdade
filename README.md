# Projetos_Faculdade
Todos os programas feitos durante o curso de Engenharia da Computação
#include<stdio.h>

int main(void)
{
	int vetor1[9];
	int vetor2[9];
	int i;
	
	printf("Digite 10 valores.(Digite ENTER para salvar o numero)\n");
	for(i=0;i<=9;i++)
	{
		scanf("%d",&vetor1[i]);
	}
		for(i=0;i<=9;i++)
		{
			if(vetor1[i]<0)
			{
				vetor2[i]=1;
			}
			else
			vetor2[i]=vetor1[i];
			
			printf("\n%d",vetor2[i]);
			}	
      }
