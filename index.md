# Acessando as configurações completas de hardware e software do sistema operacional Windows Vista/7/8/10/11/Server


Para acesso às informações do sistema incluindo os componentes físicos, aplicações e demais *software* utilizaremos a ferramenta ***Intel® System Support Utility for Windows***, que permite a geração de um relatório completo das configurações da máquina.

## Baixar o ISSU e executar a análise

1) Acesse o [link](https://github.com/webertsaturnino/tutoriais/raw/main/acesso-config-sistemas/apps/intel-ssu-windows.exe)  e baixe o arquivo ***intel-ssu-windows.exe***;

2) Execute o arquivo arquivo baixado (***intel-ssu-windows.exe***). Caso surja  um diálogo do sistema com a mensagem "Deseja permitir que este aplicativo faça alterações no seu dispositivo?", clique em "Sim". Será aberta a janela do ***Intel® System Support Utility (ISSU)***. Marque a caixa de seleção ***Everything*** e depois no botão "***Scan***". 

Feito isto, o ISSU realizará a detecção de todos os componentes do computador. Esta etapa pode demorar até 1min.  
![enter image description here](https://raw.githubusercontent.com/webertsaturnino/tutoriais/main/acesso-config-sistemas/imagens/ssu-1.png?token=GHSAT0AAAAAABSMJMTAHXOUJT33KEWX3YQYYRTVPNA)

 ## Visualizar e exportar os resultados

3) Após a execução da etapa anterios, a janela do ISSU será atualizada e exibirá um resumo da informações do sistema.
   
      ![enter image description here](https://raw.githubusercontent.com/webertsaturnino/tutoriais/307c72212d3c30b47092b023148a1f68d451d21e/acesso-config-sistemas/imagens/ssu-2.png?token=GHSAT0AAAAAABSMJMTBSMFEPP4MXDGWRDBSYRTVSJA)  
4) No menu *dropdown* na parte superior esquerda  da janela do *ISSU* estará selecionada a opção **Summary View**; Clicando neste menu haverá outra opção ***Detailed View***. Selecione-a para visualizar as configurações completas do computador.
   
   ![enter image description here](https://raw.githubusercontent.com/webertsaturnino/tutoriais/main/acesso-config-sistemas/imagens/ssu-2-detail.png?token=GHSAT0AAAAAABSMJMTAZB7IFTSF2D56OVPYYRTVUWA)
   
5) Para gerar um relatório completo das informações obtidas pelo **ISSU**, clique no botão "**Next>**", localizado no canto inferir direito da tela.

9) A seguir, clique no botão "**Save**". 
   
![enter image description here](https://raw.githubusercontent.com/webertsaturnino/tutoriais/main/acesso-config-sistemas/imagens/ssu-3.png?token=GHSAT0AAAAAABSMJMTBMQVDN4EBIRKZXHEKYRTVXNA)

6) Será aberta um diálogo padrão do Windows para salvar arquivos. Dê um nome ao arquivo que será gerado e escolha uma pasta de sua preferência. Por último clique em "Salvar".

7) Será salvo um arquivo de texto (*.txt*) contendo um relatório detalhado das informações da máquina.

