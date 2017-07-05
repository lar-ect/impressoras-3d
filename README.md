# Impressoras 3D - *Open Hardware*

Este repositório tem o objetivo de organizar alguns informações sobre a construção de impressoras 3D *Open Hardware*. Uma descrição mais detalhada sobre impressora 3D pode ser vista em http://en.wikipedia.org/wiki/3D_printer. Uma descrição sobre várias impressoras Open Hardware pode ser obtida em http://reprap.org/wiki/RepRap_Options. 

## Componentes 

* Bico aquecido
  * [Aliexpress - J-head Hotend](https://www.aliexpress.com/item/3D-Printer-All-metal-J-head-Hotend-with-Cooling-Fan-PTFE-Tubing-for-1-75MM-E3D/32705472496.html?spm=2114.13010608.0.0.vGe41u)
* Frames i3 e outras
  * [Imprimindo 3D](http://imprimindo3d.lojaintegrada.com.br) 
  * [Fabrica de Produtos](https://www.facebook.com/fabricadeprodutos/)   
* Guias lineares
  * [Só Bronze - Recife](http://www.sobronze.com.br/) 
  * [Compal](http://www.compal.com.br/)
  * [Aço Potiguar](http://acopotiguar.com.br/)
* Parafusos 
  * CENTPAR - Central de Parafusos 
* Motores
  * [Nema 17](https://pt.aliexpress.com/item/Best-Excellent-NEMA17-3D-printers-stepper-motor-CNC-stepper-motor-78-Oz-in-48mm-stepping-motor/1590567905.html)
* Arduino Mega R3  
* RAMPS 1.4 (eBay)  
* 5x Drivers A4988 
* Correias GT2 2m + 2x polias 
* 1x Hotend (p/ 1.75 mm) 
* 3x switches / endstops
* 2x Rolamentos 608zz 
* 1x Fonte industrial 350W / 12V / 30A 
* 1x Mesa aquecida Mk2a
* 2x Acoplador eixo Z motor com barra roscada 
* [Sensor de Auto-Nivelamento](http://www.geeetech.com/wiki/index.php/3DTouch_Auto_Leveling_Sensor)

## Softwares utilizados neste impressora 

* Modelagem 3D: 
  * Sketchup (Gerar um arquivo ".stl"); 
  * OpenSCAD
* Fatiador:
  * Slic3r (Gerar um arquivo “.gcode”)
* Interface Gráfica do Usuário: 
  * Pronterface (Carregar o arquivo “.gcode”, as instruções de operação da impressora);
* Firmware: 
  * Marlin (Executa as operações do arquivo “.gcode”);


## Montagem 
### RAMPs 1.4
* Colocar jumpers para os *drivers* do eixo X, Y e X, mas não para o Extrusor. 

## Referências

### Tutorial de Auto-Nivelamento da Mesa 
* [3D Printing](http://www.3dprinting.com.br/dicas-e-tutoriais/tutorial-de-implementacao-de-bed-auto-leveling-bal/)
* [Em pdf](https://08628075991197910836.googlegroups.com/attach/c67e2a0598b0a194/TUTORIAL%20DE%20IMPLEMENTA%C3%87%C3%83O%20DE%20BED%20AUTO%20LEVELING.pdf?part=0.1&vt=ANaJVrF4SgNgVcomuoIsErOoiZ2uviPCncn9K82lKFVaIng1bmcfyw80gyWCuXN4jlvmyBBQEVfyjWL3g3Rpshhh90ouAPD6617ZUSJRR7YA8a-iOdS9BPo)


### Guias de montagem 

* Modelo Prusa I3: https://groups.google.com/forum/#!msg/reprapbr/u-JUxPvh0I4/YEVQeBHdJwEJ
* Modelo Prusa Mendel I2: http://www.nextdayreprap.co.uk/prusa-mendel-build-manual/ 
* Modelo Prusa Mendel, manual pdf: http://www.geeetech.com/Documents/Prusa%20Mendel%20Build%20Manual.zip
* Modelo Prusa Mendel (Reprap): http://manuais3dm.blogspot.com.br/;
* Modelo Prusa I3: http://snapguide.com/guides/build-the-3d-printer-from-tato/;
* Modelo Prusa I3 (Reprap): http://reprap.org/wiki/Prusa_i3_Rework_Introduction;
* Modelo Graber i3: http://twelvepro.com/index.php?route=information/information&information_id=8 
* Modelo i3 MakerFarm: http://www.makerfarm.com/index.php/build-instructions/ 
* Graber i3: https://github.com/sgraber/Graber 

### Configuração 

* Caculadora Prusa: http://www.prusaprinters.org/calculator/ 

### Impressoras prontas ou kits de montagem

* Prusa Mendel: http://www.3dmachine.com.br/kits.html;
* Prusa Air: http://www.sethi3d.com.br/categoria/impressora-3d.html;
* Modelo Comercial (Baseado na Prusa): http://metamaquina.com.br/;

### Fornecedores no Brasil 
* [Sethi 3D](http://www.sethi3d.com.br/hotend-bico-inox-sethi3d)

### Forum de discussão no Brasil
* [Grupo de email - RepRapBR](https://groups.google.com/forum/#!forum/reprapbr)

### Gerenciamento via Wi-Fi
* [Tutorial controlando a impressão wi-fi com OctoPrint](https://groups.google.com/forum/#!topic/reprapbr/eJrmM_aRh9s)

### Cola para mesa 
* Uso de laquê, http://blog.render.com.br/diversos/impressao-3d-fixador-de-cabelo-cola-ou-nada/ 

### Apresentações
* [Campus Party 7 (São Paulo - 2014)](http://www.youtube.com/watch?v=LAo2wK1KsX8)

## Impressoras do Laboratório 
* [Prusa I2](https://github.com/orivaldosantana/impressoras-3d/blob/master/README_Prusa_I2.md)
* [Graber I3](https://github.com/orivaldosantana/impressoras-3d/blob/master/README_Graber.md)
