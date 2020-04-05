Este é um tutorial visando a obtenção de árvores filogenéticas a partir de dados genômicos de SARS-CoV-2.

  1. Acesse os dados genômicos do Link[SARS-CoV-2](https://raw.githubusercontent.com/MikaelMarcondes/covid-19/master/dataset.csv). No campo de busca do Ubuntu, digite "gedit" e dê "Enter". Copie as sequências e salve-as como "dataset.csv";
  2. Descarregue o arquivo ["mafft_7.450-1_amd64.deb"](https://mafft.cbrc.jp/alignment/software/linux.html) para seu computador. Você vai precisar ter privilégios de acesso;
  3. Abra uma nova janela do Terminal (Ctrl+Alt+T), digite "sudo su", entre com a senha e dê "Enter".
  4. Digite "cd 'caminho para onde o arquivo MAFFT foi descarregado'" e dê "Enter";
  5. Digite "dpkg -i mafft_7.450-1_amd64.deb" e dê "Enter". Espere a instalação ser concluída;
  6. Digite "mafft" para o programa de alinhamento múltiplo de sequências começar a rodar. Dê o caminho do arquivo "dataset" como "input file". Escolha um caminho onde salvar os resultados do alinhamento de sequências. Escolha o formato "FASTA" com "ordem de entrada" (Opção X). Escolha o método "FFT-NS-2 (default)" para realização do alinhamento. Não digite nada nos parâmetros-extra, dê "Enter" e espere o alinhamento terminar.;
  7. Acesse http://phylosolutions.com/paup-test/ e descarregue o arquivo "paup4a166_ubuntu64.gz" para seu computador.
  8. Abra uma nova janela do Terminal (Ctrl+Alt+T), digite "cd 'caminho para onde o arquivo PAUP* 4 foi descarregado'" e dê "Enter". Digite "sudo chmod +x ./paup4a166_ubuntu64.gz", dê "Enter" e, se necessário, entre com a senha e dê "Enter" novamente.
