# Compter-les-alumnis
cd Documents
mbp-de-mikhail:Documents mikhailli$ man sort
mbp-de-mikhail:Documents mikhailli$ curl -o wilders.csv https://gist.githubusercontent.com/bhubr/bc3a21a0202109beeb31c4a677e0461b/raw/d8805eb82e8aabffab3b0163596c734f376617d0/wilders.csv
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 60659  100 60659    0     0   281k      0 --:--:-- --:--:-- --:--:--  299k
mbp-de-mikhail:Documents mikhailli$ grep -E "PHP.*2019|2019.*PHP" wilders.csv > php_france_2019.csv
mbp-de-mikhail:Documents mikhailli$ grep "JavaScript" wilders.csv > temp.csv
mbp-de-mikhail:Documents mikhailli$ grep -E "Toulouse|Biarritz" temp.csv > javascript_biarritz_toulouse.csv
mbp-de-mikhail:Documents mikhailli$ rm temp.csv
mbp-de-mikhail:Documents mikhailli$ history | tail -n 10 > history.txt
mbp-de-mikhail:Documents mikhailli$ 
