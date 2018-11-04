**OrtogOnBlender**
==================
![GitHub Logo](http://www.ciceromoraes.com.br/ups/OrtogOnBlender.jpg)
<h2>História</h2>

No ano de 2014 iniciou-se uma parceria entre o cirurgião bucomaxilofacial, Dr. Everton da Rosa e o 3D designer [Cicero Moraes](http://www.ciceromoraes.com.br) com o objetivo de criar uma metodologia de planejamento de cirurgia ortognática baseada em software livre. A ferramenta principal de trabalho seria o Blender 3D, poderoso software livre de modelagem e animação. No entanto, apesar de este contar com um workflow bem preparado para o campo artístico, o mesmo não poderia se dizer em relação às ciências da saúde. Dentre os muitos problemas encontrados podem ser citados: a falta de uma poderosa ferramenta de cálculos booleanos para o processo de osteotomia e criação de guias cirúrgicos, a falta de suporte e conversão de  arquivos DICOM (tomografias computadorizadas) e a distribuição difusa dos comandos pela interface, o que  dificultava em muito a utilização do software por iniciantes no mundo da computação gráfica 3D.

De 2014 a 2017 dos dois especialistas desenvolveram e lapidaram não apenas uma metodologia de uso do software livre na cirurgia ortognática, mas também uma forma de compartilhar esse conhecimento através de cursos presenciais. No segundo semestre de 2017 o OrtogOnBlender começou a ser desenvolvido e em poucos meses já contava com uma versão funcional.

<h2>Sobre o Addon</h2>

O OrtogOnBlender é um addon de planejamento digital de cirurgia ortognática, baseado no software de modelagem e animação Blender 3D e é focado na facilitação do uso de ferramentas 3D por parte de profissionais da área de cirurgia bucomaxilofacial.

Organizado em um painel na parte esquerda da 3D View, o addon tem em sua estrutura os seguintes passos:

* **Importa Tomo**: Reconstrução dos ossos e do mole em 3D, a partir de uma tomografia computadorizada.

* **Importar Tomo 3D/Moldes**: Importação da reconstrução da tomografia computadorizada ou digitalização de moles das arcadas dentárias, efetuadas em software externo.

* **Zoom Cena**: Elementos de visualização da cena.

* **Cria Fotogrametria**: Digitalização de faces a partir de fotografias.

* **Importa Fotogrametria**: Importa digitalização de face efetuada em software externo.

* **Alinha  Faces**: Alinha a face e a redimensiona utilizando as informações fornecidas pelo usuário.

* **Importar Cefalometria**: Importa imagem de cefalometria para alinhamento da face.

* **Redimensiona e Alinha Faces**: Redimensiona a face baseada em medida conhecida e alinha a fotogrametria em relação ao mole reconstruído a partir da tomografia.

* **Osteotomia**: Osteotomia dos ossos da cabeça, com ferramentas de booleana complexa e configura cada uma das peças separadas (coloração e nomeamento).

* **Dinâmica do Mole**: Atrela a deformação da pele em relação a movimentação dos ossos provindos da osteotomia.

* **Criação do Splint**: Configuração dos estados do planejamento digital e criação dos splints cirúrgicos, para posterior impressão 3D

<h2>Como Instalar (Geral)</h2>

* Baixe o arquivo em “Clone or download”
* No Blender vá em: `File` → `User Preferences` → `Addons` → `Install from file` Procure o arquivo OrtogOnBlender-master.zip, clique sobre ele e em seguida no botão: `Install from file`
* Ativar a opção `ortog:OrtogOnBlender` e configure os caminhos dos scripts expandindo a setinha do lado esquerdo.
* Para manter o addon ativo clique em: `Save User Settings`.

<h2>Como Instalar (Detalhado)</h2>

* Tutorial de instalação no Windows: http://www.ciceromoraes.com.br/doc/pt_br/OrtogOnBlender/Instalacao_Windows.html

* Tutorial de instalação no Mac OS X: http://www.ciceromoraes.com.br/doc/pt_br/OrtogOnBlender/Instalacao_MacOSX.html

* Tutorial de instalação no Linux: http://www.ciceromoraes.com.br/doc/pt_br/OrtogOnBlender/Instalacao_Linux.html

<h2>Dependências</h2>

O OrtogOnBlender utiliza uma série de addons e bibliotecas/programas, alguns nativos e outros externos em relação ao Blender 3D, são eles:

<h4>Addons</h4>

* Measureit (nativo)
* 3D Navigation (nativo)
* Import Images as Planes (nativo)
* Cork on Blender - https://github.com/dfelinto/cork-on-blender	
* Cut Mesh - https://github.com/patmo141/cut_mesh
* Object Alignment - https://github.com/patmo141/object_alignment

<h4>Programas</h4>

* Meshlab (instalador) - http://www.meshlab.net/
* OpenMVG (código-fonte) - https://github.com/openMVG/openMVG
* OpenMVS (código-fonte) - http://cdcseacave.github.io/openMVS/
* MVE/SMVS (código-fonte) - https://github.com/flanggut/smvs
* Dicom2Mesh (código-fonte) - https://github.com/AOT-AG/DicomToMesh

<h3>Agradecimentos</h3>

[Dalai Felinto](https://github.com/dfelinto/), [Pierre Moulon](https://github.com/pmoulon), [Patrick Moore](https://github.com/patmo141/), [Adrian Schneider](https://github.com/eidelen), Rodrigo Dornelles, Liogi Iwaki Filho, Antônio Eduardo Izidro, Paulo Henrique  Luiz de Freitas, Vinicius de Paula Ribeiro, Richard Gravalos, José Patrício Neto, Hugo Santos Cunha, Frederico Yonezaki, Eduardo Correa Costa, Renata Porto Stypulkowski, Samuel Cardoso Santiago Júnior, José Arnaldo dos Santos Júnior, Lucio Gamboa Villegas, Walace Guimarães Matos e Adriano Rocha Campos.
