# Perfil icc para Positivo Vision R15
Repositório criado com objetivo de tentar compensar o balanço de branco **excessivamente amarelado** e o gama estourado do monitor do meu laptop Positivo Vision R15, porém sem prometer nenhum milagre.

Antes de prosseguir, segue um aviso:

Este repositório não serve de referência para todos os Positivo Vision R15, pois a tela pode variar sem que deixe de ser full HD IPS, além de que todo monitor tende a mudar a reprodução de cores conforme desgaste natural de uso e conforme a forma que foi fabricado;

Nenhum perfil de cores, imagem ou documentação publicado neste repositório, tem garantia expressa ou implícita de quem o disponibilizou.

Não há nenhuma promessa no tocante a fazer o laptop ser destinado a qualquer meio de produção audiovisual, pois este laptop não foi feito pra esta finalidade, então caso você trabalhe com isso, compre um laptop feito para isso ou um monitor profissional.

Os perfis icc deste repositório não serão corrigidos e nem atualizados, sendo somente publicado 1 única vez de acordo com as condições específicas do meu laptop na data de publicação. Caso o meu perfil icc não resolva o seu problema, eu recomendo fazer a sua própria calibração.

Uma dica para saber se estes perfis ICC são potencialmente úteis pra você, é verificar se a cor verde (#00FF00) parece um verde-limão. Se o verde aparecendo na tela neste exato momento não for parecido com verde-limão, este repositório deve ser desconsiderado e estes perfis não serão úteis pra você.
![Verde #00FF00](https://github.com/fernandoisnaldo/Projeto-RDS-220/blob/main/%2300FF00-verde.png)

[Perfil de cores 7300K](https://github.com/fernandoisnaldo/Perfil-icc-rds220/blob/main/2807%20%231%202024-08-27%2020-55%207300K%202.2%20(absolute)%20M-S%20XYZLUT%2BMTX.icc)

[Perfil de cores 6500K](https://github.com/fernandoisnaldo/Perfil-icc-rds220/blob/main/2807%20%231%202024-08-27%2014-37%20D6500%20L%20M-S%20XYZLUT%2BMTX.icc) 

Todos os perfis de cores no meu laptop tem uma cobertura de 56% do padrão sRGB, e o branco não é perfeito devido às limitações dos subpixels verdes. (eu disse que não poderia prometer milagres, então desejo boa sorte a quem for utilizar)

Para gerar estes perfis, foi usado o Datacolor Spyder X Pro e o programa DisplayCAL no sistema operacional Arch Linux.

