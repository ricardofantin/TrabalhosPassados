# GHDL
ghdl.odp é a apresentação realizada na hackatona do [1º Encontro Brasileiro de Hardware Aberto e Livre][e-hal.org.br].

A ideia inicial era apenas empacotar o software ghdl para o Debian e melhorar o plugin do codeblocks de programar em VHDL. Durante o evento diversas discussões surgiram e muitas *sugestões* foram anotadas:

* O pessoal da hackatona do kicad já tinha trabalhado com o Icarus Verilog;
* Existe um conversor VHDL para Verylog (vhd2vl);
* Seria bom analisar a lista de programas do [Fedora Eletronic Lab (FEL)][https://fedoraproject.org/wiki/ElectronicLab_Spin]:
 * O FEL usa o pacote freehdl ao invés do ghdl;
 * O FEL usa principalmente o Fedora Eclipse como IDE para linguagens de descrição de hardware;
 * O FEL tem mais algumas ferramentas para tratar com VHDL;
* Existem alguns projetos para rodar programas em FPGA's usando somente ferramentas livres:
 * [FPGAwars][http://fpgawars.github.io/] implementa uma FPGA livre e muitas ferramentas livres;
 * Existem algumas teses e dissertações sobre FPGA's abertas. Um exemplo é a dissertação [Archipelago][https://www2.eecs.berkeley.edu/Pubs/TechRpts/2014/EECS-2014-43.pdf] que discute alguns pontos;

#TODO
* Baixar a última versão do Fedora e verificar se existe alguma novidade ainda não documentada no site;
* Entrar em contato com o pessoal do Debian para começar a empacotar;
* Comparar os softwares do FEL x FPGAwars x programas de outros pacotes;
* Fazer uma lista de comparações como em [https://en.wikipedia.org/wiki/Category:Free_software_lists_and_comparisons]

