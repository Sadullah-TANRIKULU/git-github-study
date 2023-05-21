  339  man grep
  340  grep --perl-regexp "linux"
  341  grep --perl-regexp "[^a-z0-9]"
  342  mkdir linux-doodle
  343  ll
  344  cd linux-doodle/
  345  echo >> file.txt
  346  ll
  347  echo --help
  348  echo "hello linux" >> file.txt 
  349  nano file.txt 
  350  echo "wright kardeşler"
  351  uname
  352  whoami
  353  echo "hello world" >> otherfile.txt
  354  diff --help
  355  ls
  356  diff file.txt otherfile.txt 
  357  cmp file.txt otherfile.txt 
  358  comm --help
  359  comm file.txt otherfile.txt 
  360  zip file.txt 
  361  mkdir tozip
  362  cd tozip/
  363  cat >> newfile.txt
  364  cat newfile.txt 
  365  cd ..
  366  zip tozip/
  367  zip tozip
  368  ls
  369  pwd
  370  cp file.txt tozip/
  371  cd tozip/
  372  ls
  373  cd ..
  374  ls
  375  mv otherfile.txt tozip/
  376  ls
  377  tree
  378  sudo apt install tree
  379  tree
  380  ln -s /tozip/newfile.txt newlink
  381  cd tozip/
  382  ll
  383  cd ..
  384  ll
  385  ln --help
  386  man ln
  387  newlink
  388  ls
  389  ln newlink 
  390  ls
  391  cd tozip/
  392  ls
  393  history >> file.txt 
  394  cd ..
  395  cat /tozip/file.txt | less
  396  cd tozip/
  397  ls
  398  cat file.txt 
  399  cat file.txt | less
  400  cd
  401  exit
  402  cd doodle/
  403  code .
  404  cd backend/
  405  npm run dev
  406  exit
  407  npm i winston
  408  exit
  409  cd ..
  410  exit
  411  npm run dev
  412  exit
  413  sudo apt update
  414  sudo apt install sqlite3
  415  sqlite3 --version
  416  npm i -g @sap/cds-dk
  417  sudo npm i -g @sap/cds-dk
  418  cds
  419  cds --version
  420  ll
  421  mv doodle/ Desktop/
  422  ls
  423  cd Desktop/
  424  ls
  425  mkdir bookshop
  426  cd bookshop/
  427  cds init my-bookshop
  428  cd ..
  429  ls
  430  cd bookshop/
  431  ls
  432  cd ..
  433  cd bookshop/
  434  cd my-bookshop/
  435  code .
  436  exit
  437  # ...first add the Cloud Foundry Foundation public key and package repository to your system
  438  wget -q -O - https://packages.cloudfoundry.org/debian/cli.cloudfoundry.org.key | sudo apt-key add -
  439  echo "deb https://packages.cloudfoundry.org/debian stable main" | sudo tee /etc/apt/sources.list.d/cloudfoundry-cli.list
  440  # ...then, update your local package index, then finally install the cf CLI
  441  sudo apt-get update
  442  sudo apt-get install cf7-cli
  443  cf
  444  cd Desktop/
  445  cat >> cf-url.txt
  446  ls
  447  cat cf-url.txt 
  448  cd
  449  cf login -a https://api.cf.us10.hana.ondemand.com
  450  npm i -g mbt
  451  sudo npm i -g mbt
  452  cf plugins
  453  cf install-plugin multiapps
  454  exit
  455  npm install
  456  cds watch
  457  npm i sqlite3 -D
  458  cds deploy --to sqlite:db/my-bookshop.db
  459  sqlite3 db/my-bookshop.db -cmd .dump
  460  cds watch
  461  cds add hana,mta,xsuaa,approuter --for production
  462  npm update --package-lock-only
  463  cf login
  464  cf target
  465  mbt build -t gen --mtar mta.tar
  466  cf target
  467  cf target -o a20b0345trial -s dev
  468  cf target -o fc4090a1-50fd-4e80-894a-ce1501ec886c -s dev
  469  cf api https://api.cf.us10-001.hana.ondemand.com
  470  cf login
  471  mbt build -t gen --mtar mta.tar
  472  sudo npm install -g mbt --unsafe-perm=true --allow-root
  473  mbt build -t gen --mtar mta.tar
  474  make --version
  475  sudo apt install make
  476  mbt build -t gen --mtar mta.tar
  477  cf deploy gen/mta.tar
  478  cf deploy -i 446df727-d7f5-11ed-8bef-eeee0a8ef097 -a retry
  479  cf dmol -i 446df727-d7f5-11ed-8bef-eeee0a8ef097
  480  cf deploy -i 446df727-d7f5-11ed-8bef-eeee0a8ef097 -a retry
  481  cf dmol -i 446df727-d7f5-11ed-8bef-eeee0a8ef097
  482  cd ..
  483  history >> cmd_history.txt
  484  ll
  485  cd 
  486  exit
  487  git clone https://github.com/Sadullah-TANRIKULU/express-postgres2.git
  488  exit
  489  code .
  490  exit
  491  node --version
  492  npm run dev
  493  npm i
  494  npm run dev
  495  exit
  496  PGPASSWORD=PhH2k527iI5uGPihqa2X psql -h containers-us-west-33.railway.app -U postgres -p 6243 -d railway
  497  exit
  498  npm i
  499  npm update
  500  npm i
  501  npm run start
  502  exit
  503  touch dood.txt
  504  code .
  505  npm run start
  506  where brave-browser
  507  which brave-browser
  508  npm run start
  509  exit
  510  code .
  511  npm run start
  512  npm i uuidv4
  513  npm run start
  514  npm uninstall uuidv4
  515  npm i hat
  516  npm run start
  517  exit
  518  cd Desktop/
  519  mkdir job-seek
  520  mv Resume-Sadullah-TANRIKULU.docx job-seek/
  521  cd ..
  522  cd Desktop/
  523  cd job-seek/
  524  ls
  525  CD ..
  526  cd ..
  527  exit
  528  code .
  529  npm run start
  530  exit
  531  java -version
  532  # https://github.com/SAP/SapMachine/wiki/Installation
  533  sudo bash
  534  apt-get install -y --no-install-recommends wget ca-certificates gnupg2
  535  export GNUPGHOME="$(mktemp -d)"
  536  wget -q -O - https://dist.sapmachine.io/debian/sapmachine.old.key | gpg --batch --import
  537  gpg --batch --export --armor 'DA4C 00C1 BDB1 3763 8608 4E20 C7EB 4578 740A EEA2' > /etc/apt/trusted.gpg.d/sapmachine.old.gpg.asc
  538  wget -q -O - https://dist.sapmachine.io/debian/sapmachine.key | gpg --batch --import
  539  gpg --batch --export --armor 'CACB 9FE0 9150 307D 1D22 D829 6275 4C3B 3ABC FE23' > /etc/apt/trusted.gpg.d/sapmachine.gpg.asc
  540  gpgconf --kill all && rm -rf "$GNUPGHOME"
  541  echo "deb http://dist.sapmachine.io/debian/amd64/ ./" > /etc/apt/sources.list.d/sapmachine.list
  542  apt-get update
  543  apt-get install sapmachine-11-jdk
  544  which eclipse
  545  where eclipse
  546  eclipse
  547  java -version
  548  find man
  549  man find
  550  find --help
  551  find -depth -i . "eclipse"
  552  find -depth . "eclipse"
  553  sudo bash
  554  cd Downloads/eclipse-installer/
  555  ./eclipse-inst 
  556  cd ..
  557  eclipse
  558  exit
  559  sudo snap install discord
  560  discord
  561  exit
  562  sudo apt update
  563  apt list --updateable
  564  apt list --upgradeable
  565  sudo apt install artha
  566  artha
  567  exit
  568  sudo apt uninstall artha
  569  sudo apt auto-remove artha
  570  cd Desktop/
  571  ls
  572  ./esperantiloTM.bin
  573  sudo ./esperantiloTM.bin
  574  chmod +x esperantiloTM.bin
  575  ll
  576  touch linux_notes.txt
  577  ./esperantiloTM.bin 
  578  cat esperantiloTM.bin 
  579  cls
  580  clear
  581  ll
  582  rm esperantiloTM.bin 
  583  ll
  584  sudo snap install dialect
  585  dialect
  586  sudo snap auto-remove dialect
  587  sudo snap autoremove dialect
  588  history
  589  sudo snap uninstall dialect
  590  sudo apt auto-remove dialect
  591  sudo snap remove dialect
  592  sudo snap install dialect
  593  sudo snap remove dialect
  594  exit
  595  code .
  596  npm run start
  597  exit
  598  cd Desktop/
  599  cd my-redux-template-app/
  600  code .
  601  npm run start
  602  exit
  603  apt-get
  604  apt-get reinstall
  605  sudo apt-get
  606  sudo apt-get reinstall
  607  sudo apt-get update
  608  sudo apt-get upgrade
  609  exit
  610  cd Desktop/my-redux-template-app/
  611  code .
  612  npm run start
  613  exit
  614  cd Desktop/my-redux-template-app/
  615  code .
  616  npm run start
  617  exit
  618  code .
  619  exit
  620  pwd
  621  ll
  622  exit
  623  cd Desktop/
  624  touch asd.txt
  625  ls
  626  mv EPM_Product_SOAP.WSDL EPM_Product_SOAP.wsdl
  627  ls
  628  exit
  629  cd Desktop/
  630  mkdir angular-apps
  631  cd angular-apps/
  632  npm install -g @angular/cli
  633  sudo npm install -g @angular/cli
  634  ng --version
  635  npm ng --version
  636  ng -V
  637  ng version
  638  ng new angular-redux-linux
  639  ls
  640  cd angular-redux-linux/
  641  code .
  642  ng serve -o
  643  cd ..
  644  rm -rf angular-redux-linux/
  645  exit
  646  ng add @angular/material
  647  ng g @angular/material:dashboard my-dashboard
  648  ng g @angular/material:navigation navigation
  649  npm i @angular/animations
  650  ng g m guests && ng g s guests/guests
  651  npm i @ngrx/store --save && npm i @ngrx/effects --save && npm i @ngrx/schematics --save-dev
  652  ng g @ngrx/schematics:feature guests/+store/Guest -m guests/guests.module.ts --flat
  653  ng g c @ngrx/schematics:feature guests/+store/Guest -m guests/guests.module.ts --flat
  654  ng g c guests/guests
  655  exit
  656  ng version
  657  cd Desktop/
  658  ls
  659  cd angular-apps/
  660  ls
  661  ng new angular-redux
  662  npm i @ng-bootstrap/ng-bootstrap bootstrap @ngrx/core @ngrx/effects @ngrx/store ngrx-store-logger
  663  npm i @ng-bootstrap/ng-bootstrap bootstrap @ngrx/effects @ngrx/store ngrx-store-logger
  664  npm i @ng-bootstrap/ng-bootstrap bootstrap ngrx-store-logger
  665  npm i ngrx-store-logger
  666  npm i @ng-bootstrap/ng-bootstrap
  667  npm i bootstrap
  668  npm i @ng-bootstrap/ng-bootstrap
  669  npm i @ngrx/effects @ngrx/store
  670  npm i @ngrx/effects
  671  npm i @ngrx/store
  672  ls
  673  cd angular-redux/
  674  ls
  675  cd ..
  676  ls
  677  rm package-lock.json package.json 
  678  ls
  679  rm --help
  680  rm -r -v node_modules/
  681  ls
  682  clear
  683  # ng g m to-do
  684  cd angular-redux/
  685  ng g m to-do
  686  tree
  687  code .
  688  ng g s to-do
  689  ng g s to-do/to-do
  690  npm i ngx-pagination
  691  npm i @ngrx
  692  npm i ngrx
  693  npm i ngrx/store
  694  cd ..
  695  rm -r angular-redux/
  696  rm -rf angular-redux/
  697  ls
  698  exit
  699  cd Desktop/angular-apps/
  700  ls
  701  mkdir angular-redux-demo
  702  cd angular-redux-demo/
  703  ng --version
  704  ng version
  705  sudo npm i -g angular-cli@~13
  706  sudo npm i -g angular-cli@~13.1
  707  sudo npm i -g @angular-cli@~13.1
  708  sudo npm i -g angular-cli@~11
  709  sudo npm i -g angular-cli@~14
  710  sudo npm i -g angular-cli@~15
  711  sudo npm i -g angular-cli
  712  ng version
  713  ng init
  714  ng --help
  715  ng serve --help
  716  ng serve -help
  717  ng new .
  718  cd ..
  719  rmdir angular-redux-demo/
  720  ng new angular-redux-demo --skip-tests --minimal
  721  ls
  722  npm i redux ng2-redux
  723  npm audit fix
  724  npm audit fix --force
  725  ng serve -o
  726  ls
  727  cd angular-redux-demo/
  728  ng serve -o
  729  exit
  730  code .
  731  # npm i @ngrx/store --save
  732  npm uninstall ng2-redux redux
  733  npm i @ngrx/store --save
  734  exit
  735  # sudo apt-get install emacs
  736  apt update
  737  sudo apt update
  738  sudo apt-get install emacs
  739  emacs --version
  740  emacs
  741  exit
  742  cd Desktop/
  743  touch helpme.txt
  744  exit
  745  cd Desktop/
  746  ls -lt
  747  ls -la
  748  ls -lat
  749  ls -d
  750  ls -ld
  751  ls -lda
  752  ls -f
  753  ls -F
  754  ls --file-type
  755  ls -h
  756  ls -lh
  757  ls -lsh
  758  ls -l
  759  ls -m
  760  ls --help
  761  pwd
  762  cd Desktop/
  763  ls
  764  ls -l
  765  ls -la
  766  man ls
  767  whoami
  768  uname
  769  uname -a
  770  uname --help
  771  ls -l
  772  stat consistencyEvenIfSmall.jpeg 
  773  stat job-seek/
  774  whatis man
  775  whatis apt
  776  whatis snap
  777  whatis slack
  778  whatis top
  779  top --help
  780  top -d --help
  781  top -d 0.5
  782  htop
  783  sudo snap install htop
  784  htop
  785  whatis df
  786  df --help
  787  df -Th
  788  free
  789  free --help
  790  free -h
  791  free -th
  792  cat /proc/meminfo 
  793  whereis --help
  794  whereis -m ls
  795  whereis -m rm
  796  whereis -s rm
  797  whereis -b rm
  798  whereis -m cat
  799  exit
  800  du --help
  801  exit
  802  btp
  803  cf
  804  # tar -vxzf 
  805  ls
  806  cd Downloads/
  807  ls
  808  tar -vxzf btp-cli-linux-amd64-2.38.0.tar.gz
  809  ls
  810  cd linux-amd64/
  811  ls
  812  btp
  813  ./btp
  814  exit
  815  ./btp
  816  btp
  817  cd Downloads/linux-amd64/
  818  ls
  819  which cf
  820  mv btp /usr/bin/
  821  cp btp /usr/bin/
  822  sudo cp btp /usr/bin/
  823  which btp
  824  cd
  825  btp
  826  clear
  827  btp target
  828  clear
  829  btp
  830  btp help
  831  clear
  832  btp help
  833  exit
  834  pwd
  835  cd Desktop/
  836  mkdir btp-abap-presentation
  837  sudo apt list apache*
  838  sudo apt install apache2
  839  sudo systemctl enable --now apache2
  840  sudo ufw status
  841  sudo ufw allow --help
  842  ufw allow --help
  843  ufw --help
  844  sudo ufw allow http
  845  sudo ufw allow https
  846  sudo ufw status
  847  sudo ufw status numbered
  848  sudo systemctl enable --now apache2
  849  sudo ufw status numbered
  850  cd /var/www/html/
  851  ls
  852  less --help
  853  less index.html
  854  sudo ufw show added
  855  sudo ufw status
  856  sudo ufw enable
  857  sudo ufw status
  858  sudo ufw allow https
  859  sudo ufw allow http
  860  sudo ufw status
  861  sudo ufw show added
  862  sudo ufw status
  863  sudo systemctl enable --now apache2
  864  sudo ufw status numbered
  865  sudo ufw allow http
  866  sudo ufw allow https
  867  sudo ufw status numbered
  868  restart
  869  sudo ufw status numbered
  870  ufw --help
  871  sudo systemctl start apache2
  872  sudo systemctl status
  873  sudo ufw status
  874  nc --help
  875  nc -vz 10.0.222.51 22
  876  sudo ufw allow ssh
  877  sudo ufw status
  878  sudo ufw allow http
  879  sudo ufw allow https
  880  sudo ufw status
  881  curl --help
  882  curl localhost:80
  883  ip address
  884  ipaddr
  885  hostname -I
  886  ifconfig -a
  887  sudo apt install net-tools
  888  ifconfig -a
  889  localhost
  890  ip addr
  891  cd /etc/apache2/
  892  ls
  893  sudoedit apache2.conf 
  894  cd ..
  895  cd
  896  ip addr
  897  cd /etc/apache2/
  898  sudoedit apache2.conf 
  899  sudo ufw allow 'Apache'
  900  sudo ufw status
  901  cd
  902  cd /var/www/html/
  903  ls
  904  mv index.html defaultindex.html
  905  sudo mv index.html defaultindex.html
  906  sudo cp defaultindex.html index.html
  907  ls
  908  sudoedit index.html 
  909  curl localhost
  910  exit
  911  sudo systemctl stop apache2
  912  sudo systemctl start apache2
  913  sudo systemctl stop apache2
  914  man ls
  915  ls
  916  ls -A --author
  917  ls -A
  918  ls --author
  919  ls -l --author
  920  ls -l
  921  man ls
  922  ls --color
  923  ls -l --color
  924  ls -la
  925  ls -la --color
  926  man ls
  927  man pwd
  928  pwd -logical
  929  pwd --logical
  930  pwd -L
  931  pwd -P
  932  echo -e "hello guys\nhow ya doing\nI'm getting excited when I start to examine linux commands\nwhat doy you think?"
  933  man echo
  934  echo -v "hey"
  935  echo -v "hey" "what"
  936  man echo
  937  echo -a "woo" 
  938  echo "this sentence goes into newfile.txt" >> newfile.txt
  939  ls
  940  cat newfile.txt 
  941  history >> cmd_history.txt
  942  ls
  943  cat cmd_history.txt 
  944  exit
  945  cd Downloads/
  946  ls
  947  dpkg --help
  948  dpkg -i anydesk_6.2.1-1_amd64.deb
  949  sudo dpkg -i anydesk_6.2.1-1_amd64.deb 
  950  sudo apt-get install anydesk
  951  sudo apt --fix-broken install anydesk
  952  sudo apt autoremove anydesk
  953  sudo apt update
  954  sudo apt install widget
  955  wget -qO - https://keys.anydesk.com/repos/DEB-GPG-KEY | sudo apt-key add -
  956  sudo snap install anydesk
  957  anydesk
  958  ls
  959  rm -rf anydesk_6.2.1-1_amd64.deb debian-binary control.tar.gz data.tar.gz 
  960  ls
  961  exit
  962  code .
  963  ng serve --open
  964  cd ..
  965  git
  966  git clone https://github.com/Sadullah-TANRIKULU/hogvarts-test.git
  967  ls
  968  cd hogvarts-test/
  969  ng serve --open
  970  code .
  971  npm i
  972  ng serve --open
  973  git status
  974  git add .
  975  git commit -m "quiz questions and options ready"
  976  git push
  977  exit
  978  which eclipse
  979  where eclipse
  980  cd Downloads/
  981  ls
  982  cd
  983  pwd
  984  ls
  985  find --help
  986  tree .
  987  ls
  988  cd eclipse
  989  tree
  990  ls *.ini
  991  find ./ -regex '*.ini'
  992  ls
  993  cd java-2023-03/
  994  ls
  995  cd eclipse/
  996  ls
  997  nano eclipse.ini 
  998  ls
  999  cd configuration/
 1000  ls
 1001  nano config.ini 
 1002  cd ..
 1003  nano eclipse.ini 
 1004  exit
 1005  java
 1006  java --version
 1007  which java
 1008  exit
 1009  ls
 1010  cd hogvarts-test/
 1011  ls -la
 1012  cat package.json 
 1013  ng serve --open
 1014  cd 
 1015  pwd
 1016  ls
 1017  cd Desktop/
 1018  mkdir
 1019  mkdir git-github-study
 1020  cd git-github-study/
 1021  git init
 1022  ls -al
 1023  echo "this is a git-github study file" >> github_study.txt
 1024  ls
 1025  cat github_study.txt 
 1026  git add .
 1027  git commit -m "first commit"
 1028  git branch -M master
 1029  git remote add origin https://github.com/Sadullah-TANRIKULU/git-github-study.git
 1030  git push -u origin master
 1031  ls
 1032  git branch -a
 1033  git checkout -B devSado
 1034  git branch -a
 1035  echo "devSado branch made changes" >> github_study.txt 
 1036  git status
 1037  git add .
 1038  git commit -m "new changes"
 1039  git push
 1040  git remote -v
 1041  git push -u origin
 1042  git push --set-upstream origin devSado
 1043  ls
 1044  echo "come on man" >> github_study.txt 
 1045  git status
 1046  git add .
 1047  git commit -m "second commit"
 1048  git push
 1049  git status
 1050  cat github_study.txt 
 1051  git push
 1052  git push -u origin
 1053  git config --global user.name "Sadullah-TANRIKULU"
 1054  git config --global user.email "sadullahtanrikulu@gmail.com"
 1055  git config --help
 1056  git config --show-origin
 1057  git config 
 1058  git config --get-all
 1059  git config --worktree
 1060  git config --list --show-origin
 1061  git pull
 1062  ls
 1063  cat github_study.txt 
 1064  exit
 1065  code .
 1066  which brave
 1067  which brave-browser
 1068  ng add @angular/material
 1069  exit
 1070  cd Desktop/
 1071  cd angular-apps/
 1072  ls
 1073  cd hogvarts-test/
 1074  ng serve
 1075  exit
 1076  sudo snap-store update
 1077  brave-browser
 1078  sudo snap refresh
 1079  brave-browser
 1080  sudo snap refresh snap-store
 1081  snap-store --quit && sudo snap refresh snap-store
 1082  exit
 1083  code .
 1084  npm list -g
 1085  ng serve
 1086  cd ..
 1087  ls
 1088  zip --help
 1089  git rebase --help
 1090  git rebase help
 1091  cd ..
 1092  lsd
 1093  ls
 1094  cd git-github-study/
 1095  ls
 1096  cat github_study.txt 
 1097  git branch -a
 1098  echo "whassup y'all" >> github_study.txt 
 1099  cat github_study.txt 
 1100  git status
 1101  git add .
 1102  git commit -m "last commit"
 1103  git status
 1104  git push
 1105  git rebase master
 1106  git checkout master && git pull
 1107  git status
 1108  git rebase --edit-todo
 1109  git branch -a
 1110  git rebase --skip
 1111  git merge --help
 1112  git merge --continue
 1113  git merge --no-commit
 1114  git checkout devSado
 1115  git add .
 1116  git commit -a
 1117  git status
 1118  git rebase --continue
 1119  git branch -a
 1120  git rebase --skip
 1121  git checkout master
 1122  git pull
 1123  git merge
 1124  git merge --help
 1125  git merge --abort
 1126  git diff
 1127  git merge --help
 1128  cd ..
 1129  cd angular-apps/
 1130  ls
 1131  cd hogvarts-test/
 1132  ng serve
 1133  exit
 1134  git merge devSado master
 1135  git add .
 1136  git status
 1137  git fetch
 1138  git merge origin/master
 1139  git pull origin master
 1140  git branch -a
 1141  git checkout devSado
 1142  git status
 1143  git commit -m "noluyo ya"
 1144  git branch -a
 1145  git checkout devSado
 1146  git pull
 1147  git branch -a
 1148  git rebase master
 1149  git rebase --continue
 1150  git rebase --abort
 1151  git status
 1152  git pull
 1153  git checkout master
 1154  git pull
 1155  git checkout devSado
 1156  git rebase master
 1157  cat github_study.txt 
 1158  git branch -a
 1159  cat github_study.txt 
 1160  git status
 1161  git push
 1162  code .
 1163  cd
 1164  pwd
 1165  cd Desktop/
 1166  cd angular-apps/
 1167  git clone https://github.com/ashish173/greenquiz.git
 1168  ls
 1169  cd greenquiz/
 1170  ls -al
 1171  cat package.json 
 1172  npm i
 1173  ng serve
 1174  ls
 1175  yarn add
 1176  sudo apt install cmdtest
 1177  yarn add
 1178  yarn
 1179  ng serve
 1180  ls
 1181  nano package.json 
 1182  npm i
 1183  python
 1184  python3
 1185  python2
 1186  sudo apt update && sudo apt install python2
 1187  ls
 1188  python2
 1189  npm i
 1190  nano package.json 
 1191  npm i
 1192  ls
 1193  cd ..
 1194  ls
 1195  rm -R greenquiz/
 1196  rm -rf greenquiz/
 1197  ls
 1198  unzip angular-8-quiz-app-swbaxu.zip 
 1199  ls
 1200  mkdir ng8-quiz-app && cd ng8-quiz-app && unzip angular-8-quiz-app-swbaxu.zip 
 1201  ls
 1202  unzip --help
 1203  cd ..
 1204  unzip angular-8-quiz-app-swbaxu.zip ng8-quiz-app/
 1205  unzip angular-8-quiz-app-swbaxu.zip -d ng8-quiz-app/
 1206  ls
 1207  cd ng8-quiz-app/
 1208  ls
 1209  cd ..
 1210  ls
 1211  rm -rf angular.json package.json README.md src/ tsconfig.json 
 1212  ls
 1213  rm -rf angular-8-quiz-app-swbaxu.zip 
 1214  ls
 1215  cd ng8-quiz-app/
 1216  ls
 1217  cat package.json 
 1218  npm install
 1219  node -v
 1220  npm -v
 1221  angular -v
 1222  npm list -g
 1223  npm i -g @angular/cli@~13
 1224  sudo npm i -g @angular/cli@~13
 1225  npm list -g
 1226  sudo npm uninstall -g @angular/cli@~15
 1227  npm list -g
 1228  npm i
 1229  ls
 1230  cat angular.json 
 1231  ls
 1232  ng serve
 1233  npm i
 1234  npm i --force
 1235  npm audit fix
 1236  ls
 1237  ng serve
 1238  node --trace-deprecation
 1239  node
 1240  cd ..
 1241  ls
 1242  rm -rf ng8-quiz-app/
 1243  ls
 1244  exit
 1245  ls
 1246  code .
 1247  ng g c postlist
 1248  ng g pipe demopipe
 1249  ng g c child
 1250  ng g c child2
 1251  exit
 1252  cd Desktop/
 1253  ls
 1254  cd angular-apps/
 1255  ls
 1256  mkdir learn-ng
 1257  cd learn-ng/
 1258  ng --help
 1259  ng help
 1260  ng version
 1261  ng new --help
 1262  ng new --skip-tests --skip-git --routing=false --minimal --directory=./
 1263  ls
 1264  ng serve --help
 1265  ng serve --open --port=4242
 1266  exit
 1267  cd ..
 1268  mkdir learn-ng2
 1269  cd learn-ng2/
 1270  ls
 1271  history
 1272  ng new --skip-tests --skip-git --routing=false --minimal --directory=./
 1273  ls
 1274  ng serve --open --port=4242
 1275  exit
 1276  ng g c home
 1277  exit
 1278  pwd
 1279  cd Desktop/
 1280  cd angular-apps/
 1281  ls
 1282  cd learn-ng2
 1283  ls
 1284  code .
 1285  ng g c parent1 && ng g c parent2 && ng g c parent1/child1 && ng g c parent2/child2 && ng g pipe demopipe
 1286  ng serve --open --port=4242
 1287  exit
 1288  code .
 1289  git checkout master
 1290  git branch -a
 1291  git pull
 1292  git checkout devSado
 1293  git rebase master
 1294  exit
 1295  code .
 1296  git branch -a
 1297  git rebase master
 1298  git checkout master
 1299  git pull
 1300  git checkout devSado
 1301  git status
 1302  git branch -a
 1303  git add .
 1304  git commit -m "fast forward"
 1305  git push
 1306  echo "how ya doin" >> github_study.txt 
 1307  cat github_study.txt 
 1308  git status
 1309  git add .
 1310  git commit -a
 1311  # git push
 1312  git push
 1313  git pull
 1314  git branch -a
 1315  git rebase --update-refs
 1316  git rebase --abort
 1317  git push
 1318  git pull
 1319  git fetch --help
 1320  git fetch -all
 1321  git fetch --all
 1322  git pull
 1323  git remote -v
 1324  git config pull.rebase false
 1325  git pull
 1326  git branch -a
 1327  git push
 1328  git checkout devSado
 1329  cat github_study.txt 
 1330  git rebase master
 1331  cat github_study.txt 
 1332  exit
 1333  history
 1334  cd Desktop/
 1335  ls
 1336  cd git-github-study/
 1337  ls
 1338  history >> cli_history.md
